## 1. Introdução
<div style="text-align: justify; text-indent: 2cm;"><b>Léxico</b> é uma técnica utilizada na Engenharia de Requisitos para descrever, de forma clara e padronizada, os termos e conceitos relevantes de um sistema (SERRANO et al.). Cada termo léxico representa um símbolo ou expressão da linguagem utilizada no domínio do problema, e sua definição facilita o entendimento comum entre os envolvidos no projeto, como desenvolvedores, usuários e <i>stakeholders</i>.</div>

## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">Como pode ser observado no cronograma apresentado na <b>Tabela 1</b> e de acordo com as características apontadas na <b>Seção 2.2.</b>, as integrantes <a href="https://github.com/ludmilaaysha">Ludmila Nunes</a> e <a href="https://github.com/maymarquee">Mayara Marques</a> foram responsáveis pelo desenvolvimento dos léxicos relacionados ao aplicativo do projeto.</div>

### 2.1. Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Cronograma de elaboradores dos léxicos</p></font>

<center>

| Nome                                                    |Data       | Hora  | Função                                                        | 
| ------------------------------------------------------- | ------------------------------------------------------------ | ---------- | ----- |
| [Ludmila Nunes](https://github.com/ludmilaaysha)        | 14/05/2025 | - | Elaboradora dos léxicos                                                | 
| [Mayara Marques](https://github.com/maymarquee)         | 14/05/2025 | - | Elaboradora dos léxicos                                                |

</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### 2.2. Abordagem utilizada

<div style="text-align: justify; text-indent: 2cm;">Para construção do Léxico, foi utilizada a notação <b>LAL – Léxico Ampliado da Linguagem</b>, que realiza a descrição de símbolos de uma linguagem via léxico. Para construir essa descrição, são utilizados alguns elementos, os quais incluem:</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;">
<ul>
    <li><b>Noção:</b> é a denotação do símbolo, ou seja, o que ele significa. Cada símbolo possui uma ou mais noções;</li>
    <li><b>Impacto:</b> é a conotação do símbolo, isto é, como a aplicação impacta o símbolo ou como o símbolo impacta a aplicação. Cada símbolo possui um ou mais impactos;</li>
    <li><b>Sinônimos:</b> como em dicionários, são palavras ou expressões com significados equivalentes ao do símbolo. Cada símbolo pode ter nenhum, um ou vários sinônimos;</li>
    <li><b>Tipo:</b> a LAL define quatro tipos de símbolos, os quais estão descritos na <b>Tabela 2</b>. Cada símbolo pertence a um, e somente um, tipo;</li>
    <li><b>Hiperlinks:</b> são links dentro do léxico que relacionam o símbolo a um requisito ou a outro símbolo léxico.</li>
</ul>
</div>


<font size="3"><p style="text-align: center">Tabela 2: Tipos de léxicos do LAL</p></font>

<center>

| Tipo           |Noção                                                                        | Impacto                    |
| -------------- | --------------------------------------------------------------------------- | -------------------------- |
| Sujeito        | Quem é o sujeito.                                                           | As ações que executa.       |
| Verbo          | Quem realiza, quando acontece e quais os procedimentos envolvidos.          | Quais os reflexos da ação do ambiente [...] e quais os novos estados decorrentes. |
| Objeto         | Definir o objeto e identificar os outros objetos com os quais se relaciona. | Ações que podem ser aplicadas ao objeto. |
| Estado         | O que significa e quais ações levaram a esse estado.                        | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve. |

</center>

<font size="2"><p style="text-align: center">Fonte: Adaptado de (SERRANO et al.).</p></font>

## 3. Léxicos

### <a>L01: Usuário</a>

<div style="text-align: justify; text-indent: 2cm;">O primeiro léxico, apresentado na Tabela 4, faz uso dos seguintes requisitos: o sistema deve possuir uma funcionalidade de busca, que independe da tela em que o usuário se encontra (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF02</a>), o aplicativo deve possuir uma <i>navbar</i> inferior que permita que o usuário navegue pelas diversas funcionalidades principais da aplicação (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF05</a>), o sistema deve notificar o usuário sobre novas notícias (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF14</a>), o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF28</a>), o sistema deve analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF42</a>) e o sistema deve garantir que usuários com baixo letramento estatístico consigam utilizar a interface (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF04</a>).</div>

<font size="3"><p style="text-align: center">Tabela 4: Léxico 01 – Usuário (L01)</p></font>

| L01                  | Descrição                                                                                                                                                                                                                                                                                                                        |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>         | Usuário                                                                                                                                                                                                                                                                                                                          |
| <b>Classificação</b> | Sujeito                                                                                                                                                                                                                                                                                                                          |
| <b>Impacto</b>       | O usuário pode navegar pelas abas através de uma <i>navbar</i>, buscar por informações dentro do aplicativo e visualizar indicadores, notícias e outros dados.<br>O usuário é capaz de escolher se deseja ou não receber notificações, favoritar seus indicadores preferidos, configurar notificações, idioma, aparência e mais. |
| <b>Noção</b>         | O usuário pode se enquadrar no <a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/usuarios/PerfilDoUsuario/">perfil do usuário</a><br>O usuário pode ser alguém que utiliza o sistema para consultar informações oferecidas pelo IBGE, como dados estatísticos, notícias e gráficos<br>                   |
| <b>Sinônimos</b>     | Pessoa, cidadão, visitante                                                                                                                                                                                                                                                                                                       |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>


### <a>L02: Sistema</a>

