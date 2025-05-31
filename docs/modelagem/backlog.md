## Introdução

O backlog consiste em uma lista contendo as prioridades dos requisitos do projeto que fornecem valor comercial ao cliente. Cabe destacar que os itens podem ser adicionados a esse registro a qualquer momento, dessa forma que as alterações são introduzidas. O gerente de produto avalia o registro e atualiza as prioridades conforme solicitado <a id="anchor_1" href="#REF1">[1]</a>.

Neste projeto, o gerente do produto será uma pessoa externa ao projeto, mas, que ainda possui certo conhecimento de como funciona o app DeepSeek, podendo ser capaz de avaliar o registro e os requisitos que foram elicitados.

## Metolodologia

Para a criação do backlog, foi utilizado como base dois artefatos produzidos: as histórias de usuário e o documento de priorização tree-level-scale. A partir das histórias de usuário criadas, elas foram classificadas em diferentes épicos ao desenvolver o backlog, assim, cada história de usuário, que representa um requisito implementado ou não do app DeepSeek se enquadra em um dos épicos desenvolvidos para esse documento de backlog. Para a priorização delas, foi utilizada a mesma priorização obtida no documento da técnica de priorização tree-level-scale.

## Temas

Ao analisar as histórias de usuário criadas, foi possível organizá-las em (xxxxx) temas:

## Épicos

Após a definição dos temas, eles são dividios em épicos, assim, o nível de abstração das atividades que vão ser realizadas diminui. Para esse documento foram criados os seguintes épicos:

* Épico 1: Funcionalidades de IA;
* Épico 2: Controle de dados;
* Épico 3: Segurança;
* Épico 4: Funcionalidades do chat;
* Épico 5 - Interface e experiência do usuário;
* Épico 6 - Desempenho e estabilidade;
* Épico 7 - Gerenciamento de arquivos;
* Épico 8 - Integrações e API.

### Histórias de Usuário

As histórias de usuário especificam ainda mais as features, elas apresentam descricoes de uma determinada funcionalidade, geralmente seguem a forma "Eu, como ___, desejo ___, para____,". Elas estão melhor explicadas e representadas no artefato Histórias de Usuário.

### Épico 1 - Funcionalidades de IA

Esse épico inclui as histórias de usuário que envolvem o uso de funcionalidades da IA do app DeepSeek. Elas tratam de apresentar as funcionalidades que esse modelo de inteligência artificial possui. Entre algumas dessas funcionalidades está o uso da função pensamento profundo, que utiliza um modelo diferente do comum para o processamento de das informações, o R1, esse modelo possui maior precisão e raciocínio lógico, ideal para perguntas sobre matemática e programação.

Outras histórias de usuário incluem o uso de requisitos como: busca da web através da IA refinamento de respostas do modelo.

As histórias de usuário que se classificam no Épico 1 - Funcionalidades de IA, podem ser vistas na Tabela 1.

<font><p style="text-align: center">**Tabela 1** - Histórias de usuário classificadas com o Épico 1 - Funcionalidades de IA.</p></font>

| ID                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|             | HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado                                                            | #RF01                | Alta           |
|             | HU13 - Resolver um problema difícil de matemática           | #RF02                | Alta       |
|             |                                                             | #RF06                |            |
|            | HU30 – Refinar resposta gerada até atingir clareza e concisão | #RF11                | Baixa    |
|             | HU30 – Refinar resposta gerada até atingir clareza e concisão | #RF12                | Baixa    |
|             |                                                             | #RF14                |            |
|             | HU30 – Refinar resposta gerada até atingir clareza e concisão | #RF17                | Baixa    |
|            | HU24 – Retenção de contexto em diálogos longos              | #RF30                | Média      |
|             |                                                             | #RF31                |            |
|            | HU20 – Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)                                                            | #RF32                | Média           |
|             |                                                             | #RF38                |            |
|            |                                                             | #RN01                |            |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 2 - Controle de dados

Esse épico inclui as hisórias de usuário que envolvem on os dados que o usuário compartilha com o modelo DeepSeek e seus servidores. Elas tratam de discutir como esses dados são compartilhados, quais tipos podem ser compartilhados, como esses dados são armazenados, entre outros.

As histórias de usuário que se classificam no Épico 2 - Controle de dados, podem ser vistas na Tabela 2.

