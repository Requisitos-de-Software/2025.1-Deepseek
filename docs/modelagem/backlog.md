## Introdução

O backlog consiste em uma lista contendo as prioridades dos requisitos do projeto que fornecem valor comercial ao cliente. Cabe destacar que os itens podem ser adicionados a esse registro a qualquer momento, dessa forma que as alterações são introduzidas. O gerente de produto avalia o registro e atualiza as prioridades conforme solicitado <a id="anchor_1" href="#REF1">[1]</a>.

Neste projeto, o gerente do produto será uma pessoa externa ao projeto, mas, que ainda possui certo conhecimento de como funciona o app DeepSeek, podendo ser capaz de avaliar o registro e os requisitos que foram elicitados.

O Backlog é composto de dois itens, os épicos e os temas. Enquanto uma história de usuário pode ser objeto de subdivisão para que as histórias resultantes sejam pequenas o suficiente para elas possam ser individualmente acomodadas a uma arquitetura de software e assim ser implementadas dentro de uma interação, existem manifestações  do usuário que correspondem a objetivos agregadores, esses são chamados de épicos <a id="anchor_2" href="#REF2">[2]</a>. Já os temas são coleções de histórias de usuário relacionadas <a id="anchor_3" href="#REF3">[3]</a>.

## Metolodologia

Para a criação do backlog, foi utilizado como base dois artefatos produzidos: as histórias de usuário e o documento de priorização three-level-scale. A partir das histórias de usuário criadas, elas foram classificadas em diferentes épicos ao desenvolver o backlog, assim, cada história de usuário, que representa um requisito implementado ou não do app DeepSeek se enquadra em um dos épicos desenvolvidos para esse documento de backlog. Para a priorização delas, foi utilizada a mesma priorização obtida no documento da técnica de priorização three-level-scale.

## Validação com Usuário

A validação com o usuário foi feita de forma presencial, no dia 25 de junho.

<iframe width="560" height="315" src="https://www.youtube.com/embed/AEf_79M4ifc?si=Bpdy9JcrXQ0gfdkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Participantes da validação

| Participante | Papel |
| ------------ | ----- |
| Luiz | Integrante do grupo, responsável por coordenar a validação com o usuário. |
| Luisa Mel | Estudante de engenharia aeroespacial de 20 anos de idade, responsável por validar o artefato backlog. |

* [Termo de consentimento para gravação](../gravacoes/termos-de-consentimento/termo-de-consentimento-luisa_assinado_250626_185541_assinado.pdf)

## Temas

Ao analisar as histórias de usuário criadas, foi possível organizá-las em três temas:

1. **Funcionalidades**: Abrange os épicos 1, 4 e 5, englobando as funciondalidades que usuário utiliza ao interagir com a inteligência artificial assim como as histórias de usuário que se referem a como o usuário interage com o app;
2. **Dados e segurança**: Engloba os épicos 2, 3, os quais se referem as funcionalidades relacionadas à segurança do aplicativo e como os dados do usuário podem ser geridos pelo app, pelo usuário e pelos servidores;
3. **Integrações**: Engloba os épicos 7 e 8, os quais tratam das integrações do aplicativo com outros apps, além do gerenciamento de arquivos que são recebidos pelo app.

## Épicos

Após a definição dos temas, eles são dividios em épicos, assim, o nível de abstração das atividades que vão ser realizadas diminui. Para esse documento foram criados os seguintes épicos:

* **Épico 1**: Funcionalidades de IA;
* **Épico 2**: Controle de dados;
* **Épico 3**: Segurança;
* **Épico 4**: Funcionalidades do chat;
* **Épico 5**: Interface e experiência do usuário;
* **Épico 6**: Desempenho e estabilidade;
* **Épico 7**: Gerenciamento de arquivos;
* **Épico 8**: Integrações e API.

### Histórias de Usuário

As histórias de usuário especificam ainda mais os épicos, elas apresentam descrições de uma determinada funcionalidade, geralmente seguem a forma "Eu, como ___, desejo ___, para____,". Elas estão melhor explicadas e representadas no artefato Histórias de Usuário.

### Épico 1 - Funcionalidades de IA

Esse épico inclui as histórias de usuário que envolvem o uso de funcionalidades da IA do app DeepSeek. Elas tratam de apresentar as funcionalidades que esse modelo de inteligência artificial possui. Entre algumas dessas funcionalidades está o uso da função pensamento profundo, que utiliza um modelo diferente do comum para o processamento de das informações, o R1, esse modelo possui maior precisão e raciocínio lógico, ideal para perguntas sobre matemática e programação.

