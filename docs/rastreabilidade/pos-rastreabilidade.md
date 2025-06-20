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

<font><p style="text-align: center">**Tabela 1** - Template para a criação dos elos dos requisitos.</p></font>

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
| Luiz         | Criação dos elos para os requisitos #RF01, #RF02, #RF03, #RF04, #RF05, #RF06, #RF06, #RF08 | [#RF01](../rastreabilidade/pos-rastreabilidade.md#rf01), [#RF02](../rastreabilidade/pos-rastreabilidade.md#rf02), [#RF03](../rastreabilidade/pos-rastreabilidade.md#rf03), [#RF04](../rastreabilidade/pos-rastreabilidade.md#rf04), [#RF05](../rastreabilidade/pos-rastreabilidade.md#rf05), [#RF06](../rastreabilidade/pos-rastreabilidade.md#rf06), [#RF07](../rastreabilidade/pos-rastreabilidade.md#rf07), [#RF08](../rastreabilidade/pos-rastreabilidade.md#rf08) |
| Fábio        | Criação dos elos para os requisitos #RF09, #RF10, #RF11, #RF12, #RF13, #RF15, #RF16 | [#RF09](../rastreabilidade/pos-rastreabilidade.md#rf09), [#RF10](../rastreabilidade/pos-rastreabilidade.md#rf10), [#RF11](../rastreabilidade/pos-rastreabilidade.md#rf11), [#RF12](../rastreabilidade/pos-rastreabilidade.md#rf12), [#RF13](../rastreabilidade/pos-rastreabilidade.md#rf13), [#RF15](../rastreabilidade/pos-rastreabilidade.md#rf15), [#RF16](../rastreabilidade/pos-rastreabilidade.md#rf16) |
| Gabriela     | Criação dos elos para os requisitos #RF28, #RF29, #RF30, #RF31, #RF32, #RF33, #RF35, #RF36, #RF38, #RN01 | [#RF28](../rastreabilidade/pos-rastreabilidade.md#rf28), [#RF29](../rastreabilidade/pos-rastreabilidade.md#rf29), [#RF30](../rastreabilidade/pos-rastreabilidade.md#rf30), [#RF31](../rastreabilidade/pos-rastreabilidade.md#rf31), [#RF32](../rastreabilidade/pos-rastreabilidade.md#rf32), [#RF33](../rastreabilidade/pos-rastreabilidade.md#rf33), [#RF35](../rastreabilidade/pos-rastreabilidade.md#rf35), [#RF36](../rastreabilidade/pos-rastreabilidade.md#rf36), [#RF38](../rastreabilidade/pos-rastreabilidade.md#rf38), [#RN01](../rastreabilidade/pos-rastreabilidade.md#rn01) |
| Davi         | Criação dos elos para os requisitos #RF14, #RF34, #RF14, #RF19, #RF21, #RF37, #RN06 | [#RF14](../rastreabilidade/pos-rastreabilidade.md#rf14), [#RF34](../rastreabilidade/pos-rastreabilidade.md#rf34), [#RF14](../rastreabilidade/pos-rastreabilidade.md#rf14), [#RF19](../rastreabilidade/pos-rastreabilidade.md#rf19), [#RF21](../rastreabilidade/pos-rastreabilidade.md#rf21), [#RF37](../rastreabilidade/pos-rastreabilidade.md#rf37), [#RN06](../rastreabilidade/pos-rastreabilidade.md#rn06) |
| Ana Clara    | Criação dos elos para os requisitos #RF17, #RF20, #RF22, #RF23, #RF24, #RF25, #RF26, #RF27 | [#RF17](../rastreabilidade/pos-rastreabilidade.md#rf17), [#RF20](../rastreabilidade/pos-rastreabilidade.md#rf20), [#RF22](../rastreabilidade/pos-rastreabilidade.md#rf22), [#RF23](../rastreabilidade/pos-rastreabilidade.md#rf23), [#RF24](../rastreabilidade/pos-rastreabilidade.md#rf24), [#RF25](../rastreabilidade/pos-rastreabilidade.md#rf25), [#RF26](../rastreabilidade/pos-rastreabilidade.md#rf26), [#RF27](../rastreabilidade/pos-rastreabilidade.md#rf27) |
| Luiz    | Criação dos elos para os requisitos #RF01, #RF02, #RF03, #RF04, #RF05, #RF06, #RF06, #RF08 | [#RF01](../rastreabilidade/pos-rastreabilidade.md#rf01), [#RF02](../rastreabilidade/pos-rastreabilidade.md#rf02), [#RF03]((../rastreabilidade/pos-rastreabilidade.md#rf03)), [#RF04](../rastreabilidade/pos-rastreabilidade.md#rf04), [#RF05](../rastreabilidade/pos-rastreabilidade.md#rf05), [#RF06](../rastreabilidade/pos-rastreabilidade.md#rf06), [#RF07](../rastreabilidade/pos-rastreabilidade.md#rf07), [#RF08](../rastreabilidade/pos-rastreabilidade.md#rf08) |
| Fábio    | Criação dos elos para os requisitos #RF09, #RF10, #RF11, #RF12, #RF13, #RF15, #RF16 | [#RF09](../rastreabilidade/pos-rastreabilidade.md#rf09), [#RF10](../rastreabilidade/pos-rastreabilidade.md#rf10), [#RF11]((../rastreabilidade/pos-rastreabilidade.md#rf11)), [#RF12](../rastreabilidade/pos-rastreabilidade.md#rf12), [#RF13](../rastreabilidade/pos-rastreabilidade.md#rf13), [#RF15](../rastreabilidade/pos-rastreabilidade.md#rf15), [#RF16](../rastreabilidade/pos-rastreabilidade.md#rf16)|
| Mateus    | Criação dos elos para os requisitos #RN10, #RN11, #RN12, #RN13, #RN14, #RN15 | [#RN10](../rastreabilidade/pos-rastreabilidade.md#rn10), [#RN11](../rastreabilidade/pos-rastreabilidade.md#rn10), [#RN12](../rastreabilidade/pos-rastreabilidade.md#rn12), [#RN13](../rastreabilidade/pos-rastreabilidade.md#rn13), [#RN14](../rastreabilidade/pos-rastreabilidade.md#rn14), [#RN15](../rastreabilidade/pos-rastreabilidade.md#rn15) |
| Ana Joyce | Criação dos elos para os requisitos #RN02, #RN03, #RN04, #RN05, #RN07, #RN08, #RN09 | [#RN02](../rastreabilidade/pos-rastreabilidade.md#rn02), [#RN03](../rastreabilidade/pos-rastreabilidade.md#rn03), [#RN04]((../rastreabilidade/pos-rastreabilidade.md#rn04)), [#RN05](../rastreabilidade/pos-rastreabilidade.md#rn05), [#RN07](../rastreabilidade/pos-rastreabilidade.md#rn07), [#RN08](../rastreabilidade/pos-rastreabilidade.md#rn08), [#RN09](../rastreabilidade/pos-rastreabilidade.md#rn09)|