<font><p style="text-align: center">**Tabela 2** - Histórias de usuário classificadas com o Épico 2 - Controle de dados.</p></font>

| ID                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|                 |                                                             | #RF22                |            |
|                 | HU17 - Controlar quais dados são compartilhados com a IA    | #RF25                | Média      |
|               |                                                             | #RN04                |            |
|                 |                                                             | #RN09                |            |
|                 |                                                             | #RN10                |            |
|                 |                                                             | #RN11                |            |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 3 - Segurança

Esse épico inclui as histórias de usuário que envolvem a questão da segurança ao utilizar o aplicativo. Um dos exemplos é o requisito #RF26, que busca ter a funcionalidade de autenticaçao multifator para que usuário acesse funcionalidades avaçadas do app, eletambém está representado na história de usuário com ID HU16.

As histórias de usuário que se classificam no Épico 3 - Segurança, podem ser vistas na Tabela 3.

<font><p style="text-align: center">**Tabela 3** - Histórias de usuário classificadas com o Épico 3 - Segurança.</p></font>

| ID                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|                         |                                                             | #RF04                |            |
|                         |                                                             | #RF21                |            |
|                         |                                                             | #RF24                |            |
|                         | HU16 - Autenticar a conta para acessar funcionalidades avançadas | #RF26                | Não fazer           |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 4 - Funcionalidades do chat

Inclui funcionalidades que são utilizadas ao criar um chat com a IA mas não possuem uma forte (ou nenhuma) relação com o modelo de IA utilizado no app. Entre essas funcionalidades está a opção de poder salvar o chat entre múltiplas plataformas, assim, um usuário pode começar uma conversa com o DeepSeek em seu notebook e continuar mais tarde em seu smartphone.

As histórias de usuário que se classificam no Épico 4 - Funcionalidades do chat, podem ser vistas na Tabela 4.

<font><p style="text-align: center">**Tabela 4** - Histórias de usuário classificadas com o Épico 4 - Funcionalidades do chat.</p></font>

| ID                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|           | HU18 - Salvar chat entre plataformas                        | #RF05                | Média      |
|           |                                                             | #RF07                |            |
|           |                                                             | #RF08                |            |
|           |                                                             | #RF09                |            |
|           |                                                             | #RF10                |            |
|           | HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado                                                            | #RF13                | Alta           
|           | HU30 – Refinar resposta gerada até atingir clareza e concisãoresultado                                                            | #RF13                | Baixa           ||
|           | HU15 - Interromper chat em andamento                        | #RF19                |Baixa       |
|           |                                                             | #RF33                |            |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 5 - Interface e experiência do usuário

Este épico busca incluir aquelas histórias de usário que tratam de detalhar aqueles requisitos que são relacionados à interface do app e a experiência que o usuário tem ao integarir com o aplicativo. Assim, questões voltadas para a acessibilidade e legibilidade se enquadram nesse épico bem como outros histórias de usuário parecidas.

As histórias de usuário que se classificam no Épico 5 - Interface e experiência do usuário, podem ser vistas na Tabela 5.

<font><p style="text-align: center">**Tabela 5** - Histórias de usuário classificadas com o Épico 5 - Interface e experiência do usuário.</p></font>

| ID                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|  |                                                             | #RF15               |            |
|  | HU23 – As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis.                                                            | #RF18               | Baixa           |
|  |                                                             | #RF23               |            |
|  | HU19 – Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO                                                            | #RF27               | Alta           |
|  |                                                             | #RF28               |            |
|  | HU14 - Visualizar em tempo real o status do servidor        | #RF29               | Não fazer  |
|  |                                                             | #RF34               |            |
|  | HU21 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico        | #RF35               | Baixa           |
|  |                                                             | #RF36               |            |
|  |                                                             | #RN02               |            |
|  |                                                             | #RN05               |            |
|  |                                                             | #RN06               |            |
|  |                                                             | #RN13               |            |
|  |                                                             | #RN14               |            |
|  | HU27 – Alterar idioma da interface do DeepSeek              | #RN15               | Média      |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 6 - Desempenho e estabilidade

Este épico busca tratar daquelas histórias de usuário que discutem o desempenho do app e como ele deve performar sob determinadas condições impostas.

As histórias de usuário que se classificam no Épico 6 - Desempenho e estabilidade, podem ser vistas na Tabela 6.