Outras histórias de usuário incluem o uso de requisitos como: busca da web através da IA refinamento de respostas do modelo.

As histórias de usuário que se classificam no Épico 1 - Funcionalidades de IA, podem ser vistas na Tabela 1.

<font><p style="text-align: center">**Tabela 1** - Histórias de usuário classificadas com o Épico 1 - Funcionalidades de IA.</p></font>

|   ID   | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------ | ------------------------------------------------------------| -------------------- | ---------- |
| #BK01 | [#HU13 - Resolver um problema difícil de matemática](../modelagem/historias-de-usuario.md#hu13)           | [#RF02](../elicitacao/requisitos-gerais.md)                | Alta       |
| #BK02  | [HU30 – Refinar resposta gerada até atingir clareza e concisão](../modelagem/historias-de-usuario.md#hu30) | [#RF11, #RF12, #RF17](../elicitacao/requisitos-gerais.md)                | Baixa    |
| #BK03 | [HU36 – Exibir citações de fontes](../modelagem/historias-de-usuario.md#hu36)                              | [#RF14](../elicitacao/requisitos-gerais.md), #ROF08                | Baixa           |
| #BK04 | [#HU10 – Citar fontes da web nas pesquisas](../modelagem/historias-de-usuario.md#hu10)                               | [#RF14](../elicitacao/requisitos-gerais.md)               | Baixa           |
| #BK05  | [HU24 – Retenção de contexto em diálogos longos](../modelagem/historias-de-usuario.md#hu24)              | [#RF30](../elicitacao/requisitos-gerais.md)                | Média      |
| #BK06  | [HU32 – Implementar memória de contexto persistente entre conversas](../modelagem/historias-de-usuario.md#hu32)               | [#RF31](../elicitacao/requisitos-gerais.md)                | Média           |
| #BK07  | [#HU20 – Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)](../modelagem/historias-de-usuario.md#hu20)                                                        | [#RF32](../elicitacao/requisitos-gerais.md)                | Média           |
| #BK08  | [#HU33 – Disponibilizar resumo textual do conteúdo de vídeo importado de links do YouTube](../modelagem/historias-de-usuario.md#hu33) | [#RF38](../elicitacao/requisitos-gerais.md), #RQF23 | Alta |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 2 - Controle de dados

Esse épico inclui as hisórias de usuário que envolvem os dados que o usuário compartilha com o modelo DeepSeek e seus servidores. Elas tratam de discutir como esses dados são compartilhados, quais tipos podem ser compartilhados, como esses dados são armazenados, entre outros.

As histórias de usuário que se classificam no Épico 2 - Controle de dados, podem ser vistas na Tabela 2.

<font><p style="text-align: center">**Tabela 2** - Histórias de usuário classificadas com o Épico 2 - Controle de dados.</p></font>

|  ID   | História de usuário                                         | Requisito trabalhado | Prioridade |
| ----- | ------------------------------------------------------------| -------------------- | ---------- |
| #BK09 | [#HU02 – Confirmar a exclusão do histórico de conversas](../modelagem/historias-de-usuario.md#hu02)      | [#RF22](../elicitacao/requisitos-gerais.md)                | Baixa      |
| #BK10 | [#HU17 - Controlar quais dados são compartilhados com a IA](../modelagem/historias-de-usuario.md#hu17)    | [#RF25](../elicitacao/requisitos-gerais.md)                | Média      |
| #BK11 | [#HU06 – Controle de dados](../modelagem/historias-de-usuario.md#hu06) | [#RF25](../elicitacao/requisitos-gerais.md)                | Média      |
| #BK12 | [#HU37 – Deve fazer a exclusão automática de dados de upload](../modelagem/historias-de-usuario.md#hu37) | [#RN04](../elicitacao/requisitos-gerais.md)                |Alta           |
| #BK13 | [HU39 – Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos](../modelagem/historias-de-usuario.md#hu39)                                                            | [#RN10](../elicitacao/requisitos-gerais.md)                | Alta           |
| #BK14 | [#HU28 – Apagar conversas individuais ou todo o histórico no DeepSeek](../modelagem/historias-de-usuario.md#hu28) | [#RF16](../elicitacao/requisitos-gerais.md) | Alta |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 3 - Segurança

