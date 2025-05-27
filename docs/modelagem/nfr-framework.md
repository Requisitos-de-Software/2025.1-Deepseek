## Introdução

O NFR Framework é uma abordagem utilizada para representar e analisar os Requisitos Não-Funcionais de um projeto.
Ele tem como objetivo ajudar os desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em que está sendo analisado. Tais características incluem Requisitos Não-funcionais, Requisitos funcionais, prioridades e carga de trabalho <a id="anchor_1" href="#REF1">[1]</a>.

## Softgoal Interdependency Graph

O Softgoal Interdependency Graph é um gráfico que registra
as considerações do desenvolvedor sobre os softgoals (um objetivo que não possui uma clara
definição nem critérios de satisfação precisos) e mostra suas interdependências. Os
SIGs armazenam um registro completo das decisões de desenvolvimento além da lógica do
projeto de forma gráfica e concisa. O registro gráfico das decisões tomadas inclui Requisitos Não-funcionais bem como as suas alternativas, decisões e justificativas associadas às decisões <a id="anchor_2" href="#REF2">[2]</a>.

### Tipos de Softgoal

Como dito anteriormente, um softgoal é um objetivo que ainda não possui uma clara definição além de que os critérios de satisfação ainda não são precisos. Eles são classificados em tipos, existindo os softgoals de afirmação, de operacionalização e o NFR softgoal. Eles podem ser vistos na Figura 1.

<font size="3"><p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal</p></font>
<figure markdown class="usecaseElement">

