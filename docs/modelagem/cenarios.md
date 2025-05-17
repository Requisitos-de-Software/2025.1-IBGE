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

## 2. Cenários

<div style="text-align: justify; text-indent: 2cm;">
Os artefatos produzidos pelo grupo podem ser observados nas tabelas de 1 a -, sempre seguindo a mesma estrutura da tabela de descrição dos cenários:
</div>

<font size="3"><p style="text-align: center">Tabela 1: Estrutura da tabela de descrição dos cenários</p></font>

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

### 2.1 Cenário 1: Consultar FAQ 

<div style="text-align: justify; text-indent: 2cm;">O primeiro cenário, apresentado na Tabela 2, faz referência ao requisito não-implementado:  sistema deve possuir uma FAQ com respostas às dúvidas mais comuns (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF60</a>).</div>

<font size="3"><p style="text-align: center">Tabela 2: Cenário de consultar FAQ</p></font>

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

### 2.2 Cenário 2: Comparar indicadores por região 

<div style="text-align: justify; text-indent: 2cm;">O segundo cenário, apresentado na Tabela 3, faz referência ao requisito não-implementado: comparativo de indicadores por região. (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF29</a>).</div>

<font size="3"><p style="text-align: center">Tabela 3: Cenário de comparar indicadores por região</p></font>

<center>

| Cenário 2 | Comparar indicadores por região | 
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título** | Comparar dados de indicadores por região. | 
| **Objetivo** | Permitir que o usuário visualize e compare os indicadores por região. | 
| **Contexto** | Local: Página "Indicadores" do aplicativo. <br> Tempo: Aproximadamente 1min. <br> Pré-condição: Um filtro de indicadores por região deve estar disponível no aplicativo. | 
| **Atores** | Usuário do IBGE | 
| **Recursos** | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. | 
| **Episódios** | Usuário abre o aplicativo e acessa a aba "Indicadores" pela navbar. <br> Usuário seleciona a opção "Comparativos". <br> Aplicativo exibe todos os indicadores disponíveis no aplicativo junto com as regiões do Brasil, com valores correspondentes à cada região. | 
| **Restrições** | O usuário precisa ter acesso à internet. <br> O aplicativo deve possuir dados de indicadores atualizados. <br> O aplicativo deve possuir separação de regiões do país para comparar os dados. | 
| **Exceção** | Não ter acesso à internet. <br> Aplicativo não possui dados de indicadores atualizados. <br> Aplicativo não consegue correlacionar dados à regiões, e uma mensagem de erro deve ser apresentada ao usuário. | 

</center>