Esse épico inclui as histórias de usuário que envolvem a questão da segurança ao utilizar o aplicativo. Um dos exemplos é o requisito #RF26, que busca ter a funcionalidade de autenticaçao multifator para que usuário acesse funcionalidades avaçadas do app, ele também está representado na história de usuário com ID HU16.

As histórias de usuário que se classificam no Épico 3 - Segurança, podem ser vistas na Tabela 3.

<font><p style="text-align: center">**Tabela 3** - Histórias de usuário classificadas com o Épico 3 - Segurança.</p></font>

|  ID   |  História de usuário                                         | Requisito trabalhado | Prioridade |
| ----- | ------------------------------------------------------------| -------------------- | ---------- |
| #BK15 | [#HU41 – Deve possuir a opção de login com conta Google/Apple ID](../modelagem/historias-de-usuario.md#hu41)                | [#RF04](../elicitacao/requisitos-gerais.md)                | Média      |
| #BK16 | [#HU16 - Autenticar a conta para acessar funcionalidades avançadas](../modelagem/historias-de-usuario.md#hu16) | [#RF26](../elicitacao/requisitos-gerais.md)                | Não fazer           |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 4 - Funcionalidades do chat

Inclui funcionalidades que são utilizadas ao criar um chat com a IA mas não possuem uma forte (ou nenhuma) relação com o modelo de IA utilizado no app. Entre essas funcionalidades está a opção de poder salvar o chat entre múltiplas plataformas, assim, um usuário pode começar uma conversa com o DeepSeek em seu notebook e continuar mais tarde em seu smartphone.

As histórias de usuário que se classificam no Épico 4 - Funcionalidades do chat, podem ser vistas na Tabela 4.

<font><p style="text-align: center">**Tabela 4** - Histórias de usuário classificadas com o Épico 4 - Funcionalidades do chat.</p></font>

|   ID  | História de usuário                                         | Requisito trabalhado | Prioridade |
| ----- | ------------------------------------------------------------| -------------------- | ---------- |
| #BK17 | [#HU18 - Salvar chat entre plataformas](../modelagem/historias-de-usuario.md#hu18)                       | [#RF05](../elicitacao/requisitos-gerais.md)                | Média      |
| #BK18 | [#HU03 – Interação com a Inteligência Artificial](../modelagem/historias-de-usuario.md#hu03)              | [#RF07](../elicitacao/requisitos-gerais.md)                | Alta       |
| #BK19 | [#HU42 – Deve ser possível criar novos chats](../modelagem/historias-de-usuario.md#hu42)                  | [#RF08](../elicitacao/requisitos-gerais.md)                | Alta       |
| #BK20 | [#HU04 – Renomear um chat já existente](../modelagem/historias-de-usuario.md#hu04)                        | [#RF09](../elicitacao/requisitos-gerais.md)                | Média      |
| #BK21 | [HU35 – Recuperar chats anteriores](../modelagem/historias-de-usuario.md#hu35)                           | [#RF10](../elicitacao/requisitos-gerais.md), ROF04                | Média           |
| #BK22 | [HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado](../modelagem/historias-de-usuario.md#hu29)                                                            | [#RF13](../elicitacao/requisitos-gerais.md)                | Alta           
| #BK23 | [#HU15 - Interromper chat em andamento](../modelagem/historias-de-usuario.md#hu15)                        | [#RF19](../elicitacao/requisitos-gerais.md)                |Baixa       |
| #BK24 | [#HU07 – Interromper respostas em andamento](../modelagem/historias-de-usuario.md#hu07)                         | [#RF19](../elicitacao/requisitos-gerais.md)                |Baixa       |
| #BK25 | [#HU09 – Organizar conversas em pastas, listas ou temas](../modelagem/historias-de-usuario.md#hu09)   | [#RF33](../elicitacao/requisitos-gerais.md)                | Média           |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 5 - Interface e experiência do usuário

Este épico busca incluir aquelas histórias de usário que tratam de detalhar aqueles requisitos que são relacionados à interface do app e a experiência que o usuário tem ao integarir com o aplicativo. Assim, questões voltadas para a acessibilidade e legibilidade se enquadram nesse épico bem como outros histórias de usuário parecidas.

As histórias de usuário que se classificam no Épico 5 - Interface e experiência do usuário, podem ser vistas na Tabela 5.

