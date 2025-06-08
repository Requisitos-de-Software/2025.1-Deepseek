# Introdução

Este artefato com como objetivo realizar a conexão entre os requisitos elicitados durante o projeto e a sua implementação. Além disso, é ncessário explicar também a dependência desses requisitos os artefatos que foram elaborados com base neles. A rastreabilidade é composta por elos, exibindo a interrelação dos artefatos especificados.

# Metodologia

Para o desenvolvimento de pós-rastreabilidade será utilizado o meta-modelo proprosto por Toranzo. Nele, a rastreabilidade faz uso de quatro estratégias diferentes de trabalho: ele apresenta uma classificação das informações a serem rastreadas, propõe o uso de um meta-modelo para a rastreabilidade além de um modelo intermediário para o rastreamento dos requisitos e ainda inclui um processo para ser um guia para o engenheiro de requisitos na apliacação das outras três técnicas <a id="anchor_1" href="#REF1">[1]</a>.

As informações segundo Toranzo são classificadas em quatro níveis:

* **Ambiental**: Este nível é responsável por congregar as informações oriundas do contexto ambiental no qual a organização está inserida e que podem afetar o sistema que está sendo desenvolvido <a id="anchor_2" href="#REF2">[2]</a>;
* **Organizacional**: Este nível reúne as informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem afetar os requisos do sistema <a id="anchor_2" href="#REF2">[2]</a>;
* **Gerencial**: Esté nível tem como finalidade agrupar as informações relacionadas à gerência do projeto, são informações que permitem relacionar tarefas a requisitos <a id="anchor_2" href="#REF2">[2]</a>;
* **Desenvolvimento**: Esté nível agrupa as informações relacionadas aos diversos artefatos que são gerados no processo de desenvolvimento <a id="anchor_2" href="#REF2">[2]</a>.

No meta-modelo de Toranzo o suporte a rastreabilidade indentica os seguintes tipos de elos:

* **Satisfação** : é responsável por indicar que a classe de origem possui dependência com a classe de destino <a id="anchor_3" href="#REF3">[3]</a>;
* **Recurso**: é responsável por indicar a classe de origem tem dependêcia de recurso com a classe de destino <a id="anchor_3" href="#REF3">[3]</a>;
* **Responsabilidade**: é responsável por indicar participação, responsabilidade e ação das pessoas sobre os artefatos <a id="anchor_3" href="#REF3">[3]</a>;
* **Representação**: é responsável por capturar a representação ou modelagem dos requisitos <a id="anchor_3" href="#REF3">[3]</a>;
* **Alocado**: é responsável por indicar a classe de origem que está relacionada à classe de destino, representando um subsistema <a id="anchor_3" href="#REF3">[3]</a>;
* **Agregação**: é resposnável por indicar a composição de elementos <a id="anchor_3" href="#REF3">[3]</a>.

Com base nesses elos é possível elaborar a Tabela 1, que será usada como template para representar os elos dos artefatos com os requisitos desenvolvidos nesse projeto.

Tabela 1 - Template Pós-Rastreabilidade

|                  **Artefato Analisado**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  -                      |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  -                      |

Autor: Luiz

# Tabela de Contribuições

