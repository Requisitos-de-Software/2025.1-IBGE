# Requisitos Elicitados 

<div style="text-align: justify; text-indent: 2cm;"> Com o avanço das etapas do projeto, tornou-se necessária a revisão dos requisitos inicialmente elicitados para garantir sua adequação às boas práticas da Engenharia de Requisitos. Assim, durante a Entrega 6, foi conduzido um processo sistemático de refinamento dos Requisitos Funcionais (RFs) e Não Funcionais (RNFs), com o objetivo de melhorar sua clareza, eliminar ambiguidades, corrigir redundâncias e assegurar a viabilidade técnica de sua implementação. </div>

### 1. Versão Oficial

<div style="text-align: justify; text-indent: 2cm;"> Nesta seção, são apresentadas as versões oficiais dos requisitos elicitados para o aplicativo do IBGE, resultantes do processo de revisão conduzido na Entrega 6. As tabelas a seguir consolidam os Requisitos Funcionais (versão 2.0) e os Requisitos Não Funcionais (versão 2.1), já reorganizados, refinados e numerados de forma padronizada para facilitar a rastreabilidade e a futura implementação. </div> <div style="text-align: justify; text-indent: 2cm;"> As versões oficiais refletem a maturidade do processo de especificação, incorporando os ajustes realizados com base em análises críticas e nas diretrizes metodológicas propostas por Pohl e Rupp (2015), que orientam a verificação da clareza, consistência, completude e viabilidade técnica dos requisitos de software. </div>

#### 1.1. Requisitos Funcionais Versão 2.0

<div style="text-align: justify; text-indent: 2cm;">
A tabela 2 apresentada abaixo consolida os Requisitos Funcionais (RFs) definidos para o aplicativo do IBGE, organizando-os com identificadores únicos (como RF01, RF08-A, RF45-A) e suas respectivas descrições. Esses requisitos foram elaborados com base em uma análise criteriosa das funcionalidades essenciais e complementares esperadas do sistema, refletindo tanto as necessidades identificadas na fase de elicitação quanto os refinamentos realizados ao longo do processo de especificação.

A numeração dos requisitos foi organizada de maneira a refletir a evolução natural do processo de especificação. Os requisitos que permaneceram inalterados mantiveram sua numeração original (ex: RF01–RF07); aqueles que eram vagos ou genéricos foram aprimorados e receberam um sufixo “A” (ex: RF08-A, RF11-A), indicando que passaram por detalhamento ou reescrita.
</div>

<center>

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais Elicitados (versão 2.0)</p></font>