<font><p style="text-align: center">**Tabela 6** - Histórias de usuário classificadas com o Épico 6 - Desempenho e estabilidade.</p></font>

| Épico                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|          |                                                             | #RN07               |            |
|          |                                                             | #RN08               |            |
|          |                                                             | #RN12               |            |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 7 - Gerenciamento de arquivos 

Este épico se refere aos requisitos que fazem uso de arquivos, isso ocorre quando o usuário utiliza a opção de enviar um arquivo junto com um texto em uma conversa para a IA analisar. 

As histórias de usuário que se classificam no Épico 7 - Gerenciamento de arquivos, podem ser vistas na Tabela 7.

<font><p style="text-align: center">**Tabela 7** - Histórias de usuário classificadas com o Épico 7 - Gerenciamento de arquivos.</p></font>

| Épico                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|          | HU25 – Suportar múltiplos formatos de imagem e extração de texto confiável via OCR                                                            | #RF03               | Alta           |
|         | HU26 – Enviar PDF e receber texto extraído e insights preservando formatação e símbolos                                                      | #RF03               | Alta           |

Fonte: [@Luiz](https://github.com/luizfaria1989)

### Épico 8 - Integrações e API

O épico 8 busca tratar das integrações do app DeepSeek com outros aplicativos e programas, além disso ele também discute a questão da API pública do DeepSeek, componente essencial para garantir uma melhor integração do modelo com diferentes aplicativos utilizados pelo usuário.

As histórias de usuário que se classificam no Épico 8 - Inetgreções e API, podem ser vistas na Tabela 8.

<font><p style="text-align: center">**Tabela 8** - Histórias de usuário classificadas com o Épico 8 - Integrações e API.</p></font>

| Épico                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
|                  |                                                             | #RF20               |            |
|                  |                                                             | #RF37               |            |

Fonte: [@Luiz](https://github.com/luizfaria1989)

## Product backlog completo

Por fim, juntanto todas as tabelas desenvolvidas, é possível criar o product backlog completo do app DeepSeek com as histórias de usuário que foram criadas. O product backlog pode ser visto na Tabela 9.

<font><p style="text-align: center">**Tabela 9** - Product backlog do app DeepSeek</p></font>


| Épico                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
| Épico 1 - Funcionalidades de IA            | HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado                                                            | #RF01                | Alta           |
| Épico 1 - Funcionalidades de IA            | HU13 - Resolver um problema difícil de matemática           | #RF02                | Alta       |
| Épico 1 - Funcionalidades de IA            |                                                             | #RF06                |            |
| Épico 1 - Funcionalidades de IA            | HU30 – Refinar resposta gerada até atingir clareza e concisão | #RF11                | Baixa    |
| Épico 1 - Funcionalidades de IA            | HU30 – Refinar resposta gerada até atingir clareza e concisão | #RF12                | Baixa    |
| Épico 1 - Funcionalidades de IA            |                                                             | #RF14                |            |
| Épico 1 - Funcionalidades de IA            | HU30 – Refinar resposta gerada até atingir clareza e concisão | #RF17                | Baixa    |
| Épico 1 - Funcionalidades de IA            | HU24 – Retenção de contexto em diálogos longos              | #RF30                | Média      |
| Épico 1 - Funcionalidades de IA            |                                                             | #RF31                |            |
| Épico 1 - Funcionalidades de IA            | HU20 – Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)                                                            | #RF32                | Média           |
| Épico 1 - Funcionalidades de IA            |                                                             | #RF38                |            |
| Épico 1 - Funcionalidades de IA            |                                                             | #RN01                |            |
| Épico 2 - Controle de dados                | HU28 – Apagar conversas individuais ou todo o histórico no DeepSeek                                                            | #RF16                | Alta           |
| Épico 2 - Controle de dados                |                                                             | #RF22                |            |
| Épico 2 - Controle de dados                | HU17 - Controlar quais dados são compartilhados com a IA    | #RF25                | Média      |
| Épico 2 - Controle de dados                |                                                             | #RN04                |            |
| Épico 2 - Controle de dados                |                                                             | #RN09                |            |
| Épico 2 - Controle de dados                |                                                             | #RN10                |            |
| Épico 2 - Controle de dados                |                                                             | #RN11                |            |
| Épico 3 - Segurança                        |                                                             | #RF04                |            |
| Épico 3 - Segurança                        |                                                             | #RF21                |            |
| Épico 3 - Segurança                        |                                                             | #RF24                |            |
| Épico 3 - Segurança                        | HU16 - Autenticar a conta para acessar funcionalidades avançadas | #RF26                | Não fazer           |
| Épico 4 - Funcionalidades do chat          | HU18 - Salvar chat entre plataformas                        | #RF05                | Média      |
| Épico 4 - Funcionalidades do chat          |                                                             | #RF07                |            |
| Épico 4 - Funcionalidades do chat          |                                                             | #RF08                |            |
| Épico 4 - Funcionalidades do chat          |                                                             | #RF09                |            |
| Épico 4 - Funcionalidades do chat          |                                                             | #RF10                |            |
| Épico 4 - Funcionalidades do chat          | HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado                                                            | #RF13                | Alta           
| Épico 4 - Funcionalidades do chat          | HU30 – Refinar resposta gerada até atingir clareza e concisãoresultado                                                            | #RF13                | Baixa           ||
| Épico 4 - Funcionalidades do chat          | HU15 - Interromper chat em andamento                        | #RF19                |Baixa       |
| Épico 4 - Funcionalidades do chat          |                                                             | #RF33                |            |
| Épico 5 - Interface e experiência do usuário |                                                             | #RF15               |            |
| Épico 5 - Interface e experiência do usuário | HU23 – As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis.                                                            | #RF18               | Baixa           |
| Épico 5 - Interface e experiência do usuário |                                                             | #RF23               |            |
| Épico 5 - Interface e experiência do usuário | HU19 – Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO                                                            | #RF27               | Alta           |
| Épico 5 - Interface e experiência do usuário |                                                             | #RF28               |            |
| Épico 5 - Interface e experiência do usuário | HU14 - Visualizar em tempo real o status do servidor        | #RF29               | Não fazer  |
| Épico 5 - Interface e experiência do usuário |                                                             | #RF34               |            |
| Épico 5 - Interface e experiência do usuário | HU21 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico        | #RF35               | Baixa           |
| Épico 5 - Interface e experiência do usuário |                                                             | #RF36               |            |
| Épico 5 - Interface e experiência do usuário |                                                             | #RN02               |            |
| Épico 5 - Interface e experiência do usuário |                                                             | #RN05               |            |
| Épico 5 - Interface e experiência do usuário |                                                             | #RN06               |            |
| Épico 5 - Interface e experiência do usuário |                                                             | #RN13               |            |
| Épico 5 - Interface e experiência do usuário |                                                             | #RN14               |            |
| Épico 5 - Interface e experiência do usuário | HU27 – Alterar idioma da interface do DeepSeek              | #RN15               | Média      |
| Épico 6 - Desempenho e estabilidade         |                                                             | #RN07               |            |
| Épico 6 - Desempenho e estabilidade         |                                                             | #RN08               |            |
| Épico 6 - Desempenho e estabilidade         |                                                             | #RN12               |            |
| Épico 7 - Gerenciamento de arquivos         | HU25 – Suportar múltiplos formatos de imagem e extração de texto confiável via OCR                                                            | #RF03               | Alta           |
| Épico 7 - Gerenciamento de arquivos         | HU26 – Enviar PDF e receber texto extraído e insights preservando formatação e símbolos                                                      | #RF03               | Alta           |
| Épico 8 - Integrações e API                 |                                                             | #RF20               |            |
| Épico 8 - Integrações e API                 |                                                             | #RF37               |            |

Fonte: [@Luiz](https://github.com/luizfaria1989)

## Referência Bibliográfica

>  <a id="REF1" href="#anchor_1">1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. [`Foto da referência`](../images/backlog/definicao-backlog.png)

## Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/05/2025 |  1.0   | (#B01) Criação do documento do Backlog.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 23/05/2025 |  1.1   | (#B01) Adição da introdução do artefato.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 23/05/2025 |  1.2   | (#B01) Adição da referência da definição de Backlog.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 31/05/2025 |  1.3   | (#B01) Criação e descrição dos épicos 1 a 4 (Funcionalidades de IA, Controle de Dados, Segurança, Funcionalidades do chat). Categorização das histórias de usuário 12 a 18. Adição da metodologia.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@](https://github.com/) |
| 31/05/2025 |  1.4   | (#B01) Criação e descrição dos épicos 5 a 8. Categorização das histórias de usuário 19 a 30.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@](https://github.com/) |
