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

### 2.1 Cenário 1: Consultar FAQ 

<font size="3"><p style="text-align: center">Tabela 1: Cenário de consultar FAQ</p></font>

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

<font size="3"><p style="text-align: center">Tabela 2: Cenário de comparar indicadores por região</p></font>

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

<font size="3"><p style="text-align: center">Tabela 3: Notícias</p></font>

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

<font size="3"><p style="text-align: center">Tabela 4: Análise dos <i> Dados Demográficos <i> do Brasil</p></font>

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

### 2.4 Cenário 5: Calendário

<font size="3"><p style="text-align: center">Tabela 5: Calendário</p></font>

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

### 2.5 Cenário 6: Realizar censo

<div style="text-align: justify; text-indent: 2cm;">O sexto cenário, apresentado na Tabela 6, faz referência ao requisito não-implementado: Possibilidade de responder a questionários relacionados ao censo diretamente pelo app. (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/brainstorming/#anchor_B">RFB13</a>).</div>

<font size="3"><p style="text-align: center">Tabela 6: Realizar Censo </p></font>

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

### 2.6 Cenário 7: Autenticar pelo Gov.br

<div style="text-align: justify; text-indent: 2cm;">O sétimo léxico, apresentado na Tabela , faz referência ao requisito não-implementado: O sistema deve integrar-se com a conta Gov.br (<a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/tecnicas_selecionadas/entrevista/#anchor_E">RFE03</a>).</div>

<font size="3"><p style="text-align: center">Tabela 7: Autenticar pelo Gov.br </p></font>

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

<font size="3"><p style="text-align: center">Tabela 6: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento com introdução e bibliografia| [Mayara Marques](https://github.com/maymarquee)| 13/05/2025 | [Larysssa Felix](https://github.com/felixlaryssa) |
|1.1     |Inserção de cenários 1 e 2| [Mayara Marques](https://github.com/maymarquee)| 14/05/2025 | [Larysssa Felix](https://github.com/felixlaryssa) |
|1.2    |Inserção de cenários 3, 4 e 5| [Letícia Monteiro](https://github.com/LeticiaMonteiroo)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.3    |Adição de explicação de elementos básicos de cenários| [Mayara Marques](https://github.com/maymarquee)| 15/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.4    |Adição de cenários 6 e 7 | [Caio Duarte](https://github.com/caioduart3)| 15/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 