| <a id= "anchor_RF" style = "visibility: hidden;"></a>Novo ID  | Descrição Novo ID |
| --- | --- |
| RF01 | O sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios. |
| RF02 | Sistema deve possuir uma funcionalidade de busca, que independe da tela em que o usuário se encontra. |
| RF03 | Se houver algum dado/indicador atrelado à notícia lida, esse indicador deve estar presente no topo da página da notícia. |
| RF04 | A notícia deve estar na aba de notícias do aplicativo. |
| RF05 | O aplicativo deve possuir uma navbar inferior que permita que o usuário navegue pelas diversas funcionalidades principais da aplicação. |
| RF06 | Sistema deve possuir a aba de indicadores, com principais dados do IBGE, prévia de gráfico e valor com coloração simbólica (verde/vermelha). |
| RF07 | Ao clicar no dado, deve aparecer gráfico mais completo com evolução temporal do indicador. |
| RF08-A | A interface do sistema deve exibir, na tela do dado, as notícias que possuam relação com o indicador correspondente. |
| RF09 | Ao lado do nome do indicador, deve aparecer a definição daquele indicador. |
| RF10 | Uma aba de calendário deve estar presente, com eventos/pesquisas principais do IBGE. |
| RF11-A | Cada dado exibido na aba “Síntese” do aplicativo deve apresentar, de forma visível e padronizada, a fonte oficial de onde foi extraído. |
| RF12-A | O sistema deve conter uma aba de "Extras", reunindo funcionalidades complementares ao uso principal do aplicativo. Essa aba deve incluir opções como: configurações do app, gerenciamento de login e conta, canais de atendimento ao usuário, convite para amigos, envio de feedback, além de outros recursos informativos ou de suporte que venham a ser disponibilizados. |
| RF13-A | O sistema deve oferecer uma opção de controle de tipos de notificações, permitindo que o usuário ative ou desative diferentes tipos de alertas de acordo com sua preferência. As notificações configuráveis podem incluir notificações sobre Notícias, Indicadores, Agenda, etc. |
| RF14 | O sistema deve notificar o usuário sobre novas notícias. |
| RF15-A | O sistema deve oferecer uma opção de avaliação do aplicativo acessível ao usuário. |
| RF15-B | A avaliação deve permitir a coleta voluntária do perfil do usuário, incluindo dados como faixa etária, localização e frequência de uso. |
| RF15-C | A avaliação deve incluir perguntas sobre o nível de satisfação com o aplicativo, considerando critérios como facilidade de uso, confiabilidade e design. |
| RF15-D | O sistema deve registrar as funcionalidades mais utilizadas pelo usuário, a fim de apoiar a análise de uso do app. |
| RF15-E | Deve haver um campo para o usuário enviar sugestões de melhoria, de forma livre e opcional. |
| RF16-A | O sistema deve disponibilizar uma funcionalidade que permita ao usuário compartilhar o aplicativo com outras pessoas, por meio de redes sociais, e-mail ou aplicativos de mensagem. |
| RF17-A | O sistema deve oferecer uma opção de suporte ao usuário, com acesso direto aos canais oficiais de atendimento do IBGE. Essa opção deve incluir redirecionamento para o site institucional, onde o usuário poderá acessar serviços como chat, telefone, e-mail e perguntas frequentes (FAQ), conforme disponibilizado pelo IBGE. |
| RF18 | As redes sociais do IBGE devem ser linkadas. |
| RF19 | As notícias devem ser compartilháveis. |
| RF20-A | O sistema deve destacar, no calendário, os dias que possuem eventos ou pesquisas agendadas utilizando uma cor diferenciada em relação aos demais dias. |
| RF21 | O calendário deve permitir visualização de meses passados e futuros em relação ao mês atual. |
| RF22 | Na aba “síntese”, dados como gentílico, área territorial, população, renda, orçamento, IDH, matrículas, salário médio, PIB per capita e mortalidade infantil devem estar disponíveis por estado e município. |
| RF23-A | Filtros por estado e município devem estar disponíveis na aba “Síntese”. |
| RF24 | Jogos educativos sobre geografia, demografia e temas sociais. |
| RF25-A | O sistema deve ser capaz de baixar automaticamente, quando estiver conectado à internet, as informações necessárias para o funcionamento do modo offline. Esses dados devem ser armazenados localmente no dispositivo e exibidos ao usuário mesmo quando não houver conexão, garantindo acesso contínuo a conteúdos como indicadores, notícias e gráficos previamente carregados. |
| RF26 | Central de Ajuda dentro do app, com informações sobre o uso do aplicativo |
| RF27 | Notificações para notícias relevantes e atualizações dos indicadores favoritos. |
| RF28 | O usuário pode favoritar indicadores e visualizar as últimas atualizações. |
| RF29 | Comparativo de indicadores por região. |
| RF30-A | Possibilidade de responder ao censo diretamente pelo app. |
| RF31-A | Possibilidade de responder a questionários relacionados ao censo diretamente pelo aplicativo. |
| RF32-A | Possibilidade de realizar e preencher outros questionários disponibilizados pelo IBGE diretamente no aplicativo. |
| RF33 | Acesso a dados de diferentes fontes como o IBGE, através do app. |
| RF34 | Mapas interativos, com visualização de dados geográficos e demográficos. |
| RF35-A | Possibilidade de filtro por tipo de dado na aba "Indicadores" |
| RF36 | Possibilidade de exportar gráficos e resumos em formatos como PDF. |
| RF37 | Computar informações de dados e gerar relatórios para exportação. |
| RF38-A | O sistema deve disponibilizar, de forma acessível no aplicativo, demais indicadores que atualmente estão disponíveis apenas no site do IBGE. |
| RF39 | O sistema deve filtrar notícias por região e/ou tempo. |
| RF41-A | O sistema deve integrar conteúdos produzidos em outras plataformas, como YouTube, TikTok e Instagram, em uma aba dedicada. |
| RF42 | O sistema deve analisar os conteúdos acessados pelo usuário para recomendar conteúdos similares. |
| RF43 | O sistema deve permitir a comparação dos censos realizados em diferentes anos. |
| RF44 | O sistema deve exibir uma confirmação sobre a identidade do recenseador. |
| RF45-A | O sistema deve realizar previsões sobre tendências futuras e indicar políticas públicas, com base nos dados disponibilizados pela plataforma em uma aba dedicada. |
| RF46-A | O sistema deve informar, de forma acessível ao usuário, os principais fatores que influenciam a variação de cada indicador apresentado no aplicativo, na especificação do indiciador. |
| RF48 | O sistema deve comparar os locais com maior e menor taxa de resposta ao censo. |
| RF49-A | O sistema deve permitir o compartilhamento de métricas e dados exibidos no aplicativo, garantindo que a fonte oficial do IBGE esteja sempre atribuída ao conteúdo compartilhado. |
| RF51 | Opção de modo noturno. |
| RF52 | Opção de mudança de idiomas (Português, Inglês, Espanhol) |
| RF53 | Opção de alterar o tamanho da fonte (com botão) |
| RF54 | Opção de alto contraste do aplicativo (com botão) |
| RF56 | O sistema deve disponibilizar explicações simplificadas sobre os termos técnicos. |
| RF57 | O sistema deve integrar-se com a conta Gov.br. |
| RF60 | O sistema deve possuir uma FAQ com respostas às dúvidas mais comuns. |
| RF62 | O sistema deve permitir acesso às publicações completas de cada pesquisa com a metodologia detalhada. |

