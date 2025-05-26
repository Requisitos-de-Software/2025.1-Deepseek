## Introdução

As histórias de usuário descrevem o resultado, as características e a funcionalidade requisitados para o software a ser construído. Cada história, é colocada em uma ficha. Nessa ficha, o cliente atribui um valor à história baseando-se no valor de negócio global do recurso ou função. Os membros da equipe então, avaliam então cada história e atribuem a ela um custo, o qual é medido em semanas de desenvolvimento. Se a história possuir um número alto de custo, por exemplo, mais do que três semanas de desenvolvimento, é solicitado ao cliente para dividir a história em histórias menores e a atribuição de valor e custo ocorre novamente. É importante notar que podem ser escritas novas histórias a qualquer momento <a id="anchor_1" href="#REF1">[1]</a>.

## Metodologia

Tabela 2: Modelo de tabela para histórias de usuário.

| ID                        | Nome                              |
| ------------------------- | --------------------------------- |
| USXX                      | Título                            |
| Descrição                 | Eu, como XXX, desejo XXX para XXX |
| Critérios de aceitação    | - xxx  - xxx                      |
| Prioridade                | Alta, média ou baixa              |

Fonte: Repositório Bilheteria Digital, disciplina de requisitos de software <a id="anchor_2" href="#REF2">[2]</a>.

## Histórias de Usuário

## HU06 – Enviar PDF e receber texto extraído e insights preservando formatação e símbolos

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU06                       | Enviar PDF e receber texto extraído e insights preservando formatação e símbolos                                                                                                                                                                                                                                                                               |
| **Descrição**              | Eu, como Usuário, desejo enviar um PDF e receber o texto extraído e insights, preservando formatação e símbolos, para poder revisá-los e editá-los diretamente sem perder convenções de estilo.                                                                                                                                                                |
| **Critérios de aceitação** | - O sistema aceita arquivos PDF válidos;<br> - Extrai e apresenta todo o texto mantendo formatação (negrito, itálico, listas) e símbolos especiais (diacríticos, equações);<br> - Destaca possíveis inconsistências de extração (caracteres faltantes ou ilegíveis);<br> - Em caso de perda de conexão, notifica “Conexão perdida” e permite retomar o upload. |
| **Prioridade**             | Alta                                                                                                                                                                                                                                                                                                                                                           |

---

## HU07 – Buscar versão mais recente do Node.js em data específica e copiar resultado

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU07                       | Buscar versão mais recente do Node.js em data específica e copiar resultado                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como Usuário, desejo buscar a versão mais recente do Node.js em 10/05/2025 e copiar o resultado, para documentar de forma ágil a dependência no repositório.                                                                                                                                                                                    |
| **Critérios de aceitação** | - Ao buscar “versão mais recente do Node.js em 10/05/2025”, o sistema retorna “Node.js v20.7.0 – lançado em 08/05/2025”;<br> - O resultado inclui data de lançamento e um botão **Copy** ativo;<br> - A busca é concluída em menos de 3 segundos, sob condições normais de rede;<br> - Permite refinar a consulta caso não haja informação de data. |
| **Prioridade**             | Média                                                                                                                                                                                                                                                                                                                                               |

---

## HU08 – Refinar resposta gerada até atingir clareza e concisão

**Autor:** [Gabriela](https://github.com/gaubiela)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU08                       | Refinar resposta gerada até atingir clareza e concisão                                                                                                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como Usuário, desejo refinar uma resposta gerada usando **Like/Dislike/Regenerate/Copy** até atingir clareza e concisão, para obter um texto final satisfatório e pronto para uso.                                                                                                                                                                                                                         |
| **Critérios de aceitação** | - Exibe botões **Like**, **Dislike**, **Regenerate** e **Copy** para cada versão gerada;<br> - Ao clicar em **Dislike**, permite ao usuário inserir feedback e, após **Regenerate**, apresenta nova versão em até 1 s;<br> - Aceita múltiplas iterações de feedback e regeneração;<br> - Permite **Copy** na versão final avaliada com **Like**;<br> - Se a regeneração exceder 3 s, exibe opção **Cancelar**. |
| **Prioridade**             | Baixa                |                                                                                                                                                                                                                                               

## Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. [`Foto da referência`](../images/historias-de-usuario/definicao-historias-de-usuario.png)

> <a id="REF2" href="#anchor_2">2.</a> MELO, Arthur. Histórias de Usuário. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/>. Acesso em: 23 maio 2025.

## Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/05/2025 |  1.0   | (#HUO1) Criação do documento de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 23/05/2025 |  1.1   | (#HUO1) Criação da introdução e do template de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 23/05/2025 |  1.2   | (#B01) Adição da referência da definição de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 23/05/2025 |  1.3   | (#H02) Adição de conteúdo (Histórias de usuário 06, 07, 08)| [`@Gabriela`](https://github.com/gaubiela)   |  -- |
