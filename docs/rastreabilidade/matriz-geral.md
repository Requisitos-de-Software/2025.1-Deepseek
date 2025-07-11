# Introdução

Uma das técnicas mais comuns para manter a rastreabilidade dos requisitos e dos artefatos que estão sendo desenvolvidos em um projeto de software é a utilização de uma matriz de rastreabilidade. Essa matriz pode ser implementada com a utilização de softwares específicos que facilitem o seu desenvolvimento <a id="anchor_1" href="#REF1">[1]</a>.

Nessa matriz, são colocados os requisitos, o documento de origem no qual aquele requisito foi elicitado, a arquitetura, o componente e o caso de teste <a id="anchor_2" href="#REF2">[2]</a>.

A coluna dos requisitos deve ser preenchida com os requisitos elicitados no projeto. Já as demais, são preenchidas com os artefatos criados com base nequele requisito durante o processo de desenvolvimento. É importante ressaltar que essa correspondencia nem sempre é de 1 para 1, dado que, por exemplo, um requisito pode ser verificado em vários casos de teste <a id="anchor_3" href="#REF3">[3]</a>.

# Objetivos

Esse artefato tem como principal objetivo agregar os resultados obtidos nos artefatos de Backward-From e Forward-From em uma única matriz de rastreabilidade.

# Metodologia

Para o formato da matriz de rastreabilidade será utilizado o mesmo formato do repositório da disciplina de requisitos [Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/rastreabilidade/matriz-geral/) no qual a matriz de rastreabilidade irá possuir 6 colunas:

- **ID**: apresenta o identificador daquele requisito;
- **Descrição**: apresenta a descrição do requisito;
- **Pré-Rastreabilidade**: apresenta a técnica de elicitação que deu origem ao requisito;
- **Implementado?**: indica se o requisito está ou não implementado no aplicativo (Sim, Não ou Parcialmente).
- **Artefatos**: apresenta os artefatos relacionados ao requisito que foram desenvolvidos ao longo do projeto;
- **Elos**: ligação entre os requisitos e artefatos.

# Matriz Geral

Assim, é possível criar a matriz de rastreabilidade representada pela Tabela 1.

<font><p style="text-align: center">**Tabela 1** - Matriz de rastreabilidade do projeto.</p></font>

