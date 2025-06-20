## Introdução

Uma forma comum de priorizar os requisitos é dividi-los em três grandes categorias de prioridade: alta, média e baixa, contudo para que ela possa funcionar da forma correta os stakeholders devem concordar em quais são essas prioridades (WIEGERS; BEATTY,  p. 319) <a id="anchor_1" href="#REF1">[1]</a>.

A técnica three level scale transforma essa categorização de requisitos em uma matriz 2x2 que avalia a urgência e a importância de um requisito.

![Figura 1: Priorização de requisitos com base na importância e urgência. Fonte: Luiz](../images/matriz-three-level-scale.png)

Figura 1: Priorização de requisitos com base na importância e urgência. Fonte: Luiz.

Assim, os requisitos na técnica three level scale se dividem em:

* **Alta prioridade:** são requisitos que são importantes, pois os consumidores precisam daquela função, e também urgentes, dado que os consumidores precisam dela na próxima release, assim, pela definição, se o requisito pode ser implementado em uma release futura ele não é de alta prioridade (WIEGERS; BEATTY,  p. 319) <a id="anchor_2" href="#REF2">[2]</a>.

* **Média prioridade:** são requisitos que são importantes, mas os consumidores não precisam deles de forma tão urgente (WIEGERS; BEATTY,  p. 319) <a id="anchor_3" href="#REF3">[3]</a>.

* **Baixa prioridade:** são requisitos que não são tão importantes e também tão urgentes (WIEGERS; BEATTY,  p. 319) <a id="anchor_4" href="#REF4">[4]</a>.

* Os requisitos no quarto quadrante podem ser considerados urgentes para um determinado stakeholder, talvez por razões políticas, mas eles são importantes para atingir os objetivos de negócio (WIEGERS; BEATTY,  p. 319) <a id="anchor_5" href="#REF5">[5]</a> . Assim, não é ideal que um tempo seja gasto trabalhando no desenvolvimento deles, pois eles não adicionam valor suficiente para o produto (WIEGERS; BEATTY,  p. 319) <a id="anchor_5" href="#REF5">[5]</a>.

## Metodologia

Conhecendo como a técnica funciona, ela foi aplicada em reunião online gravada com 4 stakeholders a fim de decidir a prioridade dos requisitos elicitados anteriormente no projeto

As técnicas de produção in or out e three level scale foram aplicadas em conjunto, em que ao passar por um requisito, os stakeholders decidiam se aquele requisito era in ou out mas também o grau de importância, sendo eles: alta, média, baixa ou também optaram por não fazer o desenvolvimento dele (quarto quadrante). Ao fazer isso, foi possível poupar tempo dos integrantes do grupo e dos stakeholders.

### Gravação da reunião

<iframe width="560" height="315" src="https://www.youtube.com/embed/IeVB_esBSlA?si=vzQUqABiKJViKWCb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Participantes da reunião 

<font><p style="text-align: center">**Tabela 1** - Participantes da reunião da técnica de priorização Three Level Scale.</p></font>

| **Nome do participante** | **Papel** |
| ------------------------ | --------- |
| Gabriela | Integrante do grupo atuando como mediadora | 
| Luiz | Integrante do grupo aplicando a técnica de priorização Three Level Scale |
| Fábio | Integrante do grupo aplicando a técnica de priorização in or out |
| Mateus | Integrante do grupo aplicando a técnica de priorização QFD |
| Pedro Bueno | Estudande de medicina em Buenos Aires, 20 anos de idade, stakeholder 1 |
| Janaina | Estudante de arquitetura em Barra do Bugres, 20 anos de idade, stakeholder 2 |
| Kamilia Dutra | Estudante de medicina em Buenos Aires, 20 anos de idade, stakeholder 3 |

## Requisitos Priorizados com a Técnica Three Level Scale 

<font><p style="text-align: center">**Tabela 2** - Requisitos priorizados com a técnica three level scale.</p></font>

