## Cenários

## Introdução
No contexto atual de crescente uso de ferramentas baseadas em inteligência artificial, como o DeepSeek, torna-se essencial compreender de forma aprofundada as interações entre usuários e sistemas computacionais. O sucesso na adoção e na efetividade dessas ferramentas depende diretamente de seu alinhamento com as necessidades, objetivos e contextos dos usuários finais. Para garantir esse alinhamento, a disciplina de Requisitos de Softaware propõe abordagens sistemáticas que permitem entender, representar e incorporar essas necessidades ao longo do processo de modelagem. Uma das estratégias fundamentais nesse processo é a utilização de cenários, que descrevem narrativas realistas de uso e permitem a análise e refinamento dos requisitos de forma contextualizada e centrada nos usuários. Este projeto tem como objetivo aplicar essa abordagem ao desenvolvimento da modelagem de requisitos de software para o DeepSeek, utilizando a técnica de cenários como instrumento central para a validação e modelagem de requisitos funcionais e não funcionais.

Em IHC, um cenário consiste em uma “história sobre pessoas realizando uma atividade” que descreve, de forma concreta e rica em detalhes contextuais, como usuários reais ou potenciais interagem com um sistema. Conforme definido:

> “Um cenário é basicamente uma história sobre pessoas realizando uma atividade (Rosson e Carroll, 2002). É uma narrativa, textual ou pictórica, concreta, rica em detalhes contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais.”;

Os cenários servem a múltiplos propósitos no processo de design:

> “podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002). Além de poderosos, os cenários requerem menos custo e tempo quando comparados com modelos e protótipos complexos, o que os torna uma ferramenta importante em todo o processo de design de IHC.”;

Segundo Rosson & Carroll (2002) e Cooper (1999), cada cenário deve explicitar os seguintes elementos característicos:

- **Ambiente ou contexto**: detalhes da situação que motivam ou explicam os objetivos, ações e reações dos atores;
- **Atores**: pessoas interagindo com o computador ou outros elementos do ambiente; características pessoais relevantes;
- **Objetivos**: efeitos na situação que motivam as ações realizadas pelos atores;
- **Planejamento**: atividade mental dirigida para transformar um objetivo em um comportamento ou conjunto de ações;
- **Ações**: comportamento observável;
- **Eventos**: ações externas ou reações produzidas pelo computador ou outras características do ambiente; algumas delas podem ser ocultas ao ator mas importantes para o cenário;
- **Avaliação**: atividade mental dirigida para interpretar a situação.;

Essa estrutura garante que o cenário seja suficientemente detalhado para orientar a definição de requisitos, guiar decisões de design e validar a usabilidade de soluções propostas, mantendo sempre o foco nas necessidades e no contexto real dos usuários

