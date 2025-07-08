# Elos de Rastreabilidade

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">A rastreabilidade de requisitos é fundamental na engenharia de software, pois permite acompanhar sua origem, evolução e validação ao longo do projeto. Os elos entre requisitos e demais artefatos facilitam a compreensão do sistema, a análise de mudanças e o alinhamento com as necessidades dos <i>stakeholders</i>. 
</div> <div style="text-align: justify; text-indent: 2cm;">Este documento apresenta os elos de rastreabilidade conforme o <b>Meta-modelo de Toranzo</b> (SAYÃO e LEITE, 2005), que será melhor apresentado mais adiante.</div>


## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">Aqui, as informações a serem rastreadas foram classificadas em diferentes níveis, conforme sua natureza e finalidade. Segundo a literatura (SAYÃO, M.; LEITE, J.C.S.P. 2005), essas informações se organizam em quatro níveis principais: <b>ambiental</b>, <b>organizacional</b>, <b>gerencial</b> e <b>desenvolvimento</b>.</div> 

<ul style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
    <li><b>Nível ambiental</b>: trata de fatores externos à organização que podem influenciar o sistema, como leis, políticas e o cenário social ou econômico.</li> 
    <li><b>Nível organizacional</b>: refere-se a aspectos internos da organização, como sua missão, metas e padrões, que afetam as decisões sobre o sistema.</li> 
    <li><b>Nível gerencial</b>: envolve informações de gestão que ligam tarefas aos requisitos, como prazos, responsáveis e cronogramas do projeto.</li> 
    <li><b>Nível desenvolvimento</b>: engloba os artefatos técnicos criados durante o projeto, como requisitos, diagramas, código e testes.</li>
</ul> 

<div style="text-align: justify; text-indent: 2cm;">Esses níveis são fundamentais para orientar a rastreabilidade de requisitos, permitindo que a origem, a evolução e a aplicação das informações possam ser compreendidas e gerenciadas de forma eficaz ao longo do projeto.</div>

<div style="text-align: justify; text-indent: 2cm;">Além disso, foi utilizado o meta-modelo de Toranzo. Esse meta-modelo estrutura a rastreabilidade como um conjunto de “Elementos” genéricos — que podem ser requisitos, documentos, código, testes ou qualquer artefato — e “Relacionamentos” que ligam pares desses elementos. Cada relacionamento recebe um rótulo que descreve seu propósito, o qual pode ser:</div>

<ul style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
<li><b>Satisfação</b>: classe origem tem dependência de satisfação com a classe destino;
<li><b>Recurso</b>: classe origem tem dependência de recurso com a classe destino;
<li><b>Responsabilidade</b>: registra a participação, responsabilidade e ação de pessoas sobre artefatos;
<li><b>Representação</b>: captura a representação ou modelagem dos requisitos em outras linguagens;
<li><b>Alocado</b>: classe origem está relacionada à classe destino, que representa um subsistema;
<li><b>Agregação</b>: indica “composição” de elementos.
</ul>

<div style="text-align: justify; text-indent: 2cm;">O presente artefato considerará, a partir do Meta-modelo de Toranzo, tanto a relação de requisitos com artefatos quanto entre os próprios requisitos. Cabe ressaltar que, inicialmente, este artefato não contém elos para todos os requisitos elicitados, e sim para os utilizados em outras técnicas e na produção de outros artefatos da documentação.</div>

<div style="text-align: justify; text-indent: 2cm;">As seções 2.1. a 2.3. a seguir apresentam, respectivamente, o cronograma seguido pelo grupo, as legendas que explicam as siglas e o modelo utilizado na construção dos elos.</div>

### 2.1. Cronograma

<div style="text-align: center;">
O cronograma seguido pela equipe se encontra na Tabela 1.
</div>

<font size="3"><p style="text-align: center">Tabela 1: Cronograma de elaboração do artefato</p></font>

<center>

