<style>html{scroll-behavior: smooth;}</style>

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">Em uma metodologia ágil, o <b><i>Backlog</i></b> é um registro pendente de trabalhos, o qual consiste em uma lista que ranqueia os trabalhos a serem executados conforme sua prioridade (PRESSMAN et al., 2016). O <i>backlog</i> é vivo e pode ser alterado a qualquer momento, sendo adicionadas novas tarefas de acordo com o desejo do cliente e no decorrer do desenvolvimento, conforme se conhece mais sobre o usuário e o produto.</div>
<div style="text-align: justify; text-indent: 2cm;">O <i>Backlog</i> divide-se em <b><i>Backlog</i> do Produto</b> — que é a lista geral dos trabalhos a serem executados — e <b>Backlog da Sprint</b> — que é a lista de tarefas de uma <i>sprint</i>, baseada nos itens que ainda estão no Backlog do Produto. Aqui, o artefato a ser produzido será o Backlog do Produto.</div>

<div style="text-align: justify; text-indent: 2cm;">Para construção do backlog, foram utilizadas as <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">Histórias do Usuário</a> como base, as quais definiram cada item a ser inserido na lista. Com base nos requisitos elicitados, os itens também foram divididos em <a href="#22-temas">temas</a> e <a href="#23-epicos">épicos</a> correspondentes.</div>

## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">Como pode ser observado no cronograma apresentado na <b>Tabela 1</b> e de acordo com as características apontadas na <b>Seção 2.2.</b>, os integrantes do grupo foram responsáveis pelo desenvolvimento do <i>Backlog do Produto</i> relacionado ao aplicativo do projeto.</div>

### 2.1. Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Cronograma de elaboração e validação do artefato</p></font>

<center>