<font><p style="text-align: center">**Tabela 5** - Histórias de usuário classificadas com o Épico 5 - Interface e experiência do usuário.</p></font>

|   ID   | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------ | ------------------------------------------------------------| -------------------- | ---------- |
| #BK26  | [#HU23 – As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis](../modelagem/historias-de-usuario.md#hu23)                                                         | [#RF18](../elicitacao/requisitos-gerais.md)               | Baixa           |
| #BK27  | [#HU34 – Adicionar editor de texto avançado com suporte a Markdown e formatação de código](../modelagem/historias-de-usuario.md#hu34)                                                           | [#RF18](../elicitacao/requisitos-gerais.md),  #RQF15               | Baixa           |
| #BK28  | [#HU05 – Busca incremental no campo de texto](../modelagem/historias-de-usuario.md#hu05)                                                            | [#RF23](../elicitacao/requisitos-gerais.md)               | Baixa           |
| #BK29  | [#HU19 – Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO](../modelagem/historias-de-usuario.md#hu19)                                                           | [#RF27](../elicitacao/requisitos-gerais.md)               | Alta           |
| #BK30  | [#HU01 – Visualizar tutorial interativo](../modelagem/historias-de-usuario.md#hu01)                   | [#RF28](../elicitacao/requisitos-gerais.md)               | Baixa       |
| #BK31  | [#HU14 - Visualizar em tempo real o status do servidor](../modelagem/historias-de-usuario.md#hu14)        | [#RF29](../elicitacao/requisitos-gerais.md)               | Não fazer  |
| #BK32  | [#HU12 – Inserir informações por comando de voz](../modelagem/historias-de-usuario.md#hu12)                                                           | [#RF34](../elicitacao/requisitos-gerais.md)               | Alta           |
| #BK33  | [#HU21 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico](../modelagem/historias-de-usuario.md#hu21)        | [#RF35](../elicitacao/requisitos-gerais.md)               | Baixa           |
| #BK34  | [#HU38 – A interface deve seguir diretrizes de usabilidade e acessibilidade](../modelagem/historias-de-usuario.md#hu38)   | [#RN05](../elicitacao/requisitos-gerais.md)               | Alta           |
| #BK35  | [#HU27 – Alterar idioma da interface do DeepSeek](../modelagem/historias-de-usuario.md#hu27)              | [#RN15](../elicitacao/requisitos-gerais.md)               | Média      |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 6 - Desempenho e estabilidade

Este épico busca tratar daquelas histórias de usuário que discutem o desempenho do app e como ele deve performar sob determinadas condições impostas.

As histórias de usuário que se classificam no Épico 6 - Desempenho e estabilidade, podem ser vistas na Tabela 6.

<font><p style="text-align: center">**Tabela 6** - Histórias de usuário classificadas com o Épico 6 - Desempenho e estabilidade.</p></font>

|   ID   | História de usuário                                         | Requisito trabalhado | Prioridade |
| ------ | ------------------------------------------------------------| -------------------- | ---------- |
| #BK36  | [#HU40 – Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas](../modelagem/historias-de-usuario.md#hu40)                                                           | [#RN12](../elicitacao/requisitos-gerais.md)               |  Média          |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 7 - Gerenciamento de arquivos 

Este épico se refere aos requisitos que fazem uso de arquivos, isso ocorre quando o usuário utiliza a opção de enviar um arquivo junto com um texto em uma conversa para a IA analisar. 

As histórias de usuário que se classificam no Épico 7 - Gerenciamento de arquivos, podem ser vistas na Tabela 7.

<font><p style="text-align: center">**Tabela 7** - Histórias de usuário classificadas com o Épico 7 - Gerenciamento de arquivos.</p></font>

|   ID   | História de usuário                                         | Requisito trabalhado | Prioridade |
| -------| ------------------------------------------------------------| -------------------- | ---------- |
| #BK37  | [#HU25 – Suportar múltiplos formatos de imagem e extração de texto confiável via OCR](../modelagem/historias-de-usuario.md#hu25)                                                         | [#RF03](../elicitacao/requisitos-gerais.md)               | Alta           |
| #BK38  | [#HU26 – Enviar PDF e receber texto extraído e insights preservando formatação e símbolos](../modelagem/historias-de-usuario.md#hu26)                                                      | [#RF03](../elicitacao/requisitos-gerais.md)               | Alta           |
| #BK39  | [#HU08 – Enviar arquivos com suporte a leitura OCR](../modelagem/historias-de-usuario.md#hu08)      | #RIF01              | Alta           |
| #BK40  | [#HU22 – Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR](../modelagem/historias-de-usuario.md#hu22) | [#RF36](../elicitacao/requisitos-gerais.md) | Média |