## Metodologia
A metodologia deste projeto baseia-se na abordagem de design baseado em cenários, conforme proposta por Rosson e Carroll (2002) e discutida por Barbosa et al. (2021). Inicialmente, foi elaborado o [perfil do usuário](https://requisitos-de-software.github.io/2025.1-Deepseek/elicitacao/perfil-de-usuario/) do DeepSeek, com base em dados coletados por meio de análise de interface e de documentação, observação e questionário. Esses perfis foram utilizados para compor cenários de uso que retratam situações reais ou plausíveis de interação com o sistema. Cada cenário foi construído com base nos seguintes elementos: contexto, atores, objetivos, ações, eventos e avaliação das ações. A partir desses cenários, foi possível modelar requisitos do sistema, compreendendo não apenas as funcionalidades desejadas, mas também as limitações e expectativas dos usuários. Essa abordagem qualitativa, centrada no ser humano, favorece um entendimento mais profundo da experiência do usuário e permite o direcionamento dos requisitos de forma iterativa e fundamentada.

## Cenários Modelados:

## Ana Clara

## Ana Joyce

## Cenário XX: Utilização do DeepSeek com plataformas externas integradas
Autor: [Davi Emanuel](https://github.com/daviRolvr)

**Atores:**: Gabriel, 24 anos, recém-formado em Engenharia da Computação, buscando oportunidades na área de Ciência de Dados. É usuário frequente de tecnologias baseadas em IA, com alto nível de familiaridade digital. Usa o DeepSeek diariamente para organizar ideias, revisar códigos, gerar conteúdos e montar portfólios.

**Ambiente (Contexto):** Gabriel está em casa, utilizando seu notebook pessoal. Ele tem uma entrevista marcada com uma startup e deseja preparar uma apresentação rápida sobre um projeto pessoal de análise de dados que publicou no GitHub, ao mesmo tempo em que quer revisar suas experiências profissionais para destacar no LinkedIn, e organizar referências salvas no Google Drive.

**Objetivos:**

* Utilizar o DeepSeek para acessar informações de múltiplas plataformas sem alternar entre várias abas.

* Revisar e sintetizar o conteúdo de um repositório do GitHub integrado.

* Gerar um resumo das experiências e habilidades listadas no LinkedIn.

* Reunir documentos salvos no Google Drive relacionados ao projeto.

* Preparar um pitch organizado com base em todas essas fontes para compartilhar no Discord com colegas.

**Planejamento:** Gabriel conecta suas contas do GitHub, Google, LinkedIn e Discord ao DeepSeek. Ele acredita que, com essa integração, será possível cruzar dados automaticamente, gerar resumos mais ricos e se preparar melhor para entrevistas com base em todo o seu histórico digital.

**Ações:**

1. Acessa o DeepSeek e autoriza a integração com suas contas do GitHub, LinkedIn, Google e Discord.

2. Solicita à IA que analise um repositório específico do GitHub e resuma os principais algoritmos implementados.

3. Pede ao DeepSeek que acesse seu perfil do LinkedIn e gere um resumo com foco nas experiências mais relevantes para a vaga.

4. Importa automaticamente do Google Drive um PDF com anotações e dados sobre o projeto para análise complementar.

5. Gera, com o apoio da IA, uma apresentação em formato texto para compartilhar em um canal privado no Discord.

6. Revisa tudo em uma interface centralizada, sem precisar mudar de aba ou copiar/colar manualmente.

**Eventos:**

* O DeepSeek exibe a mensagem “Conectando às suas plataformas: GitHub, Google Drive, LinkedIn, Discord…”.

* A IA acessa os dados permitidos, respeitando as permissões de privacidade, e exibe um painel integrado.

* Um resumo técnico do repositório é exibido, junto com uma síntese das experiências profissionais e links para documentos relevantes.

* A plataforma sugere insights para destacar na apresentação, com base nas palavras-chave da vaga informada.

* Gabriel exporta tudo em um único documento e compartilha via Discord com um clique.

**Avaliação:**

* Gabriel considera a integração extremamente eficiente, pois economizou tempo ao reunir dados dispersos automaticamente.

* Fica satisfeito com a forma como o DeepSeek compreendeu e cruzou as informações entre plataformas.

* Avalia que conseguiu se preparar de forma estratégica para a entrevista, com mais confiança.

* Decide manter as integrações ativas para utilizar o DeepSeek como centro de produtividade no seu dia a dia profissional.

---
## Cenário XX: Pesquisa utilizando integração por voz no DeepSeek
Autor: [Davi Emanuel](https://github.com/daviRolvr)

**Atores:** Camila, 27 anos, mestranda em Psicologia Cognitiva, com bom domínio de tecnologia e rotina intensa de leitura e produção acadêmica. Utiliza o DeepSeek como assistente de pesquisa para agilizar a análise de textos científicos e sínteses bibliográficas.

**Ambiente (Contexto):** Camila está caminhando de um prédio para outro no campus da universidade, usando fones de ouvido com microfone e carregando o celular em uma das mãos. Como o tempo é curto entre uma atividade e outra, ela decide usar o DeepSeek via comando de voz para não precisar parar e digitar.

**Objetivos:**

* Consultar rapidamente o DeepSeek sem precisar usar as mãos ou digitar textos longos.

* Obter uma explicação resumida sobre o conceito de “memória episódica” com exemplos.

* Agilizar sua pesquisa enquanto se desloca, otimizando seu tempo.

**Planejamento:** Camila ativa o recurso de entrada por voz no aplicativo do DeepSeek, ciente de que a funcionalidade converte fala em texto, realiza a busca e responde por texto e/ou voz. Ela quer testar se consegue interagir naturalmente com o sistema mesmo em movimento.

**Ações:**

1. Abre o aplicativo do DeepSeek no celular.

2. Ativa o modo “Pesquisa por Voz”.

3. Diz: “DeepSeek, me explica de forma resumida o que é memória episódica e me dá dois exemplos.”

4. Aguarda o reconhecimento da fala e a geração da resposta.

5. Ouve a resposta sintetizada por voz e também lê o conteúdo em texto na tela.

6. Salva a resposta nos favoritos para revisar depois.

**Eventos:**

* O DeepSeek exibe a mensagem: “Ouvindo...”, seguida de “Interpretando sua fala...”.

* A fala é convertida em texto e exibida para confirmação.

* A IA realiza a análise e responde tanto em texto quanto em voz sintetizada.

* Sugestões adicionais aparecem na tela: “Quer saber mais sobre memória semântica?”, “Deseja salvar esta resposta?”

**Avaliação:**

* Camila considera que a experiência por voz foi fluida e natural, sem a necessidade de parar sua locomoção.

* Destaca a praticidade do sistema reconhecer sua voz em ambiente externo com ruído moderado.

* Avalia que o tempo de resposta foi satisfatório e a resposta adequada ao contexto acadêmico.

* Decide usar a funcionalidade com frequência, principalmente em momentos em que não pode digitar.



## Fabio

## Cenário XX: Acessar configurações para alterar o tema do Sistema
**Autor**:  [Fabio](https://github.com/fabinsz)

**Atores:**
Lucas, 29 anos, engenheiro de dados, mestre em Ciência da Computação. Usuário frequente do DeepSeek, utiliza a ferramenta diariamente para processar documentos técnicos, interagir com repositórios de código e extrair insights com ajuda da IA. É altamente proficiente em tecnologia e aprecia ambientes de trabalho visualmente confortáveis e personalizados.

**Ambiente (Contexto):**
Lucas está trabalhando em um coworking, em um ambiente com iluminação forte. Após algumas horas usando o DeepSeek no modo claro, começa a sentir desconforto visual. Decide, então, mudar o tema da interface para o modo escuro para aliviar a fadiga visual.

**Objetivos:**

* Alterar o tema do sistema para o modo escuro.
* Verificar se a alteração é aplicada de forma consistente em todas as seções do sistema.

**Planejamento:**
Por ser um usuário experiente, Lucas assume que a opção de personalização visual está nas configurações gerais. Ele espera conseguir mudar o tema com poucos cliques e sem precisar reiniciar a aplicação ou abrir tutoriais.

**Ações:**

1. Clica no ícone de perfil 
2. Seleciona "Configurações" no menu suspenso.
3. Encontra a opção “Tema/Aparência”.
4. Altera de “Claro” para “Escuro (Dark Mode)”.
5. Observa a transição da interface e valida se todos os elementos visuais se adaptaram corretamente.
6. Fecha o menu de configurações e retoma suas atividades no novo tema.

**Eventos:**

* O modo escuro se aplica em toda a interface, incluindo ao editor de textos e à área de visualização de documentos.

**Avaliação:**

* Lucas se sente mais confortável visualmente e satisfeito com a personalização oferecida.
* Considera a experiência rápida e intuitiva, algo essencial para não interromper seu fluxo de trabalho.

---

## Gabriela

## Cenário XX: Upload de Documento (#UC01)
**Autor**:  [Gabriela](https://github.com/gaubiela) 

**Atores:**
Júlia, 27 anos, pesquisadora em Ciência da Computação, formação superior, alta proficiência tecnológica, usa o DeepSeek diariamente para processamento avançado de documentos.

**Ambiente (Contexto):**
Em seu home office, com conexão estável de fibra óptica e deadline apertado para submeter um artigo, Júlia recebe um PDF que precisa converter em texto editável e interpretar conteúdo de forma rápida.

**Objetivos:**

* Extrair todo o texto.
* Garantir que conteúdo e insights sejam consistentes e preservados.

**Planejamento:**
Júlia decide usar o fluxo de upload do DeepSeek em vez de ferramentas manuais, pois estima maior agilidade e menor chance de erro.

**Ações:**

1. Abre o DeepSeek e seleciona “Upload de Documento”.
2. Escolhe o arquivo PDF do artigo.
3. Observa barra de progresso até 100 %.
5. Revisita arquivo para verificar consistência do conteúdo e informações fornecidas através do deepseek.

**Eventos:**

* Após o upload, um spinner que representa o carregamento é apresentado, bem como mensagens que dizem em que etapa do processamento o deepseek está.

**Avaliação:**

* Júlia percorre o texto extraído, conferindo símbolos e formatação; para cada inconsistência.
* Compara mentalmente o conteúdo gerado com o PDF original, e valida se todos os insights obtidos durante a conversa foram consistentes.

---

## Cenário XX: Consulta Atualizada via Search na Web (#UC02)
**Autor**:  [Gabriela](https://github.com/gaubiela) 

**Atores:**
Pedro, 31 anos, engenheiro de software em startup, formação em TI, utiliza DeepSeek várias vezes ao dia para se manter atualizado sobre tecnologias emergentes.

**Ambiente (Contexto):**
Em seu escritório, precisa saber imediatamente qual é a versão mais recente do Node.js em 10 de maio de 2025 para configurar o ambiente de build do time.

**Objetivos:**

* Obter a versão mais recente do Node.js no dia atual disponibilizada no site oficial.
* Copiar a informação para documentá-la no repositório interno de conhecimento.

**Planejamento:**
Pedro pretende usar a aba “Search” do DeepSeek para fazer uma busca na web, evitando acessar múltiplas abas no navegador. Caso o resultado inicial não cite a data exata, ele vai refinar a pesquisa em busca da versão mais atual no dia atual.

**Ações:**

1. Ativar a opção **Search** no DeepSeek.
2. Digita “Qual é a versão mais recente do Node.js em 10 de maio de 2025?” e pressiona Enter.
3. Aguarda < 2 s pelo resultado, que inclui número da versão e data de lançamento.
4. Clica em “Copy” ao lado do trecho “Node.js v20.7.0 – lançado em 08/05/2025”.
5. Cola a informação no README do repositório.

**Eventos:**

* Se a resposta demorar > 3 s, surge aviso de erro com opção de recarregamento.
* Cada clique em “Copy” exibe brevemente a mensagem “Copiado!” no centro superior da aba.

**Avaliação:**

* Pedro verifica se o número da versão e a data estão corretos comparando com o site nodejs.org.
* Confirma que o tempo total de busca foi inferior a 3 s, atendendo ao seu critério de agilidade.
* Se algum dado estiver divergente, refina a pesquisa para “Node.js versão estável maio 2025” e repete o fluxo.

---

## Cenário XX: Iteração de Resposta com Opções Disponíveis Para Resposta (like, dislike, regenerate, copy) (#UC03)
**Autor**:  [Gabriela](https://github.com/gaubiela) 

**Atores:**
Mariana, 25 anos, aluna de pós em Bioinformática, alta proficiência, usa o app no celular enquanto toma café entre aulas para refinar textos.

**Ambiente (Contexto):**
Num café da universidade, conexão móvel instável, ela quer melhorar o parágrafo sobre “Identificação de variantes genéticas associadas a doenças complexas” feito por ela.

**Objetivos:**

* Obter um parágrafo claro e conciso sobre o conteúdo.
* Copiar o texto final para seu documento de anotações.

**Planejamento:**
Decide iterar usando “Dislike + Regenerate” até que o resultado atenda ao estilo desejado, marcando “Like” na versão final.

**Ações:**

1. Lê o primeiro parágrafo gerado.
2. Se insatisfeita, clica em “Dislike” e fornece feedback sobre o descontentamento.
3. Toca em “Regenerate” e aguarda nova versão (\~ 1 s).
4. Repete “Dislike + Regenerate” uma vez mais se necessário.
5. Na versão satisfatória, clica em “Like” e depois em “Copy”.

**Eventos:**

* Caso a regeneração demore > 3 s, surge botão “Cancelar” para reiniciar o processo.
* Feedback “Like/Dislike” envia dados sobre o conteúdo fornecido para o DeepSeek.

**Avaliação:**
Mariana compara mentalmente cada iteração com seu padrão de clareza; quando atingir fluxo e precisão, encerra as regenerações.

## Cenário XX: Utilização da Ferramenta Pensamento Profundo para Resolver um Problema Difícil de Matemática
**Autor:** [Luiz](https://github.com/luizfaria1989)

**Atores:**
Gauss, estudante universitário de engenharia, no primeiro semestre.

**Ambiente (Contexto):**
Gauss está no quarto de sua casa fazendo exercícios de uma lista para a sua prova de cálculo 1 da próxima semana. Ao tentar resolver um dos exercícios, ele fica com dúvidas sobre como resolver um cálculo complexo de uma integral.

**Objetivos:**

* Encontrar a explicação de como se resolve um exercício difícil de matemática.
* Anotar a resolução do exercício em seu caderno junto com outras resoluções da lista.

**Planejamento:**
Decide utilizar o DeepSeek com a função de **Pensamento Profundo** para tentar encontrar a solução do exercício que está com dúvidas.

**Ações:**

1. Digita a equação do problema no chat e pede a resolução.
2. Ativa a opção "Pensamento Profundo (R1)" acima do teclado.
3. Lê a resolução do exercício difícil.

**Eventos:**

* Aparece uma mensagem de carregamento escrita "Pensando...".
* No chat aparecem o raciocínio da IA linha por linha.
* Aparece a opção de ocultar os "pensamentos" da IA para exibir apenas a resposta final.


**Avaliação:**
Gauss compara a resolução do exercício com as suas de seu caderno para garantir que o modelo do DeepSeek utilizou os mesmos conceitos aprendidos em cálculo 1.

## Bibliografia

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário.  
> DEEPSEEK AI. DeepSeek V3. Disponível em: https://github.com/deepseek-ai/DeepSeek-V  


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 09/05/2025 |  1.0   | (#CO1) Adição de introduçaõ e metodologia.| [@Ana Joyce](https://github.com/anajoyceamorim)   | [@Gabriela](https://github.com/gaubiela) |
| 10/05/2025 |  1.1   | (#CO1) Incrementa parte da documentação sobre cenários.| [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.2   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Davi Emanuel](https://github.com/daviRolvr)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 11/05/2025 |  1.3   | (#CO2) Incrementa parte da documentação sobre cenários.| [@luiz](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 14/05/2025 |  1.4   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 16/05/2025 |  1.5   | (#CO2) Incrementa parte da documentação sobre cenários.| [@Davi Emanuel](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
