# Introdução

A rastreabilidade é uma característica de sistemas, nos quais requisitos são ligados às suas respectivas fontes e aos artefatos que foram criados durante o desenvolvimento do sistema.

A rastreabilidade pode ser dividida nos tipos: backward-from, forward-from, backward-to, forward-to.

- Rastreabilidade forward-from: liga os requisitos aos artefatos de desenho e implementação.
- Rastreabilidade backward-from: liga os requisitos às suas fontes.
- Rastreabilidade forward-to: liga os documentos do plano de negócio aos requisitos.
- Rastreabilidade backward-to: liga os artefatos de desenho e implementação aos requisitos.

# Objetivos

Analisar a rastreabilidade forward-from, evidenciando os artefatos que foram criados a partir de cada um dos requisitos elicitados. A partir da matriz criada, é possível que os stakeholders acompanhem o desenvolvimento de cada um dos requisitos elicitados.

# Metodologia

Para fazer a rastreabilidade forward-from, fizemos uma matriz onde a primeira e segunda colunas se referem ao requisito enquanto as colunas seguintes se referem a cada um dos tipos de artefatos (Cenários, Léxicos, Casos de Uso, Histórias de Usuário, entre outros).

# Rastreabilidade Forward-from

## Legenda da matriz

<font><p style="text-align: center">**Tabela 1** - Legenda da matriz.</p></font>


| Sigla  |          Técnica de Modelagem       |                      
| ---- | --------------------------------- | 
| UCXX | Casos de uso (User case) |
| HUXX   | Histórias de Usuário |
| CNFRXX | NFR Framework |
| ESXX | Especificação Suplementar |
| CNXX | Cenário |
| LXXX | Léxico |

## Matriz de rastreabilidade