![TIPOS](../images/nfr-framework/tipos-de-softgoal.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

#### Interdependências

As interdependências são definições para as associações que ocorrem entre os softgoals. Essas associações são divididas em decomposições (refinamentos) e contribuições.

##### Decomposições

Existem quatro tipos diferentes de decomposição: decomposição NFR, de Operacionalização, de Afirmação e de Priorização. Nas três primeiras decomposições, os softgoals são divididos em softgoals específicos. A Figura 2 representa esses quatro tipos de decomposição <a id="anchor_3" href="#REF3">[3]</a>.

* Decomposição NFR: Refina ou subdivide um sofgoal NFR em outros softogals específicos, é util para quebrar problemas grandes em problemas menores <a id="anchor_4" href="#REF4">[4]</a>;
* Decomposição de Operacionalização: Refinina ou subdivide um sofgoal de operacionalização em outros do mesmo tipo porém mais específicos, é útil para refinar uma solução geral em soluções mais específicas <a id="anchor_4" href="#REF4">[4]</a>;
* Decomposição de Afirmação(Claims): Refina um sofgoal de afirmação em outros de afirmação, é útil para apoiar ou negar justificavas específicas do projeto que está sendo desenvolvido <a id="anchor_4" href="#REF4">[4]</a>;
* Decomposição de Priorização: É um tipo especial de decomposição, nela ocorre o refinamento de um softgoal em outro do mesmo tipo e tópicos, porém com uma prioridade associada <a id="anchor_4" href="#REF4">[4]</a>.

<font size="3"><p style="text-align: center"><b>Figura 2</b> - Tipos de Decomposição</p></font>

<figure markdown class="usecaseElement">

![DECOMPOSIÇÃO](../images/nfr-framework/figura-tipos-de-decomposicao.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

#### Contribuições

Ao longo de um projeto que faz o uso do NFR Framewok, os softgoals são refinados sucessivamente, e nesses refinamentos, um softgoal descendente pode contribuir de forma total ou parcial, além de poder ser algo positivo ou negativo, para a satisfação do ascendente. Assim, cabe destacar esses tipos de contribuição <a id="anchor_5" href="#REF5">[5]</a>.

* AND: Com esse tipo de contribuição, é determinado que se os softgoals descendentes forem satisfeitos, os softgoals ascendentes também serão satisfeitos <a id="anchor_6" href="#REF6">[6]</a>;
* OR: É o oposto da contribuição AND, na OR se algum softgoal descedente for satisfeito, o ascedente também será <a id="anchor_6" href="#REF6">[6]</a>;
* MAKE(++): Fornece uma contribuição suficientemente positiva entre um sofgoal descedente e um outro softgoal ascendente que está concebido em um nível mais alto de satisfação, assim, quando a contribuição MAKE for utilizada, se o softgoal descendente for satisfeito, o softgoal pai também será <a id="anchor_6" href="#REF6">[6]</a>;
* BREAK(--): É o oposto da contribuição MAKE, na BREAK, se o softgoal descendente for suficientemente satisfeito ou softogal pai será negado/não satisfeito <a id="anchor_6" href="#REF6">[6]</a>;
* HELP(+): Fornece uma contribuição parcialmente positiva entre um softgoal descedente e seu softgoal ascendente, assim, ao utilizar a contribuição HELP, se o softgoal descedente for parcialmente satisfeito o softgoal ascendente também será parcialmente satisfeito <a id="anchor_6" href="#REF6">[6]</a>;
* HURT(-): Fornece uma contribuição parcialmente negativa entre um softgoal descendente e seu softgoal ascedente, assim, quando a contribuição HURT é utilizada, se o softgoal descendente é satisfeito, o ascendente será parcialmente negado <a id="anchor_6" href="#REF6">[6]</a>;
* UNKNOWN(?): Fornece uma contribuição desconhecida entre os softgoals, essa contribuição pode ser positiva ou negativa <a id="anchor_6" href="#REF6">[6]</a>;
* EQUALS: Essa contribuição determina que um softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito, e caso o softgoal ascendente não for satisfeito, o softgoal descendente também não será satisfeito <a id="anchor_6" href="#REF6">[6]</a>;
- SOME: É utilizada quando o sinal da contribuição é conhecido, porém a sua extensão, parcial ou total, não é <a id="anchor_6" href="#REF6">[6]</a>.

#### Procedimento de Avaliação

Com o procedimento de avaliação é possível gerar o grau que os requisitos não funcionais são satis-
feitos por um conjunto de decisões. Assim, o procedimento de avaliação determina
se cada softgoal ou interdependência do SIG foi suficientemente satisfeito. Para fazer isso, são
atribuídos rótulos para os softgoals criados no projeto. Os tipos de rótulos utilizados são: satisfeito, fracamente satisfeito, negado, fracamente negado, conflitante, indeterminado <a id="anchor_7" href="#REF7">[7] </a>. 

Esses rótulos estão ilustrados na Figura 3.

<font size="3"><p style="text-align: center"><b>Figura 3</b> - Tipos de Rótulos</p></font>

<figure markdown class="usecaseElement">

![DECOMPOSIÇÃO](../images/nfr-framework/tipos-de-avaliacao.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>


## Metodologia

## Lista de Requisitos 


| ID       | Descrição resumida                                                                  | Tipo de Softgoal                  |
| -------- | ----------------------------------------------------------------------------------- | --------------------------------- |
| **RF03** | Upload de arquivos até 10 MB com OCR em < 35 s                                      | Operacionalização (métrica clara) |
| **RF06** | Melhorar capacidades de “deep thinking”                                             | Afirmação (vago, sem métrica)     |
| **RF14** | Exibir citações de fontes (pág., site ou trecho)                                    | Afirmação                         |
| **RF17** | Regenerar resposta em caso de erro sem recarregar a página                          | Afirmação                         |
| **RF18** | Exibir respostas em Markdown com edição de tabelas/listas complexas                 | Afirmação                         |
| **RF19** | Interromper respostas em andamento                                                  | Afirmação                         |
| **RF21** | Autenticação via token de acesso                                                    | Afirmação                         |
| **RF22** | Confirmação para limpar o histórico                                                 | Afirmação                         |
| **RF24** | Criptografia TLS em trânsito e AES-256 em repouso                                   | Afirmação                         |
| **RF25** | Controle de compartilhamento de dados pelo usuário                                  | Afirmação                         |
| **RF26** | Autenticação multifator opcional                                                    | Afirmação                         |
| **RF27** | Modo escuro/claro com sincronização automática ao SO                                | Afirmação                         |
| **RF28** | Tutorial interativo na primeira execução                                            | Afirmação                         |
| **RF30** | Melhorar retenção de contexto em diálogos longos                                    | Afirmação                         |
| **RF35** | Tooltip do título ao passar o mouse na barra lateral                                | Afirmação                         |
| **RF36** | Instruções claras de OCR na interface de envio de imagens                           | Afirmação                         |
| **RN01** | Uso da arquitetura DeepSeek-V3                                                      | Afirmação                         |
| **RN02** | Versões para Android e iOS                                                          | Afirmação                         |
| **RN03** | Histórico de conversas por 30 dias (não persistente sem salvar)                     | Afirmação                         |
| **RN04** | Exclusão automática de dados de upload                                              | Afirmação                         |
| **RN05** | Interface seguindo diretrizes de usabilidade e acessibilidade                       | Afirmação                         |
| **RN06** | Mensagens de erro claras em caso de falha                                           | Afirmação                         |
| **RN07** | Suportar múltiplas requisições simultâneas sem degradação                           | Afirmação                         |
| **RN08** | Processamento de arquivos grandes (PDF/DOCX) em ≤ 10 s e operações simples em ≤ 2 s | Operacionalização (métrica clara) |
| **RN09** | Informar claramente onde e como os dados são armazenados                            | Afirmação                         |
| **RN10** | Opt-in/out para uso de dados em re-treinamento ou venda de modelos                  | Afirmação                         |
| **RN12** | Estabilidade na geração de conteúdo pesado (PDF, cálculos)                          | Afirmação                         |
| **RN13** | ≥ 95 % dos usuários avaliando usabilidade como “Fácil” ou “Muito fácil”             | Operacionalização (métrica clara) |
| **RN14** | ≥ 90 % de concordância em “Interface clara e agradável”                             | Operacionalização (métrica clara) |
| **RN15** | ≤ 5 % dos usuários relatando dificuldade em encontrar opções/ferramentas            | Operacionalização (métrica clara) |

* **Softgoal de Afirmação**: enunciados qualitativos, sem critério de satisfação mensurável definido.
* **Softgoal de Operacionalização**: já vem com métricas precisas que permitem testar sua satisfação.

## Cartões de Especificação

## Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 30, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/definicao-nfr-framework.png)

> <a id="REF2" href="#anchor_2">2.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 30-31, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/definicao-sig.png)

> <a id="REF3" href="#anchor_3">3.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 32, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/decomposicoes.png)

> <a id="REF4" href="#anchor_4">4.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 32-33, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/tipos-de-decomposicao.png)

> <a id="REF5" href="#anchor_5">5.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 33, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/contribuicoes.png)

> <a id="REF6" href="#anchor_6">6.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 33-34, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/tipos-de-contribuicao.png)

> <a id="REF7" href="#anchor_7">7.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, p. 33-34, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 23/05/2025. [`Foto da referência`](../images/nfr-framework/procedimento-de-avaliacao.png)

## Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/05/2025 |  1.0   | (#NFR01) Criação do documento NFR Framework.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 23/05/2025 |  1.1  | (#NFR01) Adição da introdução e do texto explicando o NFR Framework.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 27/05/2025 |  1.2  | (#NFR01) Identifica requisitos alvo para NFR Framework.| [`@Gabriela`](https://github.com/gaubiela)   | --  |