| Contribuinte | Descrição                                                            | Links                                           |
|--------------|----------------------------------------------------------------------|-------------------------------------------------|
| Luiz    | Criação dos elos para os requisitos #RF01, #RF02, #RF03, #RF04, #RF05, #RF06, #RF06, #RF08 | [#RF01](../rastreabilidade/pos-rastreabilidade.md#rf01), [#RF02](../rastreabilidade/pos-rastreabilidade.md#rf02), [#RF03]((../rastreabilidade/pos-rastreabilidade.md#rf03)), [#RF04](../rastreabilidade/pos-rastreabilidade.md#rf04), [#RF05](../rastreabilidade/pos-rastreabilidade.md#rf05), [#RF06](../rastreabilidade/pos-rastreabilidade.md#rf06), [#RF07](../rastreabilidade/pos-rastreabilidade.md#rf07), [#RF08](../rastreabilidade/pos-rastreabilidade.md#rf08) |
| Fábio    | Criação dos elos para os requisitos #RF09, #RF10, #RF11, #RF12, #RF13, #RF15, #RF16 | [#RF09](../rastreabilidade/pos-rastreabilidade.md#rf09), [#RF10](../rastreabilidade/pos-rastreabilidade.md#rf10), [#RF11]((../rastreabilidade/pos-rastreabilidade.md#rf11)), [#RF12](../rastreabilidade/pos-rastreabilidade.md#rf12), [#RF13](../rastreabilidade/pos-rastreabilidade.md#rf13), [#RF15](../rastreabilidade/pos-rastreabilidade.md#rf15), [#RF16](../rastreabilidade/pos-rastreabilidade.md#rf16)|

# Rastreabilidade

Nesse tópico são apresentadas as tabelas referentes aos elos dos artefatos analisados ao longo do projeto. Assim, cada um dos 52 requisitos elicitados possuem uma tabela semelhante ao template da Tabela 1, com seus artefatos relacionados.

<a id="rf01"></a>
## #RF01 - Deve oferecer a possibilidade do usuário acionar a pesquisa na web