| Nome                                                    | Data       | Hora  | Função                                                        |
| ------------------------------------------------------- | ---------- | ----- | ------------------------------------------------------------- |
| [Caio Duarte](https://github.com/caioduart3)            | 30/05/2025 | 18:00 | Elaborador do Backlog                                         |
| [Gabriel Pinto](https://github.com/GabrielSPinto)       | 30/05/2025 | 18:00 | Elaborador do Backlog                                         |
| [João Félix](https://github.com/joaofmoreiraa)          | 30/05/2025 | 18:00 | Elaborador do Backlog                                         |
| [Laryssa Felix](https://github.com/felixlaryssa)        | 30/05/2025 | 18:00 | Elaborador do Backlog                                         |
| [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 29/05/2025 | 18:00 | Elaborador do Backlog                                         |
| [Ludmila Nunes](https://github.com/ludmilaaysha)        | 28/05/2025 | 18:00 | Elaborador do Backlog                                         |
| [Mayara Marques](https://github.com/maymarquee)         | 30/05/2025 | 18:00 | Elaborador do Backlog                                         |

</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### 2.2. Temas

<div style="text-align: justify; text-indent: 2cm;">Após a etapa de verificação e análise dos requisitos, foi observado que eles poderiam ser organizados em oito temas principais, que compõem o maior nível de abstração do backlog. Esses temas refletem áreas funcionais do sistema e agrupam funcionalidades relacionadas de forma coesa.</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;"> 
    <ul> 
        <li>Acessibilidade</li>
        <li>Censo</li>
        <li>Consultas de dados</li>
        <li>Interações</li>
        <li>Preferências</li>
    </ul> 
</div> 
<div style="text-align: justify; text-indent: 2cm;">A organização por temas facilita a priorização e a divisão das funcionalidades em blocos menores, além de contribuir para o planejamento das entregas em <i>sprints</i> de forma mais eficiente.</div>

### 2.3. Épicos

<div style="text-align: justify; text-indent: 2cm;">Cada tema identificado no backlog foi desdobrado em épicos, que representam grandes blocos de funcionalidades agrupadas por propósito comum. Um épico, por sua vez, pode ser dividido em diversas histórias de usuário menores e mais específicas, que serão implementadas ao longo das sprints.</div>

<div style="text-align: justify; text-indent: 2cm;">A seguir, estão listados os épicos definidos a partir dos temas estabelecidos:</div> 


#### E01 - Adaptação da interface para inclusão
Eu, como usuário com deficiência, quero que a interface do app seja adaptada para minhas necessidades, para que eu possa acessar os dados do IBGE de forma independente e inclusiva.

#### E02 - Acesso aos dados e resultados do Censo
Eu, como usuário, quero uma apresentação clara e interativa dos dados obtidos nas edições mais recentes do Censo Demográfico do IBGE, para compreender melhor as características da população brasileira.

#### E03 - Compartilhamento e download
Eu, como pesquisador ou estudante, quero exportar gráficos e dados em formatos como PDF ou CSV, para poder usar essas informações em meus trabalhos ou relatórios.

#### E04 - Conteúdo personalizado para usuário
Eu, como usuário frequente do app, quero poder favoritar dados, regiões ou temas, para acessar essas informações rapidamente quando precisar.

#### E05 -  Filtro de visualização dados
Eu, como usuário, quero aplicar filtros por região, tema ou período, para visualizar somente os dados relevantes para minha análise.

#### E06 - Exibição dinâmica de dados estatísticos
Eu, como cidadão interessado em dados do Brasil, quero visualizar indicadores demográficos, sociais e econômicos de forma clara e dinâmica, para entender melhor a realidade do país.

#### E07 - Navegação e ações dentro do app
Eu, como usuário do app, quero que as interações sejam fluídas e responsivas, com animações e gestos intuitivos, para facilitar a navegação entre os dados.

#### E08 - Visualização interativa
Eu, como usuário visual, quero explorar os dados do IBGE por meio de gráficos e mapas interativos, para compreender as informações de forma geográfica e intuitiva.

#### E09 - Recebimento de notificações relevantes
Eu, como cidadão engajado, quero receber notificações personalizadas sobre novos dados ou atualizações importantes, para me manter informado sobre temas que me interessam.

#### E10 - Suporte e ajuda ao usuário
Eu, como usuário com dúvidas ou dificuldades, quero acessar facilmente um canal de ajuda ou suporte dentro do app, para resolver problemas e aproveitar melhor os recursos disponíveis.

#### E11 - Acesso multilíngue ao conteúdo
Eu, como cidadão que fala outro idioma, quero acessar o conteúdo do app em diferentes línguas, para compreender plenamente as informações independentemente do meu idioma nativo.

#### E12 - Autenticação do usuário
Eu, como usuário do app, quero fazer login com segurança e praticidade, para acessar funcionalidades personalizadas e proteger meus dados.

#### E13 - Acesso a mídias
Eu, como usuário interessado em conteúdos complementares, quero acessar vídeos, áudios e imagens relacionados aos dados apresentados, para enriquecer minha compreensão de forma mais dinâmica e acessível.

<br>

#### 2.3. Modelo do backlog
<div style="text-align: justify; text-indent: 2cm;">Essa organização hierárquica do backlog, do tema ao épico, permite uma visão clara e estruturada do desenvolvimento incremental do sistema.</div>

<div style="text-align: justify; text-indent: 2cm;">Cada item segue à estrutura apresentada na <b>Tabela 2</b>, que consiste no <a href="#221-temas">tema</a> e <a href="#222-épicos">épico</a> aos quais está relacionado, a <a href="">História do Usuário</a> e seu ID, sua prioridade e seu status quanto ao progresso no desenvolvimento do projeto, o qual pode ser "Não iniciado", "Em progresso" ou "Concluído"</div>

<font size="3"><p style="text-align: center">Tabela 2: Modelo do *backlog*</p></font>

<center>

| Tema         | Épico | História do Usuário (US)        | ID  | Prioridade | Status       |
| ------------ | ----- | ------------------------------- | --- | ---------- | ------------ |
| Tema do item | E*    | História do Usuário Relacionada | US* | Should     | Em progresso |

</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

## 3. Backlog do Produto

<div style="text-align: justify; text-indent: 2cm;">O Backlog do Produto pode ser observado na Tabela 3, apresentada a seguir.</div>

<center>
<font size="3"><p style="text-align: center">Tabela 3: Backlog do Produto</p></font>

<table>
    <tr>
        <th style="text-align: center" colspan=6> Backlog do Produto - App IBGE</th>
    </tr>
    <tr>
        <td style="text-align: center"><b>Tema</b></td>
        <td style="text-align: center"><b>Épico</b></td>
        <td style="text-align: center"><b>História de Usuário (US)</b></td>
        <td style="text-align: center"><b>ID (USXX)</b></td>
        <td style="text-align: center"><b>Prioridade</b></td>
        <td style="text-align: center"><b>Status</b></td>
    </tr>
    <!-- Tema: Acessibilidade -->
    <tr>
        <td rowspan=5 style="vertical-align: middle">Acessibilidade</td>
        <td rowspan=4 style="vertical-align: middle; text-align: center"><a href="#e01---adaptacao-da-interface-para-inclusao">E01</a></td>
        <td>Eu, como usuário com deficiência visual, quero ativar o modo de alto contraste para melhorar a acessibilidade da interface.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US23</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como pessoa idosa, quero uma navegação simples com ícones claros na parte inferior da tela para não me perder ao usar o aplicativo</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US13b</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero ativar o modo noturno para reduzir o cansaço visual em ambientes escuros.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US19</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero alterar o tamanho da fonte dos textos para facilitar a leitura conforme minha necessidade.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US20</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td rowspan=1 style="vertical-align: middle; text-align: center"><a href="#e11---acesso-multilingue-ao-conteudo">E11</a></td>
        <td>Eu, como usuário não falante de português, quero trocar o idioma do aplicativo para entender plenamente as informações</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US03</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <!-- Tema: Censo -->
    <tr>
        <td rowspan=5 style="vertical-align: middle">Censo</td>
        <td rowspan=5 style="vertical-align: middle; text-align: center"><a href="#e02---acesso-aos-dados-e-resultados-do-censo">E02</a></td>
        <td>Eu, como agente censitário, quero realizar o Censo pelo aplicativo para registrar os dados das residências de forma rápida e segura.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US06</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como cidadão interessado na evolução do Brasil, quero comparar os dados dos censos realizados em diferentes anos, para entender como o país mudou ao longo do tempo.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US32</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como analista de dados, quero visualizar quais localidades tiveram maior e menor taxa de resposta ao censo, para avaliar a confiabilidade e cobertura da coleta de dados.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US33</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário visual, quero acessar os dados do Censo por meio de gráficos, infográficos e outros recursos visuais interativos, para facilitar a compreensão das informações.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US34</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero confirmar a identidade do recenseador para garantir minha segurança e a veracidade da coleta de dados.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US25</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <!-- Tema: Consultas de dados-->
    <tr>
        <td rowspan=22 style="vertical-align: middle">Consultas de dados</td>
        <!--E03-->
        <td rowspan=5 style="vertical-align: middle; text-align: center"><a href="#e03---compartilhamento-e-download">E03</a></td>
        <td>Eu, como jornalista, quero exportar os gráficos e resumos em PDF para utilizar em minhas reportagens</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US15a</a></td>
        <td>Could</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como servidor público, quero gerar um PDF com gráficos de indicadores para relatórios oficiais</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US15b</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero compartilhar um dado interessante que vi no aplicativo com meus amigos, com a fonte clara do IBGE</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US17a</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como educador, quero enviar dados do aplicativo para meus alunos com a fonte do IBGE para garantir confiabilidade da informação</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US17b</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como jornalista, quero compartilhar um print ou link de uma métrica com a atribuição automática ao IBGE para uso em redes e reportagens</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US17c</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <!--E05-->
        <td rowspan=3 style="vertical-align: middle; text-align: center"><a href="#e05----filtro-de-visualização-dados">E05</a></td>
        <td>Eu, como usuário, quero filtrar as notícias por região e/ou período de tempo para encontrar conteúdos relevantes à minha localidade e momento.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US22</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero poder filtrar os dados apresentados por tipo (ex: demográficos, econômicos) para facilitar minha análise.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US26</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como pesquisador ou usuário avançado, quero realizar buscas refinadas por dados e publicações, utilizando filtros específicos como ano, região, tema ou tipo de conteúdo, para encontrar rapidamente as informações mais relevantes para meus objetivos.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US17c</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <!--E06-->
        <td rowspan=3 style="vertical-align: middle; text-align: center"><a href="#e06---exibição-dinâmica-de-dados-estatísticos">E06</a></td>
        <td>Eu, como usuário, quero comparar indicadores por região do país para maior discernimento de dados</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US02</a></td>
        <td>Could</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero visualizar fatores que interferem (aumentam ou diminuem) cada indicador para maior entendimento de dados</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US04</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como cidadão interessado nas condições sociais e econômicas do Brasil, quero visualizar indicadores sociais e agropecuários de forma clara e acessível, para entender melhor o desenvolvimento humano e rural do país.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US36</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <!--E08-->
        <td rowspan=3 style="vertical-align: middle; text-align: center"><a href="#e08---visualização-interativa">E08</a></td>
        <td>Eu, como pesquisador, quero ver a evolução temporal de um dado ao clicar nele para entender tendências e mudanças ao longo do tempo</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US14a</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como estudante, quero visualizar um gráfico completo ao tocar em um dado para usar nas minhas apresentações e trabalhos escolares</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US14b</a></td>
        <td>Should</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como cidadão interessado em informações territoriais, desejo acessar mapas interativos que exibam dados geográficos e demográficos, para compreender melhor as informações da minha região ou do país.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US31</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <!--E13-->
        <td rowspan=3 style="vertical-align: middle; text-align: center"><a href="#e13---acesso-a-mídias">E13</a></td>
        <td>Eu, como jovem usuário, quero acessar os conteúdos do IBGE no YouTube, TikTok e Instagram diretamente pelo aplicativo</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US16a</a></td>
        <td>Could</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como educador, quero encontrar vídeos informativos do IBGE de forma centralizada para usar em sala de aula</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US16b</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário que prefere vídeos, quero ver o conteúdo em formato audiovisual sem sair do app</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US16c</a></td>
        <td>Won't</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <!--E10-->
        <td rowspan=5 style="vertical-align: middle; text-align: center"><a href="#e10---suporte-e-ajuda-ao-usuário">E10</a></td>
        <td>Eu, como usuário, quero consultar a aba de Perguntas Mais Frequentes (FAQ) para retirar dúvidas que posso ter em relação ao sistema</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US01</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário do aplicativo, desejo acessar facilmente uma opção de suporte que me leve diretamente ao site oficial do IBGE, para obter ajuda ou mais informações.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US29</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como usuário do aplicativo, desejo acessar uma Central de Ajuda dentro do app, para entender como utilizar todas as funcionalidades disponíveis.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US30</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero ver explicações simplificadas ao passar o mouse sobre termos técnicos para entender seu significado.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US21a</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero acessar um glossário de termos técnicos com explicações simples, para consulta rápida.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US21b</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <!-- Tema: Interações-->
    <tr>
        <td rowspan=7 style="vertical-align: middle">Interações</td>
        <td rowspan=6 style="vertical-align: middle; text-align: center"><a href="#e07---navegação-e-ações-dentro-do-app">E07</a></td>
        <td>Eu, como usuário do aplicativo, quero acessar rapidamente diferentes funcionalidades principais através de uma barra de navegação inferior</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US13a</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como cidadão interessado em dados públicos, quero encontrar facilmente as notícias do IBGE em uma aba específica para me manter informado</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US12</a></td>
        <td>Could</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como usuário do aplicativo, quero poder buscar informações de forma rápida, independentemente da tela em que estou, para economizar tempo e encontrar dados com facilidade.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US28</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como usuário do aplicativo, quero visualizar uma aba de calendário com os eventos e pesquisas principais do IBGE, para me manter informado sobre as datas importantes.XX</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US08</a></td>
        <td>Should</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero acessar uma aba de síntese com dados como gentílico, área territorial, população, renda, orçamento, IDH, matrículas, salário médio, PIB per capita e mortalidade infantil por estado e município, para obter informações rápidas e confiáveis sobre minha região ou outras localidades.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US09</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero que cada dado exibido na aba “Síntese” possua sua fonte de origem claramente indicada, para garantir a confiabilidade e a transparência das informações.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US10</a></td>
        <td>Could</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td rowspan=1 style="vertical-align: middle; text-align: center"><a href="#e12---autenticação-do-usuário">E12</a></td>
        <td>Eu, como cidadão, quero me autenticar no aplicativo do IBGE utilizando minha conta Gov.br, para acessar os serviços de forma segura e integrada com meus dados governamentais.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US07</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <!-- Tema: Preferências -->
    <tr>
        <td rowspan=6 style="vertical-align: middle">Preferências</td>
        <!--E04-->
        <td rowspan=3 style="vertical-align: middle; text-align: center"><a href="#e04---conteúdo-personalizado-para-usuário">E04</a></td>
        <td>Eu, como usuário, quero receber recomendações de conteúdos similares aos que já acessei, para continuar explorando temas do meu interesse.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US24</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
        <tr>
        <td>Eu, como usuário, quero poder favoritar indicadores para acessá-los rapidamente em outra seção.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US18a</a></td>
        <td>Must</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como usuário, quero visualizar as últimas atualizações dos indicadores que favoritei para acompanhar mudanças recentes.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US18b</a></td>
        <td>Should</td>
        <td>Não iniciado</td>
    </tr>
    <!--E09-->
    <tr>
        <td rowspan=3 style="vertical-align: middle; text-align: center"><a href="#e09---recebimento-de-notificações-relevantes">E09</a></td>
        <td>Eu, como usuário, quero receber notificações sobre notícias relevantes e atualizações dos meus indicadores favoritos para me manter informado de informações relevantes para mim</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US05</a></td>
        <td>Could</td>
        <td>Não iniciado</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero ser notificado quando novas notícias relacionadas aos indicadores forem publicadas, para me manter informado sobre atualizações relevantes sem precisar acessar o sistema constantemente.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US11</a></td>
        <td>Should</td>
        <td>Concluído</td>
    </tr>
    <tr>
        <td>Eu, como usuário do aplicativo, desejo ativar ou desativar as notificações, para ter controle sobre os avisos que recebo do app.</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/agil/userStories/">US27</a></td>
        <td>Must</td>
        <td>Concluído</td>
    </tr>
</table>

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

</center>

## 4. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. UnB. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3096144/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf](https://aprender3.unb.br/pluginfile.php/3096144/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 27 de maio 2025.

> PRESSMAN, Roger S; MAXIM, Bruce R. Engenharia De Software Uma Abordagem Profissional. 8. ed. Mc Graw Hill Education, 2016.

## Histórico de Versões

<font size="3"><p style="text-align: center">Tabela 4: Histórico de versões</p></font>

| Versão |              Descrição              |                      Autor                       |    Data    | Revisor                         |
| :----: | :---------------------------------: | :----------------------------------------------: | :--------: | :-----------------------------------------------------: |
|  1.0   | Criação do documento e estruturação do artefato | [Ludmila Nunes](https://github.com/ludmilaaysha) | 28/05/2025 |  [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|  1.1  | Atualização do Artefato |[Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 29/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha)   |
|  1.2  | Definição de temas e épicos |[Ludmila Nunes](https://github.com/ludmilaaysha) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 30/05/2025 | [Caio Duarte](https://github.com/caioduart3) |
|  1.3  | Elaboração de itens relativos a US01 a US05 |[Mayara Marques](https://github.com/maymarquee) | 30/05/2025 | [Caio Duarte](https://github.com/caioduart3) |
|  1.4  | Elaboração de itens relativos a US06 a US11 |[Caio Duarte](https://github.com/caioduart3) | 30/05/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
|  1.5  | Elaboração de itens relativos a US12 a US17  |[Gabriel Pinto](https://github.com/GabrielSPinto) | 30/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|  1.6  | Elaboração de itens relativos a US18 a US21  |[Ludmila Nunes](https://github.com/ludmilaaysha) | 30/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|  1.7  | Elaboração de itens relativos a US22 a US26  |[João Félix](https://github.com/joaofmoreiraa) | 30/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|  1.8  | Elaboração de itens relativos a US27 a US31  |[Laryssa Felix](https://github.com/felixlaryssa) | 30/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|  1.9  | Elaboração de itens relativos a US32 a US36  |[Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 30/05/2025 | [Mayara Marques](https://github.com/maymarquee) |


<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>