| ID | Descrição | UC | HU | CNFR | ES | CN | L |
|:---|:---|:---|:---|:---|:---|:---|:---|
| #RF01 | Deve oferecer a possibilidade do usuário acionar a pesquisa na web | [#UC07](../modelagem/casos-de-uso.md#uc07) | [#HU29](../modelagem/historias-de-usuario.md#hu29) | | | [#CN07](../modelagem/cenarios.md#cn07) | [#LX07](../modelagem//lexicos.md#lx07) |
| #RF02 | Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking) | [#UC09](../modelagem/casos-de-uso.md#uc09) | [#HU13](../modelagem/historias-de-usuario.md#hu13) | | | [#CN09](../modelagem/cenarios.md#cn09) | [#LX09](../modelagem//lexicos.md#lx09) |
| #RF03 | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s | [#UC06](../modelagem/casos-de-uso.md#uc06) | [#HU25](../modelagem/historias-de-usuario.md#hu25) | [#CNFR01](../modelagem/nfr-framework.md#cnfr01) | [#ES03](../modelagem/especificacao-suplementar.md) | [#CN06](../modelagem/cenarios.md#cn06) | [#LX06](../modelagem//lexicos.md#lx06) |
| #RF04 | Deve possuir a opção de login com conta Google/Apple ID | | [#HU41](../modelagem/historias-de-usuario.md#hu41) | | | | |
| #RF05 | Deve salvar chats entre plataformas | | [#HU18](../modelagem/historias-de-usuario.md#hu18) | | | | |
| #RF06 | Melhorar as capacidades de "deep thinking" | | | | | | |
| #RF07 | Deve haver um campo para a interação com a IA | | [#HU03](../modelagem/historias-de-usuario.md#hu03) | | | | |
| #RF08 | Deve ser possível criar novos chats | | [#HU42](../modelagem/historias-de-usuario.md#hu42) | | | | |
| #RF09 | Deve ser possível renomear um chat | | [#HU04](../modelagem/historias-de-usuario.md#hu04) | | | | |
| #RF10 | Os chats já utilizados devem poder ser acessados posteriormente | | [#HU35](../modelagem/historias-de-usuario.md#hu35) | | | | |
| #RF11 | Deve ser possível dar dislike em uma resposta da IA | [#UC08](../modelagem/casos-de-uso.md#uc08) | [#HU30](../modelagem/historias-de-usuario.md#hu30) | | | [#CN08](../modelagem/cenarios.md#cn08) | [#LX08](../modelagem/lexicos.md#lx08) |
| #RF12 | Deve ser possível dar like em uma resposta da IA | [#UC08](../modelagem/casos-de-uso.md#uc08) | [#HU30](../modelagem/historias-de-usuario.md#hu30) | | | [#CN08](../modelagem/cenarios.md#cn08) | [#LX08](../modelagem/lexicos.md#lx08) |
| #RF13 | Deve ser possível copiar uma resposta da IA | [#UC08](../modelagem/casos-de-uso.md#uc08) | [#HU30](../modelagem/historias-de-usuario.md#hu30), [#HU29](../modelagem/historias-de-usuario.md#hu29) | | | [#CN08](../modelagem/cenarios.md#cn08) | [#LX08](../modelagem/lexicos.md#lx08) |
| #RF14 | Deve exibir citações de fontes e referências em respostas baseadas em documentos, indicando página, site e/ou trecho extraído. | | [#HU36](../modelagem/historias-de-usuario.md#hu36) | | | | |
| #RF15 | Deve ser possível alterar o idioma do sistema | | [#HU27](../modelagem/historias-de-usuario.md#hu27) | | | | |
| #RF16 | Deve ser possível apagar conversas individuais ou de forma geral | | [#HU28](../modelagem/historias-de-usuario.md#hu28) | | | | |
| #RF17 | Deve ser possível regenerar uma resposta da IA de forma manual ou automática em caso de erro de servidor ou sobrecarga | [#UC08](../modelagem/casos-de-uso.md#uc08) | [#HU30](../modelagem/historias-de-usuario.md#hu30) | | | [#CN08](../modelagem/cenarios.md#cn08) | [#LX08](../modelagem/lexicos.md#lx08) |
| #RF18 | O sistema deve exibir respostas formatadas em Markdown em tabelas ou listas complexas, com possibilidade de edição pelo usuário | | [#HU23](../modelagem/historias-de-usuario.md#hu23), [#HU34](../modelagem/historias-de-usuario.md#hu34) | | | | |
| #RF19 | Deve ser possível interromper respostas em andamento | [#UC10](../modelagem/casos-de-uso.md#uc10) | [#HU07](../modelagem//historias-de-usuario.md#hu07), [#HU15](../modelagem/historias-de-usuario.md#hu15) | | | [#CN10](../modelagem/cenarios.md#cn10) | [#LX10](../modelagem/lexicos.md#lx10) |
| #RF20 | Deve possuir uma API pública | | [#HU31](../modelagem/historias-de-usuario.md#hu31) | | | | |
| #RF21 | Deve aceitar autenticação via token de acesso | | | | | | |
| #RF22 | Deve haver uma confirmação para limpar o histórico | [#UC13](../modelagem/casos-de-uso.md#uc13) | [#HU02](../modelagem/historias-de-usuario.md#hu02) | | | [#CN13](../modelagem/cenarios.md#cn13) | [#LX13](../modelagem/lexicos.md#lx13) |
| #RF23 | Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita) | | [#HU05](../modelagem/historias-de-usuario.md#hu05) | | | | |
| #RF24 | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256) | | | | | | |
| #RF25 | O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização) | | [#HU17](../modelagem/historias-de-usuario.md#hu17) | | | | |
| #RF26 | Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas | | [#HU26](../modelagem/historias-de-usuario.md#hu26) | | | | |
| #RF27 | Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO | [#UC05](../modelagem/casos-de-uso.md#uc05) | [#HU19](../modelagem/historias-de-usuario.md#hu19) | | | [#CN05](../modelagem/cenarios.md#cn05) | [#LX05](../modelagem/lexicos.md#lx05) |
| #RF28 | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades | [#UC12](../modelagem/casos-de-uso.md#uc12) | [#HU01](../modelagem/historias-de-usuario.md#hu01) | | | [#CN12](../modelagem/cenarios.md#cn12) | [#LX12](../modelagem/lexicos.md#lx12) |
| #RF29 | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) | [#UC11](../modelagem/casos-de-uso.md#uc11) | [#HU14](../modelagem/historias-de-usuario.md#hu14) | | | [#CN11](../modelagem/cenarios.md#cn11) | [#LX11](../modelagem/lexicos.md#lx11) |
| #RF30 | Melhorar retenção de contexto em diálogos longos | | [#HU24](../modelagem/historias-de-usuario.md#hu24) | | | | |
| #RF31 | Implementar memória de contexto persistente entre conversas | | [#HU32](../modelagem/historias-de-usuario.md#hu32) | | | | |
| #RF32 | Permitir escolha de modelos (seleção de diferentes versões/modelos de IA) | [#UC04](../modelagem/casos-de-uso.md#uc04) | [#HU20](../modelagem/historias-de-usuario.md#hu20) | | | [#CN04](../modelagem/cenarios.md#cn04) | [#LX04](../modelagem/lexicos.md#lx04) |
| #RF33 | Permitir organização de conversas em pastas ou listas por tema ou projeto | | [#HU09](../modelagem/historias-de-usuario.md#hu09) | | | | |
| #RF34 | Implementar comandos de voz para entrada e saída de informações | [#UC03](../modelagem/casos-de-uso.md#uc03) | [#HU12](../modelagem/historias-de-usuario.md#hu12) | | | [#CN03](../modelagem/cenarios.md#cn03) | [#LX03](../modelagem/lexicos.md#lx03) |
| #RF35 | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico | | [#HU21](../modelagem/historias-de-usuario.md#hu21) | | | | |
| #RF36 | Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR | | [#HU22](../modelagem/historias-de-usuario.md#hu22) | | | | |
| #RF37 | Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas | [#UC03](../modelagem/casos-de-uso.md#uc03) | [#HU11](../modelagem/historias-de-usuario.md#hu11) | | | [#CN03](../modelagem/cenarios.md#cn03) | [#LX03](../modelagem/lexicos.md#lx03) |
| #RF38 | Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização) | [#UC14](../modelagem/casos-de-uso.md#uc14) | [#HU33](../modelagem/historias-de-usuario.md#hu33) | | | [#CN14](../modelagem/cenarios.md#cn14) | [#LX14](../modelagem/lexicos.md#lx14) |
| #RN01 | Deve fazer o uso da arquitetura DeepSeek-V3 | | | [#CNFR12](../modelagem/nfr-framework.md#cnfr12) | [#ES07](../modelagem/especificacao-suplementar.md#es07) | | |
| #RN02 | Deve possuir versões para Android e IOS | | | [#CNFR09](../modelagem/nfr-framework.md#cnfr09) | [#ES07](../modelagem/especificacao-suplementar.md#es07) | | |
| #RN03 | Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar) | | | [#CNFR11](../modelagem/nfr-framework.md#cnfr11) | [#ES05](../modelagem/especificacao-suplementar.md#es05) | | |
| #RN04 | Deve fazer a exclusão automática de dados de upload | | | [#CNFR08](../modelagem/nfr-framework.md#cnfr08) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02) | | |
| #RN05 | A interface deve seguir diretrizes de usabilidade e acessibilidade | | | [#CNFR23](../modelagem/nfr-framework.md#cnfr23) | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01) | | |
| #RN06 | Em caso de falha, deve retornar mensagens de erro claras | | | [#CNFR24](../modelagem/nfr-framework.md#cnfr24) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02) | | |
| #RN07 | O sistema deve suportar múltiplas requisições simultâneas sem degradação | | | [#CNFR05](../modelagem/nfr-framework.md#cnfr05) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#ES06](../modelagem/especificacao-suplementar.md#es06) | | |
| #RN08 | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples | | | [#CNFR04](../modelagem/nfr-framework.md#cnfr04) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02), [#ES06](../modelagem/especificacao-suplementar.md#es06) | | |
| #RN09 | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados | | | [#CNFR10](../modelagem/nfr-framework.md#cnfr10) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES08](../modelagem/especificacao-suplementar.md#es08) | | |
| #RN10 | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos | | | [#CNFR15](../modelagem/nfr-framework.md#cnfr15) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES08](../modelagem/especificacao-suplementar.md#es08) | | |
| #RN11 | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos | | | [#CNFR29](../modelagem/nfr-framework.md#cnfr29) | [#ES05](../modelagem/especificacao-suplementar.md#es05) | | |
| #RN12 | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas | | | [#CNFR16](../modelagem/nfr-framework.md#cnfr16) | [#ES05](../modelagem/especificacao-suplementar.md#es05), [#ES02](../modelagem/especificacao-suplementar.md#es02) | | |
| #RN13 | Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras | | | [#CNFR17](../modelagem/nfr-framework.md#cnfr17) | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01) | | |
| #RN14 | Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras | | | [#CNFR18](../modelagem/nfr-framework.md#cnfr18) | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01) | | |
| #RN15 | Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras | | | [#CNFR19](../modelagem/nfr-framework.md#cnfr19) | [#ES04](../modelagem/especificacao-suplementar.md#es04), [#ES01](../modelagem/especificacao-suplementar.md#es01) | | |

Autor: Ana Clara

---

# Referência Bibliográfica

> SERRANO, Milene; SERRANO, Maurício. **Requisitos – Aula 26**. UnB, 2025. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096178/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 22 jun. 2025. [`Foto da referência`](../images/tipos-rastreabilidade/forward-from.png)

# Histórico de Versões

| Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 22/06/2025 |  1.0   | (#R01) Documentação da matriz de rastreabilidade forward-from| [`@Ana Clara`](https://github.com/anabborges)   | [`@`](https://github.com/)   |