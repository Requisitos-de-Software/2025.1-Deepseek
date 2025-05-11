## Casos de Uso

## Introdução
Os diagramas de caso de uso são uma ferramenta fundamental da linguagem de modelagem unificada (UML) que permitem representar graficamente as funcionalidades esperadas de um sistema do ponto de vista de seus usuários. Essa técnica é amplamente utilizada na engenharia de requisitos para descrever as interações entre os atores (usuários ou sistemas externos) e os serviços oferecidos pela aplicação. No contexto do projeto DeepSeek, a modelagem dos casos de uso contribui para a compreensão do comportamento do sistema sob diferentes perspectivas de interação, facilitando a comunicação entre stakeholders técnicos e não técnicos, e servindo como base para futuras etapas de projeto, desenvolvimento e testes.

## Metodologia
A modelagem dos casos de uso do DeepSeek foi conduzida com base nos princípios da UML, utilizando diagramas e descrições textuais conforme recomendação da literatura especializada. Inicialmente, identificaram-se os atores relevantes do sistema, como usuários finais, administradores e sistemas externos. Em seguida, foram definidos os principais casos de uso que representam as funcionalidades que o sistema deverá oferecer a esses atores. Os diagramas foram elaborados por meio da ferramenta Lucidchart, e cada caso de uso foi descrito com os seguintes elementos: nome, objetivo, atores envolvidos, fluxo de eventos (principal e alternativos), pré-condições, pós-condições e exceções. Essa abordagem visual e textual permite alinhar expectativas entre os envolvidos no projeto e fornecer uma visão clara do escopo funcional da aplicação.

## Casos de Uso Modelados:

## Ana Clara

## Ana Joyce

## Davi

## Fabio

## Gabriela

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

## Luiz

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
| Rastreabilidade   | #RF02, #RN07                                                                                          |

## Bibliografia

> LUCIDCHART. Diagrama de caso de uso UML. Lucidchart. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml. Acesso em: 9 maio 2025.
> DEEPSEEK AI. DeepSeek V3. Disponível em: https://github.com/deepseek-ai/DeepSeek-V  


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 09/05/2025 |  1.0   | (#UCO1) Adição de introdução e metodologia.| [@Ana Joyce](https://github.com/anajoyceamorim)   | [@Gabriela](https://github.com/gaubiela)  |
| 10/05/2025 |  1.0   | (#UCO2) Adição de conteúdo desenvolvido.| [@Gabriela](https://github.com/gaubiela)   | -- |
| 11/05/2025 |  1.1   | (#UCO2) Adição de conteúdo desenvolvido.| [@luiz](https://github.com/luizfaria1989)   | -- |