# Léxicos

## Introdução

O léxico funciona como uma notação que lista e define os símbolos (palavras ou expressões) usados em uma linguagem. Em Engenharia de Requisitos, seu papel central é identificar termos ou frases próprios do contexto social em que o sistema será aplicado. Cada símbolo do léxico é caracterizado por:

* **Noção**: o seu significado literal, aquilo que ele denota.
* **Impacto**: a sua conotação ou efeito prático, ou seja, a resposta gerada quando o símbolo é utilizado.

Para elaborar os léxicos do DeepSeek, adotamos a abordagem do **Léxico Ampliado da Linguagem (LAL)**, conforme proposta por Sayão e Carvalho. Nesse modelo, cada símbolo é classificado em uma das quatro categorias:

* **Sujeito**: identifica quem é o agente ou entidade responsável pela ação, enquanto o impacto descreve quais operações esse agente executa sobre o sistema ou ambiente.
* **Verbo**: detalha quem realiza determinada ação, em que momento ela ocorre e quais procedimentos a compõem; o impacto mapeia os efeitos dessa ação no contexto e os novos estados que podem emergir.
* **Objeto**: define o elemento ou recurso do sistema e suas associações com outros objetos; o impacto especifica que tipos de operações podem ser aplicadas a esse objeto.
* **Estado**: descreve a condição ou situação atual do sistema, indicando quais eventos o levaram a tal ponto, e o impacto projeta os estados seguintes possíveis a partir dessa condição.

Adotaremos um padrão uniforme para cada entrada do léxico, composto pelos seguintes campos:

- ID: identificador único do termo.
- Noção: significado literal que o termo denota
- Impacto: conotação ou efeito prático que sua aplicação produz no sistema.
- Classificação: categoria do símbolo (Sujeito, Verbo, Objeto ou Estado).
- Dicionário: sinônimos e expressões equivalentes.
- Rastreamento: Código Caso de Uso/Cenário

Esse esquema garante que todo termo usado no DeepSeek seja descrito de forma consistente, permitindo fácil reconhecimento e entendimento por todos os membros da equipe.

## Léxicos

### Léxico para UC01 (Upload de Documento)

| ID        | Noção               | Impacto                                                       | Classificação | Dicionário                      | Rastreamento |
| --------- | ------------------- | ------------------------------------------------------------- | ------------- | ------------------------------- | ------------ |
| L-UC01-02 | Upload de Documento | Enviar PDF ao DeepSeek para conversão em texto                | Verbo         | Subir arquivo, Enviar documento | UC01         |
| L-UC01-03 | PDF                 | Arquivo no formato Portable Document Format                   | Objeto        | Documento, Arquivo PDF          | UC01         |
| L-UC01-05 | Spinner             | Indicador visual de carregamento durante o processamento      | Objeto        | Indicador de progresso          | UC01         |
| L-UC01-06 | Texto Extraído      | Conteúdo convertido do PDF em texto                           | Objeto        | Conteúdo processado             | UC01         |

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>
---

### Léxico para UC02 (Consulta Atualizada via Search na Web)

| ID        | Noção     | Impacto                                                        | Classificação | Dicionário                 | Rastreamento |
| --------- | --------- | -------------------------------------------------------------- | ------------- | -------------------------- | ------------ |
| L-UC02-01 | Search    | Módulo que realiza consultas na web sem sair da plataforma     | Sujeito       | Busca web, Pesquisa online | UC02         |
| L-UC02-02 | Query     | Texto de busca inserido pelo usuário                           | Objeto        | Termo de pesquisa, String  | UC02         |
| L-UC02-03 | Copy      | Ação de copiar o trecho retornado para a área de transferência | Verbo         | Copiar, Duplicar           | UC02         |
| L-UC02-04 | Node.js   | Ambiente de execução JavaScript                                | Objeto        | Plataforma Node            | UC02         |
| L-UC02-05 | Resultado | Trecho retornado pela consulta, contendo versão e data         | Objeto        | Retorno, Resposta          | UC02         |

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>
---

### Léxico para UC03 (Iteração de Resposta com Feedback)

| ID        | Noção      | Impacto                                                                      | Classificação | Dicionário            | Rastreamento |
| --------- | ---------- | ---------------------------------------------------------------------------- | ------------- | --------------------- | ------------ |
| L-UC03-02 | Like       | Avaliação positiva que sinaliza satisfação com a resposta                    | Verbo         | Curtir, Aprovar       | UC03         |
| L-UC03-03 | Dislike    | Avaliação negativa que aciona feedback para nova geração de conteúdo         | Verbo         | Reprovar, Não curtir  | UC03         |
| L-UC03-04 | Regenerate | Comando que solicita ao sistema gerar novamente o texto com base no feedback | Verbo         | Regenerar, Refazer    | UC03         |
| L-UC03-05 | Copy       | Ação de copiar a resposta final para a área de transferência                 | Verbo         | Copiar, Duplicar      | UC03         |
| L-UC03-06 | Feedback   | Comentário do usuário que orienta ajustes na geração de texto                | Objeto        | Avaliação, Comentário | UC03         |

<div align="center">
    Autor: <a href="https://github.com/gaubiela">@Gabriela</a>
</div>
---

### Léxico para UC04 (Uso da função Pensamento Profundo)

| ID        | Noção                     | Impacto                                                                                                                                       | Classificação | Dicionário                     | Rastreamento |
| --------- | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------ | ------------ |
| L-UC04-01 | Chat                      | Campo de interação no qual o usuário insere perguntas e visualiza respostas do DeepSeek                                                       | Objeto        | Conversa                       | UC04         |
| L-UC04-02 | Equação                   | Entrada de texto representando um problema matemático                                                                                         | Objeto        | Problema                       | UC04         |
| L-UC04-03 | Pensamento Profundo (R1)  | Modo do DeepSeek que permite a visualização do seu fluxo de pensamento junto com a resposta, direcionado para resolver perguntas complexas    | Verbo         | Modo de resolução              | UC04         |
| L-UC04-04 | Fluxo de pensamento       | Sequência de passos do DeepSeek para resolver um determinado problema                                                                         | Objeto        | Linha de raciocínio            | UC04         |
| L-UC04-05 | Modelo R1                 | Modelo mais avançado do DeepSeek, treinado para resolver problemas de lógica, como exercícios de matemática e programação                     | Objeto        | Modelo, Inteligência artificial| UC04         |

<div align="center">
    Autor: <a href="https://github.com/Luizfaria1989">@Luiz</a>
</div>
---

## Bibliografia

> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 10/05/2025.

> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 10/05/2025.


 Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
| :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
| 10/05/2025 |  1.0   | (#LX01) Definições iniciais. | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 10/05/2025 |  1.1   | (#LX01) Adição de conteúdo desenvolvido.  | [@Gabriela](https://github.com/gaubiela)   | [@Ana Joyce](https://github.com/anajoyceamorim) |
| 11/05/2025 |  1.2   | (#LX01) Adição de conteúdo desenvolvido.  | [@Luiz](https://github.com/luizfaria1989)   | [@Ana Joyce](https://github.com/anajoyceamorim) |