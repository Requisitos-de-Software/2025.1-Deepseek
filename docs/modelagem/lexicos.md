# Léxicos

## Introdução

O léxico funciona como uma notação que lista e define os símbolos (palavras ou expressões) usados em uma linguagem. Em Engenharia de Requisitos, seu papel central é identificar termos ou frases próprios do contexto social em que o sistema será aplicado. Cada símbolo do léxico é caracterizado por:

* **Noção**: o seu significado literal, aquilo que ele denota.
* **Impacto**: a sua conotação ou efeito prático, ou seja, a resposta gerada quando o símbolo é utilizado.

Para elaborar os léxicos do DeepSeek, adotamos a abordagem do **Léxico Ampliado da Linguagem (LAL)**, conforme proposta por Sayão e Carvalho. Nesse modelo, cada símbolo é classificado em uma das quatro categorias:

* **Sujeito**: identifica quem é o agente ou entidade responsável pela ação, enquanto o impacto descreve quais operações esse agente executa sobre o sistema ou ambiente.
* **Verbo**: detalha quem realiza determinada ação, em que momento ela ocorre e quais procedimentos a compõem; o impacto mapeia os efeitos dessa ação no contexto e os novos estados que podem emergir.
* **Objeto**: define o elemento ou recurso do sistema e suas associações com outros objetos; o impacto especifica que tipos de operações podem ser aplicadas a esse objeto.
* **Estado**: descreve a condição ou situação atual do sistema, indicando quais eventos o levaram a tal ponto, e o impacto projeta os estados seguintes possíveis a partir dessa condição.

Adotaremos um padrão uniforme para cada entrada do léxico, composto pelos seguintes campos:

- ID: identificador único do termo.
- Noção: significado literal que o termo denota
- Impacto: conotação ou efeito prático que sua aplicação produz no sistema.
- Classificação: categoria do símbolo (Sujeito, Verbo, Objeto ou Estado).
- Dicionário: sinônimos e expressões equivalentes.
- Rastreamento: Código Caso de Uso/Cenário

Esse esquema garante que todo termo usado no DeepSeek seja descrito de forma consistente, permitindo fácil reconhecimento e entendimento por todos os membros da equipe.

## Tabela de Contribuições

| Contribuinte | Descrição                                                            | Links                                           |
|--------------|----------------------------------------------------------------------|-------------------------------------------------|
| Ana Joyce     | Criação dos léxicos #LX01 | [#LX01](#lx01) |
| Davi     | Criação dos léxicos #LX02, #LX03 | [#LX02](#lx02) · [#LX03](#lx03)|
| Fábio     | Criação dos léxicos #LX04, #LX05 | [#LX04](#lx04) · [#LX05](#lx05)|
| Gabriela     | Criação dos léxicos #LX06, #LX07, #LX08 | [#LX06](#lx06) · [#LX07](#lx07) · [#LX08](#lx08) |
| Luiz     | Criação dos léxicos #LX09, #LX10, #LX11 | [#LX09](#lx09) · [#LX10](#lx10) · [#LX11](#lx11) |
| Ana Clara     | Criação dos léxicos #LX12, #LX13 | [#LX12](#lx12) · [#LX13](#lx13) |
| Mateus     | Criação dos léxicos #LX14 | [#LX14](#lx14)|

## Léxicos

<a id="lx01"></a>

## #LX01 - Léxico para #UC01 (Exclusão automática de dados de upload)

| ID       | Noção                    | Impacto                                                                                    | Classificação | Dicionário                      | Rastreamento |
| -------- | ------------------------ | ------------------------------------------------------------------------------------------ | ------------- | ------------------------------- | ------------ |
| L-UC01-01 | Excluir automaticamente  | Ação realizada pelo sistema sem interferência do usuário, para apagar arquivos temporários | Verbo         | Apagar, Remover, Limpar         | UC01         |
| L-UC01-02 | Dados de Upload          | Arquivos enviados pelo usuário para análise ou uso temporário no sistema                   | Objeto        | Arquivos, Documentos, Entradas  | UC01       |
| L-UC01-03 | Tempo de retenção        | Período durante o qual os dados de upload permanecem armazenados antes da exclusão         | Estado        | Duração, Intervalo, Período     | UC01       |
| L-UC01-04 | Sessão do Usuário        | Período ativo de uso da aplicação, durante o qual uploads podem ser realizados             | Estado        | Login, Atividade, Sessão        | UC01      |
| L-UC01-05 | Armazenamento Temporário | Espaço lógico destinado a guardar arquivos que serão automaticamente excluídos             | Objeto        | Cache, Memória transitória      | UC01       |
| L-UC01-06 | Processo de verificação  | Rotina automatizada que verifica se o tempo de retenção expirou                            | Processo      | Rotina, Monitoramento, Checagem | UC01      |
| L-UC01-07 | Log de Exclusão          | Registro interno de que o dado foi excluído automaticamente pelo sistema                   | Objeto        | Registro, Histórico de eventos  | UC01     |

