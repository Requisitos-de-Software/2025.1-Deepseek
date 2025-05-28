## Introdução

As histórias de usuário descrevem o resultado, as características e a funcionalidade requisitados para o software a ser construído. Cada história, é colocada em uma ficha. Nessa ficha, o cliente atribui um valor à história baseando-se no valor de negócio global do recurso ou função. Os membros da equipe então, avaliam então cada história e atribuem a ela um custo, o qual é medido em semanas de desenvolvimento. Se a história possuir um número alto de custo, por exemplo, mais do que três semanas de desenvolvimento, é solicitado ao cliente para dividir a história em histórias menores e a atribuição de valor e custo ocorre novamente. É importante notar que podem ser escritas novas histórias a qualquer momento <a id="anchor_1" href="#REF1">[1]</a>.

## Metodologia

Tabela 2: Modelo de tabela para histórias de usuário.

| ID                        | Nome                              |
| ------------------------- | --------------------------------- |
| USXX                      | Título                            |
| Descrição                 | Eu, como XXX, desejo XXX para XXX |
| Critérios de aceitação    | - xxx  - xxx                      |
| Rastreabilidade           | Códigos dos requisitos relacionados |
| Prioridade                | Alta, média ou baixa              |

Fonte: Repositório Bilheteria Digital, disciplina de requisitos de software <a id="anchor_2" href="#REF2">[2]</a>.

### Tabela de Contribuições