<div style="text-align: justify; text-indent: 2cm;">O segundo léxico, apresentado na Tabela 5, faz uso dos seguintes requisitos: o sistema deve apresentar os indicadores sociais e agropecuários (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF38</a>), filtrar notícias por região e/ou tempo (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF39</a>), apresentar mais dados na seção síntese para os respectivos locais (estado, município) semelhante ao site de referência (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF40</a>), analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF41</a>), integrar todos ou a maioria dos aplicativos utilizados na coleta de dados de pesquisas (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF63</a>) garantir estabilidade e uso fluido, sem travamentos ou quedas frequentes (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF01</a> e <a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF02</a>) e o sistema deve garantir que usuários com baixo letramento estatístico consigam utilizar a interface (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF04</a>).</div>

<font size="3"><p style="text-align: center">Tabela 5: Léxico 02 – Sistema (L02)</p></font>

| L02                  | Descrição                                                                                                                                |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>         | Sistema                                                                                                                                  |
| <b>Classificação</b> | Sujeito                                                                                                                                  |
| <b>Impacto</b>       | Executa automaticamente funções como exibir dados, notificar o usuário e processar informações.                                          |
| <b>Noção</b>         | A aplicação desenvolvida para oferecer acesso a dados demográficos, notícias, indicadores e outras funcionalidades relacionadas ao IBGE. |
| <b>Sinônimos</b>     | Aplicativo, plataforma, ferramenta                                                                                                       |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L03: Recenseador</a>

<div style="text-align: justify; text-indent: 2cm;">O terceiro léxico, apresentado na Tabela 6, faz uso do seguinte requisito: o sistema deve exibir uma confirmação sobre a identidade do recenseador (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF44</a>).</div>

<font size="3"><p style="text-align: center">Tabela 6: Léxico 03 – Recenseador (L03)</p></font>

| L03                  | Descrição                                                                                                                                |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>         | Recenseador                                                                                                                              |
| <b>Classificação</b> | Sujeito                                                                                                                                  |
| <b>Impacto</b>       | Responsável por realizar a coleta de dados do censo, podendo interagir com o sistema.<br>O recenseador realiza <i>login</i> no sistema.  |
| <b>Noção</b>         | Agente de campo que coleta dados durante o Censo e pode usar o sistema para se identificar, acompanhar rotas ou validar dados coletados. |
| <b>Sinônimos</b>     | Agente de pesquisa, coletor                                                                                                              |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L04: Personalizar notificações</a>

<div style="text-align: justify; text-indent: 2cm;">O quarto léxico, apresentado na Tabela 7, faz uso do seguinte requisito: o sistema deve oferecer opção de controle de notificações (ativar ou desativar) (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF13</a>).</div>

<font size="3"><p style="text-align: center">Tabela 7: Léxico 04 – Personalizar notificações (L04)</p></font>

| L04                  | Descrição                                                                                                                                                                           |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>         | Personalizar notificações                                                                                                                                                           |
| <b>Classificação</b> | Verbo                                                                                                                                                                               |
| <b>Impacto</b>       | Garante que o usuário (<a href="#l01-usuario">L01</a>) só receba alertas de seu interesse.                                                                                                  |
| <b>Noção</b>         | Ação que permite ao usuário (<a href="#l01-usuario">L01</a>) ativar ou desativar alertas de notícias (<a href="#l0X-">L0X</a>), dados e atualizações importantes conforme suas preferências. |
| <b>Sinônimos</b>     | Configurar alertas, Ajustar notificações                                                                                                                                            |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L05: Consultar indicador</a>

<div style="text-align: justify; text-indent: 2cm;">O quinto léxico, apresentado na Tabela 8, faz uso do seguinte requisito: comparativo de indicadores por região (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF27</a>), o sistema deve apresentar os indicadores sociais e agropecuários (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF38</a>), o sistema deve informar quais fatores influenciam o aumento ou a diminuição de determinado indicador (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF46</a>) e o sistema deve permitir a consulta a dados demográficos e indicadores por nível territorial detalhado (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF59</a>)</div>

<font size="3"><p style="text-align: center">Tabela 8: Léxico 05 – Consultar indicador (L05)</p></font>

| L05                  | Descrição                                                                                                                                                              |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>         | Consultar indicador                                                                                                                                                    |
| <b>Classificação</b> | Verbo                                                                                                                                                                  |
| <b>Impacto</b>       | Permite ao usuário (<a href="#l01-usuario">L01</a>) visualizar dados estatísticos atualizados e gráficos interativos.                                                          |
| <b>Noção</b>         | Ação em que o usuário (<a href="#l01-usuario">L01</a>) acessa a aba de indicadores para visualizar dados como IDH, PIB per capita, mortalidade, etc., com gráficos e definição |
| <b>Sinônimos</b>     | Acessar indicador, Ver indicador                                                                                                                                       |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

## 4. Conclusão

## 5. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf)>. Acesso em: 14 de maio 2025. p. 12–20.

<font size="3"><p style="text-align: center">Figura 1: Referência de Léxicos</p></font>

<center>

<img src="../../assets/images/modelagem/fonte_lexicos.png" width="400"/>

</center>

<font size="2"><p style="text-align: center;">Fonte: (SERRANO et al.).</p></font>

## Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela X: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     | Criação e estruturação do documento | [Ludmila Nunes](https://github.com/ludmilaaysha) | 14/05/2025 | [Mayara Marques](https://github.com/maymarquee) |
|1.1     | Ajustes de rotas e âncoras | [Ludmila Nunes](https://github.com/ludmilaaysha) | 16/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>