<div align="center">
    Autor: <a href="https://github.com/anajoyceamorim">@Ana Joyce</a>
</div>

---

<a id="lx02"></a>

## #LX02 -Léxico para #UC02 (Integração com Plataformas Externas) - (#RF37)

| ID          | Noção                         | Impacto                                                                                  | Classificação |  Dicionário |Rastreamento                            |
|-------------|-------------------------------|-------------------------------------------------------------------------------------------|----------------|------------ |----------------------------------------|
| L-UC02-01   | Integração com Plataformas Externas | Ampliará o escopo de busca, exigindo gerenciamento de permissões, tokens de acesso e segurança de dados. | Verbo         | Conectar, Integrar, Vincular           |UC02        |
| L-UC02-02   | Token de Acesso                | Elemento de autenticação que garante segurança na comunicação com plataformas externas.  | Objeto        | Chave, Autenticação, Credencial        |UC02        |
| L-UC02-03   | Permissão                      | Define o que pode ser acessado ou manipulado nas plataformas externas.                   | Objeto        | Acesso, Autorização, Controle          |UC02        |
| L-UC02-04   | Plataforma Externa             | Sistemas ou serviços de terceiros conectados ao DeepSeek para busca de dados.            | Objeto        | API, Serviço, Repositório              |UC02        |
| L-UC02-05   | Segurança de Dados             | Conjunto de práticas e mecanismos que protegem os dados acessados externamente.          | Objeto        | Criptografia, Proteção, Privacidade    |UC02        |
| L-UC02-06   | Fonte Autorizada               | Origem de dados validada pelo usuário para integração com o sistema.                     | Objeto        | Origem confiável, Autorização, Fonte   |UC02        |

<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

---

<a id="lx03"></a>

## #LX03 - Léxico para #UC03 (Integração com Voz) - (#RF34)

| ID        | Noção              | Impacto                                                                 | Classificação | Dicionário                      | Rastreamento |
|-----------|--------------------|--------------------------------------------------------------------------|----------------|----------------------------------|---------------|
| L-UC03-01 | Comandar           | Permite que o usuário controle o sistema usando comandos de voz.        | Verbo          | Falar, Instruir, Ordenar         | UC03          |
| L-UC03-02 | Ouvir              | Ação do sistema de escutar o que o usuário diz.                          | Verbo          | Escutar, Captar áudio            | UC03          |
| L-UC03-03 | Reconhecimento     | Processo de identificar o que foi dito pelo usuário.                     | Objeto         | Reconhecimento de fala           | UC03          |
| L-UC03-04 | Responder          | Ato de gerar uma resposta falada ao usuário.                             | Verbo          | Falar, Responder em voz          | UC03          |
| L-UC03-05 | Acessibilidade     | Melhoria na usabilidade para pessoas com dificuldades de digitação.      | Objeto         | Inclusão, Usabilidade            | UC03          |

<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

---

<a id="lx04"></a>

## #LX04 - Léxico para #UC04 (Permite que o usuário selecione diferentes versões/modelos de IA no DeepSeek)

| ID        | Noção                  | Impacto                                                                                           | Classificação | Dicionário                                 | Rastreamento |
| --------- | ---------------------- | ------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------ | ------------ |
| L-UC04-01 | Modelo de IA           | Versão específica de um sistema de inteligência artificial com características distintas.        | Objeto        | R1, R2, R3, versão, instância              | UC04        |
| L-UC04-02 | Selecionar             | Ação de escolher um modelo de IA dentre as opções disponíveis no DeepSeek.                       | Verbo         | Escolher, trocar, alterar, definir         | UC04         |
| L-UC04-03 | Resposta da IA         | Conteúdo gerado pelo modelo de IA com base em uma entrada do usuário.                           | Objeto        | Texto, saída, solução, análise             | UC04         |
| L-UC04-04 | Comparar respostas     | Ato de analisar diferentes saídas fornecidas pelos modelos para uma mesma pergunta.              | Verbo         | Avaliar, analisar, cotejar, contrastar     | UC04        |
| L-UC04-05 | Experiência de uso     | Vivência do usuário ao interagir com a IA, influenciada pela escolha do modelo.                 | Estado        | Satisfação, controle, fluidez              | UC04         |

