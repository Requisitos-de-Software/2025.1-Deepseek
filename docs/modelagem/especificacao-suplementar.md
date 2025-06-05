# Especificação Suplementar

## Introdução

A **Especificação Suplementar** é um documento redigido em linguagem natural que reúne todos os requisitos de um sistema que não foram plenamente capturados pelos casos de uso. Ela complementa o modelo de casos de uso ao detalhar necessidades adicionais, tais como:

* **Requisitos legais e regulamentares**, incluindo conformidade com normas e padrões de aplicativos;
* **Atributos de qualidade**, como **Usabilidade**, **Confiabilidade**, **Desempenho**, **Manutenibilidade** (Suportabilidade) e **Segurança**;
* **Outros requisitos técnicos**, abrangendo sistemas e ambientes operacionais suportados, requisitos de compatibilidade e restrições de design.

A adoção da abordagem **FURPS+** (Functionality, Usability, Reliability, Performance, Supportability, mais fatores) orienta a identificação e a organização desses requisitos, garantindo cobertura completa dos aspectos funcionais e de qualidade da aplicação.

## Finalidade

A finalidade deste artefato é definir, de forma clara e estruturada, requisitos suplementares do **DeepSeek**, assegurando que atributos de qualidade, restrições de projeto e regras de negócio estejam documentados para orientar o desenvolvimento e a validação do sistema.

---

## Metodologia

