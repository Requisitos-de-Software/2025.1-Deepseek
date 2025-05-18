## Casos de Uso

## Introdução
Os diagramas de caso de uso são uma ferramenta fundamental da linguagem de modelagem unificada (UML) que permitem representar graficamente as funcionalidades esperadas de um sistema do ponto de vista de seus usuários. Essa técnica é amplamente utilizada na engenharia de requisitos para descrever as interações entre os atores (usuários ou sistemas externos) e os serviços oferecidos pela aplicação. No contexto do projeto DeepSeek, a modelagem dos casos de uso contribui para a compreensão do comportamento do sistema sob diferentes perspectivas de interação, facilitando a comunicação entre stakeholders técnicos e não técnicos, e servindo como base para futuras etapas de projeto, desenvolvimento e testes.

## Metodologia
A modelagem dos casos de uso do DeepSeek foi conduzida com base nos princípios da UML, utilizando diagramas e descrições textuais conforme recomendação da literatura especializada. Inicialmente, identificaram-se os atores relevantes do sistema, como usuários finais, administradores e sistemas externos. Em seguida, foram definidos os principais casos de uso que representam as funcionalidades que o sistema deverá oferecer a esses atores. Os diagramas foram elaborados por meio da ferramenta Lucidchart, e cada caso de uso foi descrito com os seguintes elementos: nome, objetivo, atores envolvidos, fluxo de eventos (principal e alternativos), pré-condições, pós-condições e exceções. Essa abordagem visual e textual permite alinhar expectativas entre os envolvidos no projeto e fornecer uma visão clara do escopo funcional da aplicação.

## Casos de Uso Modelados:

