# Introdução

A rastreabilidade é uma característica de sistemas, nos quais requisitos são ligados às suas respectivas fontes e aos artefatos que foram criados durante o desenvolvimento do sistema.

A rastreabilidade pode ser dividida nos tipos: backward-from, forward-from, backward-to, forward-to.

- Rastreabilidade forward-from: liga os requisitos aos artefatos de desenho e implementação.
- Rastreabilidade backward-from: liga os requisitos às suas fontes.
- Rastreabilidade forward-to: liga os documentos do plano de negócio aos requisitos.
- Rastreabilidade backward-to: liga os artefatos de desenho e implementação aos requisitos.

# Objetivos

Analisar a rastreabilidade backward-from, evidenciando qual foi a fonte de cada um dos requisitos. Dessa forma, a partir da matriz de rastreabilidade os stakeholders poderão entender o porquê de cada requisito ter sido elicitado.

# Metodologia

Para fazer a rastrabilidade backward-from, fizemos uma matriz onde a primeira e segunda colunas se referem ao requisito enquanto a terceira coluna indica a fonte do requisito e a última coluna se o requisito foi implementado ou não.

# Rastreabilidade Backward-from

## Legenda da matriz

<font><p style="text-align: center">**Tabela 1** - Códigos utilizados na Tabela 2 e seus significados.</p></font>

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

## Matriz de rastreabilidade