**Autor: [Ana Joyce](https://github.com/anajoyceamorim)**

A modelagem dos requisitos do sistema **DeepSeek** foi realizada com foco na separação entre **requisitos funcionais** e **não funcionais**.

A abordagem seguiu os seguintes passos principais:

1. **Elicitação de Requisitos** – Reuniões com stakeholders permitiram identificar as necessidades do sistema, tanto em termos de funcionalidades quanto de atributos de qualidade.
2. **Modelagem de Casos de Uso** – Os requisitos funcionais foram representados por meio de **diagramas de casos de uso**, destacando as ações que os usuários poderão realizar e suas interações com o sistema.
3. **Especificação Suplementar** – Para complementar os casos de uso, foram descritos os **requisitos não funcionais** em linguagem natural, utilizando a classificação **FURPS+**, que considera:  
**Funcionalidade**    
**Usabilidade**  
**Confiabilidade**  
**Desempenho**  
**Suportabilidade**  

Essa metodologia busca garantir que todos os aspectos essenciais ao desenvolvimento do sistema estejam bem documentados e acessíveis a todos os envolvidos no projeto.

---

## #ES01 - Design 

**Autor: [Davi Emanuel](https://github.com/daviRolvr)**

Design se refere às diretrizes e decisões arquitetônicas que orientam a estrutura e organização do sistema. Define padrões como o modelo de arquitetura (ex: MVC), estrutura de módulos, organização do código e práticas de design que devem ser seguidas durante o desenvolvimento.

Para essa categoria os requisitos identificados estão representados na tabela 1.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Design.</p></font>

| ID       | Descrição                                                                                     | Rastreamento|
|----------|-----------------------------------------------------------------------------------------------|----------------------|
| RN05     | A interface deve seguir diretrizes de usabilidade (botões visíveis, texto legível, feedback imediato) e de acessibilidade (alteração no tamanho da fonte, leitura)  |   
| RF18     | O sistema deve exibir respostas formatadas em Markdown em respostas para tabelas ou listas complexas Markdown (títulos, listas, código) com a possibilidade de edição do Markdown pelo usuário.|
| RF27     |Deve oferecer modo escuro e modo claro, com configuração manual e sincronização automática com o sistema operacional.         |
| RF35   | Ajustar visualização do título ao passar o mouse sobre o nome do chat na barra lateral de histórico para que não cubra outros elementos e posicione em local adequado.   |                 
| RF28   | Deve incluir tutorial interativo na primeira execução, explicando as principais funcionalidades. / Implementar tutorial interativo (tour guiado) destacando recursos avançados (DeepThink, Reason etc.) no onboarding.           |
| RN13     |Atingir ≥ 95 % de usuários avaliando a usabilidade como “Fácil” ou “Muito fácil” em pesquisas futuras. |
| RN14    | Alcançar ≥ 90 % de concordância em “Interface clara e agradável” em pesquisas futuras.   |
| RN15    |Reduzir para ≤ 5 % os usuários que relatam dificuldade em encontrar opções/ferramentas em pesquisas futuras.  |

## #ES02 - Implementação

**Autor: [Davi Emanuel](https://github.com/daviRolvr)**

Implementação se refere às restrições técnicas relacionadas à codificação do sistema. Inclui a escolha de linguagens de programação, frameworks, bibliotecas, bancos de dados e ferramentas específicas que devem ser utilizadas, além de padrões de codificação e compatibilidade com plataformas.

Para essa categoria os requisitos identificados estão representados na tabela 2.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Implementação.</p></font>

| ID       | Descrição                |                                                                             
|----------|-------------------------------------------------------------------------------------------------------|
| RF24    |Deve fazer o uso da arquitetura DeepSeek-V3.|                          
| RF20     | Deve possuir uma API Pública.              |   
| RF21    | Deve aceitar autenticação via token de acesso.   |                  
| RF24    | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256).  |   
| RN07     | O sistema deve suportar múltiplas requisições simultâneas sem degradação        |       
| RN08   | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤10 segundos e o tempo médio de resposta deve ser <= 2 s em operações simples |                        
| RF32   | 	Permitir escolha de modelos (seleção de diferentes versões/modelos de IA).   |             
| RF03     | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s |                          
| RF34   | 	Implementar comandos de voz para entrada e saída de informações.    |
| UC02    | Conectar nativamente a ferramentas populares (Google Drive, Google Agendas, Outlook, GitHub etc.) via integrações diretas.     |         
| RN12      | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas.|
| RF38    | Disponibilizar resumo automático de vídeos (importação de links do YouTube para sumarização).  |             
| RN06    |  Em caso de falha, deve retornar mensagens de erro claras  |
| RN04   |Deve possuir a opção de login com conta Google/Apple ID.    |           
| RF17     |Deve ser possível regenar uma resposta da IA de forma manual ou de forma automática no caso de erro de servidor ou sobrecargado sistema.|



## #ES03 - Funcionalidade

**Autor: [Ana Joyce](https://github.com/anajoyceamorim)**

Os **requisitos funcionais** do sistema **DeepSeek** foram identificados por meio de técnicas de elicitação apresentadas anteriormente neste documento. A Tabela a seguir,consolida todos os requisitos funcionais levantados.

Esses requisitos descrevem as funcionalidades que o sistema deverá oferecer, incluindo interações com o usuário, regras de negócio e comportamento esperado diante de diferentes cenários.

A especificação complementar detalha os aspectos de qualidade, técnicos e restrições que **complementam esses requisitos funcionais**, assegurando a completude da documentação de requisitos do sistema.

  <table border="1" cellpadding="5" cellspacing="0" style="border-collapse: collapse; margin-top: 10px;">
    <thead>
      <tr>
        <th>ID</th>
        <th>Descrição final</th>
        <th>Status</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>#RF01</td>
        <td>Deve oferecer a possibilidade do usuário acionar a pesquisa na web</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF02</td>
        <td>Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking)</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF03</td>
        <td>O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta &lt; 35s</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF04</td>
        <td>Deve possuir a opção de login com conta Google/Apple ID</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF05</td>
        <td>Deve salvar chats entre plataformas</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF06</td>
        <td>Melhorar as capacidades de "deep thinking"</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF07</td>
        <td>Deve haver um campo para a interação com a IA</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF08</td>
        <td>Deve ser possível criar novos chats</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF09</td>
        <td>Deve ser possível renomear um chat</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF10</td>
        <td>Os chats já utilizados devem poder ser acessados posteriormente</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF11</td>
        <td>Deve ser possível dar dislike em uma resposta da IA</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF12</td>
        <td>Deve ser possível dar like em uma resposta da IA</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF13</td>
        <td>Deve ser possível copiar uma resposta da IA</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF14</td>
        <td>Deve exibir citações de fontes e referências em respostas baseadas em documentos</td>
        <td>Parcialmente implementado</td>
      </tr>
      <tr>
        <td>#RF15</td>
        <td>Deve ser possível alterar o idioma do sistema</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF16</td>
        <td>Deve ser possível apagar conversas individuais ou de forma geral</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF17</td>
        <td>Deve ser possível regenerar uma resposta da IA em caso de erro de servidor ou sobrecarga</td>
        <td>Parcialmente implementado</td>
      </tr>
      <tr>
        <td>#RF18</td>
        <td>O sistema deve exibir respostas formatadas em Markdown com possibilidade de edição</td>
        <td>Parcialmente implementado</td>
      </tr>
      <tr>
        <td>#RF19</td>
        <td>Deve ser possível interromper respostas em andamento</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF20</td>
        <td>Deve possuir uma API pública</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF21</td>
        <td>Deve aceitar autenticação via token de acesso</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF22</td>
        <td>Deve haver uma confirmação para limpar o histórico</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF23</td>
        <td>Deve suportar busca incremental (sugestões em tempo real)</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF24</td>
        <td>Todos os dados sensíveis do usuário devem ser criptografados (TLS e AES-256)</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF25</td>
        <td>O usuário deve poder controlar quais dados são compartilhados</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF26</td>
        <td>Deve haver autenticação multifator opcional</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF27</td>
        <td>Deve oferecer modo escuro e claro, com configuração manual e sincronização automática</td>
        <td>Implementado</td>
      </tr>
      <tr>
        <td>#RF28</td>
        <td>Deve incluir tutorial interativo na primeira execução</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF29</td>
        <td>Exibir status do servidor em tempo real</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF30</td>
        <td>Melhorar retenção de contexto em diálogos longos</td>
        <td>Parcialmente implementado</td>
      </tr>
      <tr>
        <td>#RF31</td>
        <td>Implementar memória de contexto persistente entre conversas</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF32</td>
        <td>Permitir escolha de modelos de IA</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF33</td>
        <td>Permitir organização de conversas em pastas ou listas</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF34</td>
        <td>Implementar comandos de voz para entrada e saída de informações</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF35</td>
        <td>Ajustar visualização do título ao passar o mouse sobre o nome do chat</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF36</td>
        <td>Fornecer instruções claras sobre OCR na interface</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF37</td>
        <td>Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.)</td>
        <td>Não implementado</td>
      </tr>
      <tr>
        <td>#RF38</td>
        <td>Disponibilizar resumo automático de vídeos (YouTube)</td>
        <td>Não implementado</td>
      </tr>
    </tbody>
  </table>

<div align="center">
    Tabela 3. Tabela com requisitos funcionais.
</div>
<div align="center">
    Autor: <a href="https://github.com/anajoyceamorim">@Ana Joyce</a>
</div>

---

## #ES04 - Usabilidade

Nessa seção são apresentados requisitos que afetam a usabilidade do sistema, ou seja, que se referem a forma de o usuário interagir com o sistema.

**Autor: [Ana Clara](https://github.com/anabborges)**

<font><p style="text-align: center">**Tabela 4** - Requisitos de Usabilidade.</p></font>

| CASO DE USO |     ID     | Descrição |
|-------------| ---------- |-----------|
|             |   #RF04    | Deve possuir a opção de login com conta Google/Apple ID |
|             |   #RF07    | Deve haver um campo para a interação com a IA |
|             |   #RF08    | Deve ser possível criar novos chats |
|             |   #RF09    | Deve ser possível renomear um chat |
|             |   #RF10    | Os chats já utilizados devem poder ser acessados posteriormente |
|    UC08     |   #RF11    | Deve ser possível dar dislike em uma resposta da IA |
|    UC08     |   #RF12    | Deve ser possível dar like em uma resposta da IA |
|    UC08     |   #RF13    | Deve ser possível copiar uma resposta da IA |
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

<font><p style="text-align: center">**Tabela 5** - Requisitos de Confiabilidade.</p></font>

| CASO DE USO |     ID     | Descrição |
|-------------| ---------- |-----------|
|     #UC06        |   #RF03    | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s |
|      UC08       |   #RF17    | Deve ser possível regenerar uma resposta da IA de forma manual ou automática em caso de erro de servidor ou sobrecarga |
|             |   #RF24    | Todos os dados sensíveis do usuário devem ser criptografados em trânsito (TLS) e em repouso (AES-256) |
|             |   #RF25    | O usuário deve poder controlar quais dados são compartilhados (chat, histórico de buscas, localização) |
|             |   #RF26    | Deve haver autenticação multifator opcional para acesso a funcionalidades avançadas |
|  #UC06           |   #RF29    | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) |
|             |   #RF30    | Melhorar retenção de contexto em diálogos longos |
|             |   #RF31    | Implementar memória de contexto persistente entre conversas |
|             |   #RN03    | Deve guardar um histórico de conversas por 30 dias (não persistente se o usuário sair sem salvar) |
|             |   #RN04    | Deve fazer a exclusão automática de dados de upload |
|      #UC06       |   #RN06    | Em caso de falha, deve retornar mensagens de erro claras |
|       #UC04      |   #RN07    | O sistema deve suportar múltiplas requisições simultâneas sem degradação |
|      #UC06       |   #RN08    | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples |
|             |   #RN09    | Disponibilizar, no próprio app, informações claras e acessíveis sobre como e onde os dados são armazenados e utilizados |
|             |   #RN10    | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos |
|             |   #RN11    | Especificar e permitir ao usuário optar por participar ou não do uso de seus dados em re-treinamento ou venda de modelos |
|             |   #RN12    | Garantir estabilidade na geração de conteúdos pesados (PDF, cálculos), evitando erros de formatação ou falhas |

---

## #ES05 - Desempenho

**Autor: [Luiz](https://github.com/luizfaria1989)**

O desempenho se refere as condições em que os requisitos devem operar. Apresentando os limites superiores e inferiores de velocidade do sistema, as restrições de interface e o tempo de resposta.

Para essa categoria os requisitos identificados estão representados na tabela 6.

<font><p style="text-align: center">**Tabela 6** - Requisitos de Desempenho.</p></font>

| CASO DE USO |     ID     |                                   Descrição                                      |
|-------------| ---------- |--------------------------------------------------------------------------------- |
|  #UC06  |   #RF03	 | O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s |
| #UC04   |   #RN07    | O sistema deve suportar múltiplas requisições simultâneas sem degradação |
|  #UC06  |   #RN08    | O processamento de arquivos grandes (PDF/DOCX) deve ocorrer em ≤ 10 s e o tempo médio de resposta ≤ 2 s em operações simples |
|  #UC06  |   #RF29    | Exibir status do servidor em tempo real (Online, Manutenção, Sobrecarga) |


## #ES06 - Suportabilidade

**Autor: [Luiz](https://github.com/luizfaria1989)**

A suportabilidade envolve os requisitos relacionados ao suporte e manutenção do sistema. Incluindo requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado futuramente, documentação adequada além da facilidade de teste e detecção de problemas no software.

Para essa categoria os requisitos identificados estão representados na tabela 7.

<font><p style="text-align: center">**Tabela 7** - Requisitos de Suportabilidade.</p></font>

| Caso de Uso |   ID     |                                   Descrição                                             |
| ----------- | -------- | --------------------------------------------------------------------------------------- |
||   #RN02    | Deve possuir versões para Android e IOS |
||   #RN01    | Deve fazer o uso da arquitetura DeepSeek-V3 |
||   #RF20    | Deve possuir uma API pública |
||   #RF21    | Deve aceitar autenticação via token de acesso |
||   #RF37    | Conectar nativamente a ferramentas populares (Google Drive, Outlook, GitHub etc.) via integrações diretas |

## #ES07 - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

**Autor: [Fabio](https://github.com/fabinsz)**

A ajuda e documentação de usuário on-line são componentes cruciais para garantir uma boa experiência e autonomia ao utilizar um sistema. Elas fornecem orientações claras, suporte durante falhas e explicações sobre o funcionamento e o uso de dados, promovendo transparência e confiança por parte do usuário.

Para essa categoria os requisitos identificados estão representados na tabela 8.

<font><p style="text-align: center">**Tabela 8** - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.</p></font>

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
| 10/05/2025 |  1.1   | (#ES02) Adição de conteúdo desenvolvido. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim)| 
| 16/05/2025 |  1.2   | (#ES02) Adição de conteúdo desenvolvido. | [@Luiz](https://github.com/luizfaria1989)   | [@Fabio](https://github.com/fabinsz) |
| 17/05/2025 |  1.3  | (#ES02) Adição de conteúdo desenvolvido. | [@Fabio](https://github.com/fabinsz)   | [@Luiz](https://github.com/luizfaria1989) |
| 17/05/2025 |  1.4   | (#ES02) Adição de conteúdo desenvolvido. | [@Davi Emanuel](https://github.com/daviRolvr)|[@Ana Joyce](https://github.com/anajoyceamorim) |
| 18/05/2025 |  1.5  | (#ES02) Adição de conteúdo desenvolvido. | [@Ana Clara](https://github.com/anabborges)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 18/05/2025 |  1.6  | (#ES02) Adição de metodologia e funcionalidade. | [@Ana Joyce](https://github.com/anajoyceamorim)   | [@Gabriela](https://github.com/gaubiela) |
| 18/05/2025 |  1.7 | (#ES02)Correção na formatação e revisão do documento. | [@Mateus](https://github.com/MVConsorte)   | [@Luiz](https://github.com/luizfaria1989), [@Gabriela](https://github.com/gaubiela),[@Davi Emanuel](https://github.com/daviRolvr) |
| 05/06/2025 |  2.0 | (#ES02) Adição dos ids para as tabelas da especificação suplementar. | [@Luiz](https://github.com/luizfaria1989)   | [@](https://github.com/) |