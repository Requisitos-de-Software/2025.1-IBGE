# Cenários

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">
Cenários se trata de uma estratégia usada para reconhecer interações entre ambientes e sistemas (SERRANO; SERRANO, 2025). Elementos como o comportamento do software, sua dinâmica e seu fluxo são possíveis de serem entendidos com cenários.
</div>
<div style="text-align: justify; text-indent: 2cm;">
O cenário conta com elementos básicos, que são: título: que descreve em poucas palavras o cenário, objetivos/metas: que descreve o que o sistema e os usuários esperam quando o cenário se iniciar, contexto: onde o usuário se encontra para realizar o cenário, ator(es): quem está envolvido no cenário, recursos: o que é necessário para ele ocorrer, exceções: o que pode afetar negativamente o cenário e episódios: o fluxo normal de eventos desse cenário, que devem estar presentes em cada artefato.  
</div>
<div style="text-align: justify; text-indent: 2cm;">
Podemos trazer os conceitos de cenários para o aplicativo IBGE, explorando diversos cenários que os usuários da aplicação podem passar ao utilizar o aplicativo. 
</div>

## 2. Metodologia

<div style="text-align: justify; text-indent: 2cm;">
O desenvolvimento dos cenários foi realizado de forma colaborativa por todos os integrantes do grupo. Cada membro contribuiu ativamente na construção de pelo menos dois cenários, a partir da análise dos requisitos previamente elicitados e da compreensão das necessidades dos usuários do aplicativo do IBGE. O processo seguiu as diretrizes propostas pela Engenharia de Requisitos, buscando garantir que os cenários refletissem situações reais de uso do sistema.

Para organizar a produção, o grupo seguiu um cronograma previamente estabelecido, apresentado na Tabela 1, que orientou tanto as etapas de desenvolvimento quanto os prazos de entrega.
</div>

### 2.1 Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Cronograma de elaboração e validação do artefato</p></font>

<center>