| **Código do requisito** | **Descrição** | **Tipo** | **Status** | **Categoria de priorização** |
| ------------------- | --------- | ---- | ------ | -------------------------| 
| [#RF01](../elicitacao/requisitos-gerais.md) | Deve oferecer a possibilidade do usuário acionar a pesquisa na web | Funcional | Implementado | Alta prioridade | 
| [#RF02](../elicitacao/requisitos-gerais.md) | Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking) | Funcional | Implementado | Alta prioridade |
| [#RF03](../elicitacao/requisitos-gerais.md)| O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s | Funcional | Implementado | Alta prioridade |
| [#RN01](../elicitacao/requisitos-gerais.md) | Deve fazer o uso da arquitetura DeepSeek-V3 | Não funcional | Implementado | Baixa prioridade |
| [#RN02](../elicitacao/requisitos-gerais.md) | Deve possuir versões para Android e IOS | Não funcional | Implementado | Alta prioridade |
| [#RF04](../elicitacao/requisitos-gerais.md) | Deve possuir a opção de login com conta Google/Apple ID | Funcional | Implementado | Alta prioridade |
| [#RF05](../elicitacao/requisitos-gerais.md) | Deve salvar chats entre plataformas | Funcional | Implementado | Média prioridade |
| [#RF06](../elicitacao/requisitos-gerais.md) | Melhorar as capacidades de "deep thinking" | Funcional | Não implementado | Média prioridade |
| [#RF07](../elicitacao/requisitos-gerais.md) | Deve haver um campo para a interação com a IA | Funcional | Não implementado | Alta prioridade |
| [#RF08](../elicitacao/requisitos-gerais.md) | Deve ser possível criar novos chats | Funcional | Implementado | Alta prioridade |
| [#RF09](../elicitacao/requisitos-gerais.md) | Deve ser possível renomear um chat | Funcional | Implementado | Média prioridade |
| [#RF10](../elicitacao/requisitos-gerais.md)| Os chats já utilizados devem poder se acessados posteriormente | Funcional | Implementado | Média prioridade |
| [#RF11](../elicitacao/requisitos-gerais.md) | Deve ser possível dar dislike em uma resposta da IA | Funcional | Implementado | Não fazer |
| [#RF12](../elicitacao/requisitos-gerais.md) | Deve ser possível dar like em uma resposta da IA | Funcional | Implementado | Não fazer | 
| [#RF13](../elicitacao/requisitos-gerais.md) | Deve ser possível copiar uma resposta da IA | Funcional | Implementado | Alta prioridade |
| [#RF14](../elicitacao/requisitos-gerais.md) | Deve exibir citações de fontes e referências em respostas baseadas em documentos, indicando página, site e/ou trecho extraído. | Funcional | Parcialmente implementado | Baixa prioridade|
| [#RF15](../elicitacao/requisitos-gerais.md) | Deve ser possível alterar o idioma do sistema | Funcional | Implementado | Alta prioridade |
| [#RF16](../elicitacao/requisitos-gerais.md) | Deve ser possível apagar conversas individuais ou de forma geral | Funcional | Implementado | Baixa prioridade |
| [#RF17](../elicitacao/requisitos-gerais.md) | Deve ser possível regenar uma resposta da IA de forma manual ou de forma automática no caso de erro de servidor ou sobrecargado sistema | Funcional | Parcialmente implementado | Média prioridade |
| [#RF18](../elicitacao/requisitos-gerais.md) | O sistema deve exibir respostas formatadas em Markdown em respostas para tabelas ou listas complexas Markdown (títulos, listas, código) com a possibilidade de edição do Markdown pelo usuário | Funcional | Parcialmente implementado | Baixa prioridade |
| [#RF19](../elicitacao/requisitos-gerais.md) | Deve ser possível interromper respostas em andamento | Funcional | Não implementado | Baixa prioridade |
| [#RF20](../elicitacao/requisitos-gerais.md) | Deve possuir uma API Pública | Funcional | Não implementado | Alta prioridade |
| [#RF21](../elicitacao/requisitos-gerais.md) | Deve aceitar autenticação via token de acesso | Funcional | Implementado | Não fazer | 
| [#RN03](../elicitacao/requisitos-gerais.md) | Deve guardar um histórico de conversas por 30 dias - O histórico não é persistente se o usuário sair sem salvar | Não funcional | Não implementado | Baixa prioridade |
| [#RN04](../elicitacao/requisitos-gerais.md) | Deve fazer a exclusão automática de dados de upload | Não funcional | Não implementado | Média prioridade |
| [#RN05](../elicitacao/requisitos-gerais.md) | A interface deve seguir diretrizes de usabilidade (botões visíveis, texto legível, feedback imediato) e de acessibilidade (alteração no tamanho da fonte, leitura) | Não funcional | Não implementado | Alta prioridade |
| [#RF22](../elicitacao/requisitos-gerais.md) | Deve haver uma confirmação para limpar o histórico | Funcional | Não implementado | Alta prioridade |
| [#RN06](../elicitacao/requisitos-gerais.md) | Em caso de falha, deve retornar mensagens de erro claras | Não funcional | Implementado | Não fazer |
| [#RN07](../elicitacao/requisitos-gerais.md) | O sistema deve suportar múltiplas requisições simultâneas sem degradação | Não funcional | Implementado | Média prioridade |
| [#RN08](../elicitacao/requisitos-gerais.md) | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤10 segundos e o tempo médio de resposta deve ser <= 2 s em operações simples | Não funcional | Parcialmente implementado | Baixa prioridade |
| [#RF23](../elicitacao/requisitos-gerais.md) | Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita) | Funcional | Não implementado | Baixa prioridade |
| [#RF24](../elicitacao/requisitos-gerais.md) | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256) | Funcional | Implementado | Alta prioridade |
| [#RF25](../elicitacao/requisitos-gerais.md) | O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização) | Funcional | Não implementado | Média prioridade | 
| [#RF26](../elicitacao/requisitos-gerais.md) | Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas | Funcional | Não implementado | Não fazer |
| [#RF27](../elicitacao/requisitos-gerais.md) | Deve oferecer modo escuro e modo claro, com configuração manual e sincronização automática com o sistema operacional | Funcional | Implementado | Alta prioridade |
| [#RF28](../elicitacao/requisitos-gerais.md) | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades. / Implementar tutorial interativo (tour guiado) destacando recursos avançados (DeepThink, Reason etc.) no onboarding | Funcional | Não implementado | Baixa prioridade |
| [#RN09](../elicitacao/requisitos-gerais.md) | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados. | Não funcional |  Não funcional | Não implementado | Não fazer |
| [#RN10](../elicitacao/requisitos-gerais.md) | <a id="tls-rn10"></a> Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em processos de re-treinamento ou venda de modelos | Não funcional | Não implementado | Alta prioridade |
| [#RF29](../elicitacao/requisitos-gerais.md) | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) | Funcional | Não implementado | Não fazer |
| [#RF30](../elicitacao/requisitos-gerais.md) | Melhorar retenção de contexto em diálogos longos para evitar “esquecimento” ou mistura de informações previamente dadas | Funcional | Parcialmente implementado | Média prioridade |
| [#RF12](../elicitacao/requisitos-gerais.md) | <a id="tls-rn12"></a> Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas | Não funcional | Parcialmente implementado | Média prioridade |
| [#RF31](../elicitacao/requisitos-gerais.md) | Implementar memória de contexto persistente entre conversas | Funcional | Não implementado | Média prioridade |
| [#RF32](../elicitacao/requisitos-gerais.md) | Permitir escolha de modelos (seleção de diferentes versões/modelos de IA) | Funcional | Não implementado | Média prioridade |
| [#RF33](../elicitacao/requisitos-gerais.md) | Permitir organização de conversas em pastas ou listas por tema ou projeto | Funcional | Não implementado | Média prioridade |
| [#RF34](../elicitacao/requisitos-gerais.md) | Implementar comandos de voz para entrada e saída de informações | Funcional | Não implementado | Alta prioridade |
| [#RN13](../elicitacao/requisitos-gerais.md) | Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras | Não funcional | Parcialmente implementado | Baixa prioridade |
| [#RN14](../elicitacao/requisitos-gerais.md) | <a id="tls-rn14"></a> Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras | Não funcional | Não implementado | Baixa prioridade |
| [#RF15](../elicitacao/requisitos-gerais.md) | <a id="tls-rn15"></a> Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras | Não funcional | Não implementado | Baixa prioridade |
| [#RF35](../elicitacao/requisitos-gerais.md) | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico para que não cubra outros elementos e posicione em local adequado | Funcional | Não implementado | Não fazer |
| [#RF36](../elicitacao/requisitos-gerais.md) | Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR (explicar siglas e limitações) | Funcional | Não implementado | Média prioridade |
| [#RF37](../elicitacao/requisitos-gerais.md) | Conectar nativamente a ferramentas populares (Google Drive, Google Agendas, Outlook, GitHub etc.) via integrações diretas | Funcional | Não implementado | Média prioridade |
| [#RF38](../elicitacao/requisitos-gerais.md) | Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização) | Funcional | Não implementado | Alta prioridade |

<font><p style="text-align: center">**Autor** - Luiz.</p></font>

Com base na técnica de priorização de requisitos foram capaz de classificar os 52 requisitos elicitados anteriormente em quatro categorias, 17 requisitos foram classificados como muito importantes e de alta prioridade, 15 requisitos foram considerados pelos stakeholders como requisitos de média prioridade, 12 requisitos foram de baixa prioridade, não sendo tão urgentes para os consumidores e não tão importantes. Além disso, 8 requisitos foram para a quarta categoria, que não apresentam valor para o produto final desenvolvido.

---

## Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. p. 316. [`Foto da referência`](../images/three-level-scale/definicao-three-level-scale.png)

> <a id="REF2" href="#anchor_2">2.</a> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. p. 316. [`Foto da referência`](../images/three-level-scale/definicao-alta-prioridade.png)

> <a id="REF3" href="#anchor_3">3.</a> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. p. 316. [`Foto da referência`](../images/three-level-scale/definicao-media-prioridade.png)

> <a id="REF4" href="#anchor_4">4.</a> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. p. 316. [`Foto da referência`](../images/three-level-scale/definicao-baixa-prioridade.png)

> <a id="REF5" href="#anchor_5">5.</a> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. p. 316. [`Foto da referência`](../images/three-level-scale/definicao-quarto-quadrante.png)

---

## Link para o documento em versão PDF

[Documento](https://docs.google.com/document/d/1Xos-q7mQ_vuDQqeCBLC7N5xdxEBLVYF27pExJdWrvOg/edit?usp=sharing)

---

## Histórico de Versões

| Data       | Versão | Descrição                                 | Autor                                      | Revisor                       |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 02/05/2025 |  0.1   | (#Q04) Documentação referente a aplicação da técnica de priorização Three Level Scale.| [@Luiz](https://github.com/luizfaria1989)   | [@Ana Borges](https://github.com/anabborges) |
| 20/06/2025 |  1.0   | (#Q04) Transformando os requisitos priorizados em uma tabela para melhor visualização.| [@Luiz](https://github.com/luizfaria1989)   | [@](https://github.com/) |
| 20/06/2025 |  1.1   | (#Q04) Adição dos IDs dos requisitos com hiperlinks na tabela de priorização.| [@Luiz](https://github.com/luizfaria1989)   | [@](https://github.com/) |
| 20/06/2025 |  1.2   | (#Q04) Adição das referências, gravação da reunião e padronização do documento.| [@Luiz](https://github.com/luizfaria1989)   | [@](https://github.com/) |



 





    







 







 