<font size="2"><p style="text-align: center">Fonte: [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>

### 2.3 Cenário 3: Notícias 

<div style="text-align: justify; text-indent: 2cm;">O terceiro cenário, apresentado na Tabela 4, faz referência ao requisito implementado: o sistema deve possuir notícias atualizadas sobre dados demográficos/socioeconômicos do Brasil, de seus estados e municípios (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF01</a>).</div>

<font size="3"><p style="text-align: center">Tabela 4: Notícias</p></font>

<center>

| Cenário 3 | Título do Cenário |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**      | Descreva o título do cenário |
| **Objetivo**    | Permitir que o usuário acesse e leia notícias atualizadas sobre dados e <br> pesquisas realizadas pelo IBGE |
| **Contexto**    | Local: Descreva o local. <br> Tempo: Duração estimada. <br> Pré-condição: Pré-requisitos necessários. |
| **Atores**      | Usuário do IBGE |
| **Recursos**    | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. |
| **Episódios**   | O usuário abre o aplicativo do IBGE no celular. <br> Clica em "Notícias" na navbar <br> Ele seleciona uma notícia de interesse, como "Em março, indústria avança em dez dos <br> 15 locais pesquisados" <br> O usuário lê o conteúdo completo da notícia dentro do app. |
| **Restrições**  | Limitações ou condições obrigatórias |
| **Exceção**     | O que pode dar errado e como o sistema reage |

</center>

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa) e [Letícia Monteiro](https://github.com/LeticiaMonteiroo), 2025.</p></font>


### 2.4 Cenário 4: Análise dos Dados Demográficos do Brasil

<div style="text-align: justify; text-indent: 2cm;">O quarto cenário, apresentado na Tabela 5, faz referência ao requisito não-implementado: XX (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFX</a>).</div>

<font size="3"><p style="text-align: center">Tabela 5: Análise dos <i> Dados Demográficos </i> do Brasil</p></font>

<center>

| Cenário 4 | Título do Cenário |
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

### 2.5 Cenário 5: Calendário

<div style="text-align: justify; text-indent: 2cm;">O quinto cenário, apresentado na Tabela 6, faz referência ao requisito não-implementado: XX (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFX</a>).</div>

<font size="3"><p style="text-align: center">Tabela 6: Calendário</p></font>

<center>

| Cenário 5 | Título do Cenário |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**      | Visualizar calendário |
| **Objetivo**    | Permitir que o usuário visualize as datas de divulgação das pesquisas e estatísticas realizadas pelo IBGE |
| **Contexto**    | Local: Página "Calendário" do aplicativo. <br> Tempo: Aproximadamente 1min. <br> Pré-condição: Um filtro de indicadores por região deve estar disponível no aplicativo. |
| **Atores**      | Usuário do IBGE |
| **Recursos**    | Acesso à internet <br> Aplicativo do IBGE instalado no <i>smartphone</i>. |
| **Episódios**   | Passo a passo do que acontece no cenário |
| **Restrições**  | O calendário exibe apenas eventos oficiais programados pelo IBGE. <br> Requer conexão com a internet para atualizações em tempo real. |
| **Exceção**     | Caso o usuário esteja sem internet <br> A base de dados sobre as datas está errada ou desatualizada |

</center>

<font size="2"><p style="text-align: center">Fonte: [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [João Félix](https://github.com/joaofmoreiraa), 2025.</p></font>

### 2.6 Cenário 6: Realizar censo

<div style="text-align: justify; text-indent: 2cm;">O sexto cenário, apresentado na Tabela 7, faz referência ao requisito não-implementado: possibilidade de responder a questionários relacionados ao censo diretamente pelo app (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RF30</a>).</div>

<font size="3"><p style="text-align: center">Tabela 7: Realizar Censo </p></font>

<center>

| Cenário 6  | Título do Cenário                                                                                                                                                                                             |
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

### 2.7 Cenário 7: Autenticar pelo Gov.br

<div style="text-align: justify; text-indent: 2cm;">O sétimo léxico, apresentado na Tabela 8, faz referência ao requisito não-implementado: O sistema deve integrar-se com a conta Gov.br (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF57</a>).</div>

<font size="3"><p style="text-align: center">Tabela 8: Autenticar pelo Gov.br </p></font>

<center>

| Cenário 7 | Título do Cenário                                                                                                                                                                                                                                                                    |
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

### 2.8 Cenário 8: Favoritar indicadores

<div style="text-align: justify; text-indent: 2cm;">O oitavo cenário, apresentado na Tabela 9, faz referência ao requisito não-implementado: o usuário pode favoritar indicadores e visualizar as últimas atualizações (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF28</a>).</div>

<font size="3"><p style="text-align: center">Tabela 9: Favoritar indicadores e visualizar as últimas atualizações</p></font>

<center>

| Cenário 8 | Título do Cenário | 
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


### 2.9 Cenário 9: Alterar o tamanho da fonte

<div style="text-align: justify; text-indent: 2cm;">O nono cenário, apresentado na Tabela 10, faz referência ao requisito não-implementado: opção de alterar o tamanho da fonte (com botão) (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF53</a>).</div>

<font size="3"><p style="text-align: center">Tabela 10: Alterar o tamanho da fonte com botão</p></font>

<center>

| Cenário 9 | Título do Cenário | 
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


### 2.10 Cenário 10: Ativar modo noturno

<div style="text-align: justify; text-indent: 2cm;">O décimo cenário, apresentado na Tabela 11, faz referência ao requisito não-implementado: opção de modo noturno (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RF51</a>).</div>

<font size="3"><p style="text-align: center">Tabela 11:  Cenário de ativação do modo noturno</p></font>

<center>

| Cenário 10 | Título do Cenário | 
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

### 2.11 Cenário 11: Computar informações de dados e gerar relatórios para exportação

<div style="text-align: justify; text-indent: 2cm;">
Este cenário descreve o processo pelo qual o sistema computa informações estatísticas a partir dos dados selecionados e gera relatórios para exportação em formatos padrão, atendendo ao requisito RF37.
</div>

<font size="3"><p style="text-align: center">Tabela 12: Cenário de computar informações e gerar relatórios para exportação</p></font>

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

### 2.12 Cenário 2: Compartilhamento de métricas do aplicativo com a fonte atrelada ao IBGE

<div style="text-align: justify; text-indent: 2cm;">
Este cenário descreve o compartilhamento de métricas estatísticas do aplicativo, garantindo que a fonte dos dados esteja explicitamente vinculada ao IBGE, conforme o requisito RF49.
</div>

<font size="3"><p style="text-align: center">Tabela 13: Cenário de compartilhamento de métricas com referência ao IBGE</p></font>

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

## 3. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025, p. 8. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 13 maio 2025.

<div style="text-align: center">
<img src="./../../assets/images/modelagem/fonte_cenario.png" width="400"/>
</div>

> Ian Sommerville  *Engenharia de Software*. tradução Ivan Bosnic e Kalinka G. de O. Gonçalves ; revisão técnica Kechi Hirama. — 9. ed. — São Paulo : Pearson, p. 73. Disponível em: <https://www.facom.ufu.br/~william/Disciplinas%202018-2/BSI-GSI030-EngenhariaSoftware/Livro/engenhariaSoftwareSommerville.pdf>. Acesso em: 15 maio 2025.

<div style="text-align: center">
<img src="./../../assets/images/modelagem/fonte_cenario2.png" width="480"/>
</div>


## 4. Histórico de Versões 

<font size="3"><p style="text-align: center">Tabela 12: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento com introdução e bibliografia| [Mayara Marques](https://github.com/maymarquee)| 13/05/2025 | [Larysssa Felix](https://github.com/felixlaryssa) |
|1.1     |Inserção de cenários 1 e 2| [Mayara Marques](https://github.com/maymarquee)| 14/05/2025 | [Larysssa Felix](https://github.com/felixlaryssa) |
|1.2    |Inserção de cenários 3, 4 e 5| [Letícia Monteiro](https://github.com/LeticiaMonteiroo)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.3    |Adição de explicação de elementos básicos de cenários| [Mayara Marques](https://github.com/maymarquee)| 15/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.4    |Adição de cenários 6 e 7 | [Caio Duarte](https://github.com/caioduart3)| 15/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.5    |Adição de cenários 8 a 10 | [Ludmila Nunes](https://github.com/ludmilaaysha)| 17/05/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
|1.6    |Ajuste de índices e descrições de cenários e tabelas | [Ludmila Nunes](https://github.com/ludmilaaysha)| 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|1.6.1    | Corrige índice tabela de versionamento | [Ludmila Nunes](https://github.com/ludmilaaysha)| 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|1.7    |Adição de cenários 11 e 12 | [Gabriel Pinto](https://github.com/GabrielSPinto)| 17/05/2025 | [Mayara Marques](https://github.com/maymarquee) |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 