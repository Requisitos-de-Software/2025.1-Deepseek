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

* **Satisfação** : é resnposável por indicar que a classe de origem possui dependência com a classe de destino <a id="anchor_3" href="#REF3">[3]</a>;
* **Recurso**: é responsável por indicar a classe de origem tem dependêcia de recurso com a classe de destino <a id="anchor_3" href="#REF3">[3]</a>;
* **Responsabilidade**: é responsável por indicar participação, responsabilidade e ação das pessoas sobre os artefatos <a id="anchor_3" href="#REF3">[3]</a>;
* **Representação**: é responsável por capturar a representação ou modelagem dos requisitos <a id="anchor_3" href="#REF3">[3]</a>;
* **Alocado**: é responsável por indicar a classe de origem que está relacionada à classe de destino, representando um subsistema <a id="anchor_3" href="#REF3">[3]</a>;
* **Agregação**: é resposnável por indicar a composição de elementos <a id="anchor_3" href="#REF3">[3]</a>.

Com base nesses elos é possível elaborar a Tabela 1, que será usada como template para representar os elos dos artefatos com os requisitos desenvolvidos nesse projeto.

Tabela 1 - Template Pós-Rastreabilidade

|                               **Artefato Analisado** | **Classificação do Artefato Analisado** |
| :--------------------------------------------------: | :---------------------------------: |
|                     Tipos de Elo                     |       Artefatos Relacionados        |
|                      Satisfação                      |                  -                  |
|                       Recurso                        |                  -                  |
|                    Representação                     |                  -                  |
|                       Alocado                        |                  -                  |
|                      Agregação                       |                  -                  |

Autor: Luiz

# Tabela de Contribuições

# Rastreabilidade

Nesse tópico são apresentadas as tabelas referentes aos elos dos artefatos analisados ao longo do projeto. Assim, cada um dos 52 requisitos elicitados possuem uma tabela semelhante ao template da Tabela 1, com seus artefatos relacionados.

# Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/definicao-meta-modelo-toranzo.png)

> <a id="REF2" href="#anchor_2">2.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/tipos-de-informacao.png)

> <a id="REF3" href="#anchor_3">3.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 9-10.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 07/06/2025.[`Foto da referência`](../images/pos-rastreabilidade/tipos-de-informacao.png)

# Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 07/06/2025 |  1.0   | (#PR01) Criação do documento de pós-rastreabilidade.| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |
| 07/06/2025 |  1.1   | (#PR01) Elaboração da introdução, meotodologia e do template de representação dos elos.| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |