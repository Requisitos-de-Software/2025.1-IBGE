# Requisitos Elicitados 
## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">
Esse arquivo visa listar todos os requisitos elicitados com as técnicas de <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/">Análise de Interface do Usuário</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/">Brainstorming</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/">Introspecção</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/">Questionário</a> e <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/">Entrevista</a>. 
</div>

## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">
Como citado anteriormente, os requisitos foram elicitados pelas técnicas escolhidas pelo grupo. Na tabela 1, a listagem desses requisitos pode ser observada, cada um com seu ID próprio, descrição, um hyperlink de rastreabilidade para a(s) técnica(s) que o elicitou e se ele foi implementado ou não na aplicação atual. 
</div>

### 2.1 Legendas

<div style="text-align: justify; text-indent: 2cm;">
A legenda para cada sigla é a seguinte:
</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;">
<ul>
<li>RF* - Requisito Funcional nº*
<li>RNF* - Requisito Não Funcional nº*  
<li>RFA* - Requisito Funcional de Análise de Interface nº*
<li>RFB* - Requisito Funcional de Brainstorming nº*
<li>RFI* -  Requisito Funcional de Instrospecção nº* 
<li>RFQ* -  Requisito Funcional de Questionário nº*
<li>RFE* -  Requisito Funcional de Entrevista nº*
<li>RNFE* -  Requisito Não Funcional de Entrevista nº*
</ul>
</div>


## 3. Requisitos Elicitados

<font size="3"><p style="text-align: center">Tabela 1: Requisitos elicitados</p></font>

<center>

