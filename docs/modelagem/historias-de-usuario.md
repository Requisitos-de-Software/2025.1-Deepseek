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
| Luiz     | Criação das histórias de usuário HU13, HU14, HU15, HU16, HU17 e HU18 | [HU13](#hu13) · [HU14](#hu14) · [HU15](#hu15) · [HU16](#hu16) · [HU17](#hu17) · [HU18](#hu18) |
| Fábio   | Criação das histórias de usuário HU19, HU20, HU21, HU22, HU23 e HU24 | [HU19](#hu19) · [HU20](#hu20) · [HU21](#hu21) · [HU22](#hu22) · [HU23](#hu23) · [HU24](#hu24) |
| Gabriela     | Criação das histórias de usuário HU25, HU26, HU27, HU28, HU29 e HU30 | [HU25](#hu25) · [HU26](#hu26) · [HU27](#hu27) · [HU28](#hu28) · [HU29](#hu29) · [HU30](#hu30) |
| Mateus     | Criação das histórias de usuário HU31, HU32, HU33, HU34, HU35 e HU36 | [HU31](#hu31) · [HU32](#hu32) · [HU33](#hu33) · [HU34](#hu34) · [HU35](#hu35) · [HU36](#hu36) |

## Histórias de Usuário

<a id="hu13"></a>
## HU13 – Resolver um problema difícil de matemática

**Autor:** [Luiz](https://github.com/luizfaria1989)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU13                       | Resolver um problema difícil de matemática                                                                                                                                                                                                                                                                                                              |
| **Descrição**              | Eu, como Usuário, desejo utilizar funcionalidade pensamento profundo para poder ter acesso a linha de pensamento de como um determinado problema de matemática pode ser resolvido.                                      |
| **Critérios de aceitação** | - Ao fazer a pergunta no chat e ativar a opção **Pensamento Profundo (R1)** é retornado a resolução do problema de matemática que foi discutido na pergunta com o DeepSeek; <br> - Também é retornado a linha de pensamento que o modelo do DeepSeek utilizou para responder aquela pergunta.  |
| **Rastreabilidade**        | #RF02                             |
| **Prioridade**             | Alta                |

<a id="hu14"></a>
## HU14 – Visualizar em tempo real o status do servidor

**Autor:** [Luiz](https://github.com/luizfaria1989)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU14                       | Visualizar em tempo real o status do servidor                                                                                                                                                                                                                                                                                                                                 |
| **Descrição**              | Eu, como Usuário, desejo visualizar em tempo real o status do servidor do DeepSeek para decidir se envio a minha pergunta para o DeepSeek agora, ou espero ele estar disponível novamente.                                                        |
| **Critérios de aceitação** | - Ao criar um novo chat, no topo, será possível ver uma mensagem indicando se o servidor está **disponível/em manutenção/sobrecarregado/indisponível**; <br> - O status do servidor também pode ser atualizado ao clicar na seta ao lado da visualização do status caso o usuário não decida criar um novo chat.|
| **Rastreabilidade**        | #RF29                             |
| **Prioridade**             | Não fazer                | 

<a id="hu15"></a>
## HU15 – Interromper chat em andamento

**Autor:** [Luiz](https://github.com/luizfaria1989)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU15                      | Interromper chat em andamento                                                                                                                                                                                                                                                                                                                              |
| **Descrição**              | Eu, como Usuário, desejo interromper uma resposta que está sendo gerada pela IA para poder economizar meu tempo e poder enviar uma nova mensagem o mais cedo possível.                                                                                   |
| **Critérios de aceitação** | - Ao fazer uma pergunta, enquanto a resposta está sendo gerada, surge um botão, ao lado da caixa de texto, que tem a funcionalidade de interromper a resposta que está sendo gerada; <br>  - Ao clicar no botão, a resposta é interrompida e no fim dela aparece a mensagem **"Resposta interrompida pelo usuário"**.  |
| **Rastreabilidade**        | #RF19                             |
| **Prioridade**             | Baixa                |

<a id="hu16"></a>
## HU16 – Autenticar a conta para acessar funcionalidades avançadas

**Autor:** [Luiz](https://github.com/luizfaria1989)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU16                       | Autenticar a conta para acessar funcionalidades avançadas                                                                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como Usuário, desejo autenticar a minha conta do DeepSeek para poder acessar funcionalidades avançadas.                                               |
| **Critérios de aceitação** | - Ao clicar em configurações, na aba funcionalidades avançadas, é possível fazer uma autenticação para acessar funcionalidades avançadas através de um botão escrito **Autenticar conta**; <br> - Nesse botão, o usuário é redirecionado para uma página web do DeepSeek em que é pedido um código numérico de oito dígitos para ser respondido; <br> - Esse código pode ser enviado para o e-mail cadastrado na conta do usuário; <br> - Ao adicionar o código de autenticação a página retorna com uma mensagem dizendo que a conta daquele usuário está autenticada; <br> - Feito isso, quando acessar as configurações, na aba funcionalidades avançadas é possível utilizar uma série de funções avançadas. |
| **Rastreabilidade**        | #RF26                             |
| **Prioridade**             | Não fazer                |

<a id="hu17"></a>

## HU17 – Controlar quais dados são compartilhados com a IA

**Autor:** [Luiz](https://github.com/luizfaria1989)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU17                       | Controlar quais dados são compartilhados com a IA                                                                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como Usuário, desejo poder controlar quais dos meus dados serão compartilhados para poder garantir maior privacidade.                        |
| **Critérios de aceitação** | - Ao clicar em configurações, na aba **controle de dados**, é possível acessar vários toggles que indicam quais dados estão ou não estão sendo compartilhadas com a IA, como localização, histórico de pesquisa e chat. <br>  - Quando um toggle é clicado para ligar ele muda de cor, indicando que ele está ligado <br> - Um dado que não está sendo compartilhado possui o toggle com as cores em escala de cinza; <br> - Quando o usuário sair da aba controle de dados aparecerá uma mensagem com a pergunta "Deseja salvar as suas configurações de compartilhamento de dados?"; <br> - se o usuário clicar no botão **salvar configurações** ele sai da aba de controle de dados e as configurações que ele alterou já estarão funcionando normalmente no app; <br> - se o usuário clicar no botão **Não salvar**, suas configurações alteradas irão voltar para o estado anterior de quando ele entrou na aba de controle dados, ele também sái desse menu.|
| **Rastreabilidade**        | #RF25                             |
| **Prioridade**             | Média                |

<a id="hu18"></a>

## HU18 – Salvar chat entre plataformas

**Autor:** [Luiz](https://github.com/luizfaria1989)

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU18                       | Salvar chat entre plataformas                                                                                                                                                                                                                                                                                                       |
| **Descrição**              | Eu, como Usuário, desejo salvar os chats do app DeepSeek entre múltiplas plataformas para poder acessar o meu histórico de chats no meu notebook e no meu telefone.
| **Critérios de aceitação** | - Ao clicar em configurações, é possível ver um toggle com a opção **sincronizar conversas entre plataformas**, quando ativado ele fica colorido, caso esteja desligado ele estará em escala de cinza; <br> - Quando sair do menu configurações aparecerá o pop-up com o texto "Deseja salvar as suas configurações?"; <br> - Ao clicar em **Salvar configurações** ele sairá do menu e voltará para os chats, a partir desse momento seus chats já estarão sendo sincronizados entre plataformas; <br> - Ao clicar em **Não salvar** ele voltará para os chats e suas configurações alteradas não serão salvas; <br> - Considerando que a sincronização de conversas está ativada, ao enviar uma conversa em seu notebook para seu chat no DeepSeek, essa conversa irá aparecer em seu app do telefone em 1 minuto.|
| **Rastreabilidade**        | #RF05                             |
| **Prioridade**             | Média                |


<a id="hu19"></a>
## HU19 – Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO

**Autor:** [Fábio](https://github.com/fabinsz)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU19 | Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO              |
| **Descrição**              | Eu, como usuário do aplicativo DeepSeek, desejo alternar entre os modos claro e escuro manualmente ou automaticamente conforme o sistema operacional, para ter uma experiência visual mais confortável e personalizada. |
| **Critérios de aceitação** | - Deve ser possível selecionar manualmente entre o modo claro e o modo escuro nas configurações do aplicativo;<br> - O aplicativo deve oferecer uma opção para sincronizar automaticamente o tema com as configurações do sistema operacional;<br> - A mudança de tema deve ser aplicada imediatamente após a alteração;<br> - O tema selecionado (manual ou automático) deve ser mantido nas próximas execuções do aplicativo.|
| **Rastreabilidade**        |  #RF27                                                                                       |
| **Prioridade**             | Alta                                                                                       |

---

<a id="hu20"></a>
## HU20 – Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)

**Autor:** [Fábio](https://github.com/fabinsz)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU20 | Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)             |
| **Descrição**              | Eu, como usuário do aplicativo DeepSeek, desejo escolher entre diferentes modelos de IA para poder utilizar a versão mais adequada às minhas necessidades.|
| **Critérios de aceitação** | - Deve ser possível visualizar uma lista de modelos de IA disponíveis para seleção;<br> - O usuário deve conseguir selecionar manualmente o modelo desejado por meio da interface do aplicativo;<br> - O modelo selecionado deve ser aplicado às próximas interações com o sistema;<br> - O aplicativo deve informar claramente o nome e a descrição de cada modelo.|
| **Rastreabilidade**        |  #RF32                                                                                       |
| **Prioridade**             | Média                                                                                     |

---

<a id="hu21"></a>
## HU21 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico

**Autor:** [Fábio](https://github.com/fabinsz)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU21 | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico          |
| **Descrição**              | Eu, como usuário do aplicativo DeepSeek, desejo visualizar corretamente o título completo do chat ao passar o mouse sobre o nome na barra lateral de histórico, para identificar facilmente o conteúdo da conversa.|
| **Critérios de aceitação** | - Ao passar o mouse sobre o nome do chat na barra lateral, deve ser exibido um tooltip com o título completo da conversa;<br> - O tooltip deve aparecer de forma rápida e clara, sem atraso perceptível;<br> - O conteúdo exibido no tooltip deve estar legível e não deve ser cortado ou truncado;<br> - O comportamento deve ser consistente em diferentes navegadores e tamanhos de tela.|
| **Rastreabilidade**        |  #RF35                                                                                       |
| **Prioridade**             | Baixa                                                                                     |

---

<a id="hu22"></a>
## HU22 – Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico

**Autor:** [Fábio](https://github.com/fabinsz)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU22 | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico          |
| **Descrição**              | Eu, como usuário do aplicativo DeepSeek, desejo receber instruções claras e contextualizadas sobre o uso de OCR ao enviar uma imagem, para entender como a funcionalidade funciona e o que esperar do resultado.|
| **Critérios de aceitação** | - A interface de envio de imagens deve exibir instruções sobre o que é OCR e como ele será aplicado à imagem;<br> - As instruções devem ser exibidas de forma clara, concisa e visualmente acessível;<br> - As orientações devem aparecer antes ou durante o envio da imagem, de forma contextualizada;<br> - As instruções devem incluir exemplos de imagens ideais para OCR e limitações conhecidas do recurso.|
| **Rastreabilidade**        |  #RF36                                                                                       |
| **Prioridade**             | Média                                                                                   |

---

<a id="hu23"></a>
## HU23 – As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis.

**Autor:** [Fábio](https://github.com/fabinsz)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU23 | As respostas devem suportar formatações como textos de tamanhos diferentes, linhas, textos em negrito e emojis.         |
| **Descrição**              | Eu, como usuário do aplicativo DeepSeek, desejo que as respostas suportem diferentes formatações de texto, como tamanhos variados, linhas, negrito e emojis, para melhorar a clareza, expressividade e compreensão das mensagens.|
| **Critérios de aceitação** | - As respostas devem permitir o uso de diferentes tamanhos de texto para destacar conteúdos importantes;<br> - Deve ser possível aplicar negrito, itálico e sublinhado nas respostas, conforme necessário;<br> - A formatação deve incluir o uso de emojis para tornar a comunicação mais expressiva;<br> - Deve haver suporte a separação por linhas ou blocos para organizar melhor as informações.|
| **Rastreabilidade**        |  #RF18 - #ROF12                                                                                       |
| **Prioridade**             | Baixa                                                                                 |

---

<a id="hu24"></a>
## HU24 – Retenção de contexto em diálogos longos

**Autor:** [Fábio](https://github.com/fabinsz)

| ID   | Nome                                                                                       |
| ---- | ------------------------------------------------------------------------------------------ |
| HU24 | Retenção de contexto em diálogos longos.         |
| **Descrição**              | Eu, como usuário do aplicativo DeepSeek, desejo que o sistema mantenha o contexto de conversas longas para que as respostas sejam mais coerentes e relevantes ao longo do diálogo.|
| **Critérios de aceitação** | - O sistema deve manter o histórico de mensagens anteriores durante um mesmo diálogo;<br> - As respostas devem considerar referências feitas anteriormente pelo usuário no mesmo diálogo;<br> - O limite de contexto deve permitir interações extensas sem perda de informações importantes;<br> - O sistema deve informar ao usuário quando o contexto anterior não puder mais ser mantido por limitações técnicas.|
| **Rastreabilidade**        |  #RF30                                                                                     |
| **Prioridade**             | Média                                                                               |

---

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

| ID                         | Nome                                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HU08                       | Refinar resposta gerada até atingir clareza e concisão                                                                                                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como Usuário, desejo refinar uma resposta gerada usando **Like/Dislike/Regenerate/Copy** até atingir clareza e concisão, para obter um texto final satisfatório e pronto para uso.                                                                                                                                                                                                                         |
| **Critérios de aceitação** | - Exibe botões **Like**, **Dislike**, **Regenerate** e **Copy** para cada versão gerada;<br> - Ao clicar em **Dislike**, permite ao usuário inserir feedback e, após **Regenerate**, apresenta nova versão em até 1 s;<br> - Aceita múltiplas iterações de feedback e regeneração;<br> - Permite **Copy** na versão final avaliada com **Like**;<br> - Se a regeneração exceder 3 s, exibe opção **Cancelar**. |
| **Prioridade**             | Baixa                |   

---

<a id="hu31"></a>
## HU31 – Utilizar uma API Pública

**Autor:** [Mateus](https://github.com/MVConsorte)

| ID   | Nome                  |
| ---- | --------------------- |
| HU31 | Utilizar uma API Pública |
| **Descrição** | Eu, como usuário típico do DeepSeek, desejo que o sistema possua uma API Pública para que eu possa integrar suas funcionalidades a outras aplicações de meu interesse. |
| **Critérios de aceitação** | - O menu de configurações deve exibir uma seção "API Pública", contendo informações básicas sobre como obter as credenciais de acesso;<br> - Ao acessar a documentação da API, o usuário encontra instruções para autenticação, exemplos de requisição e resposta para pelo menos duas funcionalidades principais;<br> - Quando uma requisição válida é enviada para um endpoint público, o sistema deve responder com o dado esperado conforme a documentação. |
| **Rastreabilidade** | #RF20, #RIF08 |
| **Prioridade** | Alta |

---

<a id="hu32"></a>
## HU32 – Implementar memória de contexto persistente entre conversas

**Autor:** [Mateus](https://github.com/MVConsorte)

| ID   | Nome                                 |
| ---- | ------------------------------------ |
| HU32 | Implementar memória de contexto persistente entre conversas. |
| **Descrição** | Eu, como Usuário típico do DeepSeek, desejo que a IA lembre das mensagens anteriores durante a conversa para que eu não precise repetir informações ou que estas sejam descontextualizadas. |
| **Critérios de aceitação** | - Durante a mesma conversa, o usuário envia uma sequência de mensagens relacionadas e a IA referencia corretamente informações das mensagens anteriores;<br> - Se o usuário perguntar "Do que estávamos falando?", a IA recupera o tema central das últimas interações deste chat. |
| **Rastreabilidade** | #RF31, #RQF11 |
| **Prioridade** | Média |

---

<a id="hu33"></a>
## HU33 – Disponibilizar resumo textual do conteúdo de vídeo importado de links do YouTube

**Autor:** [Mateus](https://github.com/MVConsorte)

| ID   | Nome                             |
| ---- | -------------------------------- |
| HU33 | Disponibilizar resumo textual do conteúdo de vídeo importado de links do YouTube. |
| **Descrição** | Eu, como Usuário típico do DeepSeek, desejo que o sistema consiga gerar um resumo textual de vídeos importados do Youtube para entender rapidamente seu conteúdo e aspectos importantes. |
| **Critérios de aceitação** | - Ao enviar um link de vídeo do YouTube e solicitar um resumo, o sistema apresenta um campo "Resumo" com os principais pontos destacados;<br> - O botão "Gerar Resumo" deve aparecer ao lado do campo de envio quando o usuário insere links do YouTube;<br> - Apresenta-se o resumo gerado contendo entre 150 e 500 palavras|
| **Rastreabilidade** | #RF38, #RQF23 |
| **Prioridade** | Alta |

---

<a id="hu34"></a>
## HU34 – Adicionar editor de texto avançado com suporte a Markdown e formatação de código

**Autor:** [Mateus](https://github.com/MVConsorte)

| ID   | Nome                            |
| ---- | ------------------------------- |
| HU34 | Adicionar editor de texto avançado com suporte a Markdown e formatação de código. |
| **Descrição** | Eu, como Usuário típico do DeepSeek, desejo um editor de texto com suporte a Markdown e formatação de código para estruturar e refinar as informações obtidas em tais modelos. |
| **Critérios de aceitação** | O editor de texto permite que o usuário reformate respostas, ajustando a estrutura do conteúdo por meio de Markdown, incluindo listas, títulos, negrito, e outros estilos visuais;<br> - Ao adicionar uma lista dentro do editor, esta é automaticamente exibida com marcadores (pontos ou números) apropriados para manter a organização do texto.<br> - Títulos e subtítulos aparecem com destaque visual, podendo ser formatados em negrito ou com variação de tamanho, facilitando a diferenciação entre seções da resposta;<br> - Trechos de código podem ser inseridos no editor e são automaticamente formatados em blocos destacados, com realce de sintaxe para linguagens suportadas; <br> - O editor deve oferecer suporte a citações e texto destacado, exibindo-os de maneira visualmente diferenciada para garantir clareza na leitura;<br> - O usuário consegue identificar visualmente pelo menos três tipos de formatação distintos em uma mesma resposta: listas, destaque e citação;<br> - O sistema deve garantir que qualquer resposta reformatada pelo usuário seja preservada sem perda de informação ao aplicada. |
| **Rastreabilidade** | #RQF15, #RF18 |
| **Prioridade** | Baixa |

---

<a id="hu35"></a>
## HU35 – Recuperar chats anteriores

**Autor:** [Mateus](https://github.com/MVConsorte)

| ID   | Nome                       |
| ---- | -------------------------- |
| HU35 | Recuperar Chats Anteriores |
| **Descrição** | Eu, como Usuário típico do DeepSeek, desejo poder acessar conversas antigas para consultar informações já discutidas ou continuar um atendimento a partir de onde parei. |
| **Critérios de aceitação** | - Um botão no canto superior esquerdo que abre um histórico de "chats" está visível na tela inicial, exibindo a lista de chats anteriores com identificação por data e contendo a data relativa da conversa;<br> - Ao selecionar um chat do histórico, todo o conteúdo da conversa é carregado no chat atual, permitindo ao usuário visualizar e continuar a conversa normalmente.|
| **Rastreabilidade** | #RF10, #ROF04 |
| **Prioridade** | Média |

---

<a id="hu36"></a>
## HU36 – Exibir citações de fontes

**Autor:** [Mateus](https://github.com/MVConsorte)

| ID   | Nome                      |
| ---- | ------------------------- |
| HU36 | Exibir Citações de Fontes |
| **Descrição** | Eu, como Usuário, desejo que o sistema apresente citações das fontes utilizadas nas respostas, para que eu possa conferir a veracidade das informações e aprofundar meus estudos. |
| **Critérios de aceitação** | - Sempre que for exibida uma informação baseada em fonte externa, a resposta contém um campo "Fonte" ou "Referência" ao final da mensagem, com URL clicável;<br> - Ao clicar no link da fonte, o usuário é redirecionado para a página original da referência;<br> - Quando houver múltiplas referências, o sistema apresenta cada uma em uma linha separada ou com numeração sequencial. |
| **Rastreabilidade** | #ROF08, #RF14 |
| **Prioridade** | Baixa |



## Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, p. 73. [`Foto da referência`](../images/historias-de-usuario/definicao-historias-de-usuario.png)

> <a id="REF2" href="#anchor_2">2.</a> MELO, Arthur. Histórias de Usuário. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/>. Acesso em: 23 maio 2025.

## Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/05/2025 |  1.0   | (#HUO1) Criação do documento de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
| 23/05/2025 |  1.1   | (#HUO1) Criação da introdução e do template de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   | [@Mateus](https://github.com/MVConsorte)  |
<<<<<<< HEAD
| 23/05/2025 |  1.2   | (#HU01) Adição da referência da definição de histórias de usuário.| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 28/05/2025 |  1.3   | (#H02) Adição de conteúdo (Histórias de usuário 25 a 30)| [`@Gabriela`](https://github.com/gaubiela)   |  [@Luiz](https://github.com/luizfaria1989) |
| 28/05/2025 |  1.4   | (#H02) Insere tabela de contribuições e linkagem de conteúdo| [`@Gabriela`](https://github.com/gaubiela)   |  [@Luiz](https://github.com/luizfaria1989) |
| 30/05/2025 |  1.5   | (#H02) Adição de conteudo historias de usuario (19 a 24)| [`@Fábio](https://github.com/fabinsz)   |  [@Luiz](https://github.com/luizfaria1989) |
| 31/05/2025 |  1.6   | (#H02) Adição de conteúdo (Histórias de usuário 13 a 18)| [`@Luiz`](https://github.com/luizfaria1989)   |  [@Mateus](https://github.com/MVConsorte) |
| 31/05/2025 |  1.7   | (#HU02) Adição de conteúdo (Histórias de usuário 31 a 36)| [`@Mateus`](https://github.com/MVConsorte)   |  [`@`](https://github.com/) |