<div align="center">
    Autor: <a href="https://github.com/fabinsz">@Fabio</a>
</div>

---

<a id="lx05"></a>

## #LX05 - Léxico para #UC05 (Acessar configurações para alterar o tema do Sistema)

| ID        | Noção                           | Impacto                                                                                                                                          | Classificação | Dicionário                                    | Rastreamento                        |
|-----------|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|---------------|-----------------------------------------------|-------------------------------------|
| L-UC05-01 | Tema do Sistema                  | Influencia diretamente a experiência visual, conforto de uso e acessibilidade. Pode impactar também o desempenho em dispositivos com economia de energia. | Estado        | aparência, esquema de cores, layout visual, modo visual | UC05                 |
| L-UC05-02 | Configurações                    | Permite ao usuário adaptar a ferramenta às suas necessidades e preferências, promovendo usabilidade e satisfação.                                 | Objeto        | ajustes, preferências, opções do sistema | UC05        |
| L-UC05-03 | Alterar Tema                     | Garante acessibilidade e conforto visual, além de alinhar a aparência do sistema às preferências do usuário.                                     | Verbo         | mudar visual, trocar modo de exibição, personalizar interface | UC05                 |

<div align="center">
    Autor: <a href="https://github.com/fabinsz">@Fabio</a>
</div>

---

<a id="lx06"></a>

## #LX06 - Léxico para #UC06 (Upload de Documento)

| ID        | Noção               | Impacto                                                       | Classificação | Dicionário                      | Rastreamento |
| --------- | ------------------- | ------------------------------------------------------------- | ------------- | ------------------------------- | ------------ |
| L-UC01-02 | Upload de Documento | Enviar PDF ao DeepSeek para conversão em texto                | Verbo         | Subir arquivo, Enviar documento | UC01         |
| L-UC01-03 | PDF                 | Arquivo no formato Portable Document Format                   | Objeto        | Documento, Arquivo PDF          | UC01         |
| L-UC01-05 | Spinner             | Indicador visual de carregamento durante o processamento      | Objeto        | Indicador de progresso          | UC01         |
| L-UC01-06 | Texto Extraído      | Conteúdo convertido do PDF em texto                           | Objeto        | Conteúdo processado             | UC01         |

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>

---

<a id="lx07"></a>

## #LX07 - Léxico para #UC07 (Consulta Atualizada via Search na Web)

| ID        | Noção     | Impacto                                                        | Classificação | Dicionário                 | Rastreamento |
| --------- | --------- | -------------------------------------------------------------- | ------------- | -------------------------- | ------------ |
| L-UC02-01 | Search    | Módulo que realiza consultas na web sem sair da plataforma     | Sujeito       | Busca web, Pesquisa online | UC02         |
| L-UC02-02 | Query     | Texto de busca inserido pelo usuário                           | Objeto        | Termo de pesquisa, String  | UC02         |
| L-UC02-03 | Copy      | Ação de copiar o trecho retornado para a área de transferência | Verbo         | Copiar, Duplicar           | UC02         |
| L-UC02-04 | Node.js   | Ambiente de execução JavaScript                                | Objeto        | Plataforma Node            | UC02         |
| L-UC02-05 | Resultado | Trecho retornado pela consulta, contendo versão e data         | Objeto        | Retorno, Resposta          | UC02         |

--

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>

---

<a id="lx08"></a>

## #LX08 - Léxico para #UC08 (Iteração de Resposta com Feedback)

| ID        | Noção      | Impacto                                                                      | Classificação | Dicionário            | Rastreamento |
| --------- | ---------- | ---------------------------------------------------------------------------- | ------------- | --------------------- | ------------ |
| L-UC03-02 | Like       | Avaliação positiva que sinaliza satisfação com a resposta                    | Verbo         | Curtir, Aprovar       | UC03         |
| L-UC03-03 | Dislike    | Avaliação negativa que aciona feedback para nova geração de conteúdo         | Verbo         | Reprovar, Não curtir  | UC03         |
| L-UC03-04 | Regenerate | Comando que solicita ao sistema gerar novamente o texto com base no feedback | Verbo         | Regenerar, Refazer    | UC03         |
| L-UC03-05 | Copy       | Ação de copiar a resposta final para a área de transferência                 | Verbo         | Copiar, Duplicar      | UC03         |
| L-UC03-06 | Feedback   | Comentário do usuário que orienta ajustes na geração de texto                | Objeto        | Avaliação, Comentário | UC03         |

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>

