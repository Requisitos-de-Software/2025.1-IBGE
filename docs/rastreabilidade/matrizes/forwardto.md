
## 1. Introdução
A rastreabilidade forward-to (para frente) refere-se à ligação entre os documentos gerados durante o processo de elicitação — como aqueles do plano de negócios — e os requisitos relevantes do sistema. Em outras palavras, ela traça um caminho que parte do domínio de negócio e avança em direção à especificação dos requisitos funcionais e não funcionais.

## 2. Legenda

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


## 2. Forward to
<font size="3"><p style="text-align: center">Tabela 1: Forward To</p></font>

|  Fonte | Requisito    | Descrição | Implementado |
|-------|-----------|------------------|--------------|
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA1</a> | RF01  | O sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA2</a>  | RF02  | Sistema deve possuir uma funcionalidade de busca, que independe da tela em que o usuário se encontra.| Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA3</a> | RF03  | Se houver algum dado/indicador atrelado à notícia lida, esse indicador deve estar presente no topo da página da notícia. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA4</a> | RF04  | A notícia deve estar na aba de notícias do aplicativo. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA5</a> | RF05  | O aplicativo deve possuir uma navbar inferior que permita que o usuário navegue pelas diversas funcionalidades principais da aplicação. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA6</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB22</a> | RF06  | Sistema deve possuir a aba de indicadores, com principais dados do IBGE, prévia de gráfico e valor com coloração simbólica (verde/vermelha). | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA7</a> | RF07  | Ao clicar no dado, deve aparecer gráfico mais completo com evolução temporal do indicador. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA8</a> | RF08  | Notícias relacionadas ao dado devem aparecer na tela do dado. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA9</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB3</a> | RF09  | Ao lado do nome do indicador, deve aparecer a definição daquele indicador. | Sim |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA10</a> | RF10 | Uma aba de calendário deve estar presente, com eventos/pesquisas principais do IBGE. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA12</a> | RF11 | Cada dado da aba de síntese deve possuir uma fonte atrelada. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA13</a> | RF12 | Uma aba de extras deve existir. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA14</a> | RF13 |O sistema deve oferecer opção de controle de notificações (ativar ou desativar). | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA15</a> | RF14 | O sistema deve notificar o usuário sobre novas notícias.  | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA16</a> | RF15 | Deve haver uma opção de avaliação do aplicativo com coleta de perfil, satisfação, funcionalidades mais usadas e sugestões.  | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA17</a>  | RF16 | Deve haver uma opção de compartilhar o aplicativo. | Sim |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA18</a> | RF17 | Uma opção de suporte deve existir, com ligação ao site do IBGE. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA19</a>  | RF18 | As redes sociais do IBGE devem ser linkadas. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA20</a> | RF19 | As notícias devem ser compartilháveis.| Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA21</a> | RF20 | No calendário, os dias com evento/pesquisa devem ter cor diferente dos demais. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA22</a>  | RF21 | O calendário deve permitir visualização de meses passados e futuros em relação ao mês atual. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA23</a> | RF22 | Na aba “síntese”, dados como gentílico, área territorial, população, renda, orçamento, IDH, matrículas, salário médio, PIB per capita e mortalidade infantil devem estar disponíveis por estado e município. | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA24</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB9</a> | RF23 | Filtros por país, estado e município devem estar disponíveis na aba “síntese”.  | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB1</a>  | RF24 | Jogos educativos sobre geografia, demografia e temas sociais. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB2</a> | RF25 | Modo offline para uso do aplicativo sem conexão com a internet. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB6</a> | RF26 | Central de Ajuda dentro do app, com informações sobre o uso do aplicativo.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB7</a>  | RF27 | Notificações para notícias relevantes e atualizações dos indicadores favoritos.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB8</a> | RF28 | O usuário pode favoritar indicadores e visualizar as últimas atualizações. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB10</a> | RF29 | Comparativo de indicadores por região. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB11</a>  | RF30 | Possibilidade de responder a questionários relacionados ao censo diretamente pelo app. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB12</a> | RF31 | Possibilidade de realizar e preencher questionários diretamente no aplicativo. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB15</a>  | RF32 | Integração com outras fontes como sites ou APIs externas (ex: dados de transporte público).| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB16</a>  | RF33 | Acesso a dados de diferentes fontes como o IBGE, através do app.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB17</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB19</a> | RF34 | Mapas interativos, com visualização de dados geográficos e demográficos. | Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB18</a>  | RF35 | Possibilidade de filtro por tipo de dado.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB20</a>  | RF36 | Possibilidade de exportar gráficos e resumos em formatos como PDF.| Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB21</a> | RF37 | Computar informações de dados e gerar relatórios para exportação. | Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI1</a> | RF38 | O sistema deve apresentar os indicadores sociais e agropecuários. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI2</a> | RF39 | O sistema deve filtrar notícias por região e/ou tempo.  | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI3</a> | RF40 | O sistema deve apresentar mais dados na seção síntese para os respectivos locais (estado, município), como IDH, total de veículos, governante, entre outros, semelhante ao site de referência. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI4</a> | RF41 | O sistema deve exibir conteúdos produzidos para outras plataformas, como YouTube, TikTok e Instagram, em uma aba dedicada. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI5</a> | RF42 | O sistema deve analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI6</a> | RF43 |O sistema deve permitir a comparação dos censos realizados em diferentes anos.  | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI7</a>  | RF44 | O sistema deve exibir uma confirmação sobre a identidade do recenseador.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI8</a>  | RF45 | O sistema deve realizar estudos preditivos com base nos dados atuais.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI9</a> | RF46 | O sistema deve informar quais fatores influenciam o aumento ou a diminuição de determinado indicador. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI10</a> | RF47 | O sistema deve indicar políticas públicas com base na análise dos dados adquiridos. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#anchor_I">RFI11</a> | RF48 | O sistema deve comparar os locais com maior e menor taxa de resposta ao censo. | Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ01</a>  | RF49 | Compartilhamento de métricas do aplicativo com a fonte atrelada ao IBGE.| Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB13</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB14</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ04</a>   | RF50 | Possibilidade de realizar o próximo censo pelo aplicativo| Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB4</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE10</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ06</a> | RF51 | Opção de modo noturno.  | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ07</a> | RF52 | Opção de mudança de idiomas (Português, Inglês, Espanhol)  | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB5</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE11</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ08</a> | RF53 | Opção de alterar o tamanho da fonte (com botão).| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB5</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE11</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#anchor_Q">RFQ09</a> | RF54 | Opção de alto contraste do aplicativo (com botão). | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE01</a>  | RF55 | O sistema deve permitir busca refinada por dados e publicações.| Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE02</a> | RF56 | O sistema deve disponibilizar explicações simplificadas sobre os termos técnicos.  | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB23</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE03</a>| RF57 | O sistema deve integrar-se com a conta Gov.br. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE04</a> | RF58 | O sistema deve permitir o compartilhamento de gráficos com link da fonte. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#anchor_A">RFA11</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE05</a> | RF59 |O sistema deve permitir a consulta a dados demográficos e indicadores por nível territorial detalhado. | Sim |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE05</a> | RF60 | O sistema deve possuir uma FAQ com respostas às dúvidas mais comuns. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE07</a> | RF61 |O sistema deve apresentar os dados do Censo de forma visual e interativa (ex: infográficos, gráficos).  | Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE08</a> | RF62 |O sistema deve permitir acesso às publicações completas de cada pesquisa com a metodologia detalhada. | Não |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE09</a> | RF63 |O sistema deve integrar todos ou a maioria dos aplicativos utilizados na coleta de dados de pesquisas. | Não |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE01</a> | RNF01 | O sistema deve estar disponível de forma estável, sem travamentos ou quedas frequentes.  | Sim |
<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE02</a> | RNF02 | O sistema deve permitir uso fluido tanto em computadores quanto em dispositivos móveis.  | Sim |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE04</a> | RNF03 |O sistema deve ser compatível com ferramentas de acessibilidade (áudio, Libras). | | Parcialmente |
 <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_EN">RNFE05</a> | RNF04 | O sistema deve garantir que usuários com baixo letramento estatístico consigam utilizar a interface. | Não |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

## 4. Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela 2: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
| 1.0    | Criação do documento     | [Caio Duarte](https://github.com/caioduart3) | 06/06/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>