| Nome                                                    | Data       | Hora  | Função                                                        |
| ------------------------------------------------------- | ---------- | ----- | ------------------------------------------------------------- |
| [Caio Duarte](https://github.com/caioduart3)            | 15/05/2025 | 19:00 | Elaborador dos cenários                                        |
| Clístenes Mendonça                                      | 17/05/2025 | 23:00 | Cliente                                                       |
| [Gabriel Pinto](https://github.com/GabrielSPinto)       | 17/05/2025 | 16:00 | Elaborador dos cenários                                        |
| [João Félix](https://github.com/joaofmoreiraa)          | 17/05/2025 | 17:00 | Elaborador dos cenários                                        |
| [Laryssa Felix](https://github.com/felixlaryssa)        | 17/05/2025 | 16:00 | Elaboradora dos cenários                                       |
| [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 17/05/2025 | 23:00 | Elaboradora dos cenários e participante da validação           |
| [Ludmila Nunes](https://github.com/ludmilaaysha)        | 17/05/2025 | 23:00 | Elaboradora dos cenários e participante da validação           |
| [Mayara Marques](https://github.com/maymarquee)         | 17/05/2025 | 23:00 | Elaboradora dos cenários e participante da validação           |

</center>

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

## 3. Cenários

<div style="text-align: justify; text-indent: 2cm;">
Os artefatos produzidos pelo grupo podem ser observados nas tabelas de 3 a 20, sempre seguindo a mesma estrutura da tabela de descrição dos cenários:
</div>

<font size="3"><p style="text-align: center">Tabela 2: Estrutura da tabela de descrição dos cenários</p></font>

<center>

| Cenário X | Título do Cenário |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**      | Descreva o título do cenário |
| **Objetivo**    | Descreva o objetivo principal do cenário |
| **Contexto**    | Local: Descreva o local. <br> Tempo: Duração estimada. <br> Pré-condição: Pré-requisitos necessários. |
| **Atores**      | Quem participa do cenário |
| **Recursos**    | Quais recursos são utilizados |
| **Episódios**   | Passo a passo do que acontece no cenário |
| **Restrições**  | Limitações ou condições obrigatórias |
| **Exceção**     | O que pode dar errado e como o sistema reage |

</center>

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### 3.1 Cenário 1: Consultar FAQ 

<div style="text-align: justify; text-indent: 2cm;">O primeiro cenário, apresentado na Tabela 3, faz referência ao requisito não-implementado:  sistema deve possuir uma FAQ com respostas às dúvidas mais comuns (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF60</a>).</div>

<font size="3"><p style="text-align: center">Tabela 3: Cenário de consultar FAQ</p></font>

<center>

| Cenário 1 | Consultar FAQ | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Consultar aba de perguntas mais frequentes (FAQ). | 
| **Objetivo** | Permitir que o usuário visualize e consulte a aba de FAQ. | 
| **Contexto** | Local: Página "Extras" do aplicativo. <br> Tempo: De 1min a 2min. <br> Pré-condição: Existir dados (perguntas e respostas) sobre as dúvidas mais frequentes do usuário. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. | 
| **Episódios** | Usuário abre o aplicativo e acessa a aba "Extras" pela navbar. <br> Usuário seleciona a opção "FAQ". <br> Aplicativo exibe principais perguntas/dúvidas relacionadas ao sistema, junto com as respostas correspondentes.  | 
| **Restrições** | O usuário precisa ter acesso à internet. <br> A dúvida do usuário deve estar contemplada na lista de perguntas do aplicativo. <br> O aplicativo deve apresentar respostas atualizadas às perguntas. | 
| **Exceção** | Não acesso à internet. <br> Uma pergunta do usuário não está contemplada na lista de perguntas do aplicativo. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### 3.2 Cenário 2: Comparar indicadores por região 

<div style="text-align: justify; text-indent: 2cm;">O segundo cenário, apresentado na Tabela 4, faz referência ao requisito não-implementado: comparativo de indicadores por região. (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF29</a>).</div>

<font size="3"><p style="text-align: center">Tabela 4: Cenário de comparar indicadores por região</p></font>

<center>

| Cenário 2 | Comparar indicadores por região | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Comparar dados de indicadores por região. | 
| **Objetivo** | Permitir que o usuário visualize e compare os indicadores por região. | 
| **Contexto** | Local: Página "Indicadores" do aplicativo. <br> Tempo: Aproximadamente 1min. <br> Pré-condição: Um filtro de indicadores por região deve estar disponível no aplicativo. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. | 
| **Episódios** | Usuário abre o aplicativo e acessa a aba "Indicadores" pela navbar. <br> Usuário seleciona a opção "Regiões". <br> Aplicativo exibe todos os indicadores disponíveis no aplicativo junto com as regiões do Brasil, com valores correspondentes à cada região. | 
| **Restrições** | O usuário precisa ter acesso à internet. <br> O aplicativo deve possuir dados de indicadores atualizados. <br> O aplicativo deve possuir separação de regiões do país para comparar os dados. | 
| **Exceção** | Não ter acesso à internet. <br> Aplicativo não possui dados de indicadores atualizados. <br> Aplicativo não consegue correlacionar dados à regiões, e uma mensagem de erro deve ser apresentada ao usuário. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### 3.3 Cenário 3: Notícias 

<div style="text-align: justify; text-indent: 2cm;">O terceiro cenário, apresentado na Tabela 5, faz referência ao requisito implementado: o sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF01)</a> </div>

<font size="3"><p style="text-align: center">Tabela 5: Notícias</p></font>

<center>

| Cenário 3 | [Notícias](./../assets/images/PrintApp/app4.jpeg) |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**      | Acessar e visualizar notícias atualizadas |
| **Objetivo**    | Permitir que o usuário acesse e leia notícias atualizadas sobre dados e <br> pesquisas realizadas pelo IBGE |
| **Contexto**    | Local: Página "Notícias" do aplicativo do IBGE. <br> Tempo: Aproximadamente 2 minutos. <br> O aplicativo deve estar instalado e com acesso à internet ativo. |
| **Atores** | Usuário do IBGE |
| **Atores**      | Usuário do IBGE |
| **Recursos**    | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. |
| **Episódios**   | O usuário abre o aplicativo do IBGE no celular. <br> Clica em "Notícias" na navbar <br> Ele seleciona uma notícia de interesse, como "Em março, indústria avança em dez dos <br> 15 locais pesquisados" <br> O usuário lê o conteúdo completo da notícia dentro do app. |
| **Restrições**  | A leitura de notícias exige conexão ativa com a internet, sem ela o conteúdo não é carregado. |
| **Exceção**     | Caso não haja notícias disponíveis no momento ou ocorra falha na conexão, o sistema exibe uma mensagem: "Não foi possível carregar as notícias. Verifique sua conexão e tente novamente." |

</center>

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>


### 3.4 Cenário 4: Análise dos Dados Demográficos do Brasil

<div style="text-align: justify; text-indent: 2cm;">O quarto cenário, apresentado na Tabela 6, faz referência ao requisito implementado: O sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF01)</a> </div>

<font size="3"><p style="text-align: center">Tabela 6: Análise dos <i> Dados Demográficos </i> do Brasil</p></font>

<center>

| Cenário 4 | Análise dos Dados Demográficos |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**      | Análise dos dados demográficos do Brasil |
| **Objetivo**    | Consultar de dados demográficos do Brasil |
| **Contexto**    | Local: Página "Síntese" do aplicativo. <br> Tempo: Aproximadamente 1min. <br> Pré-condição: Um filtro de indicadores por região deve estar disponível no aplicativo. |
| **Atores**      | Usuário do IBGE |
| **Recursos**    | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. |
| **Episódios**   | Usuário abre o aplicativo e acessa a aba "Síntese" pela navbar. <br> Usuário seleciona a opção "Brasil". <br> Aplicativo exibe todos os dados disponíveis sobre o país.  |
| **Restrições**  | O usuário precisa estar conectado à internet. <br> O aplicativo deve conter dados atualizados para todos os locais necessários. <br> A busca deve aceitar variações nos nomes dos municípios (acentuação, abreviações). |
| **Exceção**     | Nome do local não encontrado na base de dados. <br> Falha de conexão com a internet impede a exibição das informações. <br> Dados demográficos do município ainda não estão atualizados |

</center>

<font size="2"><p style="text-align: center">Fonte: [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>

### 3.5 Cenário 5: Calendário

<div style="text-align: justify; text-indent: 2cm;">O quinto cenário, apresentado na Tabela 7, faz referência ao requisito implementado: visualização de calendário com as datas de divulgação das pesquisas e estatísticas realizadas pelo IBGE (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/analise_interface/#3-requisitos-elicitados">RF05</a>).</div>

<font size="3"><p style="text-align: center">Tabela 7: Calendário</p></font>

<center>

| Cenário 5 | Calendário |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**      | Visualizar calendário |
| **Objetivo**    | Permitir que o usuário visualize as datas de divulgação das pesquisas e estatísticas realizadas pelo IBGE |
| **Contexto**    | Local: Página "Calendário" do aplicativo. <br> Tempo: Aproximadamente 1min. <br> Pré-condição: Um filtro de indicadores por região deve estar disponível no aplicativo. |
| **Atores**      | Usuário do IBGE |
| **Recursos**    | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. |
| **Episódios**   |  Usuário abre o aplicativo e acessa a aba "Calendário" pela navbar. <br> Aplicativo exibe o calendário com as datas de divulgação das pesquisas e estatísticas. <br> Usuário navega pelo calendário para visualizar eventos futuros e passados. <br> Ao tocar em uma data específica, o aplicativo exibe os detalhes da pesquisa ou estatística correspondente|
| **Restrições**  | O calendário exibe apenas eventos oficiais programados pelo IBGE. <br> Requer conexão com a internet para atualizações em tempo real. |
| **Exceção**     | Caso o usuário esteja sem internet <br> A base de dados sobre as datas está errada ou desatualizada |

</center>

<font size="2"><p style="text-align: center">Fonte: [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [João Félix](https://github.com/joaofmoreiraa), 2025.</p></font>

### 3.6 Cenário 6: Realizar censo

<div style="text-align: justify; text-indent: 2cm;">O sexto cenário, apresentado na Tabela 8, faz referência ao requisito não-implementado: possibilidade de responder a questionários relacionados ao censo diretamente pelo app (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF30</a>).</div>

<font size="3"><p style="text-align: center">Tabela 8: Realizar Censo </p></font>

<center>

| Cenário 6  | Realizar Censo                                                                                                                                                                                             |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**     | Realização digital do Censo                                                                                                                                                                                       |
| **Objetivo**   | Permitir que o cidadão responda ao Censo de forma prática e segura, sem a necessidade de visitas domiciliares.                                                                                                    |
| **Contexto**   | O usuário acessa a plataforma digital, realiza a autenticação via Gov.br e preenche as informações solicitadas pelo Censo.                                                                                        |
| **Atores**     | Usuário do IBGE, Sistema Gov.br.                                                                                                                                                   |
| **Recursos**   | Conta Gov.br ativa, conexão com a internet, dispositivo com acesso à plataforma.                                                                                                                                  |
| **Episódios**  |  O usuário acessa a plataforma do Censo. <br> Realiza autenticação via Gov.br. <br> É direcionado ao formulário do Censo. <br> Preenche os dados solicitados. <br>  Confirma e envia as informações. |
| **Restrições** | O usuário deve possuir uma conta válida no Gov.br e conexão estável com a internet.                                                                                                                               |
| **Exceção**    | Se a autenticação falhar ou o sistema do Gov.br estiver indisponível, o preenchimento não poderá ser realizado.                                                                                                   |


</center>

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### 3.7 Cenário 7: Autenticar pelo Gov.br

<div style="text-align: justify; text-indent: 2cm;">O sétimo cenário, apresentado na Tabela 9, faz referência ao requisito não-implementado: O sistema deve integrar-se com a conta Gov.br (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF57</a>).</div>

<font size="3"><p style="text-align: center">Tabela 9: Autenticar pelo Gov.br </p></font>

<center>

| Cenário 7 | Autenticar pelo Gov.br                                                                                                                                                                                                                                                                    |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**     | Autenticação do usuário via Gov.br                                                                                                                                                                                                                                                       |
| **Objetivo**   | Verificar a identidade do usuário para garantir acesso seguro às funcionalidades da plataforma digital, como o preenchimento do Censo.                                                                                                                                                   |
| **Contexto**   | O usuário acessa a plataforma e precisa se identificar para utilizar serviços restritos, iniciando o processo de autenticação através do Gov.br.                                                                                                                                         |
| **Atores**     | Usuário do IBGE, Sistema de Autenticação Gov.br                                                                                                                                                                                                                    |
| **Recursos**   | Conta ativa no Gov.br, CPF, senha ou método de autenticação biométrica ou facial, conexão com a internet, dispositivo com acesso à plataforma.                                                                                                                                           |
| **Episódios**  | O usuário acessa a área de login da plataforma.<br>Escolhe a opção de autenticação via Gov.br.<br> É redirecionado para o ambiente do Gov.br.<br> Informa CPF e autentica com senha ou biometria.<br> Após validação, é redirecionado de volta à plataforma, já autenticado. |
| **Restrições** | O usuário deve ter uma conta válida no Gov.br e os serviços de autenticação devem estar operacionais.                                                                                                                                                                                    |
| **Exceção**    | Caso o sistema do Gov.br esteja fora do ar ou a autenticação falhe, o acesso à plataforma é negado, impossibilitando o uso de funcionalidades restritas.                                                                                                                                 |


</center>

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### 3.8 Cenário 8: Favoritar indicadores

<div style="text-align: justify; text-indent: 2cm;">O oitavo cenário, apresentado na Tabela 10, faz referência ao requisito não-implementado: o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF28</a>).</div>

<font size="3"><p style="text-align: center">Tabela 10: Favoritar indicadores e visualizar as últimas atualizações</p></font>

<center>

| Cenário 8 | Favoritar indicadores e visualizar as últimas atualizações | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | O usuário pode favoritar indicadores e visualizar as últimas atualizações | 
| **Objetivo** | Permitir que o usuário marque um indicador como favorito e visualize suas atualizações de forma rápida. | 
| **Contexto** | Local: Aba de indicadores.<br>Tempo: Aproximadamente 1min.<br>Pré-condição: Existirem indicadores disponíveis no sistema. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. | 
| **Episódios** | Usuário acessa a aba de indicadores.<br>Seleciona um indicador de interesse.<br>Clica na opção "favoritar".<br>O sistema registra a preferência.<br>Ao acessar novamente, o usuário vê o indicador favoritado com destaque e com as últimas atualizações. | 
| **Restrições** | O sistema deve registrar e manter os indicadores favoritados pelo usuário.<br>O sistema deve manter atualizados os dados exibidos para cada indicador. | 
| **Exceção** | Falha na conexão impede que as atualizações sejam carregadas.<br>O indicador foi removido ou está temporariamente indisponível. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>


### 3.9 Cenário 9: Alterar o tamanho da fonte

<div style="text-align: justify; text-indent: 2cm;">O nono cenário, apresentado na Tabela 11, faz referência ao requisito não-implementado: opção de alterar o tamanho da fonte (com botão) (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF53</a>).</div>

<font size="3"><p style="text-align: center">Tabela 11: Alterar o tamanho da fonte com botão</p></font>

<center>

| Cenário 9 | Alterar o tamanho da fonte com botão | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Ajustar o tamanho da fonte na interface do aplicativo | 
| **Objetivo** | Permitir que o usuário personalize o tamanho da fonte para melhor leitura. | 
| **Contexto** | Local: Página de configurações ou acessibilidade.<br>Tempo: De 30s a 1min.<br>Pré-condição: O botão de ajuste de fonte estar visível e funcional. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Aplicativo do IBGE instalado.<br>Acesso ao menu de configurações. | 
| **Episódios** | Usuário abre o aplicativo.<br>Acessa as configurações.<br>Localiza a seção de acessibilidade.<br>Usa os botões de + ou - para aumentar ou diminuir a fonte.<br>O aplicativo ajusta o tamanho do texto exibido. | 
| **Restrições** | O tamanho máximo e mínimo da fonte deve estar pré-definido.<br>A interface deve permanecer legível e sem quebras mesmo com tamanhos maiores. | 
| **Exceção** | O botão de ajuste de fonte não responde.<br>O texto da interface não é redimensionado corretamente. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>


### 3.10 Cenário 10: Ativar modo noturno

<div style="text-align: justify; text-indent: 2cm;">O décimo cenário, apresentado na Tabela 12, faz referência ao requisito não-implementado: opção de modo noturno (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF51</a>).</div>

<font size="3"><p style="text-align: center">Tabela 12:  Cenário de ativação do modo noturno</p></font>

<center>

| Cenário 10 | Cenário de ativação do modo noturno | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Ativar o modo noturno na interface do aplicativo | 
| **Objetivo** | Oferecer maior conforto visual ao usuário em ambientes com pouca luz. | 
| **Contexto** | Local: Página de configurações.<br>Tempo: De 30s a 1min.<br>Pré-condição: O botão de alternância de tema estar disponível e funcional. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Aplicativo do IBGE instalado.<br>Acesso ao menu de configurações. | 
| **Episódios** | Usuário abre o aplicativo.<br>Acessa a aba de configurações.<br>Ativa a opção de modo noturno.<br>A interface muda para esquema de cores escuras. | 
| **Restrições** | A alteração de tema deve ser instantânea.<br>Todos os elementos da interface devem se adaptar ao novo tema. | 
| **Exceção** | A interface não muda ao ativar o modo.<br>Alguns elementos continuam com fundo claro, dificultando a leitura. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### 3.11 Cenário 11: Computar informações de dados e gerar relatórios para exportação

<div style="text-align: justify; text-indent: 2cm;">
Este cenário descreve o processo pelo qual o sistema computa informações estatísticas a partir dos dados selecionados e gera relatórios para exportação em formatos padrão, atendendo ao requisito não-implementado (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF37</a>).
</div>

<font size="3"><p style="text-align: center">Tabela 13: Cenário de computar informações e gerar relatórios para exportação</p></font>

<center>

| Cenário 11 | Computar informações e gerar relatórios para exportação | 
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Computar dados e gerar relatórios para exportação | 
| **Objetivo** | Permitir que o usuário selecione dados, processe as informações e gere relatórios formatados para exportação. | 
| **Contexto** | Local: Área de relatórios do aplicativo.<br>Tempo: De 3 a 10 minutos.<br>Pré-condição: O usuário deve ter acesso a dados atualizados para análise. | 
| **Atores** | Usuário / Administrador | 
| **Recursos** | Acesso à internet <br> Aplicativo instalado em dispositivo compatível. | 
| **Episódios** | Usuário acessa a funcionalidade de geração de relatórios.<br>Usuário seleciona parâmetros de análise (período, indicadores, regiões).<br>O sistema processa os dados e gera o relatório.<br>Usuário escolhe formato para exportação (PDF, Excel, CSV).<br>Sistema salva o arquivo e disponibiliza para download. | 
| **Restrições** | O sistema deve garantir a integridade dos dados.<br>O relatório deve conter informações completas e formatadas corretamente.<br>O processo deve suportar múltiplos formatos de exportação. | 
| **Exceção** | Dados indisponíveis ou incompletos.<br>Erro na geração ou salvamento do relatório.<br>Interrupção de conexão durante o processo. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### 3.12 Cenário 12: Compartilhamento de métricas do aplicativo com a fonte atrelada ao IBGE

<div style="text-align: justify; text-indent: 2cm;">
Este cenário descreve o compartilhamento de métricas estatísticas do aplicativo, garantindo que a fonte dos dados esteja explicitamente vinculada ao IBGE, conforme o requisito não-implementado (<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#3-requisitos-elicitados>RF59</a>).
</div>

<font size="3"><p style="text-align: center">Tabela 14: Cenário de compartilhamento de métricas com referência ao IBGE</p></font>

<center>

| Cenário 12 | Compartilhamento de métricas do aplicativo com fonte IBGE | 
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Compartilhamento de métricas com fonte IBGE | 
| **Objetivo** | Permitir que o usuário compartilhe métricas do aplicativo com a referência clara à fonte oficial IBGE. | 
| **Contexto** | Local: Seção de métricas do aplicativo.<br>Tempo: De 1 a 3 minutos.<br>Pré-condição: Métricas atualizadas e disponíveis para compartilhamento. | 
| **Atores** | Usuário final (cidadão, pesquisador, analista) | 
| **Recursos** | Acesso à internet <br> Aplicativo instalado em dispositivo compatível. | 
| **Episódios** | Usuário seleciona opção de compartilhamento de métricas.<br>Sistema exibe métricas disponíveis.<br>Usuário escolhe métricas e formato de compartilhamento.<br>Sistema gera conteúdo com referência explícita ao IBGE.<br>Usuário seleciona plataforma para envio e confirma.<br>Sistema executa o compartilhamento. | 
| **Restrições** | A referência ao IBGE deve estar presente em todo conteúdo compartilhado.<br>O compartilhamento deve respeitar os formatos aceitos pelas plataformas sociais. | 
| **Exceção** | Métricas indisponíveis.<br>Falha na conexão durante o compartilhamento.<br>Erro ao gerar o conteúdo para envio. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.</p></font>

### 3.13 Cenário 13: Visualizar mapas interativos

<div style="text-align: justify; text-indent: 2cm;">O décimo terceiro cenário, apresentado na Tabela 15, faz referência ao requisito não-implementado: Mapas interativos, com visualização de dados geográficos e demográficos. (<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados>RF34</a>).</div>

<font size="3"><p style="text-align: center">Tabela 15:  Cenário de visualização de mapas interativos</p></font>

<center>

| Cenário 13 | Cenário de visualização de mapas interativos | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Visualizar dados geográficos e demográficos em mapas interativos | 
| **Objetivo** | Permitir que o usuário explore dados regionais de forma visual e interativa. | 
| **Contexto** | Local: Página principal do aplicativo, na seção “Mapas”.<br>Tempo: 1 a 3 minutos.<br>Pré-condição:  O dispositivo deve estar conectado à internet. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Aplicativo do IBGE instalado.<br>Acesso à seção de mapas interativos. <br> Conexão com os servidores de dados do IBGE. | 
| **Episódios** | Usuário abre o aplicativo.<br>Acessa a aba de mapas interativos.<br>Seleciona uma região no mapa (por estado ou município).<br>Escolhe o tipo de dado a ser visualizado (população, densidade demográfica, PIB etc). <br>O mapa é atualizado com camadas visuais e gráficos sobre os dados selecionados. <br> O usuário interage com o mapa (zoom, cliques, filtros).  | 
| **Restrições** | Os dados devem ser atualizados em tempo real ou com a versão mais recente disponível. <br>A interação com o mapa deve ser fluida e responsiva. <br> Camadas de dados devem ser claras e acessíveis para diferentes perfis de usuário. | 
| **Exceção** | O mapa não carrega devido à falta de conexão ou erro nos servidores. <br>Algumas camadas não são exibidas corretamente. <br>Filtros selecionados não refletem nas visualizações.  | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>

### 3.14 Cenário 14: Acessar central de ajuda

<div style="text-align: justify; text-indent: 2cm;">O décimo quarto cenário, apresentado na Tabela 16, faz referência ao requisito não-implementado: Central de Ajuda dentro do app, com informações sobre o uso do aplicativo. (<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados>RF26</a>).</div>

<font size="3"><p style="text-align: center">Tabela 16:  Cenário de Acessar central de ajuda
</p></font>

<center>

| Cenário 14 | Cenário de Acessar central de ajuda | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Acessar a Central de Ajuda com orientações sobre o uso do app | 
| **Objetivo** | Oferecer suporte rápido ao usuário com informações sobre funcionalidades e navegação do aplicativo. | 
| **Contexto** | Local: Menu principal ou ícone de ajuda na interface.<br>Tempo: 1 a 2 minutos.<br>Pré-condição:  O aplicativo deve estar com a Central de Ajuda habilitada e atualizada. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Aplicativo do IBGE instalado. <br> Acesso à internet para carregamento dinâmico de conteúdos (se aplicável). | 
| **Episódios** | Usuário abre o aplicativo.<br>Identifica dificuldades de uso ou deseja entender melhor uma funcionalidade.<br>Acessa a Central de Ajuda por meio do menu principal ou ícone de suporte. <br>Navega pelas categorias ou digita uma dúvida na barra de busca. <br> Visualiza o conteúdo explicativo (textos, imagens ou vídeos tutoriais). <br> Retorna ao uso normal do aplicativo com maior compreensão.  | 
| **Restrições** | As informações devem estar organizadas e ser de fácil acesso. <br>O conteúdo deve ser claro, direto e atualizado conforme as versões do app. <br> A busca por palavras-chave deve retornar resultados relevantes. | 
| **Exceção** | A Central de Ajuda não abre devido a falha de carregamento.<br> O conteúdo apresentado está desatualizado ou não responde à dúvida do usuário. <br> A busca não retorna resultados mesmo com termos corretos.  | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>

### 3.15 Cenário 15: Alto contraste do aplicativo

<div style="text-align: justify; text-indent: 2cm;">O décimo quinto cenário, apresentado na Tabela 17, faz referência ao requisito não-implementado: ativar modo de alto contraste para acessibilidade visual (<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/questionario/#3-requisitos-elicitados>RF54</a>).</div>

<font size="3"><p style="text-align: center">Tabela 17: Ativar modo de alto contraste</p></font>

<center>

| Cenário 15 | Ativar modo de alto contraste |
|------------|-------------------------------|
| **Título** | Ativar modo de alto contraste no aplicativo |
| **Objetivo** | Facilitar a visualização para usuários com deficiência visual ou sensibilidade à luz, aumentando a legibilidade da interface. |
| **Contexto** | Local: Página de configurações ou acessibilidade. <br> Tempo: Aproximadamente 30 segundos. <br> Pré-condição: O aplicativo deve conter a opção de ativar/desativar o alto contraste. |
| **Atores** | Usuário do IBGE |
| **Recursos** | Aplicativo do IBGE instalado. <br> Acesso ao menu de configurações ou acessibilidade. |
| **Episódios** | - Usuário abre o aplicativo. <br> - Acessa a seção de configurações. <br> - Entra no menu de acessibilidade. <br> - Localiza e ativa a opção de alto contraste. <br> - A interface é imediatamente ajustada com cores de alto contraste (ex: fundo preto e texto amarelo). |
| **Restrições** | - A paleta de cores em alto contraste deve seguir padrões de acessibilidade. <br> - Elementos visuais não devem se sobrepor ou desaparecer com o novo contraste. |
| **Exceção** | - O modo de alto contraste não é aplicado corretamente. <br> - Alguns elementos da interface se tornam ilegíveis ou com baixa distinção. |

</center>

<font size="2"><p style="text-align: center">Fonte: [João Felix](https://github.com/joaofmoreiraa), 2025.</p></font>

### 3.16 Cenário 16: Filtrar notícias por região e/ou tempo

<div style="text-align: justify; text-indent: 2cm;">O décimo sexto cenário, apresentado na Tabela 18, corresponde ao requisito não-implementado: o sistema deve permitir o filtro de notícias por região e/ou tempo (<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#31-funcionais>RF16</a>).</div>

<font size="3"><p style="text-align: center">Tabela 18: Filtrar notícias por região e/ou tempo</p></font>

| Cenário 16 | Filtrar notícias por região e/ou tempo |
|------------|----------------------------------------|
| **Título** | Aplicar filtros de região e/ou período nas notícias exibidas |
| **Objetivo** | Permitir que o usuário visualize apenas notícias relevantes com base na localização geográfica e/ou intervalo de tempo escolhido. |
| **Contexto** | Local: Página de notícias ou seção informativa do aplicativo. <br> Tempo: Entre 30 segundos e 1 minuto. <br> Pré-condição: A funcionalidade de filtro deve estar visível e funcional. |
| **Atores** | Usuário do IBGE |
| **Recursos** | Aplicativo do IBGE instalado. <br> Acesso à internet. |
| **Episódios** | - Usuário abre o aplicativo. <br> - Acessa a seção de notícias. <br> - Seleciona a opção de filtro. <br> - Escolhe uma região e/ou intervalo de tempo. <br> - O sistema exibe apenas as notícias compatíveis com os critérios selecionados. |
| **Restrições** | - O filtro deve abranger todas as regiões disponíveis no app. <br> - O intervalo de tempo deve ser ajustável por data ou por opções pré-definidas (ex: últimos 7 dias). |
| **Exceção** | - Não existem notícias disponíveis para os filtros aplicados. <br> - O filtro não responde corretamente ou retorna dados incorretos. |

<font size="2"><p style="text-align: center">Fonte: [João Felix](https://github.com/joaofmoreiraa), 2025.</p></font>

### 3.17 Cenário 17: Comparação de Censos

<div style="text-align: justify; text-indent: 2cm;">O décimo sétimo cenário, apresentado na Tabela 19, corresponde ao requisito não-implementado: O sistema deve permitir a comparação dos censos realizados em diferentes anos.(<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#31-funcionais>RF43</a>).</div>

<font size="3"><p style="text-align: center">Tabela 19: Comparação de censos</p></font>

| Cenário 17 | Comparação de Censos |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **Título**      | Comparar dados do censo de diferentes anos |
| **Objetivo**    | Permitir que o usuário visualize e compare os dados do censo de diferentes anos para entender a evolução socioeconômica do país |
| **Contexto**    | **Local:** Plataforma web do sistema de censos <br> **Tempo:** Sessão de uso (5 a 15 minutos) <br> **Pré-condição:** Usuário acessa a plataforma e os dados de múltiplos anos estão disponíveis |
| **Atores**      | Usuário interessado em dados demográficos e socioeconômicos |
| **Recursos**    | Banco de dados com censos de anos diferentes, interface de comparação, gráficos e tabelas geradas dinamicamente |
| **Episódios**   |  O usuário acessa o app <br> O sistema exibe os anos disponíveis para comparação <br> O usuário seleciona dois ou mais anos que deseja comparar <br> O sistema exibe os dados comparativos em formato visual (gráficos, tabelas, mapas) <br> O usuário analisa as diferenças entre os anos. |
| **Restrições**  | Os dados dos anos selecionados devem estar previamente cadastrados e disponíveis no sistema; limite de comparação entre no máximo 3 anos simultaneamente |
| **Exceção**     | Se o ano selecionado não possui dados disponíveis, o sistema exibe uma mensagem de erro informando a indisponibilidade e sugere anos alternativos |



<font size="2"><p style="text-align: center">Fonte:[Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>

### 3.18 Cenário 18: Comparação de Taxa de Resposta ao Censo

<div style="text-align: justify; text-indent: 2cm;">O décimo oitavo cenário, apresentado na Tabela 20, corresponde ao requisito não-implementado: O sistema deve comparar os locais com maior e menor taxa de resposta ao censo.(<a href=https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/introspeccao/#31-funcionais>RF48</a>).</div>

<font size="3"><p style="text-align: center">Tabela 20: Comparação de Taxa de Resposta ao Censo</p></font>

| Cenário 18 | Comparação de Taxa de Resposta ao Censo |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título**      | Comparar locais com maior e menor taxa de resposta ao censo |
| **Objetivo**    | Permitir que o usuário visualize quais regiões tiveram maior e menor participação no censo, auxiliando na análise de cobertura e engajamento |
| **Contexto**    | **Local:** Aplicativo **Tempo:** Sessão de uso 5 a 10 minutos <br> **Pré-condição:** Dados de taxa de resposta por localidade disponíveis no sistema |
| **Atores**      | Usuário do IBGE |
| **Recursos**    | Base de dados com taxa de resposta por localidade, interface de visualização, gráficos e mapas interativos |
| **Episódios**   |  O usuário acessa o app <br> O usuário acessa o sistema e escolhe a funcionalidade de comparação por taxa de resposta   <br> O usuário seleciona o ano do censo a ser analisado   <br> O sistema exibe um ranking com os locais de maior e menor taxa de resposta   <br> O usuário pode clicar em uma localidade para visualizar detalhes adicionais <br> O sistema permite exportar os dados ou gerar relatórios |
| **Restrições**  | Os dados devem estar atualizados e completos para todas as localidades |
| **Exceção**     | Caso alguma localidade não tenha dados disponíveis, o sistema a omite da análise e exibe um aviso informando ausência de dados para aquela região |


<font size="2"><p style="text-align: center">Fonte:[Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>

## 4. Validação 

<div style="text-align: justify; text-indent: 2cm;">Além de tudo apresentado acima, como parte fundamental da validação do artefato, os cenários foram analisados e validados pelo cliente Clístenes Mendonça, profissional da área da saúde, cuja contribuição foi essencial para garantir a aderência dos cenários às expectativas dos usuários e aos objetivos do sistema.</div>
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/YijSXiPgdEk?si=nQOiw8t6F1tCbkDc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

## 5. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025, p. 8. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 13 maio 2025.

<div style="text-align: center">
<img src="./../../assets/images/modelagem/fonte_cenario.png" width="400"/>
</div>

> Ian Sommerville  *Engenharia de Software*. tradução Ivan Bosnic e Kalinka G. de O. Gonçalves ; revisão técnica Kechi Hirama. — 9. ed. — São Paulo : Pearson, p. 73. Disponível em: <https://www.facom.ufu.br/~william/Disciplinas%202018-2/BSI-GSI030-EngenhariaSoftware/Livro/engenhariaSoftwareSommerville.pdf>. Acesso em: 15 maio 2025.

<div style="text-align: center">
<img src="./../../assets/images/modelagem/fonte_cenario2.png" width="480"/>
</div>


## 5. Histórico de Versões 

<font size="3"><p style="text-align: center">Tabela 21: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento com introdução e bibliografia| [Mayara Marques](https://github.com/maymarquee)| 13/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|1.1     |Inserção de cenários 1 e 2| [Mayara Marques](https://github.com/maymarquee)| 14/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|1.2    |Inserção de cenários 3, 4 e 5| [Letícia Monteiro](https://github.com/LeticiaMonteiroo)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.3    |Adição de explicação de elementos básicos de cenários| [Mayara Marques](https://github.com/maymarquee)| 15/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.4    |Adição de cenários 6 e 7 | [Caio Duarte](https://github.com/caioduart3)| 15/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.5    |Adição de cenários 8 a 10 | [Ludmila Nunes](https://github.com/ludmilaaysha)| 17/05/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
|1.6    |Ajuste de índices e descrições de cenários e tabelas | [Ludmila Nunes](https://github.com/ludmilaaysha)| 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|1.6.1    | Corrige índice tabela de versionamento | [Gabriel Pinto](https://github.com/GabrielSPinto)| 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|1.7    |Adição de cenários 11 e 12 | [Gabriel Pinto](https://github.com/GabrielSPinto)| 17/05/2025 | [Mayara Marques](https://github.com/maymarquee) |
|1.8    |Adição de cenários 13 e 14 | [Laryssa Felix](https://github.com/felixlaryssa)| 17/05/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
|1.9    |Adição de cenários 15 e 16 | [João Felix](https://github.com/joaofmoreiraa)| 17/05/2025 | [Mayara Marques](https://github.com/maymarquee) |
|2.0    |Inserção de elementos no cenários 3 | [Laryssa Felix](https://github.com/felixlaryssa)| 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|2.1    |Correção de links | [João Felix](https://github.com/joaofmoreiraa)| 17/05/2025 | [Mayara Marques](https://github.com/maymarquee) |
|2.2    |Adição dos Cenários 17 e 18 |[Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 17/05/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
|2.3    | Ajuste no documento |[Gabriel Pinto](https://github.com/GabrielSPinto) | 17/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|2.4    | Adição da tabela de cronograma e gravação da validação|[Mayara Marques](https://github.com/maymarquee) | 20/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|2.5  | Revisão do Documento| [Letícia Monteiro](https://github.com/LeticiaMonteiroo)| 22/06/2025 |  [Laryssa Felix](https://github.com/felixlaryssa) |


<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 