# Cenários

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">
Cenários se trata de uma estratégia usada para reconhecer interações entre ambientes e sistemas (SERRANO; SERRANO, 2025). Elementos como o comportamento do software, sua dinâmica e seu fluxo são possíveis de serem entendidos com cenários.
</div>
<div style="text-align: justify; text-indent: 2cm;">
O cenário conta com elementos básicos, que são: título, objetivos/metas, contexto, ator(es), recursos, exceções e episódios, que devem estar presentes em cada artefato.  
</div>
<div style="text-align: justify; text-indent: 2cm;">
Podemos trazer os conceitos de cenários para o aplicativo IBGE, explorando diversos cenários que os usuários da aplicação podem passar ao utilizar o aplicativo. 
</div>

## 2. Cenários

<div style="text-align: justify; text-indent: 2cm;">
Os artefatos produzidos pelo grupo podem ser observados nas tabelas de 1 a -. 
</div>

### 2.1 Cenário 1: Consultar FAQ 

<font size="3"><p style="text-align: center">Tabela 1: Cenário de consultar FAQ</p></font>

<center>

| Cenário 1 | Consultar FAQ | 
| :-:       | :-:            |
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
| :-:       | :-:            |
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

## 3. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. UnB, 2025, p. 8. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 13 maio 2025.

<div style="text-align: center">
<img src="./../../assets/images/modelagem/fonte_cenario.png" width="400"/>
</div>

## 4. Histórico de Versões 

<font size="3"><p style="text-align: center">Tabela 3: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento com introdução e bibliografia| [Mayara Marques](https://github.com/maymarquee)| 13/05/2025 | [Larysssa Felix](https://github.com/felixlaryssa) |
|1.1     |Inserção de cenários 1 e 2| [Mayara Marques](https://github.com/maymarquee)| 14/05/2025 | [Larysssa Felix](https://github.com/felixlaryssa) |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 