---

<a id="lx09"></a>

## #LX09 - Léxico para #UC09 (Uso da função Pensamento Profundo)

| ID        | Noção                     | Impacto                                                                                                                                       | Classificação | Dicionário                     | Rastreamento |
| --------- | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------ | ------------ |
| L-UC04-01 | Chat                      | Campo de interação no qual o usuário insere perguntas e visualiza respostas do DeepSeek.                                                       | Objeto        | Conversa                       | UC04         |
| L-UC04-02 | Equação                   | Entrada de texto representando um problema matemático.                                                                                         | Objeto        | Problema                       | UC04         |
| L-UC04-03 | Pensamento Profundo (R1)  | Modo do DeepSeek que permite a visualização do seu fluxo de pensamento junto com a resposta, direcionado para resolver perguntas complexas.    | Verbo         | Modo de resolução              | UC04         |
| L-UC04-04 | Fluxo de pensamento       | Sequência de passos do DeepSeek para resolver um determinado problema.                                                                         | Objeto        | Linha de raciocínio            | UC04         |
| L-UC04-05 | Modelo R1                 | Modelo mais avançado do DeepSeek, treinado para resolver problemas de lógica, como exercícios de matemática e programação.                     | Objeto        | Modelo, Inteligência artificial| UC04         |

<div align="center">
    Autor: <a href="https://github.com/Luizfaria1989">@Luiz</a>
</div>

---

<a id="lx10"></a>

## #LX10 - Léxico para #UC10 (Cancelamento de mensagem que está sendo gerada pela IA)

| ID        | Noção                     | Impacto                                                                                                                                       | Classificação | Dicionário                     | Rastreamento |
| --------- | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------ | ------------ |
| L-UC05-01 | Cancelar                      | Interromper a geração de uma mensagem que está sendo feita pela IA.                                                   | Verbo        | Interromper, parar, abortar                       | UC05         |
| L-UC05-02 | Mensagem em andamento                   | Mensagem ainda não finalizada pela IA, que está sendo gerada no momento.                                                                                      | Objeto        | Resposta em andamento, mensagem parcial                       | UC05         |
| L-UC05-03 | Usuário  | Pessoa que utiliza o app DeepSeek para interagir com a IA.   | Sujeito         | Operador, cliente             | UC05         |
| L-UC05-04  | Conexão ativa | Estado em que o aplicativo e a IA estão conectados permitindo o fluxo de mensagens | Estado | Conectado, online. | UC05 |

<div align="center">
    Autor: <a href="https://github.com/Luizfaria1989">@Luiz</a>
</div>

---

<a id="lx11"></a>

## #LX11 - Léxico para #UC11 (Visualização do status do servidor em tempo real)

| ID        | Noção                     | Impacto                                                                                                                                       | Classificação | Dicionário                     | Rastreamento |
| --------- | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------ | ------------ |
| L-UC06-01 | Visualizar                     | Ação de perceber a mensagem escrita no topo da tela do app.                                         | Verbo        | Ver, consultar, conferir, checar                       | UC06         |
| L-UC06-02 | Status do servidor                   | Informação em tempo real que indica o estado atual do servidor. | Objeto        | Situação do servidor, condição do servidor                      | UC06         |
| L-UC06-03 | Servidor em manutenção  | Estado em que o servidor está indisponível para ser utilizado pelo usuário para que ele interaja com a IA.   | Estado         | Indisponível, em reparo, offline              | UC06         |
| L-UC06-04 | Servidor funcionando normalmente      | Estado em que o servidor está disponível para ser utilizado pelo usuário para que ele interaja com a IA.                                                                       | Estado       | Online, disponível           | UC06         |

<div align="center">
    Autor: <a href="https://github.com/Luizfaria1989">@Luiz</a>
</div>

---

<a id="lx12"></a>

## #LX12 - Léxico para #UC12 (Tutorial Interativo)

