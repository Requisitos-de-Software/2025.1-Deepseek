# Especificação Suplementar

## Introdução

A **Especificação Suplementar** é um documento redigido em linguagem natural que reúne todos os requisitos de um sistema que não foram plenamente capturados pelos casos de uso. Ela complementa o modelo de casos de uso ao detalhar necessidades adicionais, tais como:

* **Requisitos legais e regulamentares**, incluindo conformidade com normas e padrões de aplicativos;
* **Atributos de qualidade**, como **Usabilidade**, **Confiabilidade**, **Desempenho**, **Manutenibilidade** (Suportabilidade) e **Segurança**;
* **Outros requisitos técnicos**, abrangendo sistemas e ambientes operacionais suportados, requisitos de compatibilidade e restrições de design.

A adoção da abordagem **FURPS+** (Functionality, Usability, Reliability, Performance, Supportability, mais fatores) orienta a identificação e a organização desses requisitos, garantindo cobertura completa dos aspectos funcionais e de qualidade da aplicação.

---

## Design
**Autor: [Davi Emanuel](https://github.com/daviRolvr)**
Design se refere às diretrizes e decisões arquitetônicas que orientam a estrutura e organização do sistema. Define padrões como o modelo de arquitetura (ex: MVC), estrutura de módulos, organização do código e práticas de design que devem ser seguidas durante o desenvolvimento.

Para essa categoria os requisitos identificados estão representados na tabela xx.

| ID       | Descrição                                                                                     | Rastreamento|
|----------|-----------------------------------------------------------------------------------------------|----------------------|
| #RD01     | A interface deve seguir diretrizes de usabilidade (botões visíveis, texto legível, feedback imediato) e de acessibilidade (alteração no tamanho da fonte, leitura)     |#RN05|
| #RD02     | O sistema deve exibir respostas formatadas em Markdown em respostas para tabelas ou listas complexas Markdown (títulos, listas, código) com a possibilidade de edição do Markdown pelo usuário|#RF18|
| #RD03     |Deve oferecer modo escuro e modo claro, com configuração manual e sincronização automática com o sistema operacional.          |#RF27 |
| #RD04     | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico para que não cubra outros elementos e posicione em local adequado.                     |#RF35|
| #RD05     | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades. / Implementar tutorial interativo (tour guiado) destacando recursos avançados (DeepThink, Reason etc.) no onboarding.           |#RF28|
| #RD06     |Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras. | #N13|   
| #RD07     | Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras.   | #RN14 |  
| #RD08     |Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras.  | #RN15 |

##  Implementação
**Autor: [Davi Emanuel](https://github.com/daviRolvr)**
Implementação se refere às restrições técnicas relacionadas à codificação do sistema. Inclui a escolha de linguagens de programação, frameworks, bibliotecas, bancos de dados e ferramentas específicas que devem ser utilizadas, além de padrões de codificação e compatibilidade com plataformas.

Para essa categoria os requisitos identificados estão representados na tabela xx.
| ID       | Descrição                                                                                             | Rastreamento|
|----------|-------------------------------------------------------------------------------------------------------|----------------------|
| #RI01     |Deve fazer o uso da arquitetura DeepSeek-V3.                          |#RN01| 
| #RI02     | Deve possuir uma API Pública.                 |#RF20|
| #RI03     | Deve aceitar autenticação via token de acesso. |           #RF21   |             
| #RI04     | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256).     |#RF24|
| #RI05     | O sistema deve suportar múltiplas requisições simultâneas sem degradação               |#RN07 |
| #RI06     | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤10 segundos e o tempo médio de resposta deve ser <= 2 s em operações simples                          |#RN08|
| #RI07     | 	Permitir escolha de modelos (seleção de diferentes versões/modelos de IA).                |#RF32V|
| #RI08     | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s                           |#RF03V|
| #RI09     | 	Implementar comandos de voz para entrada e saída de informações.    | #RF34|
| #RI10     | Conectar nativamente a ferramentas populares (Google Drive, Google Agendas, Outlook, GitHub etc.) via integrações diretas.               |#RF37|
| #RI11     | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas.|#RN12 |
| #RI12     | Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização).               |#RF38|
| #RI13     |  Em caso de falha, deve retornar mensagens de erro claras  |#RN06|
| #RI14     |Deve possuir a opção de login com conta Google/Apple ID.               |#RN04 |
| #RI15      |Deve ser possível regenar uma resposta da IA de forma manual ou de forma automática no caso de erro de servidor ou sobrecargado sistema.| #RF17 |


## Finalidade

A finalidade deste artefato é definir, de forma clara e estruturada, requisitos suplementares do **DeepSeek**, assegurando que atributos de qualidade, restrições de projeto e regras de negócio estejam documentados para orientar o desenvolvimento e a validação do sistema.

---

## Desempenho

**Autor: [Luiz](https://github.com/luizfaria1989)**

O desempenho se refere as condições em que os requisitos devem operar. Apresentando os limites superiores e inferiores de velocidade do sistema, as restrições de interface e o tempo de resposta.

Para essa categoria os requisitos identificados estão representados na tabela xx.

<font><p style="text-align: center">**Tabela xx** - Requisitos de Desempenho.</p></font>

|     ID     |                                   Descrição                                             |
| ---------- | --------------------------------------------------------------------------------------- |
|   #RF03	 | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s |
|   #RN07    | O sistema deve suportar múltiplas requisições simultâneas sem degradação |
|   #RN08    | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples |
|   #RF29    | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) |


## Suportabilidade

**Autor: [Luiz](https://github.com/luizfaria1989)**

A suportabilidade envolve os requisitos relacionados ao suporte e manutenção do sistema. Incluindo requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado futuramente, documentação adequada além da facilidade de teste e detecção de problemas no software.

Para essa categoria os requisitos identificados estão representados na tabela xx.

<font><p style="text-align: center">**Tabela xx** - Requisitos de Suportabilidade.</p></font>

|     ID     |                                   Descrição                                             |
| ---------- | --------------------------------------------------------------------------------------- |
|   #RN02    | Deve possuir versões para Android e IOS |
|   #RN01    | Deve fazer o uso da arquitetura DeepSeek-V3 |
|   #RF20    | Deve possuir uma API pública |
|   #RF21    | Deve aceitar autenticação via token de acesso |
|   #RF37    | Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas |

## Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

**Autor: [Fabio](https://github.com/fabinsz)**

A ajuda e documentação de usuário on-line são componentes cruciais para garantir uma boa experiência e autonomia ao utilizar um sistema. Elas fornecem orientações claras, suporte durante falhas e explicações sobre o funcionamento e o uso de dados, promovendo transparência e confiança por parte do usuário.

Para essa categoria os requisitos identificados estão representados na tabela xx.

<font><p style="text-align: center">**Tabela xx** - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.</p></font>

| ID    | Descrição                                                                                         |
|-------|---------------------------------------------------------------------------------------------------|
| RF28  | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades   |
| RN06  | Em caso de falha, deve retornar mensagens de erro claras                                          |
| RN09  | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados |
| RN10  | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos |



## Bibliografia

> MELO, Arthur. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>. Acesso em: 10 maio 2025.

> REPOSITÓRIO DA DISCIPLINA – Aprender 3. Template da Especificação Suplementar. Disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1390972>. Acesso em: 10 maio 2025.

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13a [slide em PDF]. Aprender³, Universidade de Brasília, 2025. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 10 maio 2025.

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 10/05/2025 |  1.0   | (#ES01) Definições iniciais. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.1   | (#ES02) Adição de conteúdo desenvolvido. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim)| 
| 16/05/2025 |  1.2   | (#ES02) Adição de conteúdo desenvolvido. | [@Luiz](https://github.com/luizfaria1989)   | [@Fabio](https://github.com/fabinsz) |
| 17/05/2025 |  1.3  | (#ES02) Adição de conteúdo desenvolvido. | [@Fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 17/05/2025 |  1.4   | (#ES02) Adição de conteúdo desenvolvido. | [@Davi Emanuel](https://github.com/daviRolvr)|[@](https://github.com/) |


