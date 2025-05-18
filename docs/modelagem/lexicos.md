<style>html{scroll-behavior: smooth;}</style>

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;"><b>Léxico</b> é uma técnica utilizada na Engenharia de Requisitos para descrever, de forma clara e padronizada, os termos e conceitos relevantes de um sistema (SERRANO et al.). Cada termo léxico representa um símbolo ou expressão da linguagem utilizada no domínio do problema, e sua definição facilita o entendimento comum entre os envolvidos no projeto, como desenvolvedores, usuários e <i>stakeholders</i>.</div>

## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">Como pode ser observado no cronograma apresentado na <b>Tabela 1</b> e de acordo com as características apontadas na <b>Seção 2.2.</b>, os integrantes do grupo foram responsáveis pelo desenvolvimento dos léxicos relacionados ao aplicativo do projeto. Além disso, o artefato foi validado pelo cliente Clístenes Mendonça, profissional da saúde e <b>mestrando em Saúde Pública</b> pela Escola Nacional de Saúde Pública da Fiocruz do Rio de Janeiro.</div>

### 2.1. Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Cronograma de elaboração e validação do artefato</p></font>

<center>

| Nome                                                    | Data       | Hora  | Função                                                        |
| ------------------------------------------------------- | ---------- | ----- | ------------------------------------------------------------- |
| [Caio Duarte](https://github.com/caioduart3)            | 16/05/2025 | 23:00 | Elaborador dos léxicos                                        |
| Clístenes Mendonça                                      | 17/05/2025 | 23:00 | Cliente                                                       |
| [Gabriel Pinto](https://github.com/GabrielSPinto)       | 17/05/2025 | 23:00 | Elaborador dos léxicos                                        |
| [João Félix](https://github.com/joaofmoreiraa)          | 18/05/2025 | 00:00 | Elaborador dos léxicos                                        |
| [Laryssa Felix](https://github.com/felixlaryssa)        | 18/05/2025 | 00:00 | Elaboradora dos léxicos                                       |
| [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 17/05/2025 | 23:00 | Elaboradora dos léxicos e participante da validação           |
| [Ludmila Nunes](https://github.com/ludmilaaysha)        | 17/05/2025 | 23:00 | Elaboradora dos léxicos e participante da validação           |
| [Mayara Marques](https://github.com/maymarquee)         | 17/05/2025 | 23:00 | Elaboradora dos léxicos e participante da validação           |

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

| Tipo    | Noção                                                                       | Impacto                                                                                  |
| ------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Sujeito | Quem é o sujeito.                                                           | As ações que executa.                                                                    |
| Verbo   | Quem realiza, quando acontece e quais os procedimentos envolvidos.          | Quais os reflexos da ação do ambiente [...] e quais os novos estados decorrentes.        |
| Objeto  | Definir o objeto e identificar os outros objetos com os quais se relaciona. | Ações que podem ser aplicadas ao objeto.                                                 |
| Estado  | O que significa e quais ações levaram a esse estado.                        | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve. |

</center>

<font size="2"><p style="text-align: center">Fonte: Adaptado de (SERRANO et al.).</p></font>

## 3. Léxicos

### <a>L01: Usuário</a>

<div style="text-align: justify; text-indent: 2cm;">O primeiro léxico, apresentado na Tabela 3, faz uso dos seguintes requisitos não-implementados: o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF28</a>), o sistema deve analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF42</a>) e o sistema deve garantir que usuários com baixo letramento estatístico consigam utilizar a interface (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF04</a>).</div>

<font size="3"><p style="text-align: center">Tabela 3: Léxico 01 – Usuário (L01)</p></font>

| L01              | Descrição                                                                                                                                                                                                                                                                                                                        |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Usuário                                                                                                                                                                                                                                                                                                                          |
| <b>Tipo</b>      | Sujeito                                                                                                                                                                                                                                                                                                                          |
| <b>Impacto</b>   | O usuário pode navegar pelas abas através de uma <i>navbar</i>, buscar por informações dentro do aplicativo e visualizar <a href="#l04-indicador">indicadores</a>, notícias e outros dados.<br>O usuário é capaz de escolher se deseja ou não receber notificações, <a href="#l06-favoritar-indicador">favoritar seus indicadores preferidos</a>, configurar notificações, idioma, aparência e mais. |
| <b>Noção</b>     | O usuário pode se enquadrar no <a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/usuarios/PerfilDoUsuario/">perfil do usuário</a><br>O usuário pode ser alguém que utiliza o <a href="#l02-sistema">sistema</a> para consultar informações oferecidas pelo IBGE, como dados estatísticos, notícias e gráficos<br>                   |
| <b>Sinônimos</b> | Pessoa, cidadão, visitante                                                                                                                                                                                                                                                                                                       |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L02: Sistema</a>

<div style="text-align: justify; text-indent: 2cm;">O segundo léxico, apresentado na Tabela 4, faz uso dos seguintes requisitos não-implementados: o sistema deve apresentar os indicadores sociais e agropecuários (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF38</a>), filtrar notícias por região e/ou tempo (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF39</a>), apresentar mais dados na seção síntese para os respectivos locais (estado, município) semelhante ao site de referência (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF40</a>), analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF41</a>), integrar todos ou a maioria dos aplicativos utilizados na coleta de dados de pesquisas (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF63</a>) garantir estabilidade e uso fluido, sem travamentos ou quedas frequentes (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF01</a> e <a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF02</a>) e o sistema deve garantir que usuários com baixo letramento estatístico consigam utilizar a interface (<a href ="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RNF04</a>).</div>

<font size="3"><p style="text-align: center">Tabela 4: Léxico 02 – Sistema (L02)</p></font>

| L02              | Descrição                                                                                                                                |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Sistema                                                                                                                                  |
| <b>Tipo</b>      | Sujeito                                                                                                                                  |
| <b>Impacto</b>   | Executa automaticamente funções como exibir dados, notificar o <a href="#l01-usuario">usuário</a> e processar informações.               |
| <b>Noção</b>     | A aplicação desenvolvida para oferecer acesso a dados demográficos, notícias, <a href="#l04-indicador">indicadores</a> e outras funcionalidades relacionadas ao IBGE. |
| <b>Sinônimos</b> | Aplicativo, plataforma, ferramenta                                                                                                       |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L03: Recenseador</a>

<div style="text-align: justify; text-indent: 2cm;">O terceiro léxico, apresentado na Tabela 5, faz uso do seguinte requisito não-implementado: o sistema deve exibir uma confirmação sobre a identidade do recenseador (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF44</a>).</div>

<font size="3"><p style="text-align: center">Tabela 5: Léxico 03 – Recenseador (L03)</p></font>

| L03              | Descrição                                                                                                                                |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Recenseador                                                                                                                              |
| <b>Tipo</b>      | Sujeito                                                                                                                                  |
| <b>Impacto</b>   | Responsável por realizar a coleta de dados do <a href="#l11-censo">censo</a>, podendo interagir com o <a href="#l02-sistema">sistema</a>.<br>O recenseador realiza <i>login</i> no sistema.  |
| <b>Noção</b>     | Agente de campo que coleta dados durante o Censo e pode usar o sistema para se identificar, acompanhar rotas ou validar dados coletados. |
| <b>Sinônimos</b> | Agente de pesquisa, coletor                                                                                                              |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L04: Indicador</a>

<div style="text-align: justify; text-indent: 2cm;">O quarto léxico, apresentado na Tabela 6, faz uso do seguinte requisitos implementados: se houver algum indicador atrelado à notícia, esse indicador deve estar no topo da página (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF03</a>), sistema deve possuir aba de indicadores (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF06</a>).</div>
<div style="text-align: justify; text-indent: 2cm;">E dos seguintes não-implementados: o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF28</a>), comparativo de indicadores por região (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF29</a>), o sistema deve apresentar indicadores sociais e agropecuários (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF38</a>) e o sistema deve informar quais fatores influenciam em determinado indicador (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF46</a>).</div>

<font size="3"><p style="text-align: center">Tabela 6: Léxico 04 – Indicador (L04)</p></font>

| L04              | Descrição                                                                                                                                                                                                                                                                                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Indicador                                                                                                                                                                                                                                                                                                                                                                                               |
| <b>Tipo</b>      | Objeto                                                                                                                                                                                                                                                                                                                                                                                                  |
| <b>Impacto</b>   | Serve como base para a visualização de dados relevantes do IBGE, permitindo ao <a href="#l01-usuario">usuário</a> compreender tendências demográficas, econômicas e sociais.                                                                                                                                                                                                                            |
| <b>Noção</b>     | Dado estatístico exibido na aba de indicadores, representando informações como IDH, PIB per capita, taxa de mortalidade infantil, entre outros. Pode ser visualizado de forma resumida ou expandida, com gráficos e coloração simbólica. Também pode ser <a href="#l05-consultar-indicador">consultado</a> e <a href="#l06-favoritar-indicador">favoritado</a> pelo <a href="#l01-usuario">usuário</a>. |
| <b>Sinônimos</b> | Dado estatístico, Métrica, Valor                                                                                                                                                                                                                                                                                                                                                                        |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### <a>L05: Consultar indicador</a>

<div style="text-align: justify; text-indent: 2cm;">O quinto léxico, apresentado na Tabela 7, faz uso dos seguintes requisitos não-implementados: comparativo de indicadores por região (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF27</a>), o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF28</a>), o sistema deve apresentar os indicadores sociais e agropecuários (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF38</a>), o sistema deve informar quais fatores influenciam o aumento ou a diminuição de determinado indicador (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF46</a>) e o sistema deve permitir a consulta a dados demográficos e indicadores por nível territorial detalhado (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF59</a>).</div>

<font size="3"><p style="text-align: center">Tabela 7: Léxico 05 – Consultar indicador (L05)</p></font>

| L05              | Descrição                                                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <b>Termo</b>     | Consultar indicador                                                                                                                                                      |
| <b>Tipo</b>      | Verbo                                                                                                                                                                    |
| <b>Impacto</b>   | Permite ao <a href="#l01-usuario">usuário</a> visualizar dados estatísticos atualizados e gráficos interativos.                                                          |
| <b>Noção</b>     | Ação em que o <a href="#l01-usuario">usuário</a> acessa a aba de <a href="#l04-indicador">indicadores</a> para visualizar dados como IDH, PIB per capita, mortalidade, etc., com gráficos e definição |
| <b>Sinônimos</b> | Acessar indicador, Ver indicador                                                                                                                                         |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L06: Favoritar indicador</a>

<div style="text-align: justify; text-indent: 2cm;">O sexto léxico, apresentado na Tabela 8, faz uso do seguinte requisito não-implementado: o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF28</a>).</div>

<font size="3"><p style="text-align: center">Tabela 8: Léxico 06 – Favoritar indicador (L06)</p></font>

| L06              | Descrição                                                                                                                                                                                                            |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Favoritar indicador                                                                                                                                                                                                  |
| <b>Tipo</b>      | Verbo                                                                                                                                                                                                                |
| <b>Impacto</b>   | Permite ao <a href="#l01-usuario">usuário</a> acessar rapidamente os <a href="#l04-indicador">indicadores</a> mais relevantes para seu perfil, facilitando o acompanhamento de suas atualizações.                                                 |
| <b>Noção</b>     | Ação realizada pelo <a href="#l01-usuario">usuário</a> ao selecionar um <a href="#l04-indicador">indicador</a> como favorito, o que o destaca para consultas futuras e permite acompanhar notificações relacionadas. |
| <b>Sinônimos</b> | Marcar indicador, Salvar indicador, Adicionar aos favoritos                                                                                                                                                          |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>


### <a>L07: Comparar indicador</a>

<div style="text-align: justify; text-indent: 2cm;">O sétimo léxico, apresentado na Tabela 9, faz uso do seguinte requisito não-implementado: comparativo de indicadores por região (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF29</a>).</div>

<font size="3"><p style="text-align: center">Tabela 9: Léxico 07 – Comparar indicador (L07)</p></font>

| L07              | Descrição                                                                                                                                                                                                            |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Comparar indicador                                                                                                                                                                                                  |
| <b>Tipo</b>      | Verbo                                                                                                                                                                                                                |
| <b>Impacto</b>   | Permite que o <a href="#l01-usuario">usuário</a> compare <a href="#l04-indicador">indicadores</a> por região, personalizando sua experiência e garantindo equidade na comparação de dados.                                                  |
| <b>Noção</b>     | Ação realizada pelo <a href="#l02-sistema">sistema</a> ao permitir que o <a href="#l01-usuario">usuário</a> <a href="#l05-consultar-indicador>"consulte indicadores</a> separados por regiões do Brasil. |
| <b>Sinônimos</b> | Contrastar indicador, examinar indicador.                                                                                                                                                         |

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### <a>L08: Modo noturno ativado</a>

<div style="text-align: justify; text-indent: 2cm;">O oitavo léxico, apresentado na Tabela 10, faz uso do seguinte requisito não-implementado: opção de modo noturno (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF51</a>).</div>

<font size="3"><p style="text-align: center">Tabela 10: Léxico 08 – Modo noturno ativado (L08)</p></font>

| L08              | Descrição                                                                                                                                                                             |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Modo noturno ativado                                                                                                                                                                  |
| <b>Tipo</b>      | Estado                                                                                                                                                                                |
| <b>Impacto</b>   | Altera o esquema de cores da interface para tons escuros, proporcionando maior conforto visual.                                                                                       |
| <b>Noção</b>     | Estado da interface quando o <a href="#l01-usuario">usuário</a> ativa o modo noturno, resultando em telas com cores escuras e texto claro, ideal para uso em ambientes com pouca luz. |
| <b>Sinônimos</b> | Tema escuro ativo, Interface escura, _Dark mode_ ativado                                                                                                                              |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L09: Alterar tamanho da fonte</a>

<div style="text-align: justify; text-indent: 2cm;">O nono léxico, apresentado na Tabela 11, faz uso do seguinte requisito não-implementado: opção de alterar o tamanho da fonte (com botão) (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF53</a>).</div>

<font size="3"><p style="text-align: center">Tabela 11: Léxico 09 – Alterar tamanho da fonte (L09)</p></font>

| L09              | Descrição                                                                                                                                                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Alterar tamanho da fonte                                                                                                                                                                                                  |
| <b>Tipo</b>      | Verbo                                                                                                                                                                                                                     |
| <b>Impacto</b>   | Proporciona maior acessibilidade e conforto visual, permitindo que o <a href="#l01-usuario">usuário</a> adapte a interface às suas necessidades.                                                                          |
| <b>Noção</b>     | Ação realizada pelo <a href="#l01-usuario">usuário</a> ao utilizar um botão para aumentar ou reduzir o tamanho da fonte exibida na interface do <a href="#l02-sistema">sistema</a>, visando melhor leitura e usabilidade. |
| <b>Sinônimos</b> | Ajustar fonte, Mudar tamanho do texto, Redimensionar texto                                                                                                                                                                |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### <a>L10: Realizar o censo pelo aplicativo</a>

<div style="text-align: justify; text-indent: 2cm;">O décimo léxico, apresentado na Tabela 12, faz referência ao requisito não-implementado: possibilidade de realizar o próximo censo pelo aplicativo (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF50</a>).</div>

<font size="3"><p style="text-align: center">Tabela 12: Léxico 10 – Realizar o censo pelo aplicativo (L10)</p></font>

| L10       | Descrição                                                                                                                                                                   |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Realizar Censo                                                                                                                                                              |
| **Tipo**      | Verbo                                                                                                                                                                       |
| **Impacto**   | Oferece maior praticidade ao eliminar a necessidade de visitas domiciliares por recenseadores.                                                                              |
| **Noção**     | O <a href="#l01-usuario">usuário</a> realiza a <a href="#l12-autenticar-via-govbr">autenticação via Gov.br</a> em sua conta e pode responder ao <a href="#l11-censo">censo</a> de forma periódica por meio da plataforma digital. |
| **Sinônimos** | Preencher censo, Participar do censo, Responder ao censo                                                                                                                    |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### <a>L11: Censo</a>

<div style="text-align: justify; text-indent: 2cm;">O décimo primeiro léxico, apresentado na Tabela 13, faz referência ao requisito não-implementado: possibilidade de realizar o próximo censo pelo aplicativo (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF50</a>).</div>

<font size="3"><p id="L10" style="text-align: center">Tabela 13: Léxico 11 – Censo (L11)</p></font>

| L11    | Descrição                                                                                                                       |
| --------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Censo                                                                                                                     |
| **Tipo**      | Objeto                                                                                                                    |
| **Impacto**   | Reúne informações periódicas dos cidadãos, fundamentais para políticas públicas e planejamento.                           |
| **Noção**     | Conjunto de dados coletados regularmente a partir das respostas fornecidas pelos <a href="#l01-usuario">usuários</a> por meio do aplicativo. |
| **Sinônimos** | Pesquisa populacional, levantamento demográfico                                                                           |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### <a>L12: Autenticar via Gov.br</a>

<div style="text-align: justify; text-indent: 2cm;">O décimo segundo léxico, apresentado na Tabela 14, faz referência ao requisito não-implementado: o sistema deve integrar-se com a conta Gov.br (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF57</a>).</div>

<font size="3"><p id="L11" style="text-align: center">Tabela 14: Léxico 12 – Autenticar via Gov.br (L12)</p></font>

| L12       | Descrição                                                                                                                                 |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Autenticar pelo Gov.br                                                                                                                    |
| **Tipo**      | Verbo                                                                                                                                     |
| **Impacto**   | Garante maior segurança e confiabilidade na identificação dos <a href="#l01-usuario">usuários</a> para a realização do Censo.                                        |
| **Noção**     | O <a href="#l01-usuario">usuário</a> acessa sua conta por meio da autenticação no Gov.br, o que permite responder ao censo periodicamente de forma digital e segura. |
| **Sinônimos** | Fazer login com Gov.br, Acessar conta Gov.br, Entrar com Gov.br                                                                           |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### <a>L13: Autenticado</a>

<div style="text-align: justify; text-indent: 2cm;">O décimo terceiro léxico, apresentado na Tabela 15, faz referência ao requisito não-implementado: o sistema deve integrar-se com a conta Gov.br (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF57</a>).</div>

<font size="3"><p id="L12" style="text-align: center">Tabela 15: Léxico 13 – Autenticado (L13)</p></font>

| L13       |                                                                                                                                                                     |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Autenticado                                                                                                                                                         |
| **Tipo**      | Estado                                                                                                                                                              |
| **Impacto**   | Representa a confirmação da identidade do <a href="#l01-usuario">usuário</a>, permitindo o acesso a funcionalidades restritas da plataforma, como o preenchimento do <a href="#l11-censo">censo</a>. |
| **Noção**     | Estado em que o <a href="#l01-usuario">usuário</a> se encontra após a verificação de sua identidade por meio do Gov.br.                                                                        |
| **Sinônimos** | Logado, Identificado, Com acesso validado                                                                                                                           |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### <a>L14: Computar e Gerar Relatórios</a>

<div style="text-align: justify; text-indent: 2cm;">
O décimo quarto léxico, apresentado na Tabela 16, refere-se ao requisito não-implementado: o sistema deve computar informações de dados e gerar relatórios para exportação (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF37</a>).
</div>

<font size="3"><p id="L37" style="text-align: center">Tabela 16: Léxico 14 – Computar e Gerar Relatórios (L14)</p></font>

| L14       |                                                                                                                                                                   |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Computar e Gerar Relatórios                                                                                                                                       |
| **Tipo**      | Funcionalidade / Ação                                                                                                                                            |
| **Impacto**   | Permite que o <a href="#l02-sistema">sistema</a> processe dados selecionados pelo <a href="#l01-usuario">usuário</a> e produza relatórios formatados, facilitando a análise e exportação de informações importantes.      |
| **Noção**     | Processo pelo qual os dados são analisados, computados e formatados para gerar relatórios exportáveis em diferentes formatos, como PDF, Excel e CSV.                |
| **Sinônimos** | Gerar Relatórios, Exportar Dados, Analisar Dados                                                                                                                 |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### <a>L15: Compartilhamento de Métricas com Fonte IBGE</a>

<div style="text-align: justify; text-indent: 2cm;">
O décimo quinto léxico, apresentado na Tabela 17, faz referência ao requisito  não-implementado: o sistema deve permitir o compartilhamento de métricas do aplicativo com a fonte atrelada ao IBGE (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF49</a>).
</div>

<font size="3"><p id="L15" style="text-align: center">Tabela 17: Léxico 15 – Compartilhamento de Métricas com Fonte IBGE (L15)</p></font>

| L15       |                                                                                                                                                                         |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Compartilhamento de Métricas com Fonte IBGE                                                                                                                             |
| **Tipo**      | Funcionalidade / Ação                                                                                                                                                    |
| **Impacto**   | Garante que as métricas compartilhadas contenham a referência clara ao IBGE, assegurando a confiabilidade e a legitimidade das informações divulgadas.                   |
| **Noção**     | Processo pelo qual o <a href="#l01-usuario">usuário</a> pode compartilhar métricas geradas pelo aplicativo, incluindo a fonte oficial do IBGE de forma explícita nos conteúdos compartilhados.      |
| **Sinônimos** | Divulgar Métricas, Enviar Estatísticas, Compartilhar Dados Oficiais                                                                                                     |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### <a>L16: Consultar FAQ</a>

<div style="text-align: justify; text-indent: 2cm;">O décimo sexto léxico, apresentado na Tabela 18, faz referência ao requisito não-implementado: o sistema deve possuir uma FAQ com respostas à dúvidas mais comuns (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF60</a>).</div>

<font size="3"><p id="L12" style="text-align: center">Tabela 18: Léxico 16 – Consultar FAQ (L16)</p></font>

| L16       |                                                                                                                                                                     |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**     | Consultar FAQ                                                                                                                                                         |
|**Tipo**      | Verbo                                                                                                                                                              |
| **Impacto**   | Retira dúvidas que o <a href="#l01-usuario">usuário</a> pode ter em relação à aplicação, melhorando a sua experiência com o <a href="#l02-sistema">sistema</a>. |
| **Noção**     | Ação que o <a href="#l01-usuario">usuário</a> realiza para retirar dúvidas relacionadas à aplicação, observando as Perguntas Mais Frequentes (FAQ, em inglês).                                                                        |
| **Sinônimos** | Acessar FAQ,  Ver FAQ.                                                                                                                          |

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### <a>L17: Alto contraste</a>

<div style="text-align: justify; text-indent: 2cm;">
O décimo sétimo léxico, apresentado na Tabela 19, faz uso do seguinte requisito não-implementado: Opção de alto contraste do aplicativo (com botão)
(<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#3-requisitos-elicitados>RF54</a>).
</div>

<font size="3"><p id="L17" style="text-align: center">Tabela 19: Léxico 17 – Alto contraste (L17)</p></font>

| L17              | Descrição                                                                                                                                                                                   |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**        | Alto contraste                                                                                                                                                             |
| **Tipo**         | Estado                                                                                                                                                                                      |
| **Impacto**      | Modifica o esquema visual da interface para exibir texto e elementos com contraste elevado, facilitando a leitura por pessoas com deficiência visual.                                      |
| **Noção**        | Estado da interface quando o <a href="#l01-usuario">usuário</a> ativa o modo de alto contraste, aplicando cores intensas e bem contrastantes entre fundo e texto, promovendo acessibilidade. |
| **Sinônimos**    | Contraste elevado, Acessibilidade visual aumentada, Interface com contraste alto                                                                                                            |

<font size="2"><p style="text-align: center">Fonte: [João Felix](https://github.com/joaofmoreiraa) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>

### <a>L18: Filtrar notícias por região e/ou tempo</a>

<div style="text-align: justify; text-indent: 2cm;">
O décimo oitavo léxico, apresentado na Tabela 20, faz uso do seguinte requisito não-implementado: o sistema deve filtrar notícias por região e/ou tempo (<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados>RF39</a>).
</div>

<font size="3"><p id="L18" style="text-align: center">Tabela 20: Léxico 18 – Filtrar notícias por região e/ou tempo (L18)</p></font>

| L18              | Descrição                                                                                                                                                                                |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Termo**        | Filtrar notícias por região e/ou tempo                                                                                                                                                   |
| **Tipo**         | Verbo                                                                                                                                                                                    |
| **Impacto**      | Permite ao <a href="#l01-usuario">usuário</a> personalizar os resultados exibidos na aba de notícias, otimizando o acesso a informações mais relevantes conforme sua localização ou interesse temporal. |
| **Noção**        | Ação de aplicar filtros para que apenas notícias relacionadas a uma determinada região ou período sejam exibidas ao <a href="#l01-usuario">usuário</a>.                                   |
| **Sinônimos**    | Selecionar por local e data, Restringir notícias, Aplicar filtro de notícias                                                                                                             |

<font size="2"><p style="text-align: center">Fonte: [João Felix](https://github.com/joaofmoreiraa) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>


### <a>L19: Consultar Central de Ajuda</a>

<div style="text-align: justify; text-indent: 2cm;">O décimo nono léxico, apresentado na Tabela 21, faz referência ao requisito não-implementado: central de Ajuda dentro do app, com informações sobre o uso do aplicativo (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF26</a>).</div>

<font size="3"><p id="L19" style="text-align: center">Tabela 21: Léxico 19 – Consultar Central de Ajuda (L19)</p></font>

| L19              | Descrição                                                                                                                                                                       |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Central de Ajuda                                                                                                                                                                |
| <b>Tipo</b>      | Substantivo composto                                                                                                                                                            |
| <b>Impacto</b>   | Facilita que o <a href="#l01-usuario">usuário</a> compreenda o funcionamento do aplicativo, melhorando a usabilidade e a experiência de navegação.                              |
| <b>Noção</b>     | Área do aplicativo onde o <a href="#l01-usuario">usuário</a> pode tirar dúvidas, consultar instruções sobre funcionalidades, e acessar perguntas frequentes sobre o uso do app. |
| <b>Sinônimos</b> | Ajuda, Suporte, FAQ, Atendimento                                                                                                                                           

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>

### <a>L20: Visualizar Mapas Interativos de dados Geográficos e Demogŕaficos</a>

<div style="text-align: justify; text-indent: 2cm;">O vigésimo léxico, apresentado na Tabela 22, faz referência ao requisito não-implementado: mapas interativos, com visualização de dados geográficos e demográficos (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF34</a>).</div>

<font size="3"><p id="L18" style="text-align: center">Tabela 22: Léxico 20 – Visualizar Mapas Interativos de dados Geográficos e Demogŕaficos (L20)</p></font>

| L20              | Descrição                                                                                                                                                                     |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <b>Termo</b>     | Mapas interativos                                                                                                                                                             |
| <b>Tipo</b>      | Substantivo composto                                                                                                                                                          |
| <b>Impacto</b>   | Permite ao <a href="#l01-usuario">usuário</a> explorar dados geográficos e demográficos por regiões, promovendo uma compreensão espacial e visual das estatísticas do país.   |
| <b>Noção</b>     | Representações visuais que possibilitam ao <a href="#l01-usuario">usuário</a> navegar pelo território brasileiro e acessar informações como população, densidade, renda, etc. |
| <b>Sinônimos</b> | Mapas dinâmicos, Visualização geográfica, Mapa temático                                                                                                                       |                                  

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>


### <a>L21: Comparação dos Censos</a>

<div style="text-align: justify; text-indent: 2cm;">
  O vigésimo primeiro léxico, apresentado na Tabela 23, faz referência ao requisito não-implementado: O sistema deve permitir a comparação dos censos realizados em diferentes anos. (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF43</a>).
</div>

<p style="text-align: center; font-size: 16px;">Tabela 23: Léxico 21 – Comparação dos Censos (L21)</p>



| L21     | Descrição                                                                                                                                                                                                                                      |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Termo     | Comparar Censos                                                                                                                                                                                                                                |
| Tipo      | Verbo                                                                                                                                                                                                                                           |
| Impacto   | Permite que o <a href="#l01-usuário">usuário</a> selecione dois ou mais censos realizados em diferentes anos e visualize suas diferenças por meio de gráficos, tabelas e resumos comparativos. A funcionalidade ajuda na análise de evolução demográfica, econômica ou social. |
| Noção     | Ação realizada no <a href="#l02-sistema">sistema</a> que possibilita a visualização paralela dos dados de censos realizados em anos distintos, destacando variações nos indicadores estatísticos coletados.                                                               |
| Sinônimos | Analisar censos, Visualizar diferenças, Comparativo de dados                                                                                                                                                                                   |

<p style="text-align: center; font-size: 14px;">Fonte: <a href="https://github.com/LeticiaMonteiroo">Letícia Monteiro</a>, 2025.</p>
                                                                                                                                                                        
### <a>L22: Taxa de Resposta</a>

<div style="text-align: justify; text-indent: 2cm;">
  O vigésimo segundo léxico, apresentado na Tabela 24, faz referência ao requisito não-implementado: o sistema deve comparar os locais com maior e menor taxa de resposta ao censo (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">RF48</a>).
</div>

<p style="text-align: center; font-size: 16px;">Tabela 24: Léxico 22 – Taxa de Resposta (L22)</p>


| L22     | Descrição                                                                                                                                                                                                                              |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Termo     | Taxa de Resposta                                                                                                                                                                                                                        |
| Tipo      | Objeto                                                                                                                                                                                                                                   |
| Impacto   | Pode ser consultada e comparada entre diferentes regiões pelo sistema. A taxa influencia relatórios, comparações e alertas relacionados à qualidade da coleta de dados.                                                                 |
| Noção     | Indicador percentual que representa a proporção da população de um local que respondeu ao Censo. Está associada a regiões específicas (municípios, estados) e é utilizada para avaliar a cobertura e a eficácia da pesquisa.             |
| Sinônimos | Índice de resposta, Proporção de respostas, Participação no censo                                                                                                                                                                       |

<p style="text-align: center; font-size: 14px;">Fonte: <a href="https://github.com/LeticiaMonteiroo">Letícia Monteiro</a>, 2025.</p>


## 4. Validação
<div style="text-align: justify; text-indent: 2cm;">A gravação da validação com o cliente pode ser acessada abaixo.</div>
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/YijSXiPgdEk?si=nQOiw8t6F1tCbkDc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

## 5. Conclusão
<div style="text-align: justify; text-indent: 2cm;"> A construção do léxico proposto neste documento demonstrou-se fundamental para garantir o alinhamento semântico entre os integrantes do projeto e os demais <i>stakeholders</i> envolvidos no desenvolvimento do sistema. Por meio da notação LAL, foi possível descrever detalhadamente os principais termos utilizados, considerando suas noções, impactos, sinônimos e classificações, promovendo. assim, uma comunicação mais precisa e eficiente. </div> 
<div style="text-align: justify; text-indent: 2cm;"> Além disso, a validação do artefato com o cliente Clístenes Mendonça contribuiu significativamente para garantir que os termos descritos representem com fidelidade o domínio do problema. A clareza conceitual proporcionada pelo léxico reforça sua importância como um artefato essencial para modelagens e implementações do sistema. </div> 

## 6. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf)>. Acesso em: 14 de maio 2025. p. 12–20.

<font size="3"><p style="text-align: center">Figura 1: Referência de Léxicos</p></font>

<center>

<img src="../../assets/images/modelagem/fonte_lexicos.png" width="400"/>

</center>

<font size="2"><p style="text-align: center;">Fonte: (SERRANO et al.).</p></font>

## Histórico de Versões

<font size="3"><p style="text-align: center">Tabela 23: Histórico de versões</p></font>

| Versão |              Descrição              |                      Autor                       |    Data    | Revisor                         |
| :----: | :---------------------------------: | :----------------------------------------------: | :--------: | :-----------------------------------------------------: |
|  1.0   | Criação e estruturação do documento | [Ludmila Nunes](https://github.com/ludmilaaysha) | 14/05/2025 |     [Mayara Marques](https://github.com/maymarquee)     |
|  1.1   | Ajustes de rotas e âncoras   | [Ludmila Nunes](https://github.com/ludmilaaysha) | 16/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|  1.2   | Adição de léxicos 4, 5, 6, 8 e 9 | [Ludmila Nunes](https://github.com/ludmilaaysha) | 16/05/2025 |     [Mayara Marques](https://github.com/maymarquee)     |
|  1.3   | Adição de léxicos 10 a 13  | [Caio Duarte](https://github.com/caioduart3) | 16/05/2025 |     [Mayara Marques](https://github.com/maymarquee)     |
|  1.4   | Adição de léxicos 14 e 15  | [Gabriel Pinto](https://github.com/GabrielSPinto) | 17/05/2025 |     [Caio Duarte](https://github.com/caioduart3)     |
|  1.5   | Adição de léxicos 7 e 16   | [Mayara Marques](https://github.com/maymarquee)  | 17/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha)     |
|  1.6   | Adição de léxicos 17 e 18  | [João Felix](https://github.com/joaofmoreiraa)  | 17/05/2025 | [Mayara Marques](https://github.com/maymarquee)     |
|  1.7   | Adição de léxicos 19 e 20  | [Laryssa Felix](https://github.com/felixlaryssa)  | 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo)   |
|  2.0   | Ajustes e correções        | [Laryssa Felix](https://github.com/felixlaryssa)  | 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo)   |
|  2.1   | Adição de léxicos 21 e 22  | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 18/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|  2.2   | Correção de âncoras e *hiperlinks* | [Ludmila Nunes](https://github.com/ludmilaaysha)  | 18/05/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
|  2.3   | Adição de conclusão | [Ludmila Nunes](https://github.com/ludmilaaysha)  | 18/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |


<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>