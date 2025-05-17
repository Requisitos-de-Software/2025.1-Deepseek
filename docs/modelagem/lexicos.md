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

## Léxicos

### Léxico para UC01 (Upload de Documento)

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

### Léxico para UC02 (Consulta Atualizada via Search na Web)

| ID        | Noção     | Impacto                                                        | Classificação | Dicionário                 | Rastreamento |
| --------- | --------- | -------------------------------------------------------------- | ------------- | -------------------------- | ------------ |
| L-UC02-01 | Search    | Módulo que realiza consultas na web sem sair da plataforma     | Sujeito       | Busca web, Pesquisa online | UC02         |
| L-UC02-02 | Query     | Texto de busca inserido pelo usuário                           | Objeto        | Termo de pesquisa, String  | UC02         |
| L-UC02-03 | Copy      | Ação de copiar o trecho retornado para a área de transferência | Verbo         | Copiar, Duplicar           | UC02         |
| L-UC02-04 | Node.js   | Ambiente de execução JavaScript                                | Objeto        | Plataforma Node            | UC02         |
| L-UC02-05 | Resultado | Trecho retornado pela consulta, contendo versão e data         | Objeto        | Retorno, Resposta          | UC02         |

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>
---

### Léxico para UC03 (Iteração de Resposta com Feedback)

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

### Léxico para UCXX (Integração com Plataformas Externas) - (#RF37)

<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

| ID          | Noção                         | Impacto                                                                                  | Classificação |  Dicionário |Rastreamento                            |
|-------------|-------------------------------|-------------------------------------------------------------------------------------------|----------------|------------ |----------------------------------------|
| L-UC04-01   | Integração com Plataformas Externas | Ampliará o escopo de busca, exigindo gerenciamento de permissões, tokens de acesso e segurança de dados. | Verbo         | Conectar, Integrar, Vincular           |UC04        |
| L-UC04-02   | Token de Acesso                | Elemento de autenticação que garante segurança na comunicação com plataformas externas.  | Objeto        | Chave, Autenticação, Credencial        |UC04        |
| L-UC04-03   | Permissão                      | Define o que pode ser acessado ou manipulado nas plataformas externas.                   | Objeto        | Acesso, Autorização, Controle          |UC04        |
| L-UC04-04   | Plataforma Externa             | Sistemas ou serviços de terceiros conectados ao DeepSeek para busca de dados.            | Objeto        | API, Serviço, Repositório              |UC04        |
| L-UC04-05   | Segurança de Dados             | Conjunto de práticas e mecanismos que protegem os dados acessados externamente.          | Objeto        | Criptografia, Proteção, Privacidade    |UC04        |
| L-UC04-06   | Fonte Autorizada               | Origem de dados validada pelo usuário para integração com o sistema.                     | Objeto        | Origem confiável, Autorização, Fonte   |UC04        |

<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

### Léxico para UCXX (Explicação de Fontes) - (#RF14)
<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

| ID          | Noção                   | Impacto                                                                                               | Classificação | Dicionário    |Rastreamento                     |
|-------------|-------------------------|--------------------------------------------------------------------------------------------------------|----------------|------------------------------------|------------------|
| L-UC05-01   | Explicação de Fontes    | Melhora a transparência do sistema e a confiança do usuário, mas exige mecanismos de explicação robustos. | Verbo         | Justificar, Esclarecer, Informar  |UC05  
| L-UC05-02   | Transparência           | Grau de clareza e abertura nas decisões do sistema sobre os resultados exibidos.                      | Objeto        | Clareza, Visibilidade, Abertura    |UC05  
| L-UC05-03   | Confiança do Usuário    | Percepção de segurança e credibilidade gerada ao entender os critérios de seleção dos resultados.     | Objeto        | Segurança, Credibilidade, Certeza  |UC05  
| L-UC05-04   | Mecanismos de Explicação| Conjunto de métodos ou algoritmos usados para justificar as escolhas do sistema.                      | Objeto        | Algoritmo, Justificativa, Regras   | UC05 
<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>
### Léxico para UC06 (Integração com Voz) - (#RF34)

<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

| ID        | Noção              | Impacto                                                                 | Classificação | Dicionário                      | Rastreamento |
|-----------|--------------------|--------------------------------------------------------------------------|----------------|----------------------------------|---------------|
| L-UC06-01 | Comandar           | Permite que o usuário controle o sistema usando comandos de voz.        | Verbo          | Falar, Instruir, Ordenar         | UC06          |
| L-UC06-02 | Ouvir              | Ação do sistema de escutar o que o usuário diz.                          | Verbo          | Escutar, Captar áudio            | UC06          |
| L-UC06-03 | Reconhecimento     | Processo de identificar o que foi dito pelo usuário.                     | Objeto         | Reconhecimento de fala           | UC06          |
| L-UC06-04 | Responder          | Ato de gerar uma resposta falada ao usuário.                             | Verbo          | Falar, Responder em voz          | UC06          |
| L-UC06-05 | Acessibilidade     | Melhoria na usabilidade para pessoas com dificuldades de digitação.      | Objeto         | Inclusão, Usabilidade            | UC06          |
<div align="center">
    Autor: <a href="https://github.com/daviRolvr">@Davi Emanuel</a>
</div>

### Léxico para UC04 (Uso da função Pensamento Profundo)

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

### Léxico para UC05 (Cancelamento de mensagem que está sendo gerada pela IA )

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

### Léxico para UC06 (Visualização do status do servidor em tempo real)

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

## Bibliografia

> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 10/05/2025.

> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 10/05/2025.


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 10/05/2025 |  1.0   | (#LX01) Definições iniciais. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.1   | (#LX01) Adição de conteúdo desenvolvido.  | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 11/05/2025 |  1.2   | (#LX01) Adição de conteúdo desenvolvido.  | [@Luiz](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 14/05/2025 |  1.3   | (#LX01) Adição de conteúdo desenvolvido.  | [@Davi Emanuel](https://github.com/daviRolvr)   | [@Luiz](https://github.com/luizfaria1989) |
| 17/05/2025 |  1.4   | (#LX01) Adição de conteúdo desenvolvido.  | [@Luiz](https://github.com/luizfaria1989)   | [Davi Emanuel@](https://github.com/daviRolvr) |