| **ID** | **Descrição**                   | **Pré-Rastreabilidade**  | **Implementado** | **Artefatos Criados**            | **Elos**       |
| ----- | -------------------------------- | ---------------------- | ----------- | ---------------------------- | ---------- |
| #RF01 | Deve oferecer a possibilidade do usuário acionar a pesquisa na web | [#RDF01](../elicitacao/analise-de-documentos.md), [#RIF01](../elicitacao/analise-de-interface.md) | Sim | [#CN07](../modelagem/cenarios.md#cn07), [#UC07](../modelagem/casos-de-uso.md#uc07), [#LX07](../modelagem//lexicos.md#lx07), [#HU29](../modelagem/historias-de-usuario.md#hu29) | [#RF01](../rastreabilidade/pos-rastreabilidade.md#rf01) |
| #RF02| Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking) | [#RDF02](../elicitacao/analise-de-documentos.md) | Sim | [#CN09](../modelagem/cenarios.md#cn09), [#UC09](../modelagem/casos-de-uso.md#uc09), [#LX09](../modelagem//lexicos.md#lx09), [#HU13](../modelagem/historias-de-usuario.md#hu13),  [#BK01](../modelagem/backlog.md#bk01)| [#RF02](../rastreabilidade/pos-rastreabilidade.md#rf02) |
| #RF03| O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s | [#RDF03](../elicitacao/analise-de-documentos.md), [#RIF01](../elicitacao/analise-de-interface.md), [#RIF05](../elicitacao/analise-de-interface.md), [#RQF01](../elicitacao/questionario.md), [#RQN09](../elicitacao/questionario.md) | Sim | [#CN06](../modelagem/cenarios.md#cn06), [#UC06](../modelagem/casos-de-uso.md#uc06), [#LX06](../modelagem//lexicos.md#lx06), [#HU25](../modelagem/historias-de-usuario.md#hu25), [#BK37](../modelagem/backlog.md#bk37) , [#ES03](../modelagem/especificacao-suplementar.md),  [#CNFR01](../modelagem/nfr-framework.md#cnfr01) | [#RF03](../rastreabilidade/pos-rastreabilidade.md#rf03) |
| #RF04 | Deve possuir a opção de login com conta Google/Apple ID | [#RDF06](../elicitacao/analise-de-documentos.md)| Sim | [#HU41](../modelagem/historias-de-usuario.md#hu41), [#BK15](../modelagem/backlog.md#bk15) | [#RF04](../rastreabilidade/pos-rastreabilidade.md#rf04) |
| #RF05 | Deve salvar chats entre plataformas | [#RDF07](../elicitacao/analise-de-documentos.md) | Sim | [#HU18](../modelagem/historias-de-usuario.md#hu18), [#BK17](../modelagem/backlog.md#bk17) | [#RF05](../rastreabilidade/pos-rastreabilidade.md#rf05) | 
| #RF06 | Melhorar as capacidades de "deep thinking" | [#RDF07](../elicitacao/analise-de-documentos.md) | Não | | [#RF06](../rastreabilidade/pos-rastreabilidade.md#rf06) |
| #RF07 | Deve haver um campo para a interação com a IA | [#ROF01](../elicitacao/observacao.md) | Sim | [#HU03](../modelagem/historias-de-usuario.md#hu03), [#BK18](../modelagem/backlog.md#bk18)  | [#RF07](../rastreabilidade/pos-rastreabilidade.md#rf07) |
| #RF08 | Deve ser possível criar novos chats | [#ROF02](../elicitacao/observacao.md) | Sim | [#HU42](../modelagem/historias-de-usuario.md#hu42), [#BK21](../modelagem/backlog.md#bk21)  | [#RF08](../rastreabilidade/pos-rastreabilidade.md#rf08) |
| #RF09 | Deve ser possível renomear um chat | [#ROF03](../elicitacao/observacao.md) | Sim |[#HU04](../modelagem/historias-de-usuario.md#hu04), [#BK20](../modelagem/backlog.md#bk20) | [#RF09](../rastreabilidade/pos-rastreabilidade.md#rf09) | 
| #RF10 | Os chats já utilizados devem poder ser acessados posteriormente | [#ROF04](../elicitacao/observacao.md) | Sim | [#HU35](../modelagem/historias-de-usuario.md#hu35), [#BK21](../modelagem/backlog.md#bk21) | [#RF10](../rastreabilidade/pos-rastreabilidade.md#rf10) |
| #RF11 | Deve ser possível dar dislike em uma resposta da IA | [#ROF05](../elicitacao/observacao.md) | Sim |[#CN08](../modelagem/cenarios.md#cn08), [#UC08](../modelagem/casos-de-uso.md#uc08), [#LX08](../modelagem/lexicos.md#lx08), [#HU30](../modelagem/historias-de-usuario.md#hu30), [#BK02](../modelagem/backlog.md#bk02) | [#RF11](../rastreabilidade/pos-rastreabilidade.md#rf11) |
| #RF12 | Deve ser possível dar like em uma resposta da IA | [#ROF06](../elicitacao/observacao.md) | Sim | [#CN08](../modelagem/cenarios.md#cn08), [#UC08](../modelagem/casos-de-uso.md#uc08), [#LX08](../modelagem/lexicos.md#lx08), [#HU30](../modelagem/historias-de-usuario.md#hu30), [#BK02](../modelagem/backlog.md#bk02)  | [#RF12](../rastreabilidade/pos-rastreabilidade.md#rf12) |
| #RF13 | Deve ser possível copiar uma resposta da IA | [#ROF07](../elicitacao/observacao.md) | Sim | [#CN08](../modelagem/cenarios.md#cn08), [#UC08](../modelagem/casos-de-uso.md#uc08), [#LX08](../modelagem/lexicos.md#lx08), [#HU30](../modelagem/historias-de-usuario.md#hu30), [#HU29](../modelagem/historias-de-usuario.md#hu29), [#BK22](../modelagem/backlog.md#bk22)  | [#RF13](../rastreabilidade/pos-rastreabilidade.md#rf13) |
| #RF14 | Deve exibir citações de fontes e referências em respostas baseadas em documentos, indicando página, site e/ou trecho extraído. | [#ROF08](../elicitacao/observacao.md), [#RIF06](../elicitacao/analise-de-interface.md), [#RQF22](../elicitacao/questionario.md) | Parcialmente implementado | [#HU36](../modelagem/historias-de-usuario.md#hu36), [#BK03](../modelagem/backlog.md#bk03)  | [#RF14](../rastreabilidade/pos-rastreabilidade.md#rf14) |
| #RF15 | Deve ser possível alterar o idioma do sistema | [#ROF09](../elicitacao/observacao.md) | Sim | [#HU27](../modelagem/historias-de-usuario.md#hu27), [#BK35](../modelagem/backlog.md#bk35)  | [#RF15](../rastreabilidade/pos-rastreabilidade.md#rf15) | 
| #RF16 | Deve ser possível apagar conversas individuais ou de forma geral | [#ROF10](../elicitacao//observacao.md), [#RIF04](../elicitacao/analise-de-interface.md) | Sim | [#HU28](../modelagem/historias-de-usuario.md#hu28), [#BK14](../modelagem/backlog.md#bk14)  | [#RF16](../rastreabilidade/pos-rastreabilidade.md#rf16) |
| #RF17 | Deve ser possível regenerar uma resposta da IA de forma manual ou automática em caso de erro de servidor ou sobrecarga | [#ROF11](../elicitacao/observacao.md), [#RQF09](../elicitacao/questionario.md), [#RQF18](../elicitacao/questionario.md) | Parcialmente implementado | [#CN08](../modelagem/cenarios.md#cn08), [#UC08](../modelagem/casos-de-uso.md#uc08), [#LX08](../modelagem/lexicos.md#lx08), [#HU30](../modelagem/historias-de-usuario.md#hu30), [#BK02](../modelagem/backlog.md#bk02)  | [#RF17](../rastreabilidade/pos-rastreabilidade.md#rf17) |
| #RF18 | O sistema deve exibir respostas formatadas em Markdown em tabelas ou listas complexas, com possibilidade de edição pelo usuário | [#ROF12](../elicitacao/observacao.md), [#RIF03](../elicitacao/analise-de-interface.md), [#RIF13](../elicitacao/analise-de-interface.md), [#RQF15](../elicitacao/questionario.md) | Parcialmente implementado | [#HU23](../modelagem/historias-de-usuario.md#hu23), [#HU34](../modelagem/historias-de-usuario.md#hu34), [#BK26](../modelagem/backlog.md#bk26), [#BK27](../modelagem/backlog.md#bk27)   | [#RF18](../rastreabilidade/pos-rastreabilidade.md#rf18) | 
| #RF19 | Deve ser possível interromper respostas em andamento | [#RIF07](../elicitacao/analise-de-interface.md) | Não | [#CN10](../modelagem/cenarios.md#cn10), [#UC10](../modelagem/casos-de-uso.md#uc10), [#LX10](../modelagem/lexicos.md#lx10), [#HU07](../modelagem//historias-de-usuario.md#hu07), [#HU15](../modelagem/historias-de-usuario.md#hu15), [#BK23](../modelagem/backlog.md#bk23), [#BK24](../modelagem/backlog.md#bk24)   | [#RF19](../rastreabilidade/pos-rastreabilidade.md#rf19) |
| #RF20 | Deve possuir uma API pública | [#RIF08](../elicitacao/analise-de-interface.md) | Não | [#HU31](../modelagem/historias-de-usuario.md#hu31), [#BK41](../modelagem/backlog.md#bk41)  | [#RF20](../rastreabilidade/pos-rastreabilidade.md#rf20) |
| #RF21 | Deve aceitar autenticação via token de acesso | [#RIF09](../elicitacao/analise-de-interface.md) | Não | | [#RF21](../rastreabilidade/pos-rastreabilidade.md#rf21) |
| #RF22 | Deve haver uma confirmação para limpar o histórico | [#RIF14](../elicitacao/analise-de-interface.md) | Não | [#CN13](../modelagem/cenarios.md#cn13), [#UC13](../modelagem/casos-de-uso.md#uc13), [#LX13](../modelagem/lexicos.md#lx13), [#HU02](../modelagem/historias-de-usuario.md#hu02), [#BK09](../modelagem/backlog.md#bk09)  | [#RF22](../rastreabilidade/pos-rastreabilidade.md#rf22) |
| #RF23 | Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita) | [#RQF01](../elicitacao/questionario.md) | Não | [#HU05](../modelagem/historias-de-usuario.md#hu05), [#BK28](../modelagem/backlog.md#bk28)  | [#RF23](../rastreabilidade/pos-rastreabilidade.md#rf23) |
| #RF24 | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256) | [#RQF02](../elicitacao/questionario.md) | Sim | | [#RF24](../rastreabilidade/pos-rastreabilidade.md#rf24) |
| #RF25 | O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização) | [#RQF03](../elicitacao/questionario.md) | Não | [#HU17](../modelagem/historias-de-usuario.md#hu17), [#BK10](../modelagem/backlog.md#bk10), [#BK11](../modelagem/backlog.md#bk11)   | [#RF25](../rastreabilidade/pos-rastreabilidade.md#rf25)|
| #RF26 | Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas | [#RQF04](../elicitacao/questionario.md) | Não | [#HU26](../modelagem/historias-de-usuario.md#hu26), [#BK16](../modelagem/backlog.md#bk16)  | [#RF26](../rastreabilidade/pos-rastreabilidade.md#rf26) |
| #RF27 | Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO | [#RQF06](../elicitacao/questionario.md) | Sim | [#CN05](../modelagem/cenarios.md#cn05), [#UC05](../modelagem/casos-de-uso.md#uc05), [#LX05](../modelagem/lexicos.md#lx05), [#HU19](../modelagem/historias-de-usuario.md#hu19), [#BK29](../modelagem/backlog.md#bk29)  | [#RF27](../rastreabilidade/pos-rastreabilidade.md#rf27) |
| #RF28 | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades | [#RQF07](../elicitacao/questionario.md) | Não | [#CN12](../modelagem/cenarios.md#cn12), [#UC12](../modelagem/casos-de-uso.md#uc12), [#LX12](../modelagem/lexicos.md#lx12), [#HU01](../modelagem/historias-de-usuario.md#hu01), [#BK30](../modelagem/backlog.md#bk30)  | [#RF28](../rastreabilidade/pos-rastreabilidade.md#rf28) |
| #RF29 | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) | [#RQF08](../elicitacao/questionario.md) | Não | [#CN11](../modelagem/cenarios.md#cn11), [#UC11](../modelagem/casos-de-uso.md#uc11), [#LX11](../modelagem/lexicos.md#lx11), [#HU14](../modelagem/historias-de-usuario.md#hu14),  [#BK31](../modelagem/backlog.md#bk31)  | [#RF29](../rastreabilidade/pos-rastreabilidade.md#rf29) |
| #RF30 | Melhorar retenção de contexto em diálogos longos | [#RQF10](../elicitacao/questionario.md) | Parcialmente implementado | [#HU24](../modelagem/historias-de-usuario.md#hu24), [#BK06](../modelagem/backlog.md#bk06)  | [#RF30](../rastreabilidade/pos-rastreabilidade.md#rf30) |
| #RF31 | Implementar memória de contexto persistente entre conversas | [#RQF11](../elicitacao/questionario.md) | Não | [#HU32](../modelagem/historias-de-usuario.md#hu32), [#BK02](../modelagem/backlog.md#bk02)  | [#RF31](../rastreabilidade/pos-rastreabilidade.md#rf31) |
| #RF32 | Permitir escolha de modelos (seleção de diferentes versões/modelos de IA)	 | [#RQF12](../elicitacao/questionario.md) | Não | [#CN04](../modelagem/cenarios.md#cn04), [#UC04](../modelagem/casos-de-uso.md#uc04), [#LX04](../modelagem/lexicos.md#lx04), [#HU20](../modelagem/historias-de-usuario.md#hu20), [#BK07](../modelagem/backlog.md#bk07) | [#RF32](../rastreabilidade/pos-rastreabilidade.md#rf32) |
| #RF33 | Permitir organização de conversas em pastas ou listas por tema ou projeto | [#RQF13](../elicitacao/questionario.md) | Não | [#HU09](../modelagem/historias-de-usuario.md#hu09), [#BK25](../modelagem/backlog.md#bk25)   | [#RF33](../rastreabilidade/pos-rastreabilidade.md#rf33) |
| #RF34 | Implementar comandos de voz para entrada e saída de informações | [#RQF16](../elicitacao/questionario.md) | Não | [#CN03](../modelagem/cenarios.md#cn03), [#UC03](../modelagem/casos-de-uso.md#uc03), [#LX03](../modelagem/lexicos.md#lx03), [#HU12](../modelagem/historias-de-usuario.md#hu12), [#BK32](../modelagem/backlog.md#bk32)  | [#RF34](../rastreabilidade/pos-rastreabilidade.md#rf34) |
| #RF35 | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico | [#RQF17](../elicitacao/questionario.md) | Não | [#HU21](../modelagem/historias-de-usuario.md#hu21), [#BK33](../modelagem/backlog.md#bk33)  | [#RF35](../rastreabilidade/pos-rastreabilidade.md#rf35) |
| #RF36 | Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR | [#RQF20](../elicitacao/questionario.md) | Não | [#HU22](../modelagem/historias-de-usuario.md#hu22), [#BK40](../modelagem/backlog.md#bk40) | [#RF36](../rastreabilidade/pos-rastreabilidade.md#rf36) |
| #RF37 | Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas | [#RQF14](../elicitacao/questionario.md) | Não | [#CN03](../modelagem/cenarios.md#cn03), [#UC03](../modelagem/casos-de-uso.md#uc03), [#LX03](../modelagem/lexicos.md#lx03), [#HU11](../modelagem/historias-de-usuario.md#hu11), [#BK42](../modelagem/backlog.md#bk42)  | [#RF37](../rastreabilidade/pos-rastreabilidade.md#rf37) |
| #RF38 | Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização) | [#RQF23](../elicitacao/questionario.md) | Não | [#CN14](../modelagem/cenarios.md#cn14), [#UC14](../modelagem/casos-de-uso.md#uc14), [#LX14](../modelagem/lexicos.md#lx14), [#HU33](../modelagem/historias-de-usuario.md#hu33), [#BK08](../modelagem/backlog.md#bk08)  | [#RF38](../rastreabilidade/pos-rastreabilidade.md#rf38) |
| #RN01 | Deve fazer o uso da arquitetura DeepSeek-V3 | [#RDN04](../elicitacao/analise-de-documentos.md) | Sim | [#ES07](../modelagem/especificacao-suplementar.md#es07), [#CNFR12](../modelagem/nfr-framework.md#cnfr12) | [#RN01](../rastreabilidade/pos-rastreabilidade.md#rn01) |
| #RN02 | Deve possuir versões para Android e IOS | [#RDN05](../elicitacao/analise-de-documentos.md) | Sim | [#ES07](../modelagem/especificacao-suplementar.md#es07), [#CNFR09](../modelagem/nfr-framework.md#cnfr09) | [#RN02](../rastreabilidade/pos-rastreabilidade.md#rn02) |
| #RN03 | Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar) | [#RIN10](../elicitacao/analise-de-interface.md) |Não | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#CNFR11](../modelagem/nfr-framework.md#cnfr11) | [#RN03](../rastreabilidade/pos-rastreabilidade.md#rn03) |
| #RN04 | Deve fazer a exclusão automática de dados de upload | [#RIN10](../elicitacao/analise-de-interface.md) | Não | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#CNFR08](../modelagem/nfr-framework.md#cnfr08) | [#RN04](../rastreabilidade/pos-rastreabilidade.md#rn04) |
| #RN05 | A interface deve seguir diretrizes de usabilidade e acessibilidade | [#RIN12](../elicitacao/analise-de-interface.md), [#RQF05](../elicitacao/questionario.md) | Não | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01), [#CNFR23](../modelagem/nfr-framework.md#cnfr23) | [#RN05](../rastreabilidade/pos-rastreabilidade.md#rn05) |
| #RN06 | Em caso de falha, deve retornar mensagens de erro claras | [#RIN15](../elicitacao/analise-de-interface.md) | Sim | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#CNFR24](../modelagem/nfr-framework.md#cnfr24) | [#RN06](../rastreabilidade/pos-rastreabilidade.md#rn06) |
| #RN07 | O sistema deve suportar múltiplas requisições simultâneas sem degradação | [#RIN16](../elicitacao/analise-de-interface.md) | Sim | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#ES06](../modelagem/especificacao-suplementar.md#es06), [#CNFR05](../modelagem/nfr-framework.md#cnfr05) | [#RN07](../rastreabilidade/pos-rastreabilidade.md#rn07) |
| #RN08 | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples | [#RIN17](../elicitacao/analise-de-interface.md), [#RQN04](../elicitacao/questionario.md) | Parcialmente implementado | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#ES06](../modelagem/especificacao-suplementar.md#es06), [#CNFR04](../modelagem/nfr-framework.md#cnfr04) | [#RN08](../rastreabilidade/pos-rastreabilidade.md#rn08) |
| #RN09 | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados | [#RQN01](../elicitacao/questionario.md) | Não | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES08](../modelagem/especificacao-suplementar.md#es08), [#CNFR10](../modelagem/nfr-framework.md#cnfr10) | [#RN09](../rastreabilidade/pos-rastreabilidade.md#rn09) |
| #RN10 | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos | [#RQN02](../elicitacao/questionario.md) | Não | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES08](../modelagem/especificacao-suplementar.md#es08), [#CNFR15](../modelagem/nfr-framework.md#cnfr15) | [#RN10](../rastreabilidade/pos-rastreabilidade.md#rn10) |
| #RN11 | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos | [#RQN02](../elicitacao/questionario.md) | Não | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#CNFR29](../modelagem/nfr-framework.md#cnfr29) | [#RN11](../rastreabilidade/pos-rastreabilidade.md#rn11) |
| #RN12 | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas | [#RQN05](../elicitacao/questionario.md) | Não | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#CNFR16](../modelagem/nfr-framework.md#cnfr16) | [#RN12](../rastreabilidade/pos-rastreabilidade.md#rn12) |
| #RN13 | Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras | [#RQN06](../elicitacao/questionario.md) | Parcialmente implementado | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01), [#CNFR17](../modelagem/nfr-framework.md#cnfr17) | [#RN13](../rastreabilidade/pos-rastreabilidade.md#rn13) |
| #RN14 | Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras | [#RQN07](../elicitacao/questionario.md) | Não | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01), [#CNFR18](../modelagem/nfr-framework.md#cnfr18) | [#RN14](../rastreabilidade/pos-rastreabilidade.md#rn14) |
| #RN15 | Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras | [#RQN08](../elicitacao/questionario.md) | Não | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01), [#CNFR19](../modelagem/nfr-framework.md#cnfr19) | [#RN15](../rastreabilidade/pos-rastreabilidade.md#rn15) |

