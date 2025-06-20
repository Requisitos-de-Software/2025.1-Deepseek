## Introdução
No contexto atual de crescente uso de ferramentas baseadas em inteligência artificial, como o DeepSeek, torna-se essencial compreender de forma aprofundada as interações entre usuários e sistemas computacionais. O sucesso na adoção e na efetividade dessas ferramentas depende diretamente de seu alinhamento com as necessidades, objetivos e contextos dos usuários finais. Para garantir esse alinhamento, a disciplina de Requisitos de Softaware propõe abordagens sistemáticas que permitem entender, representar e incorporar essas necessidades ao longo do processo de modelagem. Uma das estratégias fundamentais nesse processo é a utilização de cenários, que descrevem narrativas realistas de uso e permitem a análise e refinamento dos requisitos de forma contextualizada e centrada nos usuários. Este projeto tem como objetivo aplicar essa abordagem ao desenvolvimento da modelagem de requisitos de software para o DeepSeek, utilizando a técnica de cenários como instrumento central para a validação e modelagem de requisitos funcionais e não funcionais.

Em IHC, um cenário consiste em uma “história sobre pessoas realizando uma atividade” que descreve, de forma concreta e rica em detalhes contextuais, como usuários reais ou potenciais interagem com um sistema. Conforme definido:

> “Um cenário é basicamente uma história sobre pessoas realizando uma atividade (Rosson e Carroll, 2002). É uma narrativa, textual ou pictórica, concreta, rica em detalhes contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais.”<a id="anchor_1" href="#REF1">[1]</a>;

Os cenários servem a múltiplos propósitos no processo de design:

> “podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002). Além de poderosos, os cenários requerem menos custo e tempo quando comparados com modelos e protótipos complexos, o que os torna uma ferramenta importante em todo o processo de design de IHC.” <a id="anchor_2" href="#REF2">[2]</a>;

Segundo Rosson & Carroll (2002) e Cooper (1999), cada cenário deve explicitar os seguintes elementos característicos:

- **Ambiente ou contexto**: detalhes da situação que motivam ou explicam os objetivos, ações e reações dos atores <a id="anchor_3" href="#REF3">[3]</a>;
- **Atores**: pessoas interagindo com o computador ou outros elementos do ambiente; características pessoais relevantes <a id="anchor_3" href="#REF3">[3]</a>;
- **Objetivos**: efeitos na situação que motivam as ações realizadas pelos atores <a id="anchor_3" href="#REF3">[3]</a>;
- **Planejamento**: atividade mental dirigida para transformar um objetivo em um comportamento ou conjunto de ações <a id="anchor_3" href="#REF3">[3]</a>;
- **Ações**: comportamento observável <a id="anchor_3" href="#REF3">[3]</a>;
- **Eventos**: ações externas ou reações produzidas pelo computador ou outras características do ambiente; algumas delas podem ser ocultas ao ator mas importantes para o cenário <a id="anchor_3" href="#REF3">[3]</a>;
- **Avaliação**: atividade mental dirigida para interpretar a situação. <a id="anchor_3" href="#REF3">[3]</a>;

Essa estrutura garante que o cenário seja suficientemente detalhado para orientar a definição de requisitos, guiar decisões de design e validar a usabilidade de soluções propostas, mantendo sempre o foco nas necessidades e no contexto real dos usuários.

Assim, criamos a Tabela 1, para servir de template para a construção dos cenários desse documento.

<font><p style="text-align: center">**Tabela 01** - Tabela template para a construção dos cenários.</p></font>

| **Item** | **Descrição** |
| ---- | :-----------------------------------------------------------: |
| **Titulo** |   -     |
| **Código** | - |
| **Caso de uso trabalhado** | - |
| **Atores** | - |
| **Ambiente (Contexto)** | - |
| **Objetivos** | - |
| **Planejamento** | -  |
| **Ações** | - |
| **Eventos** | - |
| **Avaliação** | - |

<font><p style="text-align: center">**Autor** - Luiz.</p></font>

