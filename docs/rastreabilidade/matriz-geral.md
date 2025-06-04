# Introdução

Uma das técnicas mais comuns para manter a rastreabilidade dos requisitos e dos artefatos que estão sendo desenvolvidos em um projeto de software, é a utilização de uma matriz de rastreabilidade. Essa matriz pode ser implementada com a utilização de softwares específicos que facilitem o seu desenvolvimento <a id="anchor_1" href="#REF1">[1]</a>.

Nessa matriz, são colocados os requisitos, o documento de origem no qual aquele requisito foi elicitado, a arquitetura, o componente e o caso de teste <a id="anchor_2" href="#REF2">[2]</a>.

A coluna dos requisitos deve ser preenchida com os requisitos elicitados no projeto. Já as demais, são preenchidas com os artefatos criados com base nequele requisito durante o processo de desenvolvimento. É importante ressaltar que essa correspondencia nem sempre é de 1 para 1, dado que, por exemplo, um requisito pode ser verificado em vários casos de teste <a id="anchor_3" href="#REF3">[3]</a>.

# Objetivos

Esse artefato tem como principal objetivo agregar os resultados obtidos nos artefatos de Backward-From e Forward-From em uma única matriz de rastreabilidade.

# Metodologia

Para o formato da matriz de rastreabilidade será utilizado o mesmo formato do repositório da disciplina de requisitos [Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/rastreabilidade/matriz-geral/) no qual a matriz de rastreabilidade irá possuir 7 colunas:

- **ID**: apresenta o identificador daquele requisito;
- **Descrição**: apresenta a descrição do requisito;
- **Pré-Rastreabilidade**: apresenta a técnica de elicitação que deu origem ao requisito;
- **Implementado?**: indica se o requisito está ou não implementado no aplicativo (Sim, Não ou Parcialmente).
- **Artefatos**: apresenta os artefatos relacionados ao requisito que foram desenvolvidos ao longo do projeto;
- **Elos**: ligação entre os requisitos e artefatos.

# Matriz Geral

Assim, é possível criar a matriz de rastreabilidade representada pela Tabela 1.

| ID    | Descrição                        | Pré-Rastreabilidade    |Implementado | Artefatos                    | Elos       |
| ----- | -------------------------------- | ---------------------- | ----------- | ---------------------------- | ---------- |
| #RF01 | Deve oferecer a possibilidade do usuário acionar a pesquisa na web | [#RDF01](../elicitacao/analise-de-documentos.md), [#RIF01](../elicitacao/analise-de-interface.md) | Sim | [Cenários](../modelagem/cenarios.md), [Casos de uso](../modelagem/casos-de-uso.md), [Léxicos](../modelagem//lexicos.md), [Backlog](../modelagem/backlog.md), [Histórias de usuário](../modelagem/historias-de-usuario.md) | |
| #RF02| Deve haver a possibilidade de uso do pensamento profundo para solução de problemas (Deep Thinking) | [#RDF02](../elicitacao/analise-de-documentos.md) | Sim | [Cenários](../modelagem/cenarios.md), [Casos de uso](../modelagem/casos-de-uso.md), [Léxicos](../modelagem//lexicos.md), [Backlog](../modelagem/backlog.md), [Histórias de usuário](../modelagem/historias-de-usuario.md) | |
| #RF03| O sistema deve aceitar uploads de arquivos de até 10MB nos formatos PDF, DOCX, TXT e imagens (com OCR) com tempo de resposta < 35s | [#RDF03](../elicitacao/analise-de-documentos.md), [#RIF01](../elicitacao/analise-de-interface.md), [#RIF05](../elicitacao/analise-de-interface.md), [#RQF01](../elicitacao/questionario.md), [#RQN09](../elicitacao/questionario.md) | Sim | [Cenários](../modelagem/cenarios.md), [Casos de uso](../modelagem/casos-de-uso.md), [Léxicos](../modelagem//lexicos.md), [Backlog](../modelagem/backlog.md), [Histórias de usuário](../modelagem/historias-de-usuario.md), [Especificação suplementar](../modelagem/especificacao-suplementar.md),  [NFR Framework](../modelagem/nfr-framework.md) | |


# Referência Bibliográfica

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 12.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 04/06/2025.[`Foto da referência`](../images/matriz-geral/definicao-matriz-geral.png)


> <a id="REF2" href="#anchor_2">2.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 12.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 04/06/2025.[`Foto da referência`](../images/matriz-geral/componentes-matriz-geral.png)

> <a id="REF3" href="#anchor_3">3.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005, p. 12-13.  Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 04/06/2025.[`Foto da referência`](../images/matriz-geral/explicacao-componentes-matriz-geral.png)

> <a id="REF4" href="#anchor_4">4.</a> MELO, Arthur. Matriz Geral. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/rastreabilidade/matriz-geral/>. Acesso em: 04/06/2025.


# Histórico de Versões

 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 04/06/2025 |  1.0   | (#MG01) Criação do documento de matriz geral.| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |
| 04/06/2025 |  1.1  | (#MG01) Adição da introdução, objetivos, metodologia, criação da matriz geral. Adição dos requisitos RF01-RF03| [`@Luiz`](https://github.com/luizfaria1989)   | [@](https://github.com/)  |