| ID         | Noção                                            | Impacto                                                                 | Classificação | Dicionário                | Rastreamento |
|------------|--------------------------------------------------|------------------------------------------------------------------------|---------------|---------------------------|--------------|
| L-UC12-01   | Tutorial                                         | Conjunto de instruções interativas para ensinar o uso da plataforma    | Objeto        | Guia, Manual  | UC12          |
| L-UC12-02   | Introdução                                       | Explicação sobre o propósito do tutorial                       | Objeto        | Apresentação inicial      | UC12          |
| L-UC12-03   | Finalizar o Tutorial                          | Ação de concluir o tutorial, permitindo que o usuário retorne à plataforma | Verbo        | Concluir, Terminar        | UC12          |
| L-UC12-04   | Notificação de Conclusão                        | Aviso exibido ao usuário quando o tutorial é concluído com sucesso     | Objeto        | Alerta, Mensagem final    | UC12          |
| L-UC12-05   | Sistema                                    | Plataforma utilizada para realizar a interação com o usuário e controlar a limpeza do histórico | Objeto        | DeepSeek, Plataforma      | UC12          |
| L-UC12-06   | Concluído                                       | Estado em que o tutorial já foi utilizado uma vez pelo usuário                           | Estado       | Finalizado, Assistido        | UC12          |

<div align="center">
    Autor: <a href="https://github.com/anabborges">@Ana Clara</a>
</div>

---

<a id="lx13"></a>

## #LX13 - Léxico para #UC13 (Exclusão do histórico de conversas)

| ID         | Noção                                            | Impacto                                                                 | Classificação | Dicionário                | Rastreamento |
|------------|--------------------------------------------------|------------------------------------------------------------------------|---------------|---------------------------|--------------|
| L-UC13-01   | Limpar Histórico                                 | Ação de remover todas as conversas do usuário armazenadas no sistema | Verbo        | Apagar, Excluir           | UC13          |
| L-UC13-02   | Histórico                                       | Registro das conversas antigas realizadas no sistema                  | Objeto        | Conversas antigas        | UC13          |
| L-UC13-03   | Confirmar                                      | Processo de solicitação de confirmação para garantir que o usuário deseja excluir o histórico | Verbo        | Validar, Autorizar       | UC13          |
| L-UC13-04   | Mensagem de Confirmação                          | Aviso exibido ao usuário, perguntando se ele tem certeza de que deseja apagar o histórico | Objeto        | Alerta, Aviso | UC13          |
| L-UC13-05   | Notificação de Sucesso                          | Mensagem exibida após a conclusão bem-sucedida do processo de apagar o histórico | Objeto        | Alerta, Mensagem final    | UC13          |
| L-UC13-06   | Sistema                                    | Plataforma utilizada para realizar a interação com o usuário e controlar a limpeza do histórico | Objeto        | DeepSeek, Plataforma      | UC13          |
| L-UC13-07   | Estado do Histórico                             | Condição atual das conversas armazenadas no sistema antes da exclusão | Estado        | Histórico, Registros      | UC13          |

<div align="center">
    Autor: <a href="https://github.com/anabborges">@Ana Clara</a>
</div>

---

<a id="lx14"></a>

## #LX14 - Léxico para #UC14 (Resumo de Vídeos do YouTube)