Autor: Luiz

Com a Tabela 2, é possível encontrar os códigos utilizados ao longo do desenvolvimento dos artefatos e seus significados.

<font><p style="text-align: center">**Tabela 2** - Códigos utilizados na Tabela 1 e seus significados.</p></font>

|  **Identificador** |                                                 **Significado**                                                  |
| ------------------ | ---------------------------------------------------------------------------------------------------------------- |
| **#RFXX**          | Código para um requisito funcional |
| **#RNXX**           | Código para um requisito não funcional |
| **#RDFXXX**         | Código para um requisito funcional elicitado com a técnica de [análise de documentos](../elicitacao/analise-de-documentos.md) |
| **#RDNXXX**         | Código para um requisito não funcional elicitado com a técnica de [análise de documentos](../elicitacao/analise-de-documentos.md) |
| **#RIFXXX**         | Código para um requisito funcional elicitado com a técnica de [análise de interface](../elicitacao/analise-de-interface.md) |
| **#RINXXX**         | Código para um requisito não funcional elicitado com a técnica de [análise de interface](../elicitacao/analise-de-interface.md) |
| **#RQFXX**          | Código para um requisito funcional elicitado com a técnica de [questionário](../elicitacao/questionario.md) |
| **#RQNXX**          | Código para um requisito não funcional elicitado com a técnica de [questionário](../elicitacao/questionario.md) |
| **#ROFXX**          | Código para um requisito funcional elicitado com a técnica de [observação](../elicitacao/observacao.md) |
| **#RONXX**          | Código para um requisito não funcional elicitado com a técnica de [observação](../elicitacao/observacao.md) |
| **#UCXX**           | Representa  uma tabela de caso de uso desenvolvida para o artefato [casos de uso](../modelagem/casos-de-uso.md) |
| **#CNXX**           | Representa um cenário desenvolvido para o artefato [cenários](../modelagem/cenarios.md) |
| **#LXXX**           | Representa uma tabela de léxicos para um caso de uso no artefato [léxicos](../modelagem/lexicos.md) |
| **#ESXX**           | Representa um tópico no artefato de [especificação suplementar](../modelagem/especificacao-suplementar.md) |
| **#HUXX**          | Representa história de usuário no artefato [histórias de usuário](../modelagem/historias-de-usuario.md) |
| **#BKXX**          | Representa um tópico no artefato [backlog](../modelagem/backlog.md) |
| **#CNFRXX**        | Representa um cartão de especificação no artefato [NFR Framework](../modelagem/nfr-framework.md) |