| Nome                                                    | Data       | Hora  | Função                                                    |
| ------------------------------------------------------- | ---------- | ----- | --------------------------------------------------------- |
| [Caio Duarte](https://github.com/caioduart3)            | 08/06/2025 | 21:00 | Elaborador dos elos                                       |
| [Ludmila Nunes](https://github.com/ludmilaaysha)        | 08/06/2025 | 10:00 | Elaborador dos elos (RF01, RF06, RF28, RF51, RF53 e RF56) |
| [Mayara Marques](https://github.com/maymarquee)         | 08/06/2025 | 21:30 | Elaborador dos elos                                       |
| [Gabriel Pinto](https://github.com/GabrielSPinto)       | 14/06/2025 | 17:00 | Elaborador dos elos                                       |
| [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 22/06/2025 | 18:00 | Elaborador dos elos                                       |
|  [Laryssa Felix](https://github.com/felixlaryssa)       | 06/07/2025 | 18:00 | Elaborador dos elos                                       |


</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### 2.2. Legendas

<div style="text-align: justify; text-indent: 2cm;">
A legenda para cada sigla é a seguinte:
</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;">
<ul>
<li>RF* - Requisito Funcional nº*
<li>RNF* - Requisito Não Funcional nº*  
<li>EX -  Elo nº X
<li>Tipo do Elo -  Tipo do rótulo, o qual pode se enquadrar em Satisfação, Recurso, Responsabilidade, Alocado, Representação ou Agregação
</ul>
</div>

### 2.3. Modelo

<font size="3"><p style="text-align: center">Tabela 2: Modelo de ficha dos elos</p></font>

| ID do Elo | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|----------------|------------------------------------------|-----------------------------------------|
| RF*EX    | Tipo de Elo    | Nome do artefato ou elemento relacionado | Comentário ou detalhe útil              |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

## 3. Elos de Rastreabilidade

<div style="text-align: justify; text-indent: 2cm;">Esta seção apresenta alguns elos com base nos requisitos elicitados e artefatos produzidos, que podem ser observados da tabela 3 a 9.</div>

### RF01: Notícias atualizadas

<div style="text-align: justify; text-indent: 2cm;">A tabela 3 abaixo apresenta elos relacionados ao requisito <b>RF01: O sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios.</b></div>

<font size="3"><p style="text-align: center">Tabela 3: Tabela de elos do RF01. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF01E1   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#3-requisitos-elicitados">Técnica de Análise de Interface - RFA1</a> | Sessão de Análise de Interface gerou RFA1, que originou RF01 |
| RF01E2   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito recebeu a prioridade de 8,473 |
| RF01E3   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito recebeu a classificação "Must have" (deve ter) |
| RF01E4   | Gerencial| Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $1,00 |
| RF01E5   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade N/A, pois já está implementado |
| RF01E6   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 6 votos |
| RF01E7   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Implementados |
| RF01E8   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 3 |
| RF01E9  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US37: Exibição de notícias atualizadas" |
| RF01E10  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | Requisito traduzido como User Story US37 backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### RF06: Aba de indicadores prévia de gráfico e valor com coloração simbólica.

<div style="text-align: justify; text-indent: 2cm;">A tabela 4 abaixo apresenta elos relacionados ao requisito <b>RF06: Sistema deve possuir a aba de indicadores, com principais dados do IBGE, prévia de gráfico e valor com coloração simbólica (verde/vermelha).</b></div>

<font size="3"><p style="text-align: center">Tabela 4: Tabela de elos do RF06. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF06E1   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#3-requisitos-elicitados">Técnica de Análise de Interface - RFA6</a> | Sessão de Análise de Interface gerou RFA6, que originou RF06 |
| RF06E2   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">Técnica de Brainstorming - RFB22</a> | Sessão de Brainstorming gerou RFB22, que originou RF06 |
| RF06E3   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito recebeu a prioridade de 7,959 |
| RF06E4   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito RF06 recebeu a classificação "Must have" (deve ter) |
| RF06E5   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $1,00 |
| RF06E6   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade N/A, pois já está implementado |
| RF06E7   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 2 votos |
| RF06E8   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF06E9   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 8 |
| RF06E10   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se aos Léxicos L01, L04, L05 e L06 |
| RF06E11  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US18: Favoritar e visualizar indicadores" |
| RF06E12  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | Requisito traduzido como User Story US18a e US18b no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### RF28: O usuário pode favoritar indicadores e visualizar as últimas atualizações.

<div style="text-align: justify; text-indent: 2cm;">A tabela 5 abaixo apresenta elos relacionados ao requisito <b>RF28: O usuário pode favoritar indicadores e visualizar as últimas atualizações.</b></div>

<font size="3"><p style="text-align: center">Tabela 5: Tabela de elos do RF28. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF28E1   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">Técnica de Brainstorming - RFB8</a> | Sessão de Brainstorming gerou RFB8, que originou RF28 |
| RF28E2   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito recebeu a prioridade de 6,675 |
| RF28E3   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito recebeu a classificação "Should have" (deveria ter) |
| RF28E4   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $1,00 |
| RF28E5   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Baixa" |
| RF28E6   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 3 votos |
| RF28E7   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF28E8   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 8 |
| RF28E9   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se aos Léxicos L01, L04, L05 e L06 |
| RF28E10  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US18: Favoritar e visualizar indicadores" |
| RF28E11  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | Requisito traduzido como User Story US18a e US18b no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### RF51: Opção de modo noturno

<div style="text-align: justify; text-indent: 2cm;">A tabela 6 abaixo apresenta elos relacionados ao requisito <b>RF51: Opção de modo noturno.</b></div>

<font size="3"><p style="text-align: center">Tabela 6: Tabela de elos do RF51. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF51E1   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">Técnica de Brainstorming - RFB4</a> | Sessão de Brainstorming gerou RFB4, que originou RF51 |
| RF51E2   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#4-requisitos-elicitados">Técnica de Entrevista - RFE10</a> | Entrevista gerou RFE10, que originou RF51 |
| RF51E3   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#3-requisitos-elicitados">Técnica de Questionário - RFQ06</a> | Aplicação de questionário gerou RFQ06, que originou RF51 |
| RF51E4   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito recebeu a prioridade de 12,314 |
| RF51E5   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito recebeu a classificação "Could have" (poderia ter) |
| RF51E6   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $0,50 |
| RF28-E7   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Alta" |
| RF51E8   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 1 voto |
| RF51E9   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF51E10   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 10 |
| RF51E11   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se ao Léxico L08 |
| RF51E12  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US19: Ativar modo noturno (Não Implementado)" |
| RF51E13  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | Requisito traduzido como User Story US19 no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### RF53: Opção de alterar o tamanho da fonte (com botão)

<div style="text-align: justify; text-indent: 2cm;">A tabela 7 abaixo apresenta elos relacionados ao requisito <b>RF53: Opção de alterar o tamanho da fonte (com botão).</b></div>

<font size="3"><p style="text-align: center">Tabela 7: Tabela de elos do RF53. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF51E1   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">Técnica de Brainstorming - RFB5</a> | Sessão de Brainstorming gerou RFB5, que originou RF53 |
| RF51E2   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#4-requisitos-elicitados">Técnica de Entrevista - RFE11</a> | Entrevista gerou RFE11, que originou RF53 |
| RF51E3   | Desenvolvimento | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#3-requisitos-elicitados">Técnica de Questionário - RFQ08</a> | Aplicação de questionário gerou RFQ08, que originou RF53 |
| RF51E4   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito recebeu a prioridade de 11.083 |
| RF51E5   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito recebeu a classificação "Must have" (deve ter) |
| RF51E6   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu 	$2,00 |
| RF28-E7   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Alta" |
| RF51E8   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 3 votos |
| RF51E9   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF51E10   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 9 |
| RF51E11   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se ao Léxico L09 |
| RF56E10  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US20: Alterar o tamanho da fonte (Não Implementado)" |
| RF56E11  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | Requisito traduzido como User Story US20 no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### RF56: Explicações simplificadas sobre os termos técnicos

<div style="text-align: justify; text-indent: 2cm;">A tabela 8 abaixo apresenta elos relacionados ao requisito <b>RF56: O sistema deve disponibilizar explicações simplificadas sobre os termos técnicos.</b></div>

<font size="3"><p style="text-align: center">Tabela 8: Tabela de elos do RF56. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF56E1   | Desenvolvimento | Recurso    | <a href=""https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#4-requisitos-elicitados">Técnica de Entrevista - RFE02</a> | Entrevista gerou RFE02, que originou RF56 |
| RF56E2   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito recebeu a prioridade de 18,471 |
| RF56E3   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito recebeu a classificação "Should have" (deveria ter) |
| RF56E4   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu 	$2,00 |
| RF56E5   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Alta" |
| RF56E6   | Gerencial | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 1 voto |
| RF56E7   | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF56E10  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US21: Explicações simplificadas sobre termos técnicos (Não Implementado)" |
| RF56E11  | Desenvolvimento | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | Requisito traduzido como User Story US21 no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

###  RF30: Possibilidade de responder a questionários relacionados ao censo diretamente pelo app.

<div style="text-align: justify; text-indent: 2cm;">A tabela 9 abaixo apresenta elos relacionados ao requisito <b>RF30: Possibilidade de responder ao censo diretamente pelo app.</b></div>

<font size="3"><p style="text-align: center">Tabela 9: Tabela de elos do RF30. </p></font>


| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|----------------|------------------------------------------|-----------------------------------------|
| RF30E1   |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">Técnica de Brainstorming - RFB8</a> | Sessão de Brainstorming gerou RFB14, que originou RF30 |
| RF30E3   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito RF32 recebeu a prioridade de 6,024 |
| RF30E4   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito RF30 recebeu a classificação "Must have" (deve ter) |
| RF30E5  |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $2,00 |
| RF30E6  |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Baixa" |
| RF30E7  |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 4 votos |
| RF30E8  |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF30E9  |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 6 |
| RF30E10 |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se aos Léxicos L10 e L11 |
| RF30E11 |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US06: "Realizar Censo" |
| RF30E12 |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | RF30 traduzido como User Story US06 no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### RF04: A notícia deve estar na aba de notícias do aplicativo

A tabela 10 abaixo apresenta elos relacionados ao requisito RF04: A notícia deve estar na aba de notícias do aplicativo.

<font size="3"><p style="text-align: center">Tabela 10: Tabela de elos do RF04. </p></font>

| ID do Elo | Nível          | Tipo de Elo     | Artefato / Elemento Relacionado                                                                 | Observações                                                                 |
|-----------|----------------|------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| RF04E1    | Desenvolvimento| Recurso         | [Análise de Interface - RFA3](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/) | Sessão propôs navegação por abas. |
| RF04E2    | Gerencial      | Recurso         | [MoSCoW](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/) | Classificado como “Must Have”. |
| RF04E3    | Desenvolvimento| Representação   | [Histórias do Usuário – US07](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/) | Relacionado à exibição de notícias. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### RF05: Navbar inferior com funcionalidades principais

A tabela 11 abaixo apresenta elos relacionados ao requisito RF05: Navbar inferior com funcionalidades principais.

<font size="3"><p style="text-align: center">Tabela 11: Tabela de elos do RF05. </p></font>

| ID do Elo | Nível          | Tipo de Elo     | Artefato / Elemento Relacionado                                                                 | Observações                                                                 |
|-----------|----------------|------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| RF05E1    | Desenvolvimento| Recurso         | [Brainstorming - RFB15](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/) | Sugestão sobre usabilidade. |
| RF05E2    | Gerencial      | Recurso         | [First Things First](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/) | Prioridade alta atribuída. |
| RF05E3    | Desenvolvimento| Representação   | [Diagrama de Casos de Uso](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/) | Presente no caso de uso "Navegar entre abas". |
| RF05E4    | Desenvolvimento| Representação   | [Cenários](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/) | Representado no Cenário 2. |
| RF05E5    | Desenvolvimento| Representação   | [User Story US05](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/) | Aborda navegação por navbar inferior. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### RF07: Gráfico com evolução temporal do indicador

A tabela 12 abaixo apresenta elos relacionados ao requisito RF07: Gráfico com evolução temporal do indicador.

<font size="3"><p style="text-align: center">Tabela 12: Tabela de elos do RF07. </p></font>

| ID do Elo | Nível          | Tipo de Elo     | Artefato / Elemento Relacionado                                                                 | Observações                                                                 |
|-----------|----------------|------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| RF07E1    | Desenvolvimento| Recurso         | [Brainstorming - RFB2](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/) | Sugestão de visualização temporal. |
| RF07E2    | Gerencial      | Recurso         | [Votação](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/) | Requisito recebeu votos. |
| RF07E3    | Desenvolvimento| Representação   | [User Story US15](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/) | Trata da exibição de gráfico detalhado. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### RF36: Exportar gráficos e resumos em PDF

A tabela 13 abaixo apresenta elos relacionados ao requisito RF36: Exportar gráficos e resumos em PDF.

<font size="3"><p style="text-align: center">Tabela 13: Tabela de elos do RF36. </p></font>

| ID do Elo | Nível          | Tipo de Elo     | Artefato / Elemento Relacionado                                                                 | Observações                                                                 |
|-----------|----------------|------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| RF36E1    | Desenvolvimento| Recurso         | [Questionário – RFQ12](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/) | Solicitado pelos usuários. |
| RF36E2    | Gerencial      | Recurso         | [MoSCoW](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/) | Classificado como Should Have. |
| RF36E3    | Desenvolvimento| Representação   | [User Story US30](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/) | Exportação em PDF descrita. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### RF41: Exibir conteúdos de redes sociais

A tabela 14 abaixo apresenta elos relacionados ao requisito RF41: Exibir conteúdos de redes sociais.

<font size="3"><p style="text-align: center">Tabela 14: Tabela de elos do RF41. </p></font>

| ID do Elo | Nível          | Tipo de Elo     | Artefato / Elemento Relacionado                                                                 | Observações                                                                 |
|-----------|----------------|------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| RF41E1    | Desenvolvimento| Recurso         | [Entrevista – RFE04](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/) | Solicita integração com mídias. |
| RF41E2    | Gerencial      | Recurso         | [100 Dólares](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/) | Valor médio: $0,75. |
| RF41E3    | Desenvolvimento| Representação   | [User Story US27](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/) | Está descrito como história de integração. |
| RF41E4    | Desenvolvimento| Representação   | [Léxicos](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/) | Associado a termos: YouTube, TikTok. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### RF49: Compartilhar métricas com fonte IBGE

A tabela 15 abaixo apresenta elos relacionados ao requisito RF49: Compartilhar métricas com fonte IBGE.

<font size="3"><p style="text-align: center">Tabela 15: Tabela de elos do RF49. </p></font>

| ID do Elo | Nível          | Tipo de Elo     | Artefato / Elemento Relacionado                                                                 | Observações                                                                 |
|-----------|----------------|------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| RF49E1    | Desenvolvimento| Recurso         | [Brainstorming – RFB7](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/) | Proposto como funcionalidade. |
| RF49E2    | Gerencial      | Recurso         | [3 Níveis](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/) | Classificação: Alta. |
| RF49E3    | Desenvolvimento| Representação   | [User Story US31](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/) | Presente no backlog ágil. |
| RF49E4    | Desenvolvimento| Representação   | [Léxicos](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/) | Termo relacionado a fonte de dados IBGE. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### RF43: O sistema deve permitir a comparação dos censos realizados em diferentes anos.

<div style="text-align: justify; text-indent: 2cm;">A tabela 16 abaixo apresenta elos relacionados ao requisito <b>RF43: O sistema deve permitir a comparação dos censos realizados em diferentes anos.</b></div>

<font size="3"><p style="text-align: center">Tabela 16: Tabela de elos do RF43. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|---------|------------------------------------------|-----------------------------------------|
| RF43E1   |      | Recurso    | [Técnica de Introspecção - RFI16](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao) | Sessão de Brainstorming gerou RFB12, que originou RF43 |
| RF43E2   |      | Recurso    | [First Things First](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/) | O Requisito RF43 recebeu a prioridade de X,XXX |
| RF43E3   |      | Recurso    | [MoSCoW](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/) | O Requisito RF43 recebeu a classificação "X have" |
| RF43E4   |      | Recurso    | [100 Dólares](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/) | O Requisito recebeu $X,XX |
| RF43E5   |      | Recurso    | [Priorização por 3 Níveis](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/) | O Requisito recebeu prioridade "X" |
| RF43E6   |      | Recurso    | [Votação](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/) | O Requisito recebeu X votos |
| RF43E7   |      | Representação    | [Diagrama de Casos de Uso](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/) | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF43E8   |      | Representação    | [Cenários](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/) | O Requisito foi representado no Cenário X |
| RF43E9   |      | Representação    | [Léxicos](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/)  | O Requisito associa-se aos Léxicos LX e LY |
| RF43E10  |      | Representação    | [Histórias do Usuário](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/)  | O Requisito aparece na "USXX: Comparar censos históricos" |
| RF43E11  |      | Representação    | [Backlog do Produto](https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/)  | RF43 traduzido como User Story USXX no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>

### RF26: Central de Ajuda dentro do app, com informações sobre o uso do aplicativo.

<div style="text-align: justify; text-indent: 2cm;">A tabela 13 abaixo apresenta elos relacionados ao requisito <b>RF26: Central de Ajuda dentro do app, com informações sobre o uso do aplicativo.</b></div>

<font size="3"><p style="text-align: center">Tabela 13: Tabela de elos do RF26. </p></font>

| ID do Elo | Nível | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|-------|---------|------------------------------------------|-----------------------------------------|
| RF26E1   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA9</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#6-requisitos-elicitados">RFB6</a>| A Sessão de Brainstorming originou o RF26  |
| RF26E2   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito RF26 recebeu a prioridade de 4.804 |
| RF26E3   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito RF26 recebeu a classificação "Must have" (deve ter) |
| RF26E4   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $1,50 |
| RF26E5   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Alta" |
| RF26E6   |      | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 0 votos |
| RF26E7   |      | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se ao Léxicos L19 |

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>

## 4. Bibliografia

> SAYÃO, M.; LEITE, J.C.S.P. **Rastreabilidade de Requisitos**. Monografias em Ciência da Computação – Pontífica Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005. Disponível em: [https://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf](https://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf). Acesso em: 08 de junho de 2025.

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 26. UnB.

## 5. Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela 6: Histórico de versões</p></font>

<center>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     | Criação do documento | [Ludmila Nunes](https://github.com/ludmilaaysha)| 08/06/2025 | [Caio Duarte](https://github.com/caioduart3)  |
|1.1     | Adição dos elos do RF28 | [Ludmila Nunes](https://github.com/ludmilaaysha)| 08/06/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto)  |
|1.2     | Adição dos elos do RF30 | [Caio Duarte](https://github.com/caioduart3)  | 08/06/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha)  |
|1.3     | Adição dos elos do RF60 | [Mayara Marques](https://github.com/maymarquee)  | 08/06/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha)  |
|1.4    | Ajustes RF e RNF     | [Gabriel Pinto](https://github.com/GabrielSPinto) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 08/06/2025 | [Caio Duarte](https://github.com/caioduart3) |
|1.5     | Adição dos elos do RF09 | [Gabriel Pinto](https://github.com/GabrielSPinto)  | 14/06/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha)  |
|1.6  | Adição dos elos do RF43 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 22/06/2025 |  [Gabriel Pinto](https://github.com/GabrielSPinto)   |
|2.0  | Adição dos elos do RF01, RF06, RF51, RF53 e RF56 e dos niveis da informação | [Ludmila Nunes](https://github.com/ludmilaaysha) | 06/07/2025 |  [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|2.1  | Exclusão dos elos anteriores e Adição dos elos do RF04, RF05, RF07, RF36, RF41 e RF49 | [Gabriel Pinto](https://github.com/GabrielSPinto) | 06/07/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|2.2  | Adição do elo RF26  | [Laryssa Felix](https://github.com/felixlaryssa) | 06/07/2025 |  [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |

</center>

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>
