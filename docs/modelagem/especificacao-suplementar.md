# Especificação Suplementar

## Introdução

A **Especificação Suplementar** é um documento redigido em linguagem natural que reúne todos os requisitos de um sistema que não foram plenamente capturados pelos casos de uso. Ela complementa o modelo de casos de uso ao detalhar necessidades adicionais, tais como:

* **Requisitos legais e regulamentares**, incluindo conformidade com normas e padrões de aplicativos;
* **Atributos de qualidade**, como **Usabilidade**, **Confiabilidade**, **Desempenho**, **Manutenibilidade** (Suportabilidade) e **Segurança**;
* **Outros requisitos técnicos**, abrangendo sistemas e ambientes operacionais suportados, requisitos de compatibilidade e restrições de design.

A adoção da abordagem **FURPS+** (Functionality, Usability, Reliability, Performance, Supportability, mais fatores) orienta a identificação e a organização desses requisitos, garantindo cobertura completa dos aspectos funcionais e de qualidade da aplicação.

---

## Finalidade

A finalidade deste artefato é definir, de forma clara e estruturada, requisitos suplementares do **DeepSeek**, assegurando que atributos de qualidade, restrições de projeto e regras de negócio estejam documentados para orientar o desenvolvimento e a validação do sistema.

---

## Usabilidade

Nessa seção são apresentados requisitos que afetam a usabilidade do sistema, ou seja, que se referem a forma de o usuário interagir com o sistema.