| Contribuinte | Descrição                                                            | Links                                           |
|--------------|----------------------------------------------------------------------|-------------------------------------------------|
| Gabriela     | Criação das histórias de usuário HU25, HU26, HU27, HU28, HU29 e HU30 | [HU25](#hu25) · [HU26](#hu26) · [HU27](#hu27) · [HU28](#hu28) · [HU29](#hu29) · [HU30](#hu30) |



## Histórias de Usuário

<a id="hu25"></a>
## HU25 – Suportar múltiplos formatos de imagem e extração de texto confiável via OCR

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU25 | Suportar múltiplos formatos de imagem e extração de texto confiável via OCR                |
| **Descrição**              | Eu, como Usuário do DeepSeek, desejo que o sistema aceite uploads de diferentes formatos de imagem (JPG, PNG, TIFF, BMP) e extraia texto com alta fidelidade, para poder analisar documentos gráficos de várias origens sem perder símbolos ou trechos importantes. |
| **Critérios de aceitação** | - O DeepSeek aceita arquivos nos formatos JPG, PNG, TIFF e BMP;<br> - Extrai texto mantendo símbolos especiais (diacríticos, equações) e formatação básica;<br> - Taxa de precisão mínima de 95 % na extração de caracteres alfanuméricos;<br> - Tempo de resposta para OCR de cada imagem ≤ 35 s. |
| **Rastreabilidade**        | #RF03                                                                                       |
| **Prioridade**             | Alta                                                                                       |

---

<a id="hu26"></a>
## HU26 – Enviar PDF e receber texto extraído e insights preservando formatação e símbolos

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID   | Nome                                                                                                       |
| ---- | ---------------------------------------------------------------------------------------------------------- |
| HU26 | Enviar PDF e receber texto extraído e insights preservando formatação e símbolos                           |
| **Descrição**              | Eu, como Usuário, desejo enviar um PDF e receber o texto extraído e insights, preservando formatação e símbolos, para poder revisá-los e editá-los diretamente sem perder convenções de estilo. |
| **Critérios de aceitação** | - O sistema aceita arquivos PDF válidos;<br> - Extrai e apresenta todo o texto mantendo formatação (negrito, itálico, listas) e símbolos especiais (diacríticos, equações);<br> - Destaca possíveis inconsistências de extração (caracteres faltantes ou ilegíveis);<br> - Em caso de perda de conexão, notifica “Conexão perdida” e permite retomar o upload. |
| **Rastreabilidade**        | #RF03                                                                                                       |
| **Prioridade**             | Alta                                                                                                       |

---

<a id="hu27"></a>
## HU27 – Alterar idioma da interface do DeepSeek

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID   | Nome                                           |
| ---- | ---------------------------------------------- |
| HU27 | Alterar idioma da interface do DeepSeek        |
| **Descrição**              | Eu, como Usuário multilíngue, desejo poder selecionar o idioma da interface do DeepSeek (por exemplo, Português, Inglês e Espanhol), para utilizar o aplicativo no meu idioma preferido e compreender melhor todas as funcionalidades. |
| **Critérios de aceitação** | - Há um controle de seleção de idioma acessível em “Configurações”;<br> - Estão disponíveis ao menos Português, Inglês e Espanhol;<br> - A troca de idioma aplica-se instantaneamente a todos os textos da interface;<br> - A preferência de idioma é lembrada em sessões futuras. |
| **Rastreabilidade**        | #RF15                                         |
| **Prioridade**             | Média                                          |

---

<a id="hu28"></a>
## HU28 – Apagar conversas individuais ou todo o histórico no DeepSeek

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID   | Nome                                                |
| ---- | --------------------------------------------------- |
| HU28 | Apagar conversas individuais ou todo o histórico    |
| **Descrição**              | Eu, como Usuário preocupado com privacidade, desejo poder apagar conversas específicas ou limpar todo o histórico no DeepSeek, para controlar meus dados pessoais e manter meu espaço de trabalho organizado. |
| **Critérios de aceitação** | - Cada conversa exibe botão “Apagar” ao passar o mouse;<br> - Há opção “Limpar todo o histórico” em “Configurações”;<br> - Em ambos os casos, o sistema exibe diálogo de confirmação antes da exclusão;<br> - Após confirmação, a(s) conversa(s) é(ão) removida(s) imediatamente da lista. |
| **Rastreabilidade**        | #RF16                                         |
| **Prioridade**             | Alta                                           |

---

<a id="hu29"></a>
## HU29 – Buscar versão mais recente do Node.js em data específica e copiar resultado

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID   | Nome                                                               |
| ---- | ------------------------------------------------------------------ |
| HU29 | Buscar versão mais recente do Node.js em data específica e copiar resultado |
| **Descrição**              | Eu, como Usuário, desejo buscar a versão mais recente do Node.js em 10/05/2025 e copiar o resultado, para documentar de forma ágil a dependência no repositório. |
| **Critérios de aceitação** | - Ao buscar “versão mais recente do Node.js em 10/05/2025”, o sistema retorna “Node.js v20.7.0 – lançado em 08/05/2025”;<br> - O resultado inclui data de lançamento e um botão **Copy** ativo;<br> - A busca é concluída em menos de 3 segundos;<br> - Permite refinar a consulta caso não haja informação de data. |
| **Rastreabilidade**        | #RF01, #RF13                              |
| **Prioridade**             | Média                                        |

---

<a id="hu30"></a>
## HU30 – Refinar resposta gerada até atingir clareza e concisão

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID   | Nome                                               |
| ---- | -------------------------------------------------- |
| HU30 | Refinar resposta gerada até atingir clareza e concisão |
| **Descrição**              | Eu, como Usuário, desejo refinar uma resposta gerada usando **Like/Dislike/Regenerate/Copy** até atingir clareza e concisão, para obter um texto final satisfatório e pronto para uso. |
| **Critérios de aceitação** | - Exibe botões **Like**, **Dislike**, **Regenerate** e **Copy** para cada versão gerada;<br> - Ao clicar em **Dislike**, permite feedback e, após **Regenerate**, apresenta nova versão em até 1 s;<br> - Aceita múltiplas iterações de feedback e regeneração;<br> - Permite **Copy** na versão final avaliada com **Like**;<br> - Se a regeneração exceder 3 s, exibe opção **Cancelar**. |
| **Rastreabilidade**        | #RF11, #RF12, #RF13, #RF17             |
| **Prioridade**             | Baixa                                           |

---

## Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. [`Foto da referência`](../images/historias-de-usuario/definicao-historias-de-usuario.png)

> <a id="REF2" href="#anchor_2">2.</a> MELO, Arthur. Histórias de Usuário. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/>. Acesso em: 23 maio 2025.

## Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/05/2025 |  1.0   | (#HUO1) Criação do documento de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 23/05/2025 |  1.1   | (#HUO1) Criação da introdução e do template de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 23/05/2025 |  1.2   | (#B01) Adição da referência da definição de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 28/05/2025 |  1.3   | (#H02) Adição de conteúdo (Histórias de usuário 25 a 30)| [`@Gabriela`](https://github.com/gaubiela)   |  -- |
| 28/05/2025 |  1.4   | (#H02) Insere tabela de contribuições e linkagem de conteúdo| [`@Gabriela`](https://github.com/gaubiela)   |  -- |