|                  **RF01**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                      |
|                       Recurso                        | [Cenário #CN07](../modelagem/cenarios.md#cn07)                      |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC07](../modelagem/casos-de-uso.md#uc07), <br> [Léxico #LX07](../modelagem/lexicos.md#lx07)                                            |
|                      Agregação                       |                  [História de usuário #HU29](../modelagem/historias-de-usuario.md#hu29)                      |

Fonte: Luiz

<a id="rf02"></a>
## #RF02 - Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking)

|                  **RF02**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                                            |
|                       Recurso                        | [Cenário #CN09](../modelagem/cenarios.md#cn09)                      |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC09](../modelagem/casos-de-uso.md#uc09), <br> [Léxico #LX09](../modelagem/lexicos.md#lx09)                                            |
|                      Agregação                       |                  [História de usuário #HU13](../modelagem/historias-de-usuario.md#hu13), <br> [Épico 1 - Funcionalidades de IA #BK01](../modelagem/backlog.md#bk01)                      |

Fonte: Luiz

<a id="rf03"></a>
## #RF03 - O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s

|                  **RF03**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |  [#ES06 - Desempenho](../modelagem/especificacao-suplementar.md#es06) |
|                       Recurso                        | [Cenário #CN06](../modelagem/cenarios.md#cn06)                      |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC06](../modelagem/casos-de-uso.md#uc06), <br> [Léxico #LX06](../modelagem/lexicos.md#lx06)                                            |
|                      Agregação                       |                  [História de usuário #HU25](../modelagem/historias-de-usuario.md#hu25), <br> [Épico 7 - Gerenciamento de arquivos #BK37](../modelagem/backlog.md#bk37)                      |

Fonte: Luiz

<a id="rf04"></a>
## #RF04 - Deve possuir a opção de login com conta Google/Apple ID

|                  **RF04**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES07 - Suportabilidade](../modelagem/especificacao-suplementar.md#es07) |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                                         |
|                      Agregação                       |                  [História de usuário #HU41](../modelagem/historias-de-usuario.md#hu41), <br> [Épico 3 - Segurança #BK15](../modelagem/backlog.md#bk15)                      |

Fonte: Luiz

<a id="rf05"></a>
## #RF05 - Deve salvar chats entre plataformas

|                  **RF05**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05)
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [História de usuário #HU18](../modelagem/historias-de-usuario.md#hu18), <br> [Épico 4 - Funcionalidades do chat #BK17](../modelagem/backlog.md#bk17)                      |

Fonte: Luiz

<a id="rf06"></a>
## #RF06 - Melhorar as capacidades de "deep thinking"

|                  **RF05**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  -                      |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  -                      |

Fonte: Luiz

<a id="rf07"></a>
## #RF07 - Deve haver um campo para a interação com a IA

|                  **RF07**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04) <br> [#ES01 - Design](../modelagem/especificacao-suplementar.md#es01),                                           |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [História de usuário #HU03](../modelagem/historias-de-usuario.md#hu03), <br> [Épico 4 - Funcionalidades do chat #BK18](../modelagem/backlog.md#bk18)                      |

<a id="rf08"></a>
## #RF08 - Deve ser possível criar novos chats

|                  **RF08**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |   [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                                           |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [História de usuário #HU42](../modelagem/historias-de-usuario.md#hu42), <br> [Épico 5 - Interface e experiência do usuário #BK21](../modelagem/backlog.md#bk21)                      |

<a id="rf09"></a>
## #RF09 - Deve ser possível renomear um chat


|                  **RF09**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        -              |
|                    Representação                     |                  -                      |
|                       Alocado                        | -                                       |
|                      Agregação                       |                  [História de usuário #HU04](../modelagem/historias-de-usuario.md#hu04), <br>  [Épico 4 - Funcionalidades do chat #BK20](../modelagem/backlog.md#bk20)                    |

Fonte: Fábio

<a id="rf10"></a>
## #RF10 - Os chats já utilizados devem poder ser acessados posteriormente

|                  **RF10**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        -              |
|                    Representação                     |                  -                      |
|                       Alocado                        |                                     -  |
|                      Agregação                       |                                    -  |

Fonte: Fábio

<a id="rf11"></a>
## #RF11 - Deve ser possível dar dislike em uma resposta da IA

|                  **RF11**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        [Cenário #CN08](../modelagem/cenarios.md#cn08)               |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC08](../modelagem/casos-de-uso.md#uc08), <br> [Léxico #LX08](../modelagem/lexicos.md#lx08)                                        |
|                      Agregação                       |                                   -     |

Fonte: Fábio

<a id="rf12"></a>
## #RF12 - Deve ser possível dar like em uma resposta da IA

|                  **RF12**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        [Cenário #CN08](../modelagem/cenarios.md#cn08)               |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC08](../modelagem/casos-de-uso.md#uc08), <br> [Léxico #LX08](../modelagem/lexicos.md#lx08)                                        |
|                      Agregação                       |                                   -     |

Fonte: Fábio

<a id="rf13"></a>
## #RF13 - Deve ser possível copiar uma resposta da IA

|                  **RF13**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        [Cenário #CN08](../modelagem/cenarios.md#cn08)               |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC08](../modelagem/casos-de-uso.md#uc08), <br> [Léxico #LX08](../modelagem/lexicos.md#lx08)                                        |
|                      Agregação                       |                                   -     |

Fonte: Fábio

<a id="rf14"></a>
## #RF14 - Deve exibir citações de fontes e referências em respostas baseadas em documentos, indicando página, site e/ou trecho extraído 

<a id="rf15"></a>
## #RF15 - Deve ser possível alterar o idioma do sistema

|                  **RF15**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        -              |
|                    Representação                     |                  -                      |
|                       Alocado                        | -                |
|                      Agregação                       |                                   [História de usuário #HU27](../modelagem/historias-de-usuario.md#hu27), <br>  [Épico 5 - Interface e experiência do usuário #BK35](../modelagem/backlog.md#bk35)       |

Fonte: Fábio

<a id="rf16"></a>
## #RF16 - Deve ser possível apagar conversas individuais ou de forma geral

|                  **RF16**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04), <br> [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        [Cenário #CN13](../modelagem/cenarios.md#cn13)                |
|                    Representação                     |                  -                      |
|                       Alocado                        | -                              |
|                      Agregação                       |                                   [História de usuário #HU28](../modelagem/historias-de-usuario.md#hu28), <br>  [Épico 2 - Controle de dados #BK14](../modelagem/backlog.md#bk14)       |

Fonte: Fábio

<a id="rf17"></a>
## #RF17 - Deve ser possível regenerar uma resposta da IA de forma manual ou automática em caso de erro de servidor ou sobrecarga

<a id="rf18"></a>
## #RF18 - O sistema deve exibir respostas formatadas em Markdown em tabelas ou listas complexas, com possibilidade de edição pelo usuário

<a id="rf19"></a>
## #RF19 - Deve ser possível interromper respostas em andamento

<a id="rf20"></a>
## #RF20 - Deve possuir uma API pública

<a id="rf21"></a>
## #RF21 - Deve aceitar autenticação via token de acesso

<a id="rf22"></a>
## #RF22 - Deve haver uma confirmação para limpar o histórico

<a id="rf23"></a>
## #RF23 - Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita)

<a id="rf24"></a>
## #RF24 - Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256)

<a id="rf25"></a>
## #RF25 - O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização)

<a id="rf26"></a>
## #RF26 - Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas

<a id="rf27"></a>
## #RF27 - Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO

<a id="rf28"></a>
## #RF28 - Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades

<a id="rf29"></a>
## #RF29 - Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga)

<a id="rf30"></a>
## #RF30 - Melhorar retenção de contexto em diálogos longos

<a id="rf31"></a>
## #RF31 - Implementar memória de contexto persistente entre conversas

<a id="rf32"></a>
## #RF32 - Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)

<a id="rf33"></a>
## #RF33 - Permitir organização de conversas em pastas ou listas por tema ou projeto

<a id="rf34"></a>
## #RF34 - Implementar comandos de voz para entrada e saída de informações

<a id="rf35"></a>
## #RF34 - Implementar comandos de voz para entrada e saída de informações

<a id="rf36"></a>
## #RF36 - Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR

<a id="rf37"></a>
## #RF37 - Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas

<a id="rf38"></a>
## #RF38 - Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização)

<a id="rn01"></a>
## #RN01 - Deve fazer o uso da arquitetura DeepSeek-V3

<a id="rn02"></a>
## #RN02 - Deve possuir versões para Android e IOS

<a id="rn03"></a>
## #RN03 - Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar)

<a id="rn04"></a>
## #RN04 - Deve fazer a exclusão automática de dados de upload

<a id="rn05"></a>
## #RN05 - A interface deve seguir diretrizes de usabilidade e acessibilidade

<a id="rn06"></a>
## #RN06 - Em caso de falha, deve retornar mensagens de erro claras	

<a id="rn07"></a>
## #RN07 - O sistema deve suportar múltiplas requisições simultâneas sem degradação

<a id="rn08"></a>
## #RN08 - O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples

<a id="rn09"></a>
## #RN09 - Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados

<a id="rn10"></a>
## #RN10 - Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos

<a id="rn11"></a>
## #RN11 - Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos

<a id="rn12"></a>
## #RN12 - Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas

<a id="rn13"></a>
## #RN13 - Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras

<a id="rn14"></a>
## #RN14 - Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras	

<a id="rn15"></a>
## #RN15 - Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras

# Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/definicao-meta-modelo-toranzo.png)

> <a id="REF2" href="#anchor_2">2.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/tipos-de-informacao.png)

> <a id="REF3" href="#anchor_3">3.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9-10.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/tipos-elos-toranzo.png)

# Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 07/06/2025 |  1.0   | (#PR01) Criação do documento de pós-rastreabilidade.| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |
| 07/06/2025 |  1.1   | (#PR01) Elaboração da introdução, meotodologia e do template de representação dos elos.| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |
| 07/06/2025 |  1.2   | (#PR01) Adição dos requisitos do projeto e seus hiperlinks.| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |
| 07/06/2025 |  1.3   | (#PR01) Adição das tabelas dos elos para os requisitos #RF01-#RF08  | [`@Luiz`](https://github.com/)  | [@](https://github.com/)  |
| 07/06/2025 |  1.4   | (#PR01) Adição das tabelas dos elos para os requisitos #RF09-#RF13 #RF15-#RF16  | [`@Fabio`](https://github.com/fabinsz)  | [@](https://github.com/)  |