## Ana Joyce
## [#UCXX] -  Exclusão automática de dados de upload
**Autor:** [Ana Joyce](https://github.com/anajoyceamorim)

| #UCXX | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | O sistema deve excluir automaticamente os dados enviados via upload após determinado período ou após o uso concluído, garantindo segurança e privacidade. |
| Ator              | Sistema                                                                      |
| Pré-condições     | O usuário realizou um upload de arquivo (documento, imagem, PDF, etc.) para uso temporário no DeepSeek.    |
| Ação              | O sistema verifica uploads armazenados e realiza exclusão automática conforme a política de retenção definida.   |
| Fluxo principal   | 	<ul><li>O usuário realiza o upload de um arquivo temporário</br><ul><li>O sistema processa o conteúdo e o utiliza conforme a solicitação do usuário</br><li>Após finalização da tarefa, inicia-se a contagem de tempo para retenção temporária</br><li>O sistema verifica periodicamente os arquivos expirados</br><li>Arquivos vencidos são excluídos automaticamente</br><li>Um log interno é registrado para fins de auditoria</li></ul></li></ul> |
| Fluxo alternativo | <ul><li>O usuário encerra a sessão sem usar o conteúdo do upload</br><ul><li>O sistema aplica o mesmo ciclo de exclusão após o tempo padrão</li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Erro no mecanismo de exclusão automática</br><ul><li>O sistema registra a falha e envia alerta para manutenção interna</li></ul></li></ul> |
| Pós-condições     | Arquivos temporários são removidos automaticamente; nenhum dado de upload permanece após o período estabelecido.  |
| Data de Criação   | 18/05/2025        |
| Rastreabilidade   | #RN04 — Exclusão automática de dados de upload #RIN11 — Requisito relacionado à segurança de dados   |

## Davi
## [#UCXX] - Permite que o usuário use o DeepSeek e o integre com plataformas Externas.
**Autor:** [Davi Emanuel](https://github.com/daviRolvr)

| #UCXX | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | 	O usuário pode conectar plataformas externas (GitHub, Google, LinkedIn, Discord) ao DeepSeek para ampliar fontes de informação. |
| Ator              | 	Usuário                                                                                                         |
| Pré-condições     | 	Acesso à internet, conta em plataformas externas, autorização do usuário para integração.                                                          |
| Ação              | O usuário integra uma ou mais plataformas externas ao DeepSeek.                                                      |
| Fluxo principal   | <ul><li>Usuário abre o DeepSeek</br><ul><li>O usuário acessa a aba de integrações</br><ul><li>Seleciona uma plataforma (ex: GitHub)</br><ul><li>Autoriza o acesso via token ou login OAuth</br></li></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li>O usuário tenta integrar, mas não tem sessão ativa na plataforma</br><ul><li>O DeepSeek redireciona para login externo e, após sucesso, finaliza a integração</br>|
| Fluxo de exceção  | <ul><li>A autorização da plataforma externa é negada ou expira</br><ul><li>O sistema informa falha na conexão e sugere nova tentativa</br> |
| Pós-condições     | O DeepSeek pode acessar dados autorizados das plataformas externas para enriquecer as respostas ou contexto do usuário.                    |
| Data de Criação   | 17/05/2025                                                                                                     |
| Rastreabilidade   | #RF37     |

## [#UCXX] - Permite que o usuário use o Deepseek com a funcionalidade de integração por Voz.
**Autor:** [Davi Emanuel](https://github.com/daviRolvr)

| #UCXX | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | 		O usuário é capaz de realizar perguntas ao DeepSeek por meio de comandos de voz. |
| Ator              | 		Usuário                                                                                                     |
| Pré-condições     | Acesso à internet, microfone habilitado, permissão concedida ao app para uso de áudio.                                                         |
| Ação              | O usuário interage com o DeepSeek por comando de voz para realizar perguntas ou pesquisas.                                                   |
| Fluxo principal   | <ul><li>O usuário acessa o aplicativo</br><ul><li>Ativa o modo de entrada por voz</br><ul><li>Faz uma pergunta verbalmente</br><ul><li>O DeepSeek converte voz em texto e responde</br></li></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo</br><ul><li>Ativa o modo de entrada por voz</br><ul><li>Sistema detecta ausência de fala</br><ul><li> Solicita nova tentativa ou oferece teclado como alternativa|
| Fluxo de exceção  | <ul><li>O microfone do usuário está desativado ou bloqueado</br><ul><li>O sistema exibe mensagem de erro solicitando ativação do microfone</br> |
| Pós-condições     | O usuário recebe a resposta para sua pergunta em texto.                    |
| Data de Criação   | 17/05/2025                                                                                                     |
| Rastreabilidade   | #RF14     |
                                                                                      
## Fabio

## [UCXX] - Permite que o usuário selecione diferentes versões/modelos de IA no DeepSeek
**Autor:** [Fabio](https://github.com/fabinsz)

| #UCXX | Informações                                                                                                                                      |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Descrição**         | Permite que o usuário selecione diferentes versões de modelos de IA (ex: R1, R2, R3) no DeepSeek, personalizando o estilo e a profundidade das respostas. |
| **Ator**              | Júlia                                                                                                                           |
| **Pré-condições**     | Estar com o DeepSeek aberto e com conexão à internet.                                                                            |
| **Ação**              | Júlia decide escolher o modelo que melhor se adequa à sua necessidade de resposta antes de enviar uma pergunta à IA.            |
| **Fluxo principal**   | <ul><li>Júlia abre o DeepSeek</br><ul><li>Seleciona “Modelos de IA” no canto superior direito</br><ul><li>Visualiza as opções R1, R2 e R3 com descrições</br><ul><li>Escolhe o modelo R2 por preferir respostas mais diretas</br><ul><li>Digita sua pergunta no campo de chat</br><ul><li>Clica na seta para enviar</br><ul><li>Lê a resposta gerada pelo modelo R2</li></ul></li></ul></li></ul></li></ul></li></ul></li></ul> |
| **Fluxo alternativo** | <ul><li>Júlia está insatisfeita com a resposta gerada pelo modelo atual</br><ul><li>Retorna à seleção de modelos</br><ul><li>Escolhe o modelo R1 para uma explicação mais aprofundada</br><ul><li>Reenvia a mesma pergunta</br><ul><li>Lê a nova resposta mais detalhada</li></ul></li></ul></li></ul></li></ul> |
| **Fluxo de exceção**  | <ul><li>Ao tentar trocar o modelo, a conexão com o servidor falha</br><ul><li>DeepSeek exibe a mensagem: “Erro ao carregar modelos. Verifique sua conexão.”</br><ul><li>Usuária tenta novamente após restabelecer a internet</li></ul></li></ul></li></ul> |
| **Pós-condições**     | Júlia recebe uma resposta ajustada ao modelo escolhido, com o estilo e profundidade desejados.                                  |
| **Data de Criação**   | 17/05/2025                                                                                                                       |
| **Rastreabilidade**   | #RF32   

## [UCXX] - Permite que o usuário acesse as configurações para alterar o tema do sistema (claro/escuro), ajustando a aparência da interface conforme suas preferências.

**Autor:** [Fabio](https://github.com/fabinsz)

| #UCXX              | Informações                                                                                                                                                     |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**       | Permite que o usuário acesse as configurações do DeepSeek para alterar o tema visual da interface, escolhendo entre tema claro ou escuro, de acordo com suas preferências. |
| **Ator**            | Lucas                                                                                                                                                            |
| **Pré-condições**   | Estar logado no DeepSeek com conexão ativa à internet. Interface carregada.                                                                                      |
| **Ação**            | Lucas deseja mudar o tema do sistema para modo escuro, pois está em um ambiente com pouca luz.                                                                  |
| **Fluxo principal** | <ul><li>Lucas abre o DeepSeek</br><ul><li>Clica no ícone de menu ou perfil</br><ul><li>Seleciona “Configurações”</br><ul><li>Clica em “Tema do Sistema”</br><ul><li>Escolhe “Modo Escuro”</br><ul><li>Confirma a alteração</br><ul><li>A interface do sistema muda imediatamente</li></ul></li></ul></li></ul></li></ul></li></ul></li></ul> |
| **Fluxo alternativo** | <ul><li>Lucas acessa o DeepSeek</br><ul><li>Vai até “Configurações”</br><ul><li>Percebe que o modo escuro já está ativado</br><ul><li>Decide não realizar alterações</li></ul></li></ul></li></ul> |
| **Fluxo de exceção** | <ul><li>Lucas tenta acessar “Configurações”</br><ul><li>A página demora para carregar ou apresenta erro</br><ul><li>DeepSeek exibe mensagem: “Erro ao carregar configurações”</br><ul><li>Lucas recarrega a página e tenta novamente</li></ul></li></ul></li></ul></li></ul> |
| **Pós-condições**   | O sistema permanece com o tema selecionado até nova alteração. A preferência visual do usuário foi respeitada.                                                   |
| **Data de Criação** | 17/05/2025                                                                                                                                                       |
| **Rastreabilidade** | #RF27                                                                                                                |

 


## [#UC01] - Permite que o usuário envie um PDF e receba o texto extraído e insights, preservando formatação e símbolos.
**Autor:** [Gabriela](https://github.com/gaubiela)

| #UC01 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | Permite que o usuário envie um PDF e receba o texto extraído e insights, preservando formatação e símbolos. |
| Ator              | Júlia                                                                                                         |
| Pré-condições     | PDF acessível no dispositivo                                                             |
| Ação              | Júlia faz upload de um PDF e obtém o texto e insights extraídos                                                           |
| Fluxo principal   | <ul><li>Júlia abre o DeepSeek</br><ul><li>Seleciona “Upload de Documento”</br><ul><li>Escolhe o PDF e confirma</br><ul><li>DeepSeek processa apresenta texto e  insights extraídos</br></li></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li>Júlia abre o DeepSeek</br><ul><li>Seleciona “Upload de Documento”</br><ul><li>DeepSeek detecta formato inválido e exibe mensagem de erro</br></li></ul></li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Inicia upload do PDF</br><ul><li>Conexão é perdida</br><ul><li>DeepSeek notifica “Conexão perdida” e oferece retomar</br></li></ul></li></ul></li></ul> |
| Pós-condições     | Texto completo disponível como conteúdo editável; inconsistências sinalizadas para revisão                     |
| Data de Criação   | 10/05/2025                                                                                                     |
| Rastreabilidade   | #RF03, #RN06, #RN08                                                                                            |


---
## [#UC02] - Permite buscar, em menos de 3 s, a versão mais recente do Node.js em 10/05/2025 e copiar o resultado.
**Autor:** [Gabriela](https://github.com/gaubiela)

| #UC02 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | Permite buscar, em menos de 3 s, a versão mais recente do Node.js em 10/05/2025 e copiar o resultado.      |
| Ator              | Pedro                                                                                                         |
| Pré-condições     | Internet ativa; aba **Search** habilitada no DeepSeek                                                        |
| Ação              | Pedro busca a versão do Node.js e copia o trecho retornado                                                   |
| Fluxo principal   | <ul><li>Pedro ativa a aba **Search**</br><ul><li>Digita “versão mais recente do Node.js em 10/05/2025”</br><ul><li>Sistema retorna “Node.js v20.7.0 – lançado em 08/05/2025” e exibe botão **Copy**</br></li></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li>Resultado sem data</br><ul><li>Pedro refina a query para “Node.js versão estável maio 2025” e repete a busca</br></li></ul></li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Consulta demora > 3 s</br><ul><li>Sistema exibe aviso de lentidão com opção “Recarregar”</br></li></ul></li></ul></li></ul> |
| Pós-condições     | Versão documentada no repositório; critério de agilidade validado                                             |
| Data de Criação   | 10/05/2025                                                                                                     |
| Rastreabilidade   | #RF01, #RF13                                                                                                   |


---
## [#UC03] - Permite refinar uma resposta gerada usando **Like/Dislike/Regenerate/Copy** até atingir clareza e concisão.
**Autor:** [Gabriela](https://github.com/gaubiela)

| #UC03 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | Permite refinar uma resposta gerada usando **Like/Dislike/Regenerate/Copy** até atingir clareza e concisão. |
| Ator              | Mariana                                                                                                       |
| Pré-condições     | Resposta inicial gerada; conexão ativa                                                        |
| Ação              | Mariana itera feedback e copia a versão final do texto                                                        |
| Fluxo principal   | <ul><li>Mariana lê o parágrafo inicial</br><ul><li>Clica em **Dislike** e fornece feedback</br><ul><li>Clica em **Regenerate** e aguarda nova versão (~ 1 s)</br></li></ul></li></ul></li></ul><ul><li>Clica em **Like** e depois em **Copy** na versão final</br></li></ul> |
| Fluxo alternativo | <ul><li>Regeneração demora > 3 s</br><ul><li>Sistema exibe botão **Cancelar** para interromper</br></li></ul></li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Feedback não traz mudança satisfatória</br><ul><li>Mariana fornece comentário mais detalhado e regenera novamente</br></li></ul></li></ul></li></ul> |
| Pós-condições     | Parágrafo final satisfatório; avaliação registrada                                                             |
| Data de Criação   | 10/05/2025                                                                                                     |
| Rastreabilidade   | #RF11, #RF12, #RF13, #RF17                                                                                     |

## [UC04] - Permite que o usuário resolva problemas difíceis, como os de matemática, oferecendo o fluxo de pensamento da IA além da resposta. Utiliza o modelo R1 do DeepSeek
**Autor:** [Luiz](https://github.com/luizfari1989)

| #UC04 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | Permite que o usuário resolva problemas difíceis, como os de matemática, oferecendo o fluxo de pensamento da IA além da resposta. Utiliza o modelo R1 do DeepSeek |
| Ator              | Gauss                                                                                                         |
| Pré-condições     | Internet ativa, aba **Pensamento Profundo (R1)**  habilitada no DeepSeek                                                            |
| Ação              | Gauss digita a equação que está com dúvidas e pede para a IA resolvê-la                                                       |
| Fluxo principal   | <ul><li>Gauss abre o DeepSeek</br><ul><li>Seleciona "Pensamento Profundo (R1)"</br><ul><li>Digita a equação do problema que está com dúvidas no chat</br><ul><li>Clica na seta para enviar</br></li><ul><li>Lê a resposta da IA</li></ul></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li>Gauss abre o DeepSeek</br><ul><li>Seleciona “Pensamento Profundo (R1)”</br><ul><li>Percebe que é uma pergunta simples de ser resolvida</br></li><ul><li>Desativa o modo "Pensamento Profundo (R1)"</li></ul></ul></li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Inicia o desenvolvimento da pergunta</br><ul><li>Conexão é perdida</br><ul><li>DeepSeek notifica “Conexão perdida” e oferece retomar</br></li></ul></li></ul></li></ul> |
| Pós-condições     | Texto completo disponível com equações além do fluxo de consciência da IA                  |
| Data de Criação   | 11/05/2025                                                                                                     |
| Rastreabilidade   | #RF02, #RN07  

## [UC05] - Permite que o usuário cancele uma mensagem em andamento da IA no chat
**Autor:** [Luiz](https://github.com/luizfari1989)

| #UC05 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | Permite que o usuário cancele uma mensagem que está sendo gerada pela IA no chat |
| Ator              | João                                                                                                         |
| Pré-condições     | Internet ativa, uma mensagem precisa obrigatoriamente estar sendo gerada pela IA no chat                                                      |
| Ação              | João cancela uma mensagem que está sendo gerada pois ela está incorreta                                     |
| Fluxo principal   | <ul><li>João abre o DeepSeek</br><ul><li>Digita a sua mensagem no chat</br><ul><li>Clica na seta para enviar</br><ul><li>Lê o início da resposta que está sendo gerada pela IA</br><ul><li>Clica em "Interromper mensagem em andamento"</br></li></ul></li></ul></li></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li>João abre o DeepSeek</br><ul><li>Digita a sua mensagem no chat</br><ul><li>Clica na seta para enviar</br><ul><li>Não encontra nenhum problema na mensagem que está sendo gerada pela IA</ul></li><ul></ul></ul></li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Inicia o desenvolvimento da pergunta</br><ul><li>Conexão é perdida</br><ul><li>DeepSeek notifica “Conexão perdida” e oferece a opção de retomar</br></li></ul></li></ul></li></ul> |
| Pós-condições     | Texto gerado parcialmente com a mensagem "Mensagem cancelada pelo usuário" escrita embaixo            |
| Data de Criação   | 16/05/2025                                                                                                     |
| Rastreabilidade   | #RF19

## [UC06] - Permite que o usuário veja o status do servidor, indicando se ele está em manutenção ou disponível para uso do chat da IA
**Autor:** [Luiz](https://github.com/luizfari1989)

| #UC06 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | Permite que o usuário veja o status do servidor da IA, indicando se ele está em manutenção ou funcionando normalmente|
| Ator              | Clarice                                                                                                         |
| Pré-condições     | Internet ativa, Estar na tela de conversa com o DeepSeek                                                            |
| Ação              | Visualizar a mensagem no topo da tela indicando o status do servidor no momento                                             |
| Fluxo principal   | <ul><li>Clarice abre o DeepSeek</br><ul><li>Visualiza a mensagem indicando que o servidor está funcionando normalmente</br><ul><li>Digita sua pergunta para o chat da IA</br><ul></ul></ul></li></ul></li></ul> |
| Fluxo alternativo | <ul><li>Clarice abre o DeepSeek</br><ul><li>Visualiza a mensagem indicando que o servidor está em manutenção</br><ul><li>Fecha o app</br></li><ul></ul></ul></li></ul></li></ul> |
| Fluxo de exceção  | <ul><li>Tenta abrir o app</br><ul><li>Aparece a mensagem "Aplicativo sendo atualizado"</br><ul><li>O app é fechado automaticamente</br></li></ul></li></ul></li></ul> |
| Pós-condições     | O usuário visualiza a mensagem em tempo real do status do servidor                 |
| Data de Criação   | 16/05/2025                                                                                                     |
| Rastreabilidade   | #RF29                                                                                       |

## [UC07] - Permite que o usuário entenda o funcionamento da plataforma a partir de um tutorial interativo
**Autor:** [Ana Clara](https://github.com/anabborges)

| #UC07 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | O usuário é capaz de entender o funcionamento da plataforma por meio de um tutorial interativo. |
| Ator              | Usuário                                                                                          |
| Pré-condições     | Conexão ativa.                                                |
| Ação              | O usuário acessa e segue o tutorial até concluir os passos propostos.                              |
| Fluxo principal   | <ul><li>O usuário clica em “Ver Tutorial” na tela inicial</li> <li>O sistema exibe uma introdução com explicação do objetivo da plataforma</li> <li>O usuário navega pelas seções (ex: “Como começar”, “Dar comandos”, “Usar feedback”)</li> <li>O usuário interage com exemplos sugeridos no tutorial</li> <li>Ao final, clica em “Finalizar tutorial”</li></ul> |
| Fluxo alternativo | <ul><li>O usuário considera o tutorial longo ou repetitivo; O usuário já sabe utilizar a plataforma</li> <li>Clica em “Pular tutorial”</li> <li>Sistema registra a decisão e recomenda revisitar mais tarde</li></ul> |
| Fluxo de exceção  | <ul><li>Erro no carregamento de conteúdo</li> <li>Sistema exibe mensagem “Erro ao carregar o tutorial”</li> <li>O usuário tenta novamente após atualizar a página</li></ul> |
| Pós-condições     | O usuário entende as funcionalidades principais da plataforma; tutorial marcado como concluído. |
| Data de Criação   | 15/05/2025                                                                                      |
| Rastreabilidade   | #RF28                                                                                       |

## [UC08] - Permite que o usuário apague o histórico de conversas, a partir de uma confirmação
**Autor:** [Ana Clara](https://github.com/anabborges)

| #UC08 | Informações                                                                                                    |
| ---- | -------------------------------------------------------------------------------------------------------------- |
| Descrição         | O usuário pode apagar o histórico de conversas, a partir de uma confirmação explícita. |
| Ator              | Usuário                                                                                          |
| Pré-condições     | O usuário está logado na plataforma; histórico existente; conexão ativa.                          |
| Ação              | O usuário acessa a opção de histórico e opta por apagar todas as conversas após confirmação.       |
| Fluxo principal   | <ul><li>O usuário clica em “Histórico” no menu principal</li> <li>Seleciona “Apagar histórico”</li> <li>O sistema exibe um aviso solicitando confirmação</li> <li>O usuário clica em “Confirmar”</li> <li>O sistema apaga todas as conversas do histórico</li></ul> |
| Fluxo alternativo | <ul><li>O usuário clica em “Cancelar” na janela de confirmação</li> <li>O sistema mantém o histórico intacto</li></ul> |
| Fluxo de exceção  | <ul><li>Erro de conexão no momento da exclusão</li> <li>O sistema exibe mensagem: “Erro ao apagar. Verifique sua conexão e tente novamente.”</li></ul> |
| Pós-condições     | Histórico apagado.  |
| Data de Criação   | 15/05/2025                                                                                         |
| Rastreabilidade   | #RF22                                                                                      |

## Bibliografia

> LUCIDCHART. Diagrama de caso de uso UML. Lucidchart. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml. Acesso em: 9 maio 2025.
> DEEPSEEK AI. DeepSeek V3. Disponível em: https://github.com/deepseek-ai/DeepSeek-V  


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 09/05/2025 |  1.0   | (#UCO1) Adição de introdução e metodologia.| [@Ana Joyce](https://github.com/anajoyceamorim)   | [@Gabriela](https://github.com/gaubiela)  |
| 10/05/2025 |  1.0   | (#UCO2) Adição de conteúdo desenvolvido.| [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 11/05/2025 |  1.1   | (#UCO2) Adição de conteúdo desenvolvido.| [@luiz](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 16/05/2025 |  1.2  | (#UCO2) Adição de conteúdo desenvolvido.| [@luiz](https://github.com/luizfaria1989)   | [@Davi Emanuel](https://github.com/daviRolvr) |
|16/05/2025 |  1.3  | (#UCO2) Adição de conteúdo desenvolvido.|  [@Davi Emanuel](https://github.com/daviRolvr)| [@luiz](https://github.com/luizfaria1989) |
|17/05/2025 |  1.4 | (#UCO2) Adição de conteúdo desenvolvido.|  [@Fabio](https://github.com/fabinsz)| [@Luiz](https://github.com/luizfaria1989) |
<<<<<<< HEAD
|18/05/2025 |  1.5 | (#UCO3) Adição de caso de uso Exclusão automática de dados de upload|  [@Ana Joyce](https://github.com/anajoyceamorim)| [@revisor](https://github.com/) |
=======
| 18/05/2025 |  1.5  | (#UCO2) Adição de conteúdo desenvolvido.| [@Ana Borges](https://github.com/anabborges)   | [@](https://github.com) |
>>>>>>> 890e02cc1aee195256f163d033a59017a2c1b140