# Rastreabilidade

Nesse tópico são apresentadas as tabelas referentes aos elos dos artefatos analisados ao longo do projeto. Assim, cada um dos 52 requisitos elicitados possuem uma tabela semelhante ao template da Tabela 1, com seus artefatos relacionados.

<a id="rf01"></a>

## #RF01 - Deve oferecer a possibilidade do usuário acionar a pesquisa na web

<font><p style="text-align: center">**Tabela 2** - Elos para o requisito #RF01.</p></font>

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

<font><p style="text-align: center">**Tabela 3** - Elos para o requisito #RF03.</p></font>

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

<font><p style="text-align: center">**Tabela 4** - Elos para o requisito #RF03.</p></font>

|                  **RF03**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |  [#ES06 - Desempenho](../modelagem/especificacao-suplementar.md#es06) <br> [Cartão de especificação #CNFR01](../modelagem/nfr-framework.md#cnfr01) <br> [Cartão de especificação #CNFR04](../modelagem/nfr-framework.md#cnfr04) <br> [Cartão de especificação #CNFR16](../modelagem/nfr-framework.md#cnfr16)   |
|                       Recurso                        | [Cenário #CN06](../modelagem/cenarios.md#cn06)                      |
|                    Representação                     |                  -                      |
|                       Alocado                        | [Caso de uso #UC06](../modelagem/casos-de-uso.md#uc06), <br> [Léxico #LX06](../modelagem/lexicos.md#lx06)                                            |
|                      Agregação                       |                  [História de usuário #HU25](../modelagem/historias-de-usuario.md#hu25), <br> [Épico 7 - Gerenciamento de arquivos #BK37](../modelagem/backlog.md#bk37)                      |

Fonte: Luiz

<a id="rf04"></a>

## #RF04 - Deve possuir a opção de login com conta Google/Apple ID

<font><p style="text-align: center">**Tabela 5** - Elos para o requisito #RF04.</p></font>

|                  **RF04**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES07 - Suportabilidade](../modelagem/especificacao-suplementar.md#es07) <br> [Cartão de especificação #CNFR02](../modelagem/nfr-framework.md#cnfr02) <br> [Cartão de especificação #CNFR09](../modelagem/nfr-framework.md#cnfr09) |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                                         |
|                      Agregação                       |                  [História de usuário #HU41](../modelagem/historias-de-usuario.md#hu41), <br> [Épico 3 - Segurança #BK15](../modelagem/backlog.md#bk15)                      |

Fonte: Luiz

<a id="rf05"></a>

## #RF05 - Deve salvar chats entre plataformas

<font><p style="text-align: center">**Tabela 6** - Elos para o requisito #RF05.</p></font>

|                  **RF05**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05) <br> [Cartão de especificação #CNFR03](../modelagem/nfr-framework.md#cnfr03) <br> [Cartão de especificação #CNFR11](../modelagem/nfr-framework.md#cnfr11) |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [História de usuário #HU18](../modelagem/historias-de-usuario.md#hu18), <br> [Épico 4 - Funcionalidades do chat #BK17](../modelagem/backlog.md#bk17)                      |

Fonte: Luiz

<a id="rf06"></a>

## #RF06 - Melhorar as capacidades de "deep thinking"

<font><p style="text-align: center">**Tabela 7** - Elos para o requisito #RF06.</p></font>

|                  **RF05**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  [Cartão de especificação #CNFR12](../modelagem/nfr-framework.md#cnfr12)                        |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  -                      |

Fonte: Luiz

<a id="rf07"></a>

## #RF07 - Deve haver um campo para a interação com a IA

<font><p style="text-align: center">**Tabela 8** - Elos para o requisito #RF07.</p></font>

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

<font><p style="text-align: center">**Tabela 9** - Elos para o requisito #RF08.</p></font>

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

<font><p style="text-align: center">**Tabela 10** - Elos para o requisito #RF09.</p></font>


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

<font><p style="text-align: center">**Tabela 11** - Elos para o requisito #RF10.</p></font>

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

<font><p style="text-align: center">**Tabela 12** - Elos para o requisito #RF11.</p></font>

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

<font><p style="text-align: center">**Tabela 13** - Elos para o requisito #RF12.</p></font>

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

<font><p style="text-align: center">**Tabela 14** - Elos para o requisito #RF13.</p></font>

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

|                  **RF14**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES03 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |        -              |
|                    Representação                     |                  -                      |
|                       Alocado                        | -                |
|                      Agregação                       |                                   [História de usuário #HU10](../modelagem/historias-de-usuario.md#hu10),[História de usuário #HU36](../modelagem/historias-de-usuario.md#hu36) <br>  [Épico 1 - Funcionalidades de uma IA #BK03](../modelagem/backlog.md#bk03), [#BK04](../modelagem/backlog.md#bk04)       |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>


<a id="rf15"></a>

## #RF15 - Deve ser possível alterar o idioma do sistema

<font><p style="text-align: center">**Tabela 16** - Elos para o requisito #RF15.</p></font>

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

<font><p style="text-align: center">**Tabela 17** - Elos para o requisito #RF16.</p></font>

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

|                  **RF17**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#UC08 - Refinar resposta gerada](../modelagem/casos-de-uso.md#uc08), <br> [#HU30 - História de usuário: Refinar resposta](../modelagem/historias-de-usuario.md#hu30) |
|                       Recurso         | [Cenário #CN08](../modelagem/cenarios.md#cn08), <br> [Léxico #LX08](../modelagem/lexicos.md#lx08) |
|                    Representação      | [#UC08 - Refinar resposta gerada](../modelagem/casos-de-uso.md#uc08) |
|                       Alocado         | - |
|                      Agregação        | [Cenário #CN08](../modelagem/cenarios.md#cn08), <br> [Léxico #LX08](../modelagem/lexicos.md#lx08) |

Fonte: Ana Clara


<a id="rf18"></a>
## #RF18 - O sistema deve exibir respostas formatadas em Markdown em tabelas ou listas complexas, com possibilidade de edição pelo usuário
|                  **RF18**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES01 - design](../modelagem/especificacao-suplementar.md#es01)                     |
|                       Recurso                        |      -      |
|                    Representação                     |                  -                      |
|                       Alocado                        | -                |
|                      Agregação                       |                                   [História de usuário #HU23](../modelagem/historias-de-usuario.md#hu23),[História de usuário #HU34](../modelagem/historias-de-usuario.md#hu34) <br>  [Épico 5 - Interface e experiencia do usuário #BK26](../modelagem/backlog.md#bk26),  [#BK27](../modelagem/backlog.md#bk27)    |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>

<a id="rf19"></a>
## #RF19 - Deve ser possível interromper respostas em andamento
|                  **RF19**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES01 - Funcionalidade](../modelagem/especificacao-suplementar.md#es03)                     |
|                       Recurso                        |      [#CN10](../modelagem/cenarios.md#cn10)      |
|                    Representação                     |                  -                      |
|                       Alocado                        | [#UC10](../modelagem/casos-de-uso.md#uc10)              |
|                      Agregação                       |                                   [História de usuário #HU07](../modelagem/historias-de-usuario.md#hu07) <br>  [Épico 4 - Funcionalidades do chat #BK24](../modelagem/backlog.md#bk24)    |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>

<a id="rf20"></a>
## #RF20 - Deve possuir uma API pública

|                  **RF20**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#HU31 - Utilizar uma API Pública](../modelagem/historias-de-usuario.md#hu31) |
|                       Recurso         |  - |
|                    Representação      | [#HU31 - Utilizar uma API Pública](../modelagem/historias-de-usuario.md#hu31) |
|                       Alocado         | - |
|                      Agregação        | [Épico 8 - Integrações e API #BK41](../modelagem/backlog.md#bk41) |

Fonte: Ana Clara

<a id="rf21"></a>
## #RF21 - Deve aceitar autenticação via token de acesso
|                  **RF21**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES01 - Implementação](../modelagem/especificacao-suplementar.md#es02)                     |
|                       Recurso                        |            |
|                    Representação                     |                  -                      |
|                       Alocado                        |             |
|                      Agregação                       |                                  |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>


<a id="rf22"></a>
## #RF22 - Deve haver uma confirmação para limpar o histórico

|                  **RF22**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#UC13 - Apagar histórico com confirmação](../modelagem/casos-de-uso.md#uc13), <br> [#HU02 - Confirmar a exclusão do histórico de conversas](../modelagem/historias-de-usuario.md#hu02) |
|                       Recurso         | [Cenário #CN13](../modelagem/cenarios.md#cn13) |
|                    Representação      | [#UC13 - Apagar histórico com confirmação](../modelagem/casos-de-uso.md#uc13) |
|                       Alocado         | [Léxico #LX13](../modelagem/lexicos.md#lx13) |
|                      Agregação        | [Épico #BK09 - Controle de dados](../modelagem/backlog.md#bk09) |

Fonte: Ana Clara

<a id="rf23"></a>
## #RF23 - Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita)

|                  **RF23**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#HU05 - Busca incremental no campo de texto](../modelagem/historias-de-usuario.md#hu05) |
|                       Recurso         | - |
|                    Representação      | - |
|                       Alocado         | - |
|                      Agregação        | [Épico #BK28 - Interface e experiência do usuário](../modelagem/backlog.md#bk28) |

Fonte: Ana Clara

<a id="rf24"></a>
## #RF24 - Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256)

|                  **RF24**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | - |
|                       Recurso         | - |
|                    Representação      | - |
|                       Alocado         | - |
|                      Agregação        | - |

Fonte: Ana Clara

<a id="rf25"></a>
## #RF25 - O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização)

|                  **RF25**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#HU17 - Controlar quais dados são compartilhados com a IA](../modelagem/historias-de-usuario.md#hu17) |
|                       Recurso         | - |
|                    Representação      | - |
|                       Alocado         | - |
|                      Agregação        | [Épico #BK11 - Controle de dados](../modelagem/backlog.md#bk11) |

Fonte: Ana Clara

<a id="rf26"></a>
## #RF26 - Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas

|                  **RF26**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#HU16 - Autenticar a conta para acessar funcionalidades avançadas](../modelagem/historias-de-usuario.md#hu16) |
|                       Recurso         | - |
|                    Representação      | - |
|                       Alocado         | - |
|                      Agregação        | [Épico #BK16 - Segurança](../modelagem/backlog.md#bk16) |

Fonte: Ana Clara

<a id="rf27"></a>
## #RF27 - Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO

|                  **RF27**              | **Classificação do Artefato Analisado** |
| ------------------------------------- | --------------------------------------- |
|                     Tipos de Elo      |       Artefatos Relacionados            |
|                      Satisfação       | [#HU19 - Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO](../modelagem/historias-de-usuario.md#hu19) |
|                       Recurso         | [Cenário #CN05](../modelagem/cenarios.md#cn05) |
|                    Representação      | - |
|                       Alocado         | [Caso de uso #UC05](../modelagem/casos-de-uso.md#uc05), <br> [Léxico #LX05](../modelagem/lexicos.md#lx05) |
|                      Agregação        | [Épico #BK29 - Interface e experiência do usuário](../modelagem/backlog.md#bk29) |

Fonte: Ana Clara

<a id="rf28"></a>
## #RF28 - Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades

| **RF28** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | [#CN12](../modelagem/cenarios.md#cn12) |
| Representação | – |
| Alocado | [#UC12](../modelagem/casos-de-uso.md#uc12), [#LX12](../modelagem/lexicos.md#lx12) |
| Agregação | [#HU01](../modelagem/historias-de-usuario.md#hu01), [#BK30](../modelagem/backlog.md#bk30) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf29"></a>
## #RF29 - Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga)

| **RF29** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | [#CN11](../modelagem/cenarios.md#cn11) |
| Representação | – |
| Alocado | [#UC11](../modelagem/casos-de-uso.md#uc11), [#LX11](../modelagem/lexicos.md#lx11) |
| Agregação | [#HU14](../modelagem/historias-de-usuario.md#hu14), [#BK31](../modelagem/backlog.md#bk31) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf30"></a>
## #RF30 - Melhorar retenção de contexto em diálogos longos

| **RF30** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | – |
| Representação | – |
| Alocado | – |
| Agregação | [#HU24](../modelagem/historias-de-usuario.md#hu24), [#BK06](../modelagem/backlog.md#bk06) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf31"></a>
## #RF31 - Implementar memória de contexto persistente entre conversas

| **RF31** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | – |
| Representação | – |
| Alocado | – |
| Agregação | [#HU31](../modelagem/historias-de-usuario.md#hu31), [#BK02](../modelagem/backlog.md#bk02) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf32"></a>
## #RF32 - Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)

| **RF32** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | [#CN04](../modelagem/cenarios.md#cn04) |
| Representação | – |
| Alocado | [#UC04](../modelagem/casos-de-uso.md#uc04), [#LX04](../modelagem/lexicos.md#lx04) |
| Agregação | [#HU20](../modelagem/historias-de-usuario.md#hu20), [#BK25](../modelagem/backlog.md#bk25) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf33"></a>
## #RF33 - Permitir organização de conversas em pastas ou listas por tema ou projeto

| **RF33** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | – |
| Representação | – |
| Alocado | – |
| Agregação | [#HU09](../modelagem/historias-de-usuario.md#hu09), [#BK25](../modelagem/backlog.md#bk25) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf34"></a>
## #RF34 - Implementar comandos de voz para entrada e saída de informações
|                  **RF34**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES02 - implementação](../modelagem/especificacao-suplementar.md#es02)                     |
|                       Recurso                        |        [#CN03](../modelagem/cenarios.md#cn03)             |
|                    Representação                     |                  -                      |
|                       Alocado                        | [#UC03](../modelagem/casos-de-uso.md#uc03)              |
|                      Agregação                       |                                   [História de usuário #HU12](../modelagem/historias-de-usuario.md#hu12), <br>  [Épico 5 - Interface e experiencia do usuário #BK32](../modelagem/backlog.md#bk32)       |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>

<a id="rf35"></a>
## #RF35 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico

| **RF35** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | – |
| Representação | – |
| Alocado | – |
| Agregação | [#HU21](../modelagem/historias-de-usuario.md#hu21), [#BK33](../modelagem/backlog.md#bk33) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf36"></a>
## #RF36 – Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR

| **RF36** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | – |
| Representação | – |
| Alocado | – |
| Agregação | [#HU22](../modelagem/historias-de-usuario.md#hu22), [#BK40](../modelagem/backlog.md#bk40) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rf37"></a>
## #RF37 - Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas
|                  **RF37**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      | [#ES07 - Suportabiliddade](../modelagem/especificacao-suplementar.md#es07)                     |
|                       Recurso                        |      [#CN02](../modelagem/cenarios.md#cn02)      |
|                    Representação                     |                  -                      |
|                       Alocado                        | [#UC10](../modelagem/casos-de-uso.md#uc02)              |
|                      Agregação                       |                                   [História de usuário #HU11](../modelagem/historias-de-usuario.md#hu11) <br>  [Épico 8 - Interações e AP1](../modelagem/backlog.md#bk42)    |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>


<a id="rf38"></a>
## #RF38 – Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização)

| **RF38** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | – |
| Recurso | [#CN14](../modelagem/cenarios.md#cn14) |
| Representação | – |
| Alocado | [#UC14](../modelagem/casos-de-uso.md#uc14), [#LX14](../modelagem/lexicos.md#lx14) |
| Agregação | [#HU33](../modelagem/historias-de-usuario.md#hu33), [#BK08](../modelagem/backlog.md#bk08) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rn01"></a>
## #RN01 – Deve fazer o uso da arquitetura DeepSeek-V3

| **RN01** | **Classificação do Artefato Analisado** |
| --- | --- |
| **Tipos de Elo** | **Artefatos Relacionados** |
| Satisfação | [#ES07](../modelagem/especificacao-suplementar.md#es07) |
| Recurso | – |
| Representação | – |
| Alocado | – |
| Agregação | [#CNFR12](../modelagem/nfr-framework.md#cnfr12) |

Autor: <a href="https://github.com/gaubiela">Gabriela</a>

<a id="rn02"></a>
## #RN02 - Deve possuir versões para Android e IOS

|               **RN02**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |   [#ES07 - Suportabilidade](../modelagem/especificacao-suplementar.md#es07)  |
|     Recurso     |   #RDN05  |
|  Representação  |  [#CNFR09](../modelagem/nfr-framework.md#cnfr09--versãoes-para-android-e-ios)  |
|   Alocado       |  -  |
|    Agregação    |  Classificação: MoSCoW -> Could, In-or-Out -> In   |

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn03"></a>
## #RN03 - Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar)

|               **RN03**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |   [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05)  |
|     Recurso     | #RIN10 |
|  Representação  | [#CNFR11](../modelagem/nfr-framework.md#cnfr11)  |
|   Alocado       |  -  |
|    Agregação    |   Classificação: MoSCoW -> Could, In-or-Out -> In  |

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn04"></a>
## #RN04 - Deve fazer a exclusão automática de dados de upload

|               **RN04**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |  [#ES02 - Implementação](../modelagem/especificacao-suplementar.md#es02) |
|     Recurso     | #RIN11 |
|  Representação  |  -  |
|   Alocado       | [Caso de uso #UC01](../modelagem/casos-de-uso.md#uc01) <br> [Léxico #LX01](../modelagem/lexicos.md#lx01) <br> [#CNFR08](../modelagem/nfr-framework.md#cnfr08)|
|    Agregação    |  Classificação: MoSCoW -> Must, In-or-Out -> In <br> [Épico 2 - Controle de dados #BK12](../modelagem/backlog.md#bk12) <br> [História de usuário #HU37](../modelagem/historias-de-usuario.md#hu37) |

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn05"></a>
## #RN05 - A interface deve seguir diretrizes de usabilidade e acessibilidade

|               **RN05**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |   [#ES01 - Design](../modelagem/especificacao-suplementar.md#es01)  |
|     Recurso     | #RIN12 e #RQF05 |
|  Representação  |  -  |
|   Alocado       | [#CNFR23](../modelagem/nfr-framework.md#cnfr23) |
|    Agregação    |   Classificação: MoSCoW -> Must, In-or-Out -> In <br> [Épico 5 - Controle de dados #BK34](../modelagem/backlog.md#bk34) <br> [História de usuário #HU38](../modelagem/historias-de-usuario.md#hu38)|

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn06"></a>
## #RN06 - Em caso de falha, deve retornar mensagens de erro claras	
|                  **RN06**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |      [#ES02](../modelagem/especificacao-suplementar.md#es02)             |
|                       Recurso                        |    -     |
|                    Representação                     |                  -                      |
|                       Alocado                        |           -              |
|                      Agregação                       |                 -    |

Autor: <a href="https://github.com/daviRolvr">Davi Emanuel</a>

<a id="rn07"></a>
## #RN07 - O sistema deve suportar múltiplas requisições simultâneas sem degradação

|               **RN07**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |   [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05)   |
|     Recurso     |  #RIN16   |
|  Representação  |  -  |
|   Alocado       |  [Caso de uso #UC09](../modelagem/casos-de-uso.md#uc09) <br> [Léxico #LX09](../modelagem/lexicos.md#lx09) <br> [#CNFR05](../modelagem/nfr-framework.md#cnfr05) |
|    Agregação    |  Classificação: MoSCoW -> Should, In-or-Out -> In   |

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn08"></a>
## #RN08 - O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples

|               **RN08**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |   [#ES02 - Implementação](../modelagem/especificacao-suplementar.md#es02)   |
|     Recurso     |  #RIN17 e #RQN04   |
|  Representação  |  -  |
|   Alocado       |  [Caso de uso #UC06](../modelagem/casos-de-uso.md#uc06) <br> [Léxico #LX06](../modelagem/lexicos.md#lx06) <br> [#CNFR04](../modelagem/nfr-framework.md#cnfr04)  |
|    Agregação    |  Classificação: MoSCoW -> Should, In-or-Out -> In    |

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn09"></a>
## #RN09 - Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados

|               **RN09**              | **Classificação do Artefato Analisado** |
| ------------------------------------| --------------------------------------- |
|   Tipos de Elo  |       Artefatos Relacionados            |
|     Satisfação  |   [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05)  |
|     Recurso     |   #RQN01  |
|  Representação  |  -  |
|   Alocado       |  [#CNFR10](../modelagem/nfr-framework.md#cnfr10)   |
|    Agregação    |  Classificação: MoSCoW -> Must, In-or-Out -> Out |

Fonte: [Ana Joyce](https://github.com/anajoyceamorim)

<a id="rn10"></a>
## #RN10 e #RN11 - Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos

|                  **Artefato Analisado**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05)                      |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [Classificação - Three Level Scale](../priorizacao/three-level-scale.md#tls-rn10)                      |

Autor: [Mateus](https://github.com/MVConsorte)

<a id="rn12"></a>
## #RN12 - Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas

|                  **Artefato Analisado**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  [#ES05 - Confiabilidade](../modelagem/especificacao-suplementar.md#es05) <br> [#ES02 - Implementação](../modelagem/especificacao-suplementar.md#es02)                    |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [Classificação - Three Level Scale](../priorizacao/three-level-scale.md#tls-rn12)                      |

Autor: [Mateus](https://github.com/MVConsorte)

<a id="rn13"></a>
## #RN13 - Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras

|                  **Artefato Analisado**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04) <br> [#ES01 - Design](../modelagem/especificacao-suplementar.md#es01)                |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [Classificação - Three Level Scale](../priorizacao/three-level-scale.md#tls-rn13)                      |

Autor: [Mateus](https://github.com/MVConsorte)

<a id="rn14"></a>
## #RN14 - Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras	

|                  **Artefato Analisado**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04) <br> [#ES01 - Design](../modelagem/especificacao-suplementar.md#es01)              |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [Classificação - Three Level Scale](../priorizacao/three-level-scale.md#tls-rn14)                      |

Autor: [Mateus](https://github.com/MVConsorte)

<a id="rn15"></a>
## #RN15 - Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras

|                  **Artefato Analisado**              | **Classificação do Artefato Analisado** |
| ---------------------------------------------------- | --------------------------------------- |
|                     Tipos de Elo                     |       Artefatos Relacionados            |
|                      Satisfação                      |                  [#ES04 - Usabilidade](../modelagem/especificacao-suplementar.md#es04) <br> [#ES01 - Design](../modelagem/especificacao-suplementar.md#es01)            |
|                       Recurso                        |                  -                      |
|                    Representação                     |                  -                      |
|                       Alocado                        |                  -                      |
|                      Agregação                       |                  [Classificação - Three Level Scale](../priorizacao/three-level-scale.md#tls-rn15)                      |

Autor: [Mateus](https://github.com/MVConsorte)

# Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/definicao-meta-modelo-toranzo.png)

> <a id="REF2" href="#anchor_2">2.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/tipos-de-informacao.png)

> <a id="REF3" href="#anchor_3">3.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9-10.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/tipos-elos-toranzo.png)

# Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 07/06/2025 |  1.0   | (#PR01) Criação do documento de pós-rastreabilidade.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.1   | (#PR01) Elaboração da introdução, meotodologia e do template de representação dos elos.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.2   | (#PR01) Adição dos requisitos do projeto e seus hiperlinks.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.3   | (#PR01) Adição das tabelas dos elos para os requisitos #RF01-#RF08  | [`@Luiz`](https://github.com/)  | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.4   | (#PR01) Adição das tabelas dos elos para os requisitos #RF09-#RF13 #RF15-#RF16  | [`@Fabio`](https://github.com/fabinsz)  | ['@Luiz'](https://github.com/luizfaria1989)  |
| 08/06/2025 |  1.5   | (#PR01) Adição das tabelas dos elos para os requisitos #RF28, #RF29, #RF30, #RF31, #RF32, #RF33, #RF35, #RF36, #RF38, #RN01  | [`@Gabriela`](https://github.com/gaubiela)  | [`@Luiz`](https://github.com/luizfaria1989) |
| 08/06/2025 |  1.6   | (#PR01) Adição das tabelas dos elos para os requisitos #RF14, #RF18, #RF19, #RF21, #RF34, #RF37  #RN06  | [`@Davi Emanuel`](https://github.com/daviRolvr)  | [`@Luiz`](https://github.com/luizfaria1989)  |
| 08/06/2025 |  1.7   | (#PR01) Adição das tabelas dos elos para os requisitos #RF17, #RF20, #RF22, #RF23, #RF24, #RF25, #RF26, #RF27  | [`@Ana Clara`](https://github.com/anabborges)  | [`@Luiz`](https://github.com/luizfaria1989)  |
| 08/06/2025 |  1.8   | (#PR01) Adição dos cartões de especificação para os elos dos requisitos #RF01-#RF08  | [`@Luiz`](https://github.com/)  | [`@`](https://github.com/)   |
| 08/06/2025 |  1.9   | (#PR01) Adição das tabelas dos elos para os requisitos #RN02 até o #RN05 e do #RN07 até o #RN09 | [`@Ana Joyce`](https://github.com/anajoyceamorim)  | [`@Luiz`](https://github.com/luizfaria1989)  |
| 08/06/2025 |  2.0   | (#PR01) Adição das tabelas dos elos para os requisitos #RN10 ao #RN15 | [`@Ana Joyce`](https://github.com| 08/06/2025 |  1.9   | (#PR01) Adição das tabelas dos elos para os requisitos #RN02 até o #RN05 e do #RN07 até o #RN09 | [`@Mateus`](https://github.com/MVConsorte)  | [`@Ana Joyce`](https://github.com/anajoyceamorim)  |
)  | [`@Luiz`](https://github.com/luizfaria1989)  |