Fonte: [Luiz](https://github.com/luizfaria1989)

### Épico 8 - Integrações e API

O épico 8 busca tratar das integrações do app DeepSeek com outros aplicativos e programas, além disso ele também discute a questão da API pública do DeepSeek, componente essencial para garantir uma melhor integração do modelo com diferentes aplicativos utilizados pelo usuário.

As histórias de usuário que se classificam no Épico 8 - Inetgreções e API, podem ser vistas na Tabela 8.

<font><p style="text-align: center">**Tabela 8** - Histórias de usuário classificadas com o Épico 8 - Integrações e API.</p></font>

|    ID   | História de usuário                                         | Requisito trabalhado | Prioridade |
| --------| ------------------------------------------------------------| -------------------- | ---------- |
| #BK41   | [HU31 – Utilizar uma API Pública](../modelagem/historias-de-usuario.md#hu31)                                                       | [#RF20](../elicitacao/requisitos-gerais.md)               | Alta           |
| #BK42   | [HU11 – Integração com plataformas externas](../modelagem/historias-de-usuario.md#hu11) | [#RF37](../elicitacao/requisitos-gerais.md)               | Média           |

Fonte: [@Luiz](https://github.com/luizfaria1989)

## Product backlog completo

Por fim, juntanto todas as tabelas desenvolvidas, é possível criar o product backlog completo do app DeepSeek com as histórias de usuário que foram criadas. O product backlog pode ser visto na Tabela 9.

<font><p style="text-align: center">**Tabela 9** - Product backlog do app DeepSeek</p></font>


|   ID    | Épico                                      | História de usuário                                         | Requisito trabalhado | Prioridade |
| --------| ------------------------------------------ | ------------------------------------------------------------| -------------------- | ---------- |
| <a id="bk01">#BK01</a> | Épico 1 - Funcionalidades de IA |  [#HU13 - Resolver um problema difícil de matemática](../modelagem/historias-de-usuario.md#hu13)           | [#RF02](../elicitacao/requisitos-gerais.md)                | Alta       |
| <a id="bk02">#BK02</a>  | Épico 1 - Funcionalidades de IA | [HU30 – Refinar resposta gerada até atingir clareza e concisão](../modelagem/historias-de-usuario.md#hu30) | [#RF11, #RF12, #RF17](../elicitacao/requisitos-gerais.md)                | Baixa    |
| <a id="bk03">#BK03</a> | Épico 1 - Funcionalidades de IA | [HU36 – Exibir citações de fontes](../modelagem/historias-de-usuario.md#hu36)                              | [#RF14](../elicitacao/requisitos-gerais.md), #ROF08                | Baixa           |
| <a id="bk04">#BK04</a> | Épico 1 - Funcionalidades de IA | [#HU10 – Citar fontes da web nas pesquisas](../modelagem/historias-de-usuario.md#hu10)                               | [#RF14](../elicitacao/requisitos-gerais.md)               | Baixa           |
| <a id="bk05">#BK05</a>  | Épico 1 - Funcionalidades de IA | [HU24 – Retenção de contexto em diálogos longos](../modelagem/historias-de-usuario.md#hu24)              | [#RF30](../elicitacao/requisitos-gerais.md)                | Média      |
| <a id="bk06">#BK06</a>  | Épico 1 - Funcionalidades de IA | [HU32 – Implementar memória de contexto persistente entre conversas](../modelagem/historias-de-usuario.md#hu32)               | [#RF31](../elicitacao/requisitos-gerais.md)                | Média           |
| <a id="bk07">#BK07</a>  | Épico 1 - Funcionalidades de IA | [#HU20 – Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)](../modelagem/historias-de-usuario.md#hu20)                                                        | [#RF32](../elicitacao/requisitos-gerais.md)                | Média           |
| <a id="bk08">#BK08</a>  | Épico 1 - Funcionalidades de IA | [#HU33 – Disponibilizar resumo textual do conteúdo de vídeo importado de links do YouTube](../modelagem/historias-de-usuario.md#hu33) | [#RF38](../elicitacao/requisitos-gerais.md), #RQF23 | Alta |
| <a id="bk09">#BK09</a> | Épico 2 - Controle de dados | [#HU02 – Confirmar a exclusão do histórico de conversas](../modelagem/historias-de-usuario.md#hu02)      | [#RF22](../elicitacao/requisitos-gerais.md)                | Baixa      |
| <a id="bk10">#BK10</a> | Épico 2 - Controle de dados | [#HU17 - Controlar quais dados são compartilhados com a IA](../modelagem/historias-de-usuario.md#hu17)    | [#RF25](../elicitacao/requisitos-gerais.md)                | Média      |
| <a id="bk11">#BK11</a> | Épico 2 - Controle de dados | [#HU06 – Controle de dados](../modelagem/historias-de-usuario.md#hu06) | [#RF25](../elicitacao/requisitos-gerais.md)                | Média      |
| <a id="bk12">#BK12</a> | Épico 2 - Controle de dados | [#HU37 – Deve fazer a exclusão automática de dados de upload](../modelagem/historias-de-usuario.md#hu37) | [#RN04](../elicitacao/requisitos-gerais.md)                |Alta           |
| <a id="bk13">#BK13</a> | Épico 2 - Controle de dados | [HU39 – Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos](../modelagem/historias-de-usuario.md#hu39)                                                            | [#RN10](../elicitacao/requisitos-gerais.md)                | Alta           |
| <a id="bk14">#BK14</a> | Épico 2 - Controle de dados | [#HU28 – Apagar conversas individuais ou todo o histórico no DeepSeek](../modelagem/historias-de-usuario.md#hu28) | [#RF16](../elicitacao/requisitos-gerais.md) | Alta |
| <a id="bk15">#BK15</a> | Épico 3 - Segurança | [#HU41 – Deve possuir a opção de login com conta Google/Apple ID](../modelagem/historias-de-usuario.md#hu41)                | [#RF04](../elicitacao/requisitos-gerais.md)                | Média      |
| <a id="bk16">#BK16</a> | Épico 3 - Segurança | [#HU16 - Autenticar a conta para acessar funcionalidades avançadas](../modelagem/historias-de-usuario.md#hu16) | [#RF26](../elicitacao/requisitos-gerais.md)                | Não fazer           |
| <a id="bk17">#BK17</a> | Épico 4 - Funcionalidades do chat | [#HU18 - Salvar chat entre plataformas](../modelagem/historias-de-usuario.md#hu18)                       | [#RF05](../elicitacao/requisitos-gerais.md)                | Média      |
| <a id="bk18">#BK18</a> | Épico 4 - Funcionalidades do chat | [#HU03 – Interação com a Inteligência Artificial](../modelagem/historias-de-usuario.md#hu03)              | [#RF07](../elicitacao/requisitos-gerais.md)                | Alta       |
| <a id="bk19">#BK19</a> | Épico 4 - Funcionalidades do chat | [#HU42 – Deve ser possível criar novos chats](../modelagem/historias-de-usuario.md#hu42)                  | [#RF08](../elicitacao/requisitos-gerais.md)                | Alta       |
| <a id="bk20">#BK20</a> | Épico 4 - Funcionalidades do chat | [#HU04 – Renomear um chat já existente](../modelagem/historias-de-usuario.md#hu04)                        | [#RF09](../elicitacao/requisitos-gerais.md)                | Média      |
| <a id="bk21">#BK21</a> | Épico 4 - Funcionalidades do chat | [HU35 – Recuperar chats anteriores](../modelagem/historias-de-usuario.md#hu35)                           | [#RF10](../elicitacao/requisitos-gerais.md), ROF04                | Média           |
| <a id="bk22">#BK22</a> | Épico 4 - Funcionalidades do chat | [HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado](../modelagem/historias-de-usuario.md#hu29)                                                            | [#RF13](../elicitacao/requisitos-gerais.md)                | Alta           
| <a id="bk23">#BK23</a> | Épico 4 - Funcionalidades do chat | [#HU15 - Interromper chat em andamento](../modelagem/historias-de-usuario.md#hu15)                        | [#RF19](../elicitacao/requisitos-gerais.md)                |Baixa       |
| <a id="bk24">#BK24</a> | Épico 4 - Funcionalidades do chat | [#HU07 – Interromper respostas em andamento](../modelagem/historias-de-usuario.md#hu07)                         | [#RF19](../elicitacao/requisitos-gerais.md)                |Baixa       |
| <a id="bk25">#BK25</a> | Épico 4 - Funcionalidades do chat | [#HU09 – Organizar conversas em pastas, listas ou temas](../modelagem/historias-de-usuario.md#hu09)   | [#RF33](../elicitacao/requisitos-gerais.md)                | Média           |
| <a id="bk26">#BK26</a>  | Épico 5 - Interface e experiência do usuário | [#HU23 – As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis](../modelagem/historias-de-usuario.md#hu23)                                                         | [#RF18](../elicitacao/requisitos-gerais.md)               | Baixa           |
| <a id="bk27">#BK27</a>  | Épico 5 - Interface e experiência do usuário | [#HU34 – Adicionar editor de texto avançado com suporte a Markdown e formatação de código](../modelagem/historias-de-usuario.md#hu34)                                                           | [#RF18](../elicitacao/requisitos-gerais.md),  #RQF15               | Baixa           |
| <a id="bk28">#BK28</a>  | Épico 5 - Interface e experiência do usuário | [#HU05 – Busca incremental no campo de texto](../modelagem/historias-de-usuario.md#hu05)                                                            | [#RF23](../elicitacao/requisitos-gerais.md)               | Baixa           |
| <a id="bk29">#BK29</a>  | Épico 5 - Interface e experiência do usuário | [#HU19 – Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO](../modelagem/historias-de-usuario.md#hu19)                                                           | [#RF27](../elicitacao/requisitos-gerais.md)               | Alta           |
| <a id="bk30">#BK30</a>  | Épico 5 - Interface e experiência do usuário | [#HU01 – Visualizar tutorial interativo](../modelagem/historias-de-usuario.md#hu01)                   | [#RF28](../elicitacao/requisitos-gerais.md)               | Baixa       |
| <a id="bk31">#BK31</a>  | Épico 5 - Interface e experiência do usuário | [#HU14 - Visualizar em tempo real o status do servidor](../modelagem/historias-de-usuario.md#hu14)        | [#RF29](../elicitacao/requisitos-gerais.md)               | Não fazer  |
| <a id="bk32">#BK32</a>  | Épico 5 - Interface e experiência do usuário | [#HU12 – Inserir informações por comando de voz](../modelagem/historias-de-usuario.md#hu12)                                                           | [#RF34](../elicitacao/requisitos-gerais.md)               | Alta           |
| <a id="bk33">#BK33</a>  | Épico 5 - Interface e experiência do usuário | [#HU21 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico](../modelagem/historias-de-usuario.md#hu21)        | [#RF35](../elicitacao/requisitos-gerais.md)               | Baixa           |
| <a id="bk34">#BK34</a>  | Épico 5 - Interface e experiência do usuário | [#HU38 – A interface deve seguir diretrizes de usabilidade e acessibilidade](../modelagem/historias-de-usuario.md#hu38)   | [#RN05](../elicitacao/requisitos-gerais.md)               | Alta           |
| <a id="bk35">#BK35</a>  | Épico 5 - Interface e experiência do usuário | [#HU27 – Alterar idioma da interface do DeepSeek](../modelagem/historias-de-usuario.md#hu27)              | [#RN15](../elicitacao/requisitos-gerais.md)               | Média      |
| <a id="bk36">#BK36</a>  | Épico 6 - Desempenho e estabilidade | [#HU40 – Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas](../modelagem/historias-de-usuario.md#hu40)                                                           | [#RN12](../elicitacao/requisitos-gerais.md)               |  Média          |
| <a id="bk37">#BK37</a>  | Épico 7 - Gerenciamento de arquivos |[#HU25 – Suportar múltiplos formatos de imagem e extração de texto confiável via OCR](../modelagem/historias-de-usuario.md#hu25)                                                         | [#RF03](../elicitacao/requisitos-gerais.md)               | Alta           |
| <a id="bk38">#BK38</a>  | Épico 7 - Gerenciamento de arquivos | [#HU26 – Enviar PDF e receber texto extraído e insights preservando formatação e símbolos](../modelagem/historias-de-usuario.md#hu26)                                                      | [#RF03](../elicitacao/requisitos-gerais.md)               | Alta           |
| <a id="bk39">#BK39</a>  | Épico 7 - Gerenciamento de arquivos | [#HU08 – Enviar arquivos com suporte a leitura OCR](../modelagem/historias-de-usuario.md#hu08)      | #RIF01              | Alta           |
| <a id="bk40">#BK40</a>  | Épico 7 - Gerenciamento de arquivos | [#HU22 – Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR](../modelagem/historias-de-usuario.md#hu22) | [#RF36](../elicitacao/requisitos-gerais.md) | Média |
| <a id="bk41">#BK41</a>   | Épico 8 - Integrações e API | [HU31 – Utilizar uma API Pública](../modelagem/historias-de-usuario.md#hu31)                                                       | [#RF20](../elicitacao/requisitos-gerais.md)               | Alta           |
| <a id="bk42">#BK42</a>   | Épico 8 - Integrações e API | [HU11 – Integração com plataformas externas](../modelagem/historias-de-usuario.md#hu11) | [#RF37](../elicitacao/requisitos-gerais.md)               | Média           |

Fonte: [Luiz](https://github.com/luizfaria1989)

---

## Referência Bibliográfica

>  <a id="REF1" href="#anchor_1">1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. [`Foto da referência`](../images/backlog/definicao-backlog.png)

>  <a id="REF2" href="#anchor_2">2.</a> VAZQUEZ, Carlos E.; SIMÕES, Guilherme S.. Engenharia de requisitos: software orientado ao negócio. 8 Rio de Janeiro: Brasport, 2016. [`Foto da referência`](../images/backlog/definicao-epicos.png)

>  <a id="REF3" href="#anchor_3">3.</a> VAZQUEZ, Carlos E.; SIMÕES, Guilherme S.. Engenharia de requisitos: software orientado ao negócio. 8 Rio de Janeiro: Brasport, 2016.[`Foto da referência`](../images/backlog/definicao-temas.png)

---

## Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/05/2025 |  1.0   | (#B01) Criação do documento do Backlog.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 23/05/2025 |  1.1   | (#B01) Adição da introdução do artefato.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 23/05/2025 |  1.2   | (#B01) Adição da referência da definição de Backlog.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 31/05/2025 |  1.3   | (#B01) Criação e descrição dos épicos 1 a 4 (Funcionalidades de IA, Controle de Dados, Segurança, Funcionalidades do chat). Categorização das histórias de usuário 12 a 18. Adição da metodologia.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Ana Joyce](https://github.com/anajoyceamorim) |
| 31/05/2025 |  1.4   | (#B01) Criação e descrição dos épicos 5 a 8. Categorização das histórias de usuário 19 a 30.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 01/06/2025 |  1.5   | (#B01) Categorização das histórias de usuário 31 a 36.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Ana Joyce](https://github.com/anajoyceamorim) |
| 01/06/2025 |  1.6   | (#B01) Categorização das histórias de usuário 01 a 06. Criação dos temas.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 01/06/2025 |  1.7   | (#B01) Categorização das histórias de usuário 37 a 42.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 01/06/2025 |  1.8   | (#B01) Categorização das histórias de usuário 7 a 12.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Ana Joyce](https://github.com/anajoyceamorim) |
| 05/06/2025 |  2.0   | (#B01) Adição dos ids para organizar o backlog.| [`@Luiz`](https://github.com/luizfaria1989)   |  [`@Fabio`](https://github.com/fabinsz) |
| 07/06/2025 |  2.1   | (#B01) Adição dos hiperlinks para as histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   |  [`@Fabio`](https://github.com/fabinsz) |
| 07/06/2025 |  2.2   | (#B01) Adição dos hiperlinks para a citação dos IDs do backlog.| [`@Luiz`](https://github.com/luizfaria1989)   |  [`@Fabio`](https://github.com/fabinsz) |
| 19/06/2025 |  2.3   | (#B01) Adição dos hiperlinks para a tabela de requisitos gerais elicitados.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Ana Clara`](https://github.com/anabborges)  |
| 26/06/2025 |  2.4   | (#B01) Adição da gravação de validação com o usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@`](https://github.com/)  |
| 27/06/2025 |  2.5  | (#B01) Adiciona o termo de consetimento da gravação da validação do backlog.| [@Luiz](https://github.com/luizfaria1989)  | [@](https://github.com/)  |
| 28/06/2025 |  2.6  | (#B01) Adiciona definição de temas e épicos.| [@Luiz](https://github.com/luizfaria1989)  | [@](https://github.com/)  |
