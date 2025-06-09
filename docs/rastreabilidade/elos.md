# Elos de Rastreabilidade

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">A rastreabilidade de requisitos é fundamental na engenharia de software, pois permite acompanhar sua origem, evolução e validação ao longo do projeto. Os elos entre requisitos e demais artefatos facilitam a compreensão do sistema, a análise de mudanças e o alinhamento com as necessidades dos <i>stakeholders</i>. 
</div> <div style="text-align: justify; text-indent: 2cm;">Este documento apresenta os elos de rastreabilidade conforme o <b>Meta-modelo de Toranzo</b> (SAYÃO e LEITE, 2005), que será melhor apresentado mais adiante.</div>


## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">O meta-modelo de Toranzo estrutura a rastreabilidade como um conjunto de “Elementos” genéricos — que podem ser requisitos, documentos, código, testes ou qualquer artefato — e “Relacionamentos” que ligam pares desses elementos. Cada relacionamento recebe um rótulo que descreve seu propósito, o qual pode ser:</div>

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
| [Caio Duarte](https://github.com/caioduart3)            | 08/06/2025 | 10:00 | Elaborador dos elos                                       |
| [Gabriel Pinto](https://github.com/GabrielSPinto)       | 08/06/2025 | 10:00 | Elaborador dos elos                                       |
| [João Félix](https://github.com/joaofmoreiraa)          | 08/06/2025 | 10:00 | Elaborador dos elos                                       |
| [Laryssa Felix](https://github.com/felixlaryssa)        | 08/06/2025 | 10:00 | Elaborador dos elos                                       |
| [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 08/06/2025 | 10:00 | Elaborador dos elos                                       |
| [Ludmila Nunes](https://github.com/ludmilaaysha)        | 08/06/2025 | 10:00 | Elaborador dos elos                                       |
| [Mayara Marques](https://github.com/maymarquee)         | 08/06/2025 | 10:00 | Elaborador dos elos                                       |

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
| RF*-EX    | Tipo de Elo    | Nome do artefato ou elemento relacionado | Comentário ou detalhe útil              |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

## 3. Elos de Rastreabilidade

<div style="text-align: justify; text-indent: 2cm;">Esta seção apresenta alguns elos com base nos requisitos elicitados e artefatos produzidos.</div>

### RF28: O usuário pode favoritar indicadores e visualizar as últimas atualizações.

| ID do Elo | Tipo de Elo    | Artefato / Elemento Relacionado          | Observações                             |
|-----------|----------------|------------------------------------------|-----------------------------------------|
| RF28-E1    | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">Técnica de Brainstorming - RFB8</a> | Sessão de Brainstorming gerou RFB8, que originou RF28 |
| RF28-E2    | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/first_things_first/">First Things First</a> | O Requisito RF28 recebeu a prioridade de 6,675 |
| RF28-E3    | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/moscow/">MoSCoW</a> | O Requisito RF28 recebeu a classificação "Should have" (deveria ter) |
| RF28-E4    | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/%24100/">100 Dólares</a> | O Requisito recebeu $1,00 |
| RF28-E5    | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/priorização_por_3_níveis/">Priorização por 3 Níveis</a> | O Requisito recebeu prioridade "Baixa" |
| RF28-E6    | Recurso    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/priorizacao_selecionadas/votacao/">Votação</a> | O Requisito recebeu 3 votos |
| RF28-E7    | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases/">Diagrama de Casos de Uso</a> | O Requisito foi representado no Diagrama de Casos de Uso para Requisitos Não Implementados |
| RF28-E8    | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/cenarios/">Cenários</a> | O Requisito foi representado no Cenário 8 |
| RF28-E9    | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/lexicos/">Léxicos</a>  | O Requisito associa-se aos Léxicos L01, L04, L05 e L06 |
| RF28-E10    | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a>  | O Requisito aparece na "US18: Favoritar e visualizar indicadores" |
| RF28-E11    | Representação    | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/productBacklog/">Backlog do Produto</a>  | RF28 traduzido como User Story US18a e US18b no backlog ágil |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

## 4. Bibliografia

> SAYÃO, M.; LEITE, J.C.S.P. **Rastreabilidade de Requisitos**. Monografias em Ciência da Computação – Pontífica Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005. Disponível em: [https://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf](https://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf). Acesso em: 08 de junho de 2025.

<br>

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 26. UnB.

## 5. Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela X: Histórico de versões</p></font>

<center>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     | Criação do documento | [Ludmila Nunes](https://github.com/ludmilaaysha)| 08/06/2025 | [Caio Duarte](https://github.com/caioduart3)  |
|1.1     | Adição dos elos do RF28 | [Ludmila Nunes](https://github.com/ludmilaaysha)| 08/06/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto)  |

</center>

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>