</center>

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>

#### 1.2. Requisitos Não Funcionais Versão 2.1

<div style="text-align: justify; text-indent: 2cm;">
A Tabela 3 consolida os Requisitos Não Funcionais (RNFs) do aplicativo do IBGE, identificados por códigos únicos (como RNF01-A, RNF09-A). Esses requisitos foram definidos com base nas necessidades de qualidade do sistema e passaram por um processo de refinamento. Requisitos genéricos foram reescritos com mais clareza (sufixo “A”), enquanto itens redundantes ou fora de escopo foram fundidos ou eliminados, garantindo rastreabilidade das mudanças.
</div>

<center>

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Funcionais Elicitados (versão 2.1)</p></font>

| Novo ID   | Descrição Novo ID |
|-----------|-------------------|
| RNF01-A   | O sistema deve manter consistência visual em todas as telas, adotando padrões unificados de cores, fontes, botões e elementos da interface. |
| RNF02-A   | Todas as ações do usuário devem gerar feedback visual e/ou sonoro imediato, como cliques, carregamentos ou envios de formulário. |
| RNF03     | O sistema deve permitir a alteração do tamanho da fonte em toda a interface. |
| RNF04     | O sistema deve oferecer a opção de ativar o modo noturno, alterando o esquema de cores para tons escuros. |
| RNF05-A   | O sistema deve ser suficientemente intuitivo para que um novo usuário consiga concluir tarefas principais em até 5 minutos, sem depender de ajuda externa. |
| RNF06-A   | A interface do sistema deve ser responsiva, adaptando-se automaticamente a diferentes tamanhos, resoluções e orientações de tela. |
| RNF07     | O sistema deve informar o usuário, em tempo real, sobre o andamento de processos como carregamento de dados, envio de formulários ou sincronização, por meio de barras de progresso, ícones animados ou mensagens de status. |
| RNF08     | O usuário deve poder desfazer ou refazer ações como desfavoritar indicadores, redefinir filtros ou cancelar comandos, evitando que erros exijam reinício completo da interação. |
| RNF09-A   | O sistema deve alertar o usuário antes de ações críticas, validar os dados inseridos e exibir mensagens de erro claras, sem jargões técnicos. |
| RNF10     | O sistema deve apresentar tempo médio entre falhas (MTBF - Mean Time Between Failures) superior a 100 horas de uso contínuo. |
| RNF11-A   | O aplicativo deve recuperar automaticamente sessões interrompidas e preservar a integridade dos dados mesmo em encerramentos inesperados. |
| RNF12     | Em caso de falha, o sistema deve registrar o erro localmente e sincronizar com o servidor assim que houver conexão, para fins de diagnóstico e correção. |
| RNF15     | A comunicação entre o aplicativo e os servidores do IBGE deve utilizar protocolos seguros (ex: HTTPS), garantindo a confiabilidade na transferência de dados. |
| RNF16     | O aplicativo deve passar por testes de estresse e de carga para garantir seu funcionamento estável mesmo com picos de acesso simultâneo. |
| RNF17     | O sistema deve garantir interoperabilidade com diferentes versões dos principais sistemas operacionais móveis (Android e iOS), mantendo a estabilidade entre atualizações. |
| RNF18     | O sistema deve apresentar tempo de resposta inferior a 2 segundos para carregamento de telas principais, como visualização de notícias, dados e gráficos. |
| RNF19-A   | O aplicativo não deve exceder 40% de uso da CPU nem 250 MB de RAM durante operações intensas, assegurando bom desempenho em dispositivos intermediários. |
| RNF21     | O aplicativo deve estar disponível para acesso 99,5% do tempo ao longo do mês, considerando atualizações, falhas e manutenções. |
| RNF22     | O sistema deve suportar pelo menos 5.000 acessos simultâneos sem degradação perceptível de desempenho. |
| RNF23     | O tempo de sincronização de dados com o servidor não deve ultrapassar 5 segundos em redes 4G ou superiores. |
| RNF24-A   | O aplicativo deve ter transições de até 1 segundo entre seções e tempo de inicialização inferior a 3 segundos em dispositivos de entrada compatíveis. |
| RNF25     | O sistema deve realizar compressão de dados para reduzir o tempo de carregamento de conteúdo, principalmente em conexões móveis com baixa velocidade. |
| RNF26     | O desempenho do aplicativo deve ser validado em pelo menos três modelos diferentes de smartphones (baixo, médio e alto desempenho), garantindo funcionalidade mínima em cada um deles. |
| RNF27-A   | O sistema deve estar totalmente em conformidade com a LGPD (Lei nº 13.709/2018), garantindo tratamento legal, seguro e transparente de dados pessoais. |
| RNF28-A   | Todos os dados pessoais devem ser criptografados em trânsito (TLS 1.2+) e em repouso (AES-256 ou superior). |
| RNF30-A   | O sistema deve exibir termos de uso e política de privacidade claros antes da coleta de dados, acessíveis na tela inicial e no menu de configurações. |
| RNF31-A   | O sistema deve obter consentimento explícito para uso de dados pessoais e permitir sua correção, exclusão ou recusa de coleta anônima. |
| RNF33-A   | O sistema deve registrar e proteger logs de autenticação e envio de dados, com retenção mínima de 5 anos e acesso restrito por perfil. |
| RNF37     | O sistema deve realizar backups automáticos dos dados críticos diariamente, com retenção mínima de 30 dias e possibilidade de restauração em até 24 horas. |
| RNF38-A   | O design visual deve seguir a identidade institucional do IBGE, com uso oficial das cores e logotipo conforme diretrizes. |
| RNF40-A   | O design do sistema deve priorizar simplicidade, clareza e fluidez, facilitando a navegação e interpretação de dados com gráficos e elementos visuais intuitivos. |
| RNF43-A   | O sistema deve ter arquitetura modular e design escalável para futura adição de novos dados, filtros e relatórios. |
| RNF44     | O aplicativo deve estar apto a funcionar de forma offline para consulta de dados previamente sincronizados, com atualização automática quando a conexão for restabelecida. |
| RNF45-A   | O aplicativo deve ser desenvolvido com tecnologias e frameworks compatíveis com Android e iOS, adaptando-se a diversos tamanhos de tela. |
| RNF46-A   | O código-fonte deve seguir boas práticas, com versionamento, documentação e uso legal de bibliotecas licenciadas. |
| RNF47     | O sistema deve ser compatível com bibliotecas gráficas modernas para renderização de gráficos estatísticos. |
| RNF51-A   | O aplicativo deve conter uma seção de ajuda com FAQs, tutoriais e instruções, redigidas em linguagem simples e acessível em diferentes dispositivos. |
| RNF58-A   | Todos os dados exibidos devem respeitar as licenças de uso e conter as devidas citações e fontes do IBGE. |
| RNF59-A   | O software e componentes de terceiros devem ser licenciados adequadamente, preferencialmente sob licenças abertas compatíveis com uso governamental. |
| RNF61     | O uso do aplicativo será gratuito e restrito apenas a fins informativos e educacionais, conforme normas institucionais. |
| RNF62     | O sistema deve respeitar as leis brasileiras vigentes relacionadas à proteção de dados, propriedade intelectual, acessibilidade digital e direitos do consumidor. |
| RNF66-A   | O sistema deve atender às diretrizes nacionais e internacionais de acessibilidade, incluindo compatibilidade com leitores de tela e o Modelo de Acessibilidade de Governo Eletrônico (eMAG), garantindo uso por pessoas com deficiência. |
| RNF68     | O aplicativo deve ser registrado junto ao órgão responsável, quando aplicável, garantindo proteção contra uso indevido ou cópia não autorizada. |
| RNF73     | Padrão internacional para gestão da segurança da informação, recomendável para proteger dados sensíveis do sistema. |
| RNF74     | Norma brasileira que trata de ergonomia na interação humano-computador, aplicável à interface do sistema. |
| RNF78-A   | Os elementos de navegação devem ser intuitivos, com rótulos claros e acessíveis em até dois toques, utilizando linguagem adequada ao público geral. |
| RNF79     | Todas as telas devem possuir contraste mínimo de 4.5:1 entre texto e plano de fundo, conforme as diretrizes WCAG 2.1 de acessibilidade digital. |
| RNF82     | Os formulários devem apresentar mensagens de erro específicas e orientativas, posicionadas próximas aos campos com problemas. |
| RNF84     | Os gráficos e mapas exibidos devem possuir alternativas textuais ou descrições acessíveis para garantir entendimento a todos os usuários. |


</center>

<font size="2"><p style="text-align: center">Fonte: [Larysssa Felix](https://github.com/felixlaryssa) e [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

## 2. Bibliografia

> POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam – Foundation Level – IREB compliant. 2. ed. Santa Barbara: Rocky Nook, 2015.

## 3. Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela 3: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação da documento|[Gabriel Pinto](https://github.com/GabrielSPinto)| 14/06/2025 |[Letícia Monteiro](https://github.com/LeticiaMonteiroo)|

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>