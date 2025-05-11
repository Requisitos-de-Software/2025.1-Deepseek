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

## Davi
## Cenário XX: Pesquisa sem utilização de aprimoramentos no DeepSeek 

**Atores:**
Nathalia, 21 anos, estudante do 6º semestre do curso de Direito, com familiaridade mediana com tecnologia, utiliza o DeepSeek algumas vezes por semana para apoiar suas pesquisas acadêmicas.

**Ambiente (Contexto):**
Marina está na biblioteca da universidade, utilizando seu notebook conectado ao Wi-Fi da instituição. Ela precisa encontrar jurisprudências e artigos sobre a aplicação do princípio da dignidade da pessoa humana em decisões do Supremo Tribunal Federal (STF), pois tem uma apresentação de seminário na aula de Direito Constitucional no dia seguinte.

**Objetivos:**

* Localizar rapidamente decisões judiciais e doutrinas relevantes sobre o princípio da dignidade da pessoa humana.

* Obter resumos automáticos para facilitar a compreensão inicial do conteúdo.

* Organizar as informações de forma clara para apresentar à turma com segurança.

**Planejamento:**
Marina decide utilizar o DeepSeek por acreditar que a ferramenta pode sintetizar melhor o conteúdo jurídico e economizar tempo, evitando a leitura extensa de documentos jurídicos inteiros logo de início.

**Ações:**

1. Acessa o DeepSeek pelo navegador.

2. Digita na barra de pesquisa: “jurisprudência STF dignidade da pessoa humana”.

3. Filtra os resultados para mostrar apenas decisões judiciais e artigos acadêmicos.

4. lê os resumos automáticos fornecidos pela ferramenta.

5. Copia trechos relevantes e anota os links originais para referência.

**Eventos:**

* O DeepSeek exibe uma animação de carregamento com a mensagem “interpretando/pensando”.

* A plataforma retorna uma lista de decisões do STF, trechos doutrinários e artigos comentados por especialistas.


* São sugeridos também temas relacionados ou artigos para aprofundamento do tópico.

**Avaliação:**

* Nathalia compara os resumos com as decisões completas e valida que os trechos principais foram bem interpretados.

* Considera que o tempo de pesquisa foi bastante reduzido e que o conteúdo está pronto para ser utilizado na apresentação.

* Salva os links e resumos no seu bloco de notas digital e encerra a pesquisa satisfeita.

## Fabio

## Gabriela

## Cenário XX: Upload de Documento (#UC01)

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
| 10/05/2025 |  1.1   | (#CO1) Incrementa parte da documentação sobre cenários.| [@Gabriela](https://github.com/gaubiela)   | - |
| 10/05/2025 |  1.2   | (#CO2) Incrementa parte da documentação sobre cenários.| [@daviRolvr](https://github.com/daviRolvr)   | - |
| 11/05/2025 |  1.3   | (#CO2) Incrementa parte da documentação sobre cenários.| [@luiz](https://github.com/luizfaria1989)   | - |