| ID    | Descrição | Rastreabilidade | Implementado |
|-------|-----------|------------------|--------------|
| RF01  | O sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA1</a> | Sim |
| RF02  | Sistema deve possuir uma funcionalidade de busca, que independe da tela em que o usuário se encontra. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA2</a> | Sim |
| RF03  | Se houver algum dado/indicador atrelado à notícia lida, esse indicador deve estar presente no topo da página da notícia. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA3</a> | Sim |
| RF04  | A notícia deve estar na aba de notícias do aplicativo. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA4</a> | Sim |
| RF05  | O aplicativo deve possuir uma navbar inferior que permita que o usuário navegue pelas diversas funcionalidades principais da aplicação. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA5</a> | Sim |
| RF06  | Sistema deve possuir a aba de indicadores, com principais dados do IBGE, prévia de gráfico e valor com coloração simbólica (verde/vermelha). | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA6</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB22</a> | Sim |
| RF07  | Ao clicar no dado, deve aparecer gráfico mais completo com evolução temporal do indicador. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA7</a> | Sim |
| RF08  | Notícias relacionadas ao dado devem aparecer na tela do dado. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA8</a> | Sim |
| RF09  | Ao lado do nome do indicador, deve aparecer a definição daquele indicador. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA9</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB3</a> | Sim |
| RF10 | Uma aba de calendário deve estar presente, com eventos/pesquisas principais do IBGE. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA10</a> | Sim |
| RF11 | Cada dado da aba de síntese deve possuir uma fonte atrelada. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA12</a> | Sim |
| RF12 | Uma aba de extras deve existir. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA13</a> | Sim |
| RF13 |O sistema deve oferecer opção de controle de notificações (ativar ou desativar). | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA14</a> | Sim |
| RF14 | O sistema deve notificar o usuário sobre novas notícias. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA15</a> | Sim |
| RF15 | Deve haver uma opção de avaliação do aplicativo com coleta de perfil, satisfação, funcionalidades mais usadas e sugestões. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA16</a> | Sim |
| RF16 | Deve haver uma opção de compartilhar o aplicativo. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA17</a> | Sim |
| RF17 | Uma opção de suporte deve existir, com ligação ao site do IBGE. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA18</a> | Sim |
| RF18 | As redes sociais do IBGE devem ser linkadas. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA19</a> | Sim |
| RF19 | As notícias devem ser compartilháveis. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA20</a> | Sim |
| RF20 | No calendário, os dias com evento/pesquisa devem ter cor diferente dos demais. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA21</a> | Sim |
| RF21 | O calendário deve permitir visualização de meses passados e futuros em relação ao mês atual. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA22</a> | Sim |
| RF22 | Na aba “síntese”, dados como gentílico, área territorial, população, renda, orçamento, IDH, matrículas, salário médio, PIB per capita e mortalidade infantil devem estar disponíveis por estado e município. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA23</a> | Sim |
| RF23 | Filtros por país, estado e município devem estar disponíveis na aba “síntese”. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA24</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB9</a> | Sim |
| RF24 | Jogos educativos sobre geografia, demografia e temas sociais. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB1</a> | Não |
| RF25 | Modo offline para uso do aplicativo sem conexão com a internet. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB2</a> | Não |
| RF26 | Central de Ajuda dentro do app, com informações sobre o uso do aplicativo | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB6</a> | Não |
| RF27 | Notificações para notícias relevantes e atualizações dos indicadores favoritos. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB7</a> | Não |
| RF28 | O usuário pode favoritar indicadores e visualizar as últimas atualizações. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB8</a> | Não |
| RF29 | Comparativo de indicadores por região. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB10</a> | Não |
| RF30 | Possibilidade de responder a questionários relacionados ao censo diretamente pelo app. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB11</a> | Não |
| RF31 | Possibilidade de realizar e preencher questionários diretamente no aplicativo. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB12</a> | Não |
| RF32 | Integração com outras fontes como sites ou APIs externas (ex: dados de transporte público). | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB15</a> | Não |
| RF33 | Acesso a dados de diferentes fontes como o IBGE, através do app. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB16</a> | Não |
| RF34 | Mapas interativos, com visualização de dados geográficos e demográficos. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB17</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB19</a> | Não |
| RF35 | Possibilidade de filtro por tipo de dado. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB18</a> | Não |
| RF36 | Possibilidade de exportar gráficos e resumos em formatos como PDF. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB20</a> | Não |
| RF37 | Computar informações de dados e gerar relatórios para exportação. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB21</a> | Não |
| RF38 | O sistema deve apresentar os indicadores sociais e agropecuários. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI1</a> | Não |
| RF39 | O sistema deve filtrar notícias por região e/ou tempo. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI2</a> | Não |
| RF40 | O sistema deve apresentar mais dados na seção síntese para os respectivos locais (estado, município), como IDH, total de veículos, governante, entre outros, semelhante ao site de referência. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI3</a> | Não |
| RF41 | O sistema deve exibir conteúdos produzidos para outras plataformas, como YouTube, TikTok e Instagram, em uma aba dedicada. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI4</a> | Não |
| RF42 | O sistema deve analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI5</a> | Não |
| RF43 |O sistema deve permitir a comparação dos censos realizados em diferentes anos. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI6</a> | Não |
| RF44 | O sistema deve exibir uma confirmação sobre a identidade do recenseador. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI7</a> | Não |
| RF45 | O sistema deve realizar estudos preditivos com base nos dados atuais. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI8</a> | Não |
| RF46 | O sistema deve informar quais fatores influenciam o aumento ou a diminuição de determinado indicador. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI9</a> | Não |
| RF47 | O sistema deve indicar políticas públicas com base na análise dos dados adquiridos. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI10</a> | Não |
| RF48 | O sistema deve comparar os locais com maior e menor taxa de resposta ao censo. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI11</a> | Não |
| RF49 | Compartilhamento de métricas do aplicativo com a fonte atrelada ao IBGE | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ01</a> | Não |
| RF50 | Possibilidade de realizar o próximo censo pelo aplicativo | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB13</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB14</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ04</a>  | Não |
| RF51 | Opção de modo noturno | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB4</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE10</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ06</a>  | Não |
| RF52 | Opção de mudança de idiomas (Português, Inglês, Espanhol) | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ07</a>  | Não |
| RF53 | Opção de alterar o tamanho da fonte (com botão) | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB5</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE11</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ08</a>   | Não |
| RF54 | Opção de alto contraste do aplicativo (com botão) | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB5</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE11</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ09</a>  | Não |
| RF55 | O sistema deve permitir busca refinada por dados e publicações. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE01</a> | Não |
| RF56 | O sistema deve disponibilizar explicações simplificadas sobre os termos técnicos. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE02</a> | Não |
| RF57 | O sistema deve integrar-se com a conta Gov.br. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB23</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE03</a> | Não |
| RF58 | O sistema deve permitir o compartilhamento de gráficos com link da fonte. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE04</a> | Não |
| RF59 |O sistema deve permitir a consulta a dados demográficos e indicadores por nível territorial detalhado. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA11</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE05</a>  | Sim |
| RF60 | O sistema deve possuir uma FAQ com respostas às dúvidas mais comuns. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE05</a> | Não |
| RF61 |O sistema deve apresentar os dados do Censo de forma visual e interativa (ex: infográficos, gráficos). | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE07</a> | Não |
| RF62 |O sistema deve permitir acesso às publicações completas de cada pesquisa com a metodologia detalhada. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE08</a> | Não |
| RF63 |O sistema deve integrar todos ou a maioria dos aplicativos utilizados na coleta de dados de pesquisas. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE09</a> | Não |
| RNF01 | O sistema deve estar disponível de forma estável, sem travamentos ou quedas frequentes. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE01</a> | Sim |
| RNF02 | O sistema deve permitir uso fluido tanto em computadores quanto em dispositivos móveis. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE02</a> | Sim |
| RNF03 |O sistema deve ser compatível com ferramentas de acessibilidade (áudio, Libras). | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE04</a> | Parcialmente |
| RNF04 | O sistema deve garantir que usuários com baixo letramento estatístico consigam utilizar a interface. | <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE05</a> | Não |


</center>

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>


## 4. Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela 2: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação da documento|[Mayara Marques](https://github.com/maymarquee)| 23/04/2025 | [Caio Duarte](https://github.com/caioduart3)  |
|1.1     |Inserção dos requisitos com rastreabilidade, ID e implementação|[Mayara Marques](https://github.com/maymarquee)| 03/05/2025 | [Caio Duarte](https://github.com/caioduart3)  |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>