Autor: Luiz

---

# Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 12.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 04/06/2025.[`Foto da referência`](../images/matriz-geral/definicao-matriz-geral.png)


> <a id="REF2" href="#anchor_2">2.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 12.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 04/06/2025.[`Foto da referência`](../images/matriz-geral/componentes-matriz-geral.png)

> <a id="REF3" href="#anchor_3">3.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 12-13.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 04/06/2025.[`Foto da referência`](../images/matriz-geral/explicacao-componentes-matriz-geral.png)

> <a id="REF4" href="#anchor_4">4.</a> MELO, Arthur. Matriz Geral. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/rastreabilidade/matriz-geral/>. Acesso em: 04/06/2025.

---

# Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 04/06/2025 |  1.0   | (#MG01) Criação do documento de matriz geral.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 04/06/2025 |  1.1  | (#MG01) Adição da introdução, objetivos, metodologia, criação da matriz geral. Adição dos requisitos RF01-RF03| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 05/06/2025 |  1.2  | (#MG01) Explicação dos IDs presentes na matriz de rastreabilidade.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 06/06/2025 |  1.3  | (#MG01) Adição dos requisitos RF04-RF13.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 06/06/2025 |  1.4  | (#MG01) Adição dos requisitos RF14-RF38.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 06/06/2025 |  1.5  | (#MG01) Adição dos requisitos RN01-RN15.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.6  | (#MG01) Adição da tabela com os significados dos identificadores utilizados na matriz de rastreabilidade.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.7  | (#MG01) Adição dos hiperlinks dos tópicos do backlog na coluna "artefatos criados".| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 07/06/2025 |  1.8  | (#MG01) Adição dos hiperlinks dos elos do documento de pós-rastreabilidade.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@Fabio`](https://github.com/fabinsz)   |
| 08/06/2025 |  1.9  | (#MG01) Correção nos hiperlinks do arquivo.| [`@Luiz`](https://github.com/luizfaria1989)   | [`@`](https://github.com/)   |