| ID | Descrição | Pré-Rastreabilidade | Implementado |
|:---|:---|:---|:---|
| #RF01 | Deve oferecer a possibilidade do usuário acionar a pesquisa na web | [#RDF01](../elicitacao/analise-de-documentos.md), [#RIF01](../elicitacao/analise-de-interface.md) | Sim |
| #RF02 | Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking) | [#RDF02](../elicitacao/analise-de-documentos.md) | Sim |
| #RF03 | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s | [#RDF03](../elicitacao/analise-de-documentos.md), [#RIF01](../elicitacao/analise-de-interface.md), [#RIF05](../elicitacao/analise-de-interface.md), [#RQF01](../elicitacao/questionario.md), [#RQN09](../elicitacao/questionario.md) | Sim |
| #RF04 | Deve possuir a opção de login com conta Google/Apple ID | [#RDF06](../elicitacao/analise-de-documentos.md) | Sim |
| #RF05 | Deve salvar chats entre plataformas | [#RDF07](../elicitacao/analise-de-documentos.md) | Sim |
| #RF06 | Melhorar as capacidades de "deep thinking" | [#RDF07](../elicitacao/analise-de-documentos.md) | Não |
| #RF07 | Deve haver um campo para a interação com a IA | [#ROF01](../elicitacao/observacao.md) | Sim |
| #RF08 | Deve ser possível criar novos chats | [#ROF02](../elicitacao/observacao.md) | Sim |
| #RF09 | Deve ser possível renomear um chat | [#ROF03](../elicitacao/observacao.md) | Sim |
| #RF10 | Os chats já utilizados devem poder ser acessados posteriormente | [#ROF04](../elicitacao/observacao.md) | Sim |
| #RF11 | Deve ser possível dar dislike em uma resposta da IA | [#ROF05](../elicitacao/observacao.md) | Sim |
| #RF12 | Deve ser possível dar like em uma resposta da IA | [#ROF06](../elicitacao/observacao.md) | Sim |
| #RF13 | Deve ser possível copiar uma resposta da IA | [#ROF07](../elicitacao/observacao.md) | Sim |
| #RF14 | Deve exibir citações de fontes e referências em respostas baseadas em documentos, indicando página, site e/ou trecho extraído. | [#ROF08](../elicitacao/observacao.md), [#RIF06](../elicitacao/analise-de-interface.md), [#RQF22](../elicitacao/questionario.md) | Parcialmente implementado |
| #RF15 | Deve ser possível alterar o idioma do sistema | [#ROF09](../elicitacao/observacao.md) | Sim |
| #RF16 | Deve ser possível apagar conversas individuais ou de forma geral | [#ROF10](../elicitacao//observacao.md), [#RIF04](../elicitacao/analise-de-interface.md) | Sim |
| #RF17 | Deve ser possível regenerar uma resposta da IA de forma manual ou automática em caso de erro de servidor ou sobrecarga | [#ROF11](../elicitacao/observacao.md), [#RQF09](../elicitacao/questionario.md), [#RQF18](../elicitacao/questionario.md) | Parcialmente implementado |
| #RF18 | O sistema deve exibir respostas formatadas em Markdown em tabelas ou listas complexas, com possibilidade de edição pelo usuário | [#ROF12](../elicitacao/observacao.md), [#RIF03](../elicitacao/analise-de-interface.md), [#RIF13](../elicitacao/analise-de-interface.md), [#RQF15](../elicitacao/questionario.md) | Parcialmente implementado |
| #RF19 | Deve ser possível interromper respostas em andamento | [#RIF07](../elicitacao/analise-de-interface.md) | Não |
| #RF20 | Deve possuir uma API pública | [#RIF08](../elicitacao/analise-de-interface.md) | Não |
| #RF21 | Deve aceitar autenticação via token de acesso | [#RIF09](../elicitacao/analise-de-interface.md) | Não |
| #RF22 | Deve haver uma confirmação para limpar o histórico | [#RIF14](../elicitacao/analise-de-interface.md) | Não |
| #RF23 | Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita) | [#RQF01](../elicitacao/questionario.md) | Não |
| #RF24 | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256) | [#RQF02](../elicitacao/questionario.md) | Sim |
| #RF25 | O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização) | [#RQF03](../elicitacao/questionario.md) | Não |
| #RF26 | Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas | [#RQF04](../elicitacao/questionario.md) | Não |
| #RF27 | Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO | [#RQF06](../elicitacao/questionario.md) | Sim |
| #RF28 | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades | [#RQF07](../elicitacao/questionario.md) | Não |
| #RF29 | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) | [#RQF08](../elicitacao/questionario.md) | Não |
| #RF30 | Melhorar retenção de contexto em diálogos longos | [#RQF10](../elicitacao/questionario.md) | Parcialmente implementado |
| #RF31 | Implementar memória de contexto persistente entre conversas | [#RQF11](../elicitacao/questionario.md) | Não |
| #RF32 | Permitir escolha de modelos (seleção de diferentes versões/modelos de IA) | [#RQF12](../elicitacao/questionario.md) | Não |
| #RF33 | Permitir organização de conversas em pastas ou listas por tema ou projeto | [#RQF13](../elicitacao/questionario.md) | Não |
| #RF34 | Implementar comandos de voz para entrada e saída de informações | [#RQF16](../elicitacao/questionario.md) | Não |
| #RF35 | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico | [#RQF17](../elicitacao/questionario.md) | Não |
| #RF36 | Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR | [#RQF20](../elicitacao/questionario.md) | Não |
| #RF37 | Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas | [#RQF14](../elicitacao/questionario.md) | Não |
| #RF38 | Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização) | [#RQF23](../elicitacao/questionario.md) | Não |
| #RN01 | Deve fazer o uso da arquitetura DeepSeek-V3 | [#RDN04](../elicitacao/analise-de-documentos.md) | Sim |
| #RN02 | Deve possuir versões para Android e IOS | [#RDN05](../elicitacao/analise-de-documentos.md) | Sim |
| #RN03 | Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar) | [#RIN10](../elicitacao/analise-de-interface.md) | Não |
| #RN04 | Deve fazer a exclusão automática de dados de upload | [#RIN10](../elicitacao/analise-de-interface.md) | Não |
| #RN05 | A interface deve seguir diretrizes de usabilidade e acessibilidade | [#RIN12](../elicitacao/analise-de-interface.md), [#RQF05](../elicitacao/questionario.md) | Não |
| #RN06 | Em caso de falha, deve retornar mensagens de erro claras | [#RIN15](../elicitacao/analise-de-interface.md) | Sim |
| #RN07 | O sistema deve suportar múltiplas requisições simultâneas sem degradação | [#RIN16](../elicitacao/analise-de-interface.md) | Sim |
| #RN08 | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples | [#RIN17](../elicitacao/analise-de-interface.md), [#RQN04](../elicitacao/questionario.md) | Parcialmente implementado |
| #RN09 | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados | [#RQN01](../elicitacao/questionario.md) | Não |
| #RN10 | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos | [#RQN02](../elicitacao/questionario.md) | Não |
| #RN11 | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos | [#RQN02](../elicitacao/questionario.md) | Não |
| #RN12 | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas | [#RQN05](../elicitacao/questionario.md) | Não |
| #RN13 | Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras | [#RQN06](../elicitacao/questionario.md) | Parcialmente implementado |
| #RN14 | Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras | [#RQN07](../elicitacao/questionario.md) | Não |
| #RN15 | Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras | [#RQN08](../elicitacao/questionario.md) | Não |

Autor: Ana Clara

---

# Referência Bibliográfica

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 26**. UnB, 2025. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096178/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 22 jun. 2025. [`Foto da referência`](../images/tipos-rastreabilidade/backward-from.png)

# Histórico de Versões

| Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/06/2025 |  1.0   | (#R01) Documentação da matriz de rastreabilidade backward-from| [`@Ana Clara`](https://github.com/anabborges)   | [`@Luiz`](https://github.com/luizfaria1989)   |