**Autor: [Ana Clara](https://github.com/anabborges)**

<font><p style="text-align: center">**Tabela xx** - Requisitos de Usabilidade.</p></font>

| CASO DE USO |     ID     | Descrição |
|-------------| ---------- |-----------|
|             |   #RF04    | Deve possuir a opção de login com conta Google/Apple ID |
|             |   #RF07    | Deve haver um campo para a interação com a IA |
|             |   #RF08    | Deve ser possível criar novos chats |
|             |   #RF09    | Deve ser possível renomear um chat |
|             |   #RF10    | Os chats já utilizados devem poder ser acessados posteriormente |
|    #UC03         |   #RF11    | Deve ser possível dar dislike em uma resposta da IA |
|    #UC03         |   #RF12    | Deve ser possível dar like em uma resposta da IA |
|     #UC03        |   #RF13    | Deve ser possível copiar uma resposta da IA |
|             |   #RF15    | Deve ser possível alterar o idioma do sistema |
|             |   #RF16    | Deve ser possível apagar conversas individuais ou de forma geral |
|             |   #RF22    | Deve haver uma confirmação para limpar o histórico |
|             |   #RF23    | Deve suportar busca incremental (exibição de sugestões em tempo real conforme o usuário digita) |
|             |   #RF27    | Deve oferecer modo escuro e claro, com configuração manual e sincronização automática com o SO |
|             |   #RF28    | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades |
|             |   #RF33    | Permitir organização de conversas em pastas ou listas por tema ou projeto |
|             |   #RF34    | Implementar comandos de voz para entrada e saída de informações |
|             |   #RF35    | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico |
|             |   #RF36    | Fornecer, na interface de envio de imagens, instruções claras e contextualizadas sobre OCR |
|             |   #RN05    | A interface deve seguir diretrizes de usabilidade e acessibilidade |
|             |   #RN13    | Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras |
|             |   #RN14    | Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras |
|             |   #RN15    | Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras |

---

## Confiabilidade

Nessa seção são citados os requisitos referentes à confiabilidade do sistema.

**Autor: [Ana Clara](https://github.com/anabborges)**

<font><p style="text-align: center">**Tabela xx** - Requisitos de Confiabilidade.</p></font>

| CASO DE USO |     ID     | Descrição |
|-------------| ---------- |-----------|
|     #UC01        |   #RF03    | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s |
|      #UC03       |   #RF17    | Deve ser possível regenerar uma resposta da IA de forma manual ou automática em caso de erro de servidor ou sobrecarga |
|             |   #RF24    | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256) |
|             |   #RF25    | O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização) |
|             |   #RF26    | Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas |
|  #UC06           |   #RF29    | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) |
|             |   #RF30    | Melhorar retenção de contexto em diálogos longos |
|             |   #RF31    | Implementar memória de contexto persistente entre conversas |
|             |   #RN03    | Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar) |
|             |   #RN04    | Deve fazer a exclusão automática de dados de upload |
|      #UC01       |   #RN06    | Em caso de falha, deve retornar mensagens de erro claras |
|       #UC04      |   #RN07    | O sistema deve suportar múltiplas requisições simultâneas sem degradação |
|      #UC01       |   #RN08    | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples |
|             |   #RN09    | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados |
|             |   #RN10    | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos |
|             |   #RN11    | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos |
|             |   #RN12    | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas |

---

## Desempenho

**Autor: [Luiz](https://github.com/luizfaria1989)**

O desempenho se refere as condições em que os requisitos devem operar. Apresentando os limites superiores e inferiores de velocidade do sistema, as restrições de interface e o tempo de resposta.

Para essa categoria os requisitos identificados estão representados na tabela xx.

<font><p style="text-align: center">**Tabela xx** - Requisitos de Desempenho.</p></font>

| CASO DE USO |     ID     |                                   Descrição                                      |
|-------------| ---------- |--------------------------------------------------------------------------------- |
|  #UC01  |   #RF03	 | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s |
| #UC04   |   #RN07    | O sistema deve suportar múltiplas requisições simultâneas sem degradação |
|  #UC01  |   #RN08    | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples |
|  #UC06  |   #RF29    | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) |


## Suportabilidade

**Autor: [Luiz](https://github.com/luizfaria1989)**

A suportabilidade envolve os requisitos relacionados ao suporte e manutenção do sistema. Incluindo requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado futuramente, documentação adequada além da facilidade de teste e detecção de problemas no software.

Para essa categoria os requisitos identificados estão representados na tabela xx.

<font><p style="text-align: center">**Tabela xx** - Requisitos de Suportabilidade.</p></font>

| Caso de Uso |   ID     |                                   Descrição                                             |
| ----------- | -------- | --------------------------------------------------------------------------------------- |
||   #RN02    | Deve possuir versões para Android e IOS |
||   #RN01    | Deve fazer o uso da arquitetura DeepSeek-V3 |
||   #RF20    | Deve possuir uma API pública |
||   #RF21    | Deve aceitar autenticação via token de acesso |
||   #RF37    | Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas |

## Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

**Autor: [Fabio](https://github.com/fabinsz)**

A ajuda e documentação de usuário on-line são componentes cruciais para garantir uma boa experiência e autonomia ao utilizar um sistema. Elas fornecem orientações claras, suporte durante falhas e explicações sobre o funcionamento e o uso de dados, promovendo transparência e confiança por parte do usuário.

Para essa categoria os requisitos identificados estão representados na tabela xx.

<font><p style="text-align: center">**Tabela xx** - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.</p></font>

| Caso de Uso |   ID     |                                   Descrição                                             |
| ----------- | -------- | --------------------------------------------------------------------------------------- |
|| RF28  | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades   |
|UC01| RN06  | Em caso de falha, deve retornar mensagens de erro claras                                          |
|| RN09  | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados |
|| RN10  | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos |



## Bibliografia

> MELO, Arthur. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>. Acesso em: 10 maio 2025.

> REPOSITÓRIO DA DISCIPLINA – Aprender 3. Template da Especificação Suplementar. Disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1390972>. Acesso em: 10 maio 2025.

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13a [slide em PDF]. Aprender³, Universidade de Brasília, 2025. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 10 maio 2025.

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 10/05/2025 |  1.0   | (#ES01) Definições iniciais. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.1   | (#ES02) Adição de conteúdo desenvolvido. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 16/05/2025 |  1.2   | (#ES02) Adição de conteúdo desenvolvido. | [@Luiz](https://github.com/luizfaria1989)   | [@Fabio](https://github.com/fabinsz) |
| 17/05/2025 |  1.3  | (#ES02) Adição de conteúdo desenvolvido. | [@Fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 18/05/2025 |  1.4  | (#ES02) Adição de conteúdo desenvolvido. | [@Ana Clara](https://github.com/anabborges)   | [@](https://github.com/) |