| ID        | Noção                 | Impacto                                                       | Classificação | Dicionário                      | Rastreamento |
| --------- | --------------------- | ------------------------------------------------------------- | ------------- | ------------------------------- | ------------ |
| L-UC14-01 | Usuário               | Pessoa que interage com o sistema DeepSeek para gerar o resumo de vídeos. | Objeto        | Cliente, operador              | UC14         |
| L-UC14-02 | Chat                  | Interface do aplicativo onde o usuário interage com o sistema. | Objeto        | Conversa, interface            | UC14         |
| L-UC14-03 | Link do YouTube       | Endereço de um vídeo válido do YouTube inserido pelo usuário no chat. | Objeto        | URL, vídeo online              | UC14         |
| L-UC14-04 | Resumo do vídeo       | Texto gerado a partir do conteúdo do vídeo processado pela IA. | Objeto        | Síntese, sumário               | UC14         |
| L-UC14-05 | Botão "Resumir"       | Elemento interativo que permite ao usuário solicitar o resumo do vídeo. | Objeto        | Atalho, comando                | UC14         |
| L-UC14-06 | Inserir link          | Ação do usuário ao enviar um link de vídeo do YouTube no chat. | Verbo         | Adicionar, enviar              | UC14         |
| L-UC14-07 | Clicar no botão "Resumir" | Ação do usuário ao ativar a funcionalidade de resumo. | Verbo         | Pressionar, selecionar         | UC14         |
| L-UC14-08 | Processar vídeo       | Ação do sistema ao acessar o link e extrair informações do vídeo. | Verbo         | Analisar, interpretar          | UC14         |
| L-UC14-09 | Gerar resumo          | Processo automatizado realizado pelo sistema para sintetizar o conteúdo do vídeo. | Verbo         | Criar sumário, sintetizar      | UC14         |
| L-UC14-10 | Usuário logado        | Indica que o usuário autenticou sua conta e pode utilizar funcionalidades do sistema. | Estado        | Autenticado, conectado         | UC14         |
| L-UC14-11 | Vídeo válido          | Indica que o link enviado refere-se a um vídeo disponível e acessível. | Estado        | Disponível, acessível         | UC14         |
| L-UC14-12 | Processamento concluído | Estado final após a IA gerar o resumo do vídeo. | Estado        | Finalizado, completo           | UC14         |
| L-UC14-13 | Erro de rede          | Indica que houve falha na conexão com a internet. | Estado        | Falha de conexão, offline      | UC14         |
| L-UC14-14 | Link inválido         | Indica que o link inserido pelo usuário está corrompido ou não existe. | Estado        | URL incorreta, erro de link    | UC14         |
| L-UC14-15 | Vídeo indisponível    | Indica que o vídeo foi removido, privado ou restrito. | Estado        | Removido, inacessível          | UC14         |
| L-UC14-16 | Falha na geração do resumo | Indica que ocorreu um erro no processamento do vídeo. | Estado        | Erro de processamento, falha na síntese | UC14         |
| L-UC14-17 | Alucinação de IA      | Indica que o sistema gerou um resumo incorreto ou sem fundamento. | Estado        | Erro de interpretação, resposta incorreta | UC14         |

<div align="center">
    Autor: <a href="https://github.com/MVConsorte">@Mateus</a>
</div>

---

## Bibliografia

> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 10/05/2025.

> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 10/05/2025.

> JIMENEZ, Magda Alexandra Trujillo. Summarization of video from Feature Extraction Method using Image Processing & Artificial Intelligence [em linha]. 2018.

> SUN, Maojin. An intelligent retrieval method for audio and video content: deep learning technology based on artificial intelligence. IEEE Access, 2024.


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 10/05/2025 |  1.0   | (#LX01) Definições iniciais. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.1   | (#LX01) Adição de conteúdo desenvolvido.  | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 11/05/2025 |  1.2   | (#LX01) Adição de conteúdo desenvolvido.  | [@Luiz](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 14/05/2025 |  1.3   | (#LX01) Adição de conteúdo desenvolvido.  | [@Davi Emanuel](https://github.com/daviRolvr)   | [@Luiz](https://github.com/luizfaria1989) |
| 17/05/2025 |  1.4   | (#LX01) Adição de conteúdo desenvolvido.  | [@Luiz](https://github.com/luizfaria1989)   | [Davi Emanuel@](https://github.com/daviRolvr) |
| 17/05/2025 |  1.5  | (#LX01) Adição de conteúdo desenvolvido.  | [@Fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 18/05/2025 |  1.6   | (#LX01) Adição de conteúdo desenvolvido.  | [@Ana Borges](https://github.com/anabborges)   | [Davi Emanuel@](https://github.com/daviRolvr) |
| 18/05/2025 |  1.7  | (#LX01) Adição de conteúdo desenvolvido. | [@Ana Joyce](https://github.com/anajoyceamorim)   | [@Luiz](https://github.com/luizfaria1989) |
| 18/05/2025 |  1.8  | (#LX01) Adição de conteúdo desenvolvido e correção na estrutura de indexação dos léxicos e sua associação com caso de uso. | [@Mateus](https://github.com/MVConsorte)   | [@Luiz](https://github.com/luizfaria1989) |
| 05/06/2025 |  2.0  | (#LX01) Adição dos ids para os léxicos desenvolvidos. | [@Luiz](https://github.com/luizfaria1989)   | [@](https://github.com/) |
| 06/06/2025 |  2.1  | (#LX01) Adição da tabela de contribuições e dos hiberlinks para as tabelas de léxicos desenvolvidas.| [@Luiz](https://github.com/luizfaria1989)  | [@](https://github.com/)  |