## Metodologia
A metodologia deste projeto baseia-se na abordagem de design baseado em cenários, conforme proposta por Rosson e Carroll (2002) e discutida por Barbosa et al. (2021). Inicialmente, foi elaborado o [perfil do usuário](https://requisitos-de-software.github.io/2025.1-Deepseek/elicitacao/perfil-de-usuario/) do DeepSeek, com base em dados coletados por meio de análise de interface e de documentação, observação e questionário. Esses perfis foram utilizados para compor cenários de uso que retratam situações reais ou plausíveis de interação com o sistema. Cada cenário foi construído com base nos seguintes elementos: contexto, atores, objetivos, ações, eventos e avaliação das ações. A partir desses cenários, foi possível modelar requisitos do sistema, compreendendo não apenas as funcionalidades desejadas, mas também as limitações e expectativas dos usuários. Essa abordagem qualitativa, centrada no ser humano, favorece um entendimento mais profundo da experiência do usuário e permite o direcionamento dos requisitos de forma iterativa e fundamentada.

## Tabela de Contribuições

<font><p style="text-align: center">**Tabela 02** - Contribuições no documento de cenários.</p></font>

| Contribuinte | Descrição                                                            | Links                                           |
|--------------|----------------------------------------------------------------------|-------------------------------------------------|
| Ana Joyce     | Criação dos cenários #CN01 | [#CN01](#cn01) |
| Davi     | Criação dos cenários #CN02, #CN03 | [#CN02](#cn02) · [#CN03](#cn03)|
| Fábio     | Criação dos cenários #CN04, #CN05 | [#CN04](#cn04) · [#CN05](#cn05)|
| Gabriela     | Criação dos cenários #CN06, #CN07, #CN08 | [#CN06](#cn06) · [#CN07](#cn07) · [#CN08](#cn08) |
| Luiz     | Criação dos cenários #CN09, #CN10, #CN11 | [#CN09](#cn09) · [#CN10](#cn10) · [#CN11](#cn11) |
| Ana Clara     | Criação dos cenários #CN12, #CN13 | [#CN12](#cn12) · [#CN13](#cn13) |
| Mateus     | Criação dos cenários #CN14 | [#CN14](#cn14)|

<a id="cn01"></a>

## Cenários Modelados:

## #CN01 - Confirmação de exclusão de todos os chats no DeepSeek
**Autor:** [Ana Joyce](https://github.com/anajoyceamorim)   

<font><p style="text-align: center">**Tabela 03** - Cenário 01 - Confirmação de exclusão de todos os chats no DeepSeek.</p></font>

| **Item** | **Descrição** |
| ---- | ------------------------------------------------------------- |
| **Titulo** | Confirmação de exclusão de todos os chats do DeepSeek       |
| **Código** | #CN01 |
| **Caso de uso trabalhado** | [#UC01](../modelagem/casos-de-uso.md#uc01) |
| **Atores** | Lívia, 22 anos, estudante de Design Digital, utiliza o DeepSeek diariamente para registrar ideias criativas, rascunhar campanhas visuais e fazer brainstorms com colegas de classe. Costuma testar diferentes abordagens com a IA e mantém diversos chats arquivados por tema e disciplina. Tem alta familiaridade com ferramentas digitais, mas é cuidadosa com perdas de conteúdo. |
| **Ambiente (Contexto)** | Lívia está em casa, usando seu tablet com teclado acoplado, organizando seus arquivos e chats do semestre antes de iniciar um novo projeto interdisciplinar. Deseja limpar o histórico de chats antigos, mas está preocupada em apagar algo importante acidentalmente. |
| **Objetivos** | <ul><li>Organizar o DeepSeek para iniciar um novo ciclo de projetos com uma área limpa.</li><li>Evitar a exclusão acidental de conteúdos importantes ao apagar múltiplos chats.</li><li>Garantir que o sistema ofereça uma confirmação clara e explícita antes de excluir tudo.</li></ul> |
| **Planejamento** | Lívia decide apagar todos os seus chats antigos para reorganizar sua área de trabalho no DeepSeek. Antes de realizar a ação, ela espera que o sistema solicite uma confirmação visual e textual para assegurar que entende o impacto dessa decisão.  |
| **Ações** | <ol><li>Acessa o DeepSeek e abre o painel lateral de histórico de chats.</li><li>Seleciona a opção "Excluir todos os chats" no menu de configurações.</li><li>Uma janela modal aparece com a mensagem: "Tem certeza de que deseja excluir todos os chats? Esta ação é irreversível."</li><li>O sistema exige que ela digite "CONFIRMAR" no campo de texto para prosseguir com a exclusão.</li><li>Após digitar corretamente, ela clica em "Excluir definitivamente".</li><li>O DeepSeek remove todos os chats e exibe uma notificação discreta: “Todos os chats foram excluídos com sucesso.”</li></ol> |
| **Eventos** | <ul><li>O sistema detecta a ação crítica e interrompe com uma janela de confirmação obrigatória.</li><li>A interface escurece, destacando a importância da decisão.</li><li>O campo de texto para confirmação é obrigatório e sensível à grafia correta ("CONFIRMAR" em caixa alta).</li><li>O botão de exclusão só é ativado após o preenchimento correto.</li><li>A exclusão é executada somente após dupla confirmação e feedback visual claro.</li></ul> |
| **Avaliação** | <ul><li>Lívia considera a funcionalidade bem projetada, já que impediu um possível erro ao exigir confirmação explícita.</li><li>Valoriza o cuidado da interface em reforçar a gravidade da ação com destaque visual e textual.</li><li>Sente-se mais segura em utilizar funções avançadas do DeepSeek por confiar na proteção contra perdas acidentais.</li><li>Recomenda a funcionalidade a colegas que também gostam de manter o ambiente de trabalho digital limpo e organizado.</li></ul> |

<a id="cn02"></a>

## #CN02 - Utilização do DeepSeek com plataformas externas integradas
**Autor:** [Davi Emanuel](https://github.com/daviRolvr)

<font><p style="text-align: center">**Tabela 04** - Cenário 02 - Utilização do DeepSeek com plataformas externas integradas.</p></font>

| **Item** | **Descrição** |
| :--- | :--- |
| **Titulo** | Utilização do DeepSeek com plataformas externas integradas |
| **Código** | #CN02 |
| **Caso de uso trabalhado** | [#UC02](../modelagem/casos-de-uso.md#uc02)|
| **Atores** | Gabriel, 24 anos, recém-formado em Engenharia da Computação, buscando oportunidades na área de Ciência de Dados. É usuário frequente de tecnologias baseadas em IA, com alto nível de familiaridade digital. Usa o DeepSeek diariamente para organizar ideias, revisar códigos, gerar conteúdos e montar portfólios. |
| **Ambiente (Contexto)** | Gabriel está em casa, utilizando seu notebook pessoal. Ele tem uma entrevista marcada com uma startup e deseja preparar uma apresentação rápida sobre um projeto pessoal de análise de dados que publicou no GitHub, ao mesmo tempo em que quer revisar suas experiências profissionais para destacar no LinkedIn, e organizar referências salvas no Google Drive. |
| **Objetivos** | <ul><li>Utilizar o DeepSeek para acessar informações de múltiplas plataformas sem alternar entre várias abas.</li><li>Revisar e sintetizar o conteúdo de um repositório do GitHub integrado.</li><li>Gerar um resumo das experiências e habilidades listadas no LinkedIn.</li><li>Reunir documentos salvos no Google Drive relacionados ao projeto.</li><li>Preparar um pitch organizado com base em todas essas fontes para compartilhar no Discord com colegas.</li></ul> |
| **Planejamento** | Gabriel conecta suas contas do GitHub, Google, LinkedIn e Discord ao DeepSeek. Ele acredita que, com essa integração, será possível cruzar dados automaticamente, gerar resumos mais ricos e se preparar melhor para entrevistas com base em todo o seu histórico digital. |
| **Ações** | <ol><li>Acessa o DeepSeek e autoriza a integração com suas contas do GitHub, LinkedIn, Google e Discord.</li><li>Solicita à IA que analise um repositório específico do GitHub e resuma os principais algoritmos implementados.</li><li>Pede ao DeepSeek que acesse seu perfil do LinkedIn e gere um resumo com foco nas experiências mais relevantes para a vaga.</li><li>Importa automaticamente do Google Drive um PDF com anotações e dados sobre o projeto para análise complementar.</li><li>Gera, com o apoio da IA, uma apresentação em formato texto para compartilhar em um canal privado no Discord.</li><li>Revisa tudo em uma interface centralizada, sem precisar mudar de aba ou copiar/colar manualmente.</li></ol> |
| **Eventos** | <ul><li>O DeepSeek exibe a mensagem “Conectando às suas plataformas: GitHub, Google Drive, LinkedIn, Discord…”.</li><li>A IA acessa os dados permitidos, respeitando as permissões de privacidade, e exibe um painel integrado.</li><li>Um resumo técnico do repositório é exibido, junto com uma síntese das experiências profissionais e links para documentos relevantes.</li><li>A plataforma sugere insights para destacar na apresentação, com base nas palavras-chave da vaga informada.</li><li>Gabriel exporta tudo em um único documento e compartilha via Discord com um clique.</li></ul> |
| **Avaliação** | <ul><li>Gabriel considera a integração extremamente eficiente, pois economizou tempo ao reunir dados dispersos automaticamente.</li><li>Fica satisfeito com a forma como o DeepSeek compreendeu e cruzou as informações entre plataformas.</li><li>Avalia que conseguiu se preparar de forma estratégica para a entrevista, com mais confiança.</li><li>Decide manter as integrações ativas para utilizar o DeepSeek como centro de produtividade no seu dia a dia profissional.</li></ul> |

<a id="cn03"></a>

## #CN03 - Pesquisa utilizando integração por voz no DeepSeek
**Autor:** [Davi Emanuel](https://github.com/daviRolvr)

<font><p style="text-align: center">**Tabela 05** - Cenário 03 - Pesquisa utilizando integração por voz no DeepSeek.</p></font>

| **Item** | **Descrição** |
| :--- | :--- |
| **Titulo** | Pesquisa utilizando integração por voz no DeepSeek |
| **Código** | #CN03 |
| **Caso de uso trabalhado** | [#UC03](../modelagem/casos-de-uso.md#uc03) |
| **Atores** | Camila, 27 anos, mestranda em Psicologia Cognitiva, com bom domínio de tecnologia e rotina intensa de leitura e produção acadêmica. Utiliza o DeepSeek como assistente de pesquisa para agilizar a análise de textos científicos e sínteses bibliográficas. |
| **Ambiente (Contexto)** | Camila está caminhando de um prédio para outro no campus da universidade, usando fones de ouvido com microfone e carregando o celular em uma das mãos. Como o tempo é curto entre uma atividade e outra, ela decide usar o DeepSeek via comando de voz para não precisar parar e digitar. |
| **Objetivos** | <ul><li>Consultar rapidamente o DeepSeek sem precisar usar as mãos ou digitar textos longos.</li><li>Obter uma explicação resumida sobre o conceito de “memória episódica” com exemplos.</li><li>Agilizar sua pesquisa enquanto se desloca, otimizando seu tempo.</li></ul> |
| **Planejamento** | Camila ativa o recurso de entrada por voz no aplicativo do DeepSeek, ciente de que a funcionalidade converte fala em texto, realiza a busca e responde por texto e/ou voz. Ela quer testar se consegue interagir naturalmente com o sistema mesmo em movimento. |
| **Ações** | <ol><li>Abre o aplicativo do DeepSeek no celular.</li><li>Ativa o modo “Pesquisa por Voz”.</li><li>Diz: “DeepSeek, me explica de forma resumida o que é memória episódica e me dá dois exemplos.”</li><li>Aguarda o reconhecimento da fala e a geração da resposta.</li><li>Ouve a resposta sintetizada por voz e também lê o conteúdo em texto na tela.</li><li>Salva a resposta nos favoritos para revisar depois.</li></ol> |
| **Eventos** | <ul><li>O DeepSeek exibe a mensagem: “Ouvindo...”, seguida de “Interpretando sua fala...”.</li><li>A fala é convertida em texto e exibida para confirmação.</li><li>A IA realiza a análise e responde tanto em texto quanto em voz sintetizada.</li><li>Sugestões adicionais aparecem na tela: “Quer saber mais sobre memória semântica?”, “Deseja salvar esta resposta?”</li></ul> |
| **Avaliação** | <ul><li>Camila considera que a experiência por voz foi fluida e natural, sem a necessidade de parar sua locomoção.</li><li>Destaca a praticidade do sistema reconhecer sua voz em ambiente externo com ruído moderado.</li><li>Avalia que o tempo de resposta foi satisfatório e a resposta adequada ao contexto acadêmico.</li><li>Decide usar a funcionalidade com frequência, principalmente em momentos em que não pode digitar.</li></ul> |

<a id="cn04"></a>

## #CN04 - Personalização da experiência via seleção de modelos de IA
**Autor:** [Fabio](https://github.com/fabinsz)

<font><p style="text-align: center">**Tabela 06** - Cenário 04 - Personalização da experiência via seleção de modelos de IA.</p></font>

| **Item** | **Descrição** |
| :--- | :--- |
| **Titulo** | Personalização da experiência via seleção de modelos de IA |
| **Código** | #CN04 |
| **Caso de uso trabalhado** | [#UC04](../modelagem/casos-de-uso.md#uc04) |
| **Atores** | Júlia, 21 anos, estudante de Engenharia de Software, utiliza o DeepSeek para estudar, revisar conteúdos técnicos e desenvolver projetos de pesquisa em aprendizado de máquina. Gosta de testar diferentes modelos de IA para comparar estilo de resposta, profundidade analítica e rapidez. |
| **Ambiente (Contexto)** | Júlia está no laboratório de informática da universidade, usando seu notebook com internet estável. Está preparando um experimento para comparar como diferentes modelos de IA respondem a problemas complexos de lógica e quer organizar isso como parte de seu TCC. |
| **Objetivos** | <ul><li>Alternar entre diferentes versões de IA (como R1, R2, etc.) para análise comparativa.</li><li>Avaliar a profundidade, clareza e estilo das respostas fornecidas por cada modelo.</li><li>Selecionar o modelo mais adequado para cada tipo de tarefa (resumos, resolução de problemas, revisão de código, etc.).</li><li>Documentar as respostas geradas por diferentes modelos para uso futuro.</li></ul> |
| **Planejamento** | Júlia decide utilizar o recurso de troca de modelo disponível no DeepSeek para realizar sua comparação. Ela pretende submeter a mesma pergunta a cada modelo e observar as diferenças nas respostas, registrando os resultados em um documento colaborativo com sua orientadora. |
| **Ações** | <ol><li>Acessa o DeepSeek e navega até o seletor de modelo no topo da interface.</li><li>Visualiza a lista com modelos disponíveis: R1, R2, e R3.</li><li>Seleciona o modelo R1 e envia uma pergunta de lógica avançada.</li><li>Analisa a resposta da IA e copia para seu documento de análise.</li><li>Repete o processo com os modelos R2 e R3.</li><li>Compara as três respostas lado a lado, observando critérios como coerência, profundidade e criatividade.</li><li>Escolhe o modelo mais eficaz para continuar utilizando em suas interações acadêmicas.</li></ol> |
| **Eventos** | <ul><li>DeepSeek exibe “Modelo atualizado com sucesso: R2”.</li><li>A IA responde com estilos diferentes a cada modelo, permitindo variações claras de análise.</li><li>Júlia percebe que o modelo R2 oferece mais explicações intermediárias, enquanto o R1 é mais direto e o R3 tende a ser mais técnico.</li><li>O sistema salva automaticamente o modelo selecionado para futuras sessões.</li></ul> |
| **Avaliação** | <ul><li>Júlia se sente no controle de sua experiência de uso com a IA.</li><li>Considera o recurso fundamental para tarefas acadêmicas que exigem diferentes abordagens cognitivas.</li><li>Relata que o modelo R2 se encaixa melhor em situações de estudo aprofundado, enquanto o R1 é mais útil para resumos rápidos.</li><li>Reforça a intenção de continuar utilizando o DeepSeek como ferramenta de apoio no seu TCC.</li></ul> |

<a id="cn05"></a>

## #CN05 - Acessar configurações para alterar o tema do Sistema
**Autor**:  [Fabio](https://github.com/fabinsz)

<font><p style="text-align: center">**Tabela 07** - Cenário 05 - Acessar configurações para alterar o tema do Sistema.</p></font>

| **Item** | **Descrição** |
| :--- | :--- |
| **Titulo** | Acessar configurações para alterar o tema do Sistema |
| **Código** | #CN05 |
| **Caso de uso trabalhado** | [#UC05](../modelagem/casos-de-uso.md#uc05) |
| **Atores** | Lucas, 29 anos, engenheiro de dados, mestre em Ciência da Computação. Usuário frequente do DeepSeek, utiliza a ferramenta diariamente para processar documentos técnicos, interagir com repositórios de código e extrair insights com ajuda da IA. É altamente proficiente em tecnologia e aprecia ambientes de trabalho visualmente confortáveis e personalizados. |
| **Ambiente (Contexto)** | Lucas está trabalhando em um coworking, em um ambiente com iluminação forte. Após algumas horas usando o DeepSeek no modo claro, começa a sentir desconforto visual. Decide, então, mudar o tema da interface para o modo escuro para aliviar a fadiga visual. |
| **Objetivos** | <ul><li>Alterar o tema do sistema para o modo escuro.</li><li>Verificar se a alteração é aplicada de forma consistente em todas as seções do sistema.</li></ul> |
| **Planejamento** | Por ser um usuário experiente, Lucas assume que a opção de personalização visual está nas configurações gerais. Ele espera conseguir mudar o tema com poucos cliques e sem precisar reiniciar a aplicação ou abrir tutoriais. |
| **Ações** | <ol><li>Clica no ícone de perfil.</li><li>Seleciona "Configurações" no menu suspenso.</li><li>Encontra a opção “Tema/Aparência”.</li><li>Altera de “Claro” para “Escuro (Dark Mode)”.</li><li>Observa a transição da interface e valida se todos os elementos visuais se adaptaram corretamente.</li><li>Fecha o menu de configurações e retoma suas atividades no novo tema.</li></ol> |
| **Eventos** | <ul><li>O modo escuro se aplica em toda a interface, incluindo ao editor de textos e à área de visualização de documentos.</li></ul> |
| **Avaliação** | <ul><li>Lucas se sente mais confortável visualmente e satisfeito com a personalização oferecida.</li><li>Considera a experiência rápida e intuitiva, algo essencial para não interromper seu fluxo de trabalho.</li></ul> |


<a id="cn06"></a>

## #CN06 - Upload de Documento
**Autor**:  [Gabriela](https://github.com/gaubiela) 

<font><p style="text-align: center">**Tabela 08** - Cenário 06 - Upload de Documento.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Upload de Documento |
| **Código** | #CN06 |
| **Caso de uso trabalhado** | [#UC06](../modelagem/casos-de-uso.md#uc06) |
| **Atores** | Júlia, 27 anos, pesquisadora em Ciência da Computação, formação superior, alta proficiência tecnológica, usa o DeepSeek diariamente para processamento avançado de documentos. |
| **Ambiente (Contexto)** | Em seu home office, com conexão estável de fibra óptica e deadline apertado para submeter um artigo, Júlia recebe um PDF que precisa converter em texto editável e interpretar conteúdo de forma rápida. |
| **Objetivos** | <ul><li>Extrair todo o texto.</li><li>Garantir que conteúdo e insights sejam consistentes e preservados.</li></ul> |
| **Planejamento** | Júlia decide usar o fluxo de upload do DeepSeek em vez de ferramentas manuais, pois estima maior agilidade e menor chance de erro. |
| **Ações** | <ol><li>Abre o DeepSeek e seleciona “Upload de Documento”.</li><li>Escolhe o arquivo PDF do artigo.</li><li>Observa barra de progresso até 100 %.</li><li>Revisita arquivo para verificar consistência do conteúdo e informações fornecidas através do deepseek.</li></ol> |
| **Eventos** | <ul><li>Após o upload, um spinner que representa o carregamento é apresentado, bem como mensagens que dizem em que etapa do processamento o deepseek está.</li></ul> |
| **Avaliação** | <ul><li>Júlia percorre o texto extraído, conferindo símbolos e formatação; para cada inconsistência.</li><li>Compara mentalmente o conteúdo gerado com o PDF original, e valida se todos os insights obtidos durante a conversa foram consistentes.</li></ul> |

<a id="cn07"></a>

## #CN07 - Consulta Atualizada via Search na Web
**Autor**:  [Gabriela](https://github.com/gaubiela) 

<font><p style="text-align: center">**Tabela 09** - Cenário 07 - Consulta Atualizada via Search na Web.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Consulta Atualizada via Search na Web |
| **Código** | #CN07 |
| **Caso de uso trabalhado** | [#UC07](../modelagem/casos-de-uso.md#uc07) |
| **Atores** | Pedro, 31 anos, engenheiro de software em startup, formação em TI, utiliza DeepSeek várias vezes ao dia para se manter atualizado sobre tecnologias emergentes. |
| **Ambiente (Contexto)** | Em seu escritório, precisa saber imediatamente qual é a versão mais recente do Node.js em 10 de maio de 2025 para configurar o ambiente de build do time. |
| **Objetivos** | <ul><li>Obter a versão mais recente do Node.js no dia atual disponibilizada no site oficial.</li><li>Copiar a informação para documentá-la no repositório interno de conhecimento.</li></ul> |
| **Planejamento** | Pedro pretende usar a aba “Search” do DeepSeek para fazer uma busca na web, evitando acessar múltiplas abas no navegador. Caso o resultado inicial não cite a data exata, ele vai refinar a pesquisa em busca da versão mais atual no dia atual. |
| **Ações** | <ol><li>Ativar a opção **Search** no DeepSeek.</li><li>Digita “Qual é a versão mais recente do Node.js em 10 de maio de 2025?” e pressiona Enter.</li><li>Aguarda < 2 s pelo resultado, que inclui número da versão e data de lançamento.</li><li>Clica em “Copy” ao lado do trecho “Node.js v20.7.0 – lançado em 08/05/2025”.</li><li>Cola a informação no README do repositório.</li></ol> |
| **Eventos** | <ul><li>Se a resposta demorar > 3 s, surge aviso de erro com opção de recarregamento.</li><li>Cada clique em “Copy” exibe brevemente a mensagem “Copiado!” no centro superior da aba.</li></ul> |
| **Avaliação** | <ul><li>Pedro verifica se o número da versão e a data estão corretos comparando com o site nodejs.org.</li><li>Confirma que o tempo total de busca foi inferior a 3 s, atendendo ao seu critério de agilidade.</li><li>Se algum dado estiver divergente, refina a pesquisa para “Node.js versão estável maio 2025” e repete o fluxo.</li></ul> |

<a id="cn08"></a>

## #CN08 - Iteração de Resposta com Opções Disponíveis Para Resposta (like, dislike, regenerate, copy)
**Autor**:  [Gabriela](https://github.com/gaubiela) 

<font><p style="text-align: center">**Tabela 10** - Cenário 08 - Iteração de Resposta com Opções Disponíveis Para Resposta (like, dislike, regenerate, copy).</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Iteração de Resposta com Opções Disponíveis Para Resposta (like, dislike, regenerate, copy) |
| **Código** | #CN08 |
| **Caso de uso trabalhado** | [#UC08](../modelagem/casos-de-uso.md#uc08) |
| **Atores** | Mariana, 25 anos, aluna de pós em Bioinformática, alta proficiência, usa o app no celular enquanto toma café entre aulas para refinar textos. |
| **Ambiente (Contexto)** | Num café da universidade, conexão móvel instável, ela quer melhorar o parágrafo sobre “Identificação de variantes genéticas associadas a doenças complexas” feito por ela. |
| **Objetivos** | <ul><li>Obter um parágrafo claro e conciso sobre o conteúdo.</li><li>Copiar o texto final para seu documento de anotações.</li></ul> |
| **Planejamento** | Decide iterar usando “Dislike + Regenerate” até que o resultado atenda ao estilo desejado, marcando “Like” na versão final. |
| **Ações** | <ol><li>Lê o primeiro parágrafo gerado.</li><li>Se insatisfeita, clica em “Dislike” e fornece feedback sobre o descontentamento.</li><li>Toca em “Regenerate” e aguarda nova versão (~ 1 s).</li><li>Repete “Dislike + Regenerate” uma vez mais se necessário.</li><li>Na versão satisfatória, clica em “Like” e depois em “Copy”.</li></ol> |
| **Eventos** | <ul><li>Caso a regeneração demore > 3 s, surge botão “Cancelar” para reiniciar o processo.</li><li>Feedback “Like/Dislike” envia dados sobre o conteúdo fornecido para o DeepSeek.</li></ul> |
| **Avaliação** | Mariana compara mentalmente cada iteração com seu padrão de clareza; quando atingir fluxo e precisão, encerra as regenerações. |


<a id="cn09"></a>

## #CN09 - Utilização da Ferramenta Pensamento Profundo para Resolver um Problema Difícil de Matemática
**Autor:** [Luiz](https://github.com/luizfaria1989)

<font><p style="text-align: center">**Tabela 11** - Cenário 09 - Utilização da Ferramenta Pensamento Profundo para Resolver um Problema Difícil de Matemática.</p></font>


| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Utilização da Ferramenta Pensamento Profundo para Resolver um Problema Difícil de Matemática |
| **Código** | #CN09 |
| **Caso de uso trabalhado** | [#UC09](../modelagem/casos-de-uso.md#uc09) |
| **Atores** | Gauss, estudante universitário de engenharia, no primeiro semestre. |
| **Ambiente (Contexto)** | Gauss está no quarto de sua casa fazendo exercícios de uma lista para a sua prova de cálculo 1 da próxima semana. Ao tentar resolver um dos exercícios, ele fica com dúvidas sobre como resolver um cálculo complexo de uma integral. |
| **Objetivos** | <ul><li>Encontrar a explicação de como se resolve um exercício difícil de matemática.</li><li>Anotar a resolução do exercício em seu caderno junto com outras resoluções da lista.</li></ul> |
| **Planejamento** | Decide utilizar o DeepSeek com a função de **Pensamento Profundo** para tentar encontrar a solução do exercício que está com dúvidas. |
| **Ações** | <ol><li>Digita a equação do problema no chat e pede a resolução.</li><li>Ativa a opção "Pensamento Profundo (R1)" acima do teclado.</li><li>Lê a resolução do exercício difícil.</li></ol> |
| **Eventos** | <ul><li>Aparece uma mensagem de carregamento escrita "Pensando...".</li><li>No chat aparecem o raciocínio da IA linha por linha.</li><li>Aparece a opção de ocultar os "pensamentos" da IA para exibir apenas a resposta final.</li></ul> |
| **Avaliação** | Gauss compara a resolução do exercício com as suas de seu caderno para garantir que o modelo do DeepSeek utilizou os mesmos conceitos aprendidos em cálculo 1. |

<a id="cn10"></a>

## #CN10 - Opção de Interromper Resposta em Andamento
**Autor:** [Luiz](https://github.com/luizfaria1989)

<font><p style="text-align: center">**Tabela 12** - Cenário 10 - Opção de Interromper Resposta em Andamento.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Opção de Interromper Resposta em Andamento |
| **Código** | #CN10 |
| **Caso de uso trabalhado** | [#UC10](../modelagem/casos-de-uso.md#uc10) |
| **Atores** | João, desenvolvedor front-end com grande familiaridade com o uso do chat de IAs para retirar dúvidas de código. |
| **Ambiente (Contexto)** | João está no escritório de sua casa, trabalhando no desenvolvimento de um site de vendas. Durante o desenvolvimento, ele percebe que está com dúvidas sobre como utilizar o framework React para componentizar os itens do site para que possam ser reaproveitados no projeto. |
| **Objetivos** | <ul><li>Entender as principais funcionalidades do framework React.</li><li>Utilizar a função "Interromper mensagem em andamento" para evitar perda de tempo com respostas incorretas.</li></ul> |
| **Planejamento** | João decide utilizar o app DeepSeek para pedir explicações de como pode utilizar o React em seu projeto de front-end. |
| **Ações** | <ol><li>Pergunta para o DeepSeek quais são as principais funcionalidades do React.</li><li>Começa a ler a resposta da IA sobre o framework.</li><li>João percebe que a resposta que está sendo escrita pela IA está incorreta.</li><li>João clica em "Interromper mensagem em andamento".</li></ol> |
| **Eventos** | <ul><li>O início da mensagem aparece no chat de João com o DeepSeek.</li><li>A mensagem é interrompida.</li><li>Aparece o texto "Mensagem interrompida pelo usuário" logo abaixo da mensagem interrompida.</li></ul> |
| **Avaliação** | João percebe que a mensagem interrompida estava explicando sobre outra tecnologia, assim, o seu cancelamento foi útil, pois poupou tempo que gastaria lendo um texto que não se aplicava para seu projeto. |

<a id="cn11"></a>

## #CN11 - Visualização em Tempo Real do Status do Servidor
**Autor:** [Luiz](https://github.com/luizfaria1989)

<font><p style="text-align: center">**Tabela 13** - Cenário 11 - Visualização em Tempo Real do Status do Servidor.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Visualização em Tempo Real do Status do Servidor |
| **Código** | #CN11 |
| **Caso de uso trabalhado** | [#UC11](../modelagem/casos-de-uso.md#uc11) |
| **Atores** | Clarice, estudante de engenharia da computação do sétimo semestre, está estagiando em uma empresa trabalhando no setor de banco de dados. |
| **Ambiente (Contexto)** | Clarice está no escritório de sua empresa em frente o computador, está cercada de notas de aula sobre normalização de bancos de dados. Ela percebe ao analisar o modelo relacional, que uma das tabelas parece estar ferindo a terceira forma normal. Então decide tirar dúvidas com o DeepSeek para se assegurar que a tabela está realmente incorreta. |
| **Objetivos** | <ul><li>Retirar dúvidas sobre normalização de banco de dados relacionais</li><li>Utilizar a função de visualização em tempo real do status do servidor para garantir que a IA está disponível para conversa.</li></ul> |
| **Planejamento** | Clarice olha mais uma vez as suas notas de aula, procura a definição de terceira forma normal. Decide criar um chat com o DeepSeek para tirar dúvidas se as suas anotações estão certas e explicar a situação que encontrou no banco de dados de sua empresa. |
| **Ações** | <ol><li>Abre o app DeepSeek em um novo chat.</li><li>Lê uma mensagem no topo do chat dizendo "Servidor em manutenção. Chat Indisponível no momento".</li><li>Fecha o app.</li></ol> |
| **Eventos** | <ul><li>Um novo chat é criado ao abrir o app.</li><li>A mensagem de servidor em manutenção aparece no chat de Clarice.</li></ul> |
| **Avaliação** | Clarice lê a mensagem dizendo que o servidor está em manutenção, fecha o aplicativo e decide procurar respostas em outra IA. |


<a id="cn12"></a>

## #CN12 - Utilização do tutorial prático
**Autor:** [Ana Clara](https://github.com/anabborges)

<font><p style="text-align: center">**Tabela 14** - Cenário 12 - Utilização do tutorial práticos.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Utilização do tutorial prático |
| **Código** | #CN12 |
| **Caso de uso trabalhado** | [#UC12](../modelagem/casos-de-uso.md#uc12) |
| **Atores** | Joana, 22 anos, estagiária de design de produto em uma startup de tecnologia voltada para educação. Está fazendo curso superior em Design e possui proficiência intermediária em ferramentas digitais. Está começando a utilizar o DeepSeek para criar fluxos para um projeto de chat de IA da empresa e busca entender a lógica e os recursos da plataforma antes de começar o seu projeto. |
| **Ambiente (Contexto)** | Sentada no escritório, com conexão Wi-Fi estável e pouco tempo disponível, Joana acessa o DeepSeek pela primeira vez e é direcionada ao painel principal. Quer entender rapidamente como a plataforma funciona para não perder tempo em testes manuais. |
| **Objetivos** | <ul><li>Aprender o básico da plataforma de forma guiada.</li><li>Entender como iniciar um chat, dar comandos e revisar respostas.</li><li>Ter uma maior da interação do usuário com chats de IA.</li></ul> |
| **Planejamento** | Joana opta por seguir o tutorial oferecido na tela inicial ao invés de explorar por conta própria. Acredita que o passo a passo vai economizar tempo e evitar erros comuns de iniciantes. |
| **Ações** | <ol><li>Acessa o DeepSeek e clica em “Ver Tutorial”.</li><li>Lê a introdução sobre o propósito da ferramenta.</li><li>Passa por seções como: “Como iniciar um chat”, “Como dar comandos claros” e “Regenerar respostas”.</li><li>Interage com exemplos demonstrativos e simulações práticas.</li><li>Finaliza o tutorial clicando em “Concluir” e é redirecionada ao painel principal.</li></ol> |
| **Eventos** | <ul><li>Durante o tutorial, o sistema apresenta dicas visuais e animações que destacam elementos da interface.</li><li>Um marcador de progresso exibe a etapa atual e quanto falta para terminar.</li><li>Ao concluir, uma notificação confirma o término e sugere iniciar o primeiro chat real.</li></ul> |
| **Avaliação** | <ul><li>Joana sente-se segura para começar a usar a ferramenta de forma prática.</li><li>Considera o conteúdo claro e bem dividido em etapas curtas.</li><li>Acredita que o tutorial economizou tempo e reduziu a curva de aprendizado.</li></ul> |


<a id="cn13"></a>

## #CN13 - Limpeza do histórico de conversas
**Autor:** [Ana Clara](https://github.com/anabborges)

<font><p style="text-align: center">**Tabela 15** - Cenário 13 - Limpeza do histórico de conversas.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Limpeza do histórico de conversas |
| **Código** | #CN13 |
| **Caso de uso trabalhado** | [#UC13](../modelagem/casos-de-uso.md#uc13) |
| **Atores** | Henrique, 31 anos, gerente de inovação em uma empresa de tecnologia, com formação em Engenharia de Software. Usa o DeepSeek diariamente para brainstorms técnicos, geração de documentação e simulação de conversas com IA. Valoriza organização e privacidade nos dados utilizados. |
| **Ambiente (Contexto)** | Durante uma revisão semanal de atividades em seu escritório, com conexão estável, Henrique percebe que acumulou muitas conversas antigas no DeepSeek. Para manter o ambiente limpo e evitar confusão futura, decide apagar todo o histórico de conversas. |
| **Objetivos** | <ul><li>Apagar o histórico completo de conversas antigas.</li><li>Garantir que nenhum dado sensível fique armazenado.</li><li>Organizar o ambiente na plataforma.</li></ul> |
| **Planejamento** | Henrique opta por usar a função de “Limpar Histórico” oferecida pela plataforma. Sabe que o sistema exige confirmação, o que evita exclusões acidentais. |
| **Ações** | <ol><li>Acessa o DeepSeek pela interface web.</li><li>Navega até a aba de histórico de conversas.</li><li>Clica em “Limpar Histórico”.</li><li>O sistema exibe uma janela de confirmação: “Tem certeza que deseja apagar todas as conversas?”</li><li>Henrique clica em “Sim”.</li><li>As conversas são permanentemente removidas.</li></ol> |
| **Eventos** | <ul><li>Uma notificação é exibida: “Histórico apagado com sucesso.”</li><li>O histórico agora aparece vazio e a tela inicial é atualizada.</li></ul> |
| **Avaliação** | <ul><li>Henrique valida que todas as conversas antigas foram de fato apagadas.</li><li>Henrique considera o fluxo claro e a confirmação foi essencial para evitar exclusões acidentais.</li></ul> |

<a id="cn14"></a>

## #CN14 - Resumo de Vídeos do YouTube
**Autor:** [Mateus](https://github.com/MVConsorte)  

<font><p style="text-align: center">**Tabela 16** - Cenário 14 - Resumo de Vídeos do YouTube.</p></font>

| **Item** | **Descrição** |
| ---- | ---- |
| **Titulo** | Resumo de Vídeos do YouTube |
| **Código** | #CN14 |
| **Caso de uso trabalhado** | [#UC14](../modelagem/casos-de-uso.md#cn14) |
| **Atores** | Toni, 30 anos, profissional de tecnologia, usuário frequente do DeepSeek, interessado em ferramentas de automação para consumo otimizado de conteúdo. |
| **Ambiente (Contexto)** | Toni está no escritório, utilizando seu **smartphone com o aplicativo DeepSeek**. Durante uma pausa no trabalho, deseja consumir rapidamente o conteúdo de um vídeo do YouTube sem precisar assisti-lo inteiro. Ele está conectado à internet por Wi-Fi e quer um resumo do vídeo para decidir se vale a pena assisti-lo na íntegra. |
| **Objetivos** | <ul><li>Gerar um **resumo** de um vídeo do YouTube.</li><li>Consumir rapidamente as informações mais relevantes do vídeo sem precisar assisti-lo por completo.</li></ul> |
| **Planejamento** | Toni decide utilizar o DeepSeek para **importar um link do YouTube** e gerar um resumo automático. Ele entende que, com essa funcionalidade, poderá obter insights rápidos do conteúdo antes de dedicar tempo ao vídeo completo. |
| **Ações** | <ol><li>Toni abre o **DeepSeek** e acessa o chat.</li><li>Insere um **link de vídeo do YouTube** no campo de texto.</li><li>Identifica o **botão "Resumir"** abaixo da barra de texto e clica nele.</li><li>O sistema verifica a validade do link e se o vídeo está acessível.</li><li>O sistema processa o vídeo e obtém informações como **título, descrição e transcrição** (caso disponível).</li><li>O sistema aplica **técnicas de processamento de áudio** para separar **voz, música e ruídos de fundo**.</li><li>A IA analisa padrões do discurso utilizando **processamento de linguagem natural (NLP)** para detectar os principais temas do vídeo.</li><li>O sistema gera um **resumo estruturado** do vídeo e exibe o resultado no chat para Toni.</li></ol> |
| **Eventos** | <ul><li>O usuário vê um indicador de carregamento enquanto o DeepSeek está analisando o conteúdo do vídeo e processando o áudio e o texto do mesmo.</li><li>Após a conclusão, o resumo gerado aparece no chat, permitindo Toni decidir se deseja assistir ao vídeo completo.</li></ul> |
| **Avaliação** | <ul><li>Toni lê o resumo e compara com a expectativa de informação desejada.</li><li>Se o resumo for satisfatório, **economiza tempo**, evitando a necessidade de assistir ao vídeo inteiro.</li><li>Caso identifique informações relevantes, pode optar por **assistir ao vídeo completo** para aprofundar o conhecimento sobre o tema.</li></ul> |

---

## Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário, p. 172 . [`Foto da referência`](../images/cenarios/definicao-cenario.png)

> <a id="REF2" href="#anchor_2">2.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário, p. 172 . [`Foto da referência`](../images/cenarios/uso-dos-cenarios.png)

> <a id="REF3" href="#anchor_3">3.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário, p. 172 . [`Foto da referência`](../images/cenarios/itens-cenarios.png)

>  4.DEEPSEEK AI. DeepSeek V3. Disponível em: https://github.com/deepseek-ai/DeepSeek-V  

---

## Histórico de versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 09/05/2025 |  1.0   | (#CO1) Adição de introduçaõ e metodologia.| [@Ana Joyce](https://github.com/anajoyceamorim)   | [@Gabriela](https://github.com/gaubiela) |
| 10/05/2025 |  1.1   | (#CO1) Incrementa parte da documentação sobre cenários.| [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.2   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Davi Emanuel](https://github.com/daviRolvr)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 11/05/2025 |  1.3   | (#CO2) Incrementa parte da documentação sobre cenários.| [@luiz](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 14/05/2025 |  1.4   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 16/05/2025 |  1.5   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Davi Emanuel](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 16/05/2025 |  1.6   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Luiz](https://github.com/luizfaria1989)   | [@Davi Emanuel](https://github.com/daviRolvr) |
| 17/05/2025 |  1.7   | (#CO2) Incrementa parte da documentação sobre cenários.| [@fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 17/05/2025 |  1.8   | (#CO4) Incrementa parte da documentação sobre cenários.| [@Ana Joyce](https://github.com/anajoyceamorim)   | [@gaubiela](https://github.com/gaubiela) |
| 18/05/2025 |  1.9   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Ana Borges](https://github.com/anabborges)   | [@Luiz](https://github.com/luizfaria1989) |
| 18/05/2025 |  1.10  | (#CO2) Incrementa parte da documentação sobre cenários e corrige indexação dos cenários.| [@Mateus](https://github.com/MVConsorte)   | [@Luiz](https://github.com/luizfaria1989) |
| 05/06/2025 |  2.0  | (#CO2) Adição dos ids para os cenários desenvolvidos.| [@Luiz](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)  |
| 06/06/2025 |  2.1  | (#C02) Adição da tabela de contribuições e dos hiberlinks para os cenários desenvolvidos.| [@Luiz](https://github.com/luizfaria1989)  | [`@Fabio`](https://github.com/fabinsz)   |
| 19/06/2025 |  2.2  | (#C02) Modificação dos cenários para tabelas.| [@Luiz](https://github.com/luizfaria1989)  |   |
| 19/06/2025 |  2.3  | (#C02) Adiciona fotos das referências dos cenários.| [@Luiz](https://github.com/luizfaria1989)  |   |
