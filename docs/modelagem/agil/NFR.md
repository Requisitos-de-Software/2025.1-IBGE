# NFR Framework

## 1. Introdução

<div style="text-align: justify; text-indent: 2cm;">
O NFR Framework (Non-Functional Requirements Framework) é uma abordagem usada para identificar, categorizar e organizar os <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/">Requisitos Não-Funcionais</a> (non-functional requirements, NFRs) em sistemas de software.
</div>

## 2. Softgoal Interdependency Graph

<div style="text-align: justify; text-indent: 2cm;">
O Softgoal Interdependency Graph (SIG) é uma representação visual fundamental do funcionamento do NFR Framework. Ele organiza os softgoals (metas não funcionais) e explicita, de forma gráfica e concisa, as decisões da equipe de desenvolvimento em relação a esses objetivos, bem como suas interdependências e possíveis conflitos <a id="anchor_1" href="#REF1">^1^</a>.
</div>

### 2.1 Tipos de Softgoal

<div style="text-align: justify; text-indent: 2cm;">
Para a compreensão do SIG, é inexorável discernir a definição de NFR Softgoal: um objetivo que não é explicitamente definido e seus critérios de satisfação são imprecisos. Sendo assim, um softgoal é uma característica abstrata que está sujeita à vistoria, ou seja, postula-se posteriormente o destino de um determinado softgoal. Além disso, os softgoals podem ser operacionalizados, nesse caso, tomam uma forma concreta. Portanto, entende-se como funcionalidades. Por fim, há os softgoals de afirmação, os quais são escritos em linguagem natural e se tratam de registros adicionais e argumentativos, os quais podem ser incrementados ao modelo<a id="anchor_1" href="#REF1">^1^</a>. Os tipos de softgoal estão ilustrados na Figura 1.
</div>



<font size="3"><p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal</p></font>

<center>
<img src="./../../../assets/images/modelagem/fonte1NFR.png" width= "480">
</center>

<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>



#### 2.1.1 Interdependências

<div style="text-align: justify; text-indent: 2cm;">
As interdependências representam as relações estabelecidas entre diferentes softgoals no NFR Framework. Essas interdependências são classificadas em dois tipos principais: decomposições e contribuições.
</div>

#### 2.1.2 Decomposições

<div style="text-align: justify; text-indent: 2cm;">
As decomposições no NFR Framework podem ocorrer em diferentes níveis de abstração: softgoals de requisitos não funcionais (NFR), de operacionalização, de afirmação e de priorização (SILVA, 2019)<a id="anchor_1" href="#REF1">^1^</a>. Nas três primeiras categorias, os softgoals são subdivididos em softgoals mais específicos, contribuindo para a redução de ambiguidades e facilitando a análise e o refinamento dos requisitos. Os quatro tipos de decomposição estão representados na Figura 2:
</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;">
<ul>
<li>Decomposição NFR: permite dividir preocupações primordiais em partes menores, promovendo clareza e auxiliando na definição de prioridades.

<li>Decomposição de Operacionalização: visa detalhar uma solução geral, desmembrando-a em soluções específicas e concretas.

<li>Decomposição de Afirmação: utilizada para expressar a aceitação ou negação de justificativas específicas no contexto do projeto.

<li>Decomposição de Priorização: uma decomposição especial em que o softgoal é refinado em outro softgoal de mesmo tipo e tópico, mas com a associação de um nível de prioridade.
</ul>
</div>

<font size="3"><p style="text-align: center"><b>Figura 2</b> - Tipos de Decomposição</p></font>

<center>
<img src="./../../../assets/images/modelagem/fonte2NFR.png" width= "500">
</center>

<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

#### 2.1.3 Contribuições


<div style="text-align: justify; text-indent: 2cm;">
No NFR Framework, os softgoals tendem a se especializar progressivamente por meio de refinamentos. Consequentemente, um softgoal derivado pode contribuir para o softgoal do qual se originou de maneira parcial ou integral, e de forma positiva ou negativa. A seguir, apresentam-se os principais tipos de contribuição <a id="anchor_2" href="#REF2">^2^</a>:
</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;">
<ul>

<li>AND: todos os softgoals derivados devem ser satisfeitos para que o softgoal principal também o seja.

<li>OR: a satisfação de qualquer um dos softgoals derivados é suficiente para satisfazer o softgoal principal.

<li>MAKE (++): o softgoal derivado contribui de forma totalmente positiva para o softgoal principal, garantindo sua satisfação.

<li>BREAK (--): o softgoal derivado contribui de forma totalmente negativa, comprometendo a satisfação do softgoal principal.

<li>HELP (+): há uma contribuição positiva parcial, que favorece o softgoal principal, mas sem garanti-lo plenamente.

<li>HURT (-): contribuição negativa parcial, que dificulta a satisfação do softgoal principal, porém sem invalidá-lo completamente.

<li>UNKNOWN (?): o tipo e intensidade da contribuição são indeterminados.

<li>EQUALS: indica uma relação direta de equivalência entre o softgoal derivado e o softgoal principal — satisfazer um implica satisfazer o outro.

<li>SOME: a forma da contribuição (positiva ou negativa) é conhecida, mas sua intensidade permanece indefinida.
</ul>
</div>

#### 2.1.4 Propagação de Impactos

<div style="text-align: justify; text-indent: 2cm;">
A propagação de impactos no NFR Framework envolve a identificação das relações de dependência entre os requisitos não funcionais e a análise de como alterações em um requisito podem afetar outros relacionados. Esse processo exige uma compreensão clara das interações entre os requisitos, bem como a habilidade de avaliar prioridades e trade-offs entre eles.
</div>

<div style="text-align: justify; text-indent: 2cm;">
Ao considerar a propagação de impactos, engenheiros de requisitos conseguem tomar decisões mais informadas quanto a mudanças no sistema e gerenciar os possíveis efeitos colaterais de forma eficaz. A seguir, são apresentados os principais tipos de softgoals de impacto e suas respectivas notações <a id="anchor_2" href="#REF2">^2^</a>:
</div>

<div style="text-align: justify; text-indent: 2cm;">
✓ (Satisfeito): Indica que um requisito contribui positivamente para a satisfação de outro.
</div>
<div style="text-align: justify; text-indent: 2cm;">
𝒲⁺ (Fracamente satisfeito): Representa uma contribuição positiva, porém com intensidade reduzida.
</div>
<div style="text-align: justify; text-indent: 2cm;">
✗ (Negado): O requisito impacta negativamente outro, negando ou contradizendo sua realização.
</div>
<div style="text-align: justify; text-indent: 2cm;">
𝒲⁻ (Fracamente negado): Sinaliza um impacto negativo menos intenso que o anterior.
</div>
<div style="text-align: justify; text-indent: 2cm;">
⚡(Conflitante): Indica a existência de um conflito entre requisitos, com características tanto positivas quanto negativas.
</div>
<div style="text-align: justify; text-indent: 2cm;">
u (Indeterminado): Representa uma relação cujo impacto é desconhecido ou não pode ser determinado com as informações disponíveis.
</div>

## 3. Metodologia
<div style="text-align: justify; text-indent: 2cm;">
Os frameworks foram agrupados por temas, que por sua vez foram divididos em três categorias para limitar o escopo da análise. A partir desses temas, foi realizada uma introspecção para a construção do Softgoal Interdependency Graph (SIG), tomando como base os tópicos gerais definidos. O objetivo foi estabelecer relações com os requisitos não funcionais da Tabela 12.
</div>
<div style="text-align: justify; text-indent: 2cm;">
Em seguida, realizou-se uma revisão da literatura para embasar teoricamente o modelo, seguida pela validação do SIG construído. A ferramenta utilizada para a elaboração do gráfico foi o <a href="https://app.diagrams.net/">Draw.io</a>.
</div>

<!-- 
## Cartões de Especificação

 Os cartões de especificação a seguir, Tabelas de 1 a 5, foram utilizados para definir os Requisitos Não-Funcionais a serem utilizados na confecção dos NFR Frameworks. Fontes de evidência na literarura: <a id="anchor_FE2" href="#FE2">FE2</a>. 

Obs: Os valores de prioridade foram baseados no modelo de priorização First Things First que pode ser encontado [aqui](../../../elicitacao/priorizacao/firstThingsfirst).

<center>

<b>Tabela 1</b> - Cartão de Especificação 1

| Nº Requisito: 1 (<a id="anchor_NF01" href="#NF01">RNF01</a>)| Classificação: Usabilidade |
|---------------| ------------|
| Descrição: O app deve fornecer eventos direcionados.
| Justificativa: O sistema deve ser capaz de direcionar eventos ao usuário a partir de suas preferências pessoais. Assim o usuário não irá perder tempo buscando por eventos que se adequem ao seu perfil .
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. 
| Dependências: Atividade do Usuário
| Prioridade: 4,05
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

<center>

<b>Tabela 2</b> - Cartão de Especificação 2

| Nº Requisito: 2 (<a id="anchor_NF02" href="#NF02">RNF02</a>)| Classificação: Usabilidade/Eficiência |
|---------------| ------------|
| Descrição: O app deve disponibilizar todas as informações do evento em uma página.
| Justificativa: Contribui para uma melhor visualização das informações por parte do usuário, e por conseguinte melhora a eficiência do app.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: O sistema deve disponibilizar todas informações necessárias sobre o evento em uma única página.
| Dependências: Nenhuma
| Prioridade: 2,70
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

<center>

<b>Tabela 3</b> - Cartão de Especificação

| Nº Requisito: 3 (<a id="anchor_NF03" href="#NF03">RNF03</a>)| Classificação: Eficiência|
|---------------| ------------|
| Descrição: A compra de ingressos deve ser realizada em menos de 5 páginas (botões)
| Justificativa: Operações que podem ser efetuadas em menos de 5 cliques em geral são consideradas eficientes. No caso do processo de compra, quão mais rapidamente essa operação for efetuada, não só o tempo gasto pelo usuário, mas também o gasto de energia do aplicativo serão reduzidos.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: O sistema deve efetuar a operação de compra em menos de 5 cliques.
| Dependências: Informações Suficientes
| Prioridade: 1,35
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

<center>

<b>Tabela 4</b> - Cartão de Especificação 4

| Nº Requisito: 4 (<a id="anchor_NF04" href="#NF04">RNF04</a>)| Classificação: Desempenho |
|---------------| ------------|
| Descrição: As ações realizadas no app não devem demorar mais que 200 ms para responder ao usuário
| Justificativa: As ações rápidas no app garantem uma experiência fluida, mantendo o usuário engajado e evitando frustrações desnecessárias.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: As ações realizadas no app devem ser executadas e responder ao usuário em um tempo máximo de 250 ms para garantir uma experiência ágil e satisfatória.
| Dependências: Performance
| Prioridade: 0,469
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Sidney Fernando](https://github.com/nando3d3)

</center>


<center>

<b>Tabela 5</b> - Cartão de Especificação 5

| Nº Requisito: 5 (<a id="anchor_NF05" href="#NF05">RNF05</a>)| Classificação: Usabilidade |
|---------------| ------------|
| Descrição: O app deve permitir a filtragem dos eventos cadastrados no banco de dados.
| Justificativa: A filtragem de eventos no app proporciona aos usuários a capacidade de encontrar rapidamente informações relevantes, melhorando a usabilidade e a eficiência na busca de eventos específicos no banco de dados.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: Filtragem flexível.
| Dependências: Atividade do Usuário
| Prioridade: 1,042
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Sidney Fernando](https://github.com/nando3d3)

</center>

## NFR 00 - Geral

A Figura 3 a seguir demonstra o Softgoal Interdependency Graph para se ter uma visão geral.


<font size="3"><p style="text-align: center"><b>Figura 3</b> - SIG Geral</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../../assets/nfr-framework/geralL.png)

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

No entanto, dada a limitação do grupo de trabalhar apenas com Requisitos Não-Funcionais ainda não implementados pelo site, adaptou-se o SIG acima para a utilização dos tópicos necessários, presentes na Figura 4.

<font size="3"><p style="text-align: center"><b>Figura 4</b> - SIG Geral Adaptado</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../../assets/nfr-framework/geralattD.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>


## NFR 01 - Usabilidade

Os Requisitos utilizados para a confecção da Figura 5 estão presentes na Tabela 12:

- <a id="anchor_NF01" href="#NF01">RNF01</a>: indica que o usuário deve receber eventos sugeridos de acordo com sua atividade no site.
- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF05" href="#NF05">RNF05</a>: refere-se à necessidade da filtragem sob diversas óticas dentro da busca no site.


<font size="3"><p style="text-align: center"><b>Figura 5</b> - SIG Usabilidade</p></font>

<figure markdown markdown class="usecaseElement">

![SIG Usabilidade](../../assets/nfr-framework/usabilidade.png){width: 300}

</figure>

<font size="3"><p style="text-align: center"> Fonte: [Caio Duarte](https://github.com/caioduart3)</p></font>



Legenda:

- Sugestões: refere-se ao [L02 - Sugestões de Eventos](../../lexicos/#l02-sugestoes-de-eventos).
- Opções de filtro: refere-se ao [L01 - Filtrar Eventos](../../lexicos/#l01-filtrar-eventos).

### Requisitos Não-Funcionais - Usabilidade

Na Tabela 6, estão listados os RNF presentes no NFR Famework de Usabilidade :

<center>
<b>Tabela 6</b> - Requisitos Não-Funcionais 1

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Adaptação (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve ser adaptativo às atividades do usuário. | Usabilidade | Sugestões |
| Acessibilidade (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve disponibilizar as informações. | Usabilidade | Usabilidade |
| Exibir Inf. do Evento (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve exibir as informações do evento específico. | Usabilidade | Informações Relevantes |
| Sugestões Gerais (<a id="anchor_FE3" href="#FE3">FE3</a>) | O sistema deve exibir as sugestões padrões antes de se ter uma atividade do usuário no site, feitas com base no [Usuário](../../lexicos/#l05-usuario). | Usabilidade | Sugestões |

Fonte: [Caio Duarte](https://github.com/caioduart3)
</center>

### Propagação dos Impactos - Usabilidade

A seguir, na Tabela 7, temos a avaliação da propagação dos impactos relativa à Figura 5.

<center>

<b>Tabela 7</b> - Impactos Usabilidade

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Usabilidade|  𝒲-| [Gabriel Campello](https://github.com/G16C)|
|Antecipação |  𝒲+|  [Gabriel Campello](https://github.com/G16C)|
|Sugestões| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Adaptação| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Sugestões Gerais| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Atividade do Usuário| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Acessibilidade| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Busca| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Filtro| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Opções de Filtro| X|[Gabriel Campello](https://github.com/G16C)|
|Busca Multivalorada| X|[Gabriel Campello](https://github.com/G16C)|
|Informações Relevantes| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Exibir Inf. do Evento| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Página Única| X|[Gabriel Campello](https://github.com/G16C)|

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

## NFR 02 - Eficiência

Os Requisitos utilizados para a confecção da Figura 6 estão presentes na Tabela 12:

- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.


<font size="3"><p style="text-align: center"><b>Figura 6</b> - SIG Eficiência</p></font>
<figure markdown class="usecaseElement">

![SIG Eficiência](../../assets/nfr-framework/eficiencia.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Caio Duarte](https://github.com/caioduart3)</p></font>

Legenda:

- Processar em até 200ms: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.
- Apresentar 5 categorias de informações: informações suficientemente relevantes para a realização de um processo.

### Requisitos Não-Funcionais - Eficiência

Na Tabela 8, estão listados os RNF presentes no NFR Famework de Eficiência:

<center>

<b>Tabela 8</b> - Requisitos Não-Funcionais 2

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Processar em até 200ms (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição de 200ms. | Eficiência | Tempo de Resposta e Processar Requisitos |
| Limite de 5 Páginas (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma limitação da quantidade de páginas para a realização de uma tarefa. | Eficiência | Limite de Páginas |
| Apresentar 5 categorias de informações (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve exibir as informações do evento específico. | Eficiência | Apresentar Informações e Limite de 5 páginas |

Fonte: [Caio Duarte](https://github.com/caioduart3)

</center>

### Propagação dos Impactos - Eficiência

Na Tabela 9, está presente a avaliação da propagação dos impactos referentes à Figura 6.

<center>

<b>Tabela 9</b> - Impactos Eficiência

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Eficiência|  𝒲+| [Gabriel Campello](https://github.com/G16C)|
|Executar Apropriadamente |  𝒲+|  [Gabriel Campello](https://github.com/G16C)|
|Processar Requisitos| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Processar Corretamente| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Recuperar de Erros| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Prevenção de Erros|  𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Limitações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Limite de Páginas| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Apresentar Informações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Apresentar 5 categorias de informações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Limite de 5 Páginas| X|[Gabriel Campello](https://github.com/G16C)|
|Tempo de Resposta| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Processar em até 200ms| ✓ |[Gabriel Campello](https://github.com/G16C)|


Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

## NFR 03 - Desempenho

Os Requisitos utilizados para a confecção da Figura 7 estão presentes na Tabela 12:

- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.

<font size="3"><p style="text-align: center"><b>Figura 7</b> - SIG Desempenho</p></font>
<figure markdown class="usecaseElement">

![SIG Desempenho](../../assets/nfr-framework/desempenhoL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Caio Duarte](https://github.com/caioduart3) e [Sidney Fernando](https://github.com/nando3d3)</p></font>

Legenda:

- Ordem Lógica: uma compra deve aplicar a ordem lógica observada na vida real.
- Limite de 5 páginas: refere-se ao <a id="anchor_NF03" href="#NF03">RNF03</a>, o qual limita a quantidade de páginas em até 5 para a compra.
- Velocidade: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.

### Requisitos Não-Funcionais - Desempenho

Na Tabela 10, estão listados os RNF presentes no NFR Famework de Desempenho :

<center>

<b>Tabela 10</b> - Requisitos Não-Funcionais 3

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Tempo de Resposta (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) |  O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. | Desempenho | Desempenho |
| Infraestrutura (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma infraestrutura para processar os dados. | Desempenho | Tempo de Resposta |
| Servidores (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir servidores para perdurar os dados. | Desempenho | Infraestrutura |
| Manutenção em tempo real (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura. | Desempenho | Servidores e Infraestrutura |

Fonte: [Caio Duarte](https://github.com/caioduart3)

</center>

### Propagação dos Impactos - Desempenho

Na Tabela 11, está presente a avaliação da propagação dos impactos referentes à Figura 6.

<center>

<b>Tabela 11</b> - Impactos Desempenho

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Desempenho |  🗲| [Caio Duarte](https://github.com/caioduart3)|
|Realizar Ações| 🗲|[Caio Duarte](https://github.com/caioduart3)|
|Compra| 🗲|[Caio Duarte](https://github.com/caioduart3)|
|Ordem Lógica| ✓|[Caio Duarte](https://github.com/caioduart3)|
|Processar em até 200ms|  X|[Caio Duarte](https://github.com/caioduart3)|
|Limite de 5 páginas| 𝒲-|[Caio Duarte](https://github.com/caioduart3)|
|Velocidade| 𝒲-|[Caio Duarte](https://github.com/caioduart3)|
|Processar Corretamente| ✓|[Caio Duarte](https://github.com/caioduart3)|
|Tempo de Resposta| 𝒲+|[Caio Duarte](https://github.com/caioduart3)|
|Infraestrutura| 𝒲+|[Caio Duarte](https://github.com/caioduart3)|
|Servidores| 𝒲+ |[Caio Duarte](https://github.com/caioduart3)|
|Manutenção em tempo real| ✓ |[Caio Duarte](https://github.com/caioduart3)|


Fonte: [Caio Duarte](https://github.com/caioduart3)

</center>

## Requisitos Não-Funcionais

A Tabela 12 a seguir lista os Requisitos Não-Funcionais utilizados para a criação do NFR Framework.

<p style="text-align: center"><b>Tabela 12</b> - Requisitos Não-Funcionais Não Implementados</p>

| ID    | Descrição                                                                     | Rastreabilidade                                                                                                                                                                                                                                                                                                                                                                                                                               | Implementação |
| ----- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| <a id="NF01" href="#anchor_NF01">RNF01</a> | O app deve fornecer eventos direcionados.                                     | [IS10](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q11](../../../elicitacao/tecnicas/questionario/#anchor_QNF), [BS35](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS36](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS22](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF)                                                                                                                                                                                                       | Não           |
| <a id="NF02" href="#anchor_NF02">RNF02</a> | O app deve disponibilizar todas as informações do evento em uma página.       | [IS11](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [BS25](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS26](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS27](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS28](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS29](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS30](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS15](<(../../../elicitacao/tecnicas/observacao/#anchor_OBSNF)>), [OBS16](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF) | Não           |
| <a id="NF03" href="#anchor_NF03">RNF03</a> | A compra deve ser feita em no máximo 5 páginas.                               | [IS13](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [IS16](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q14](../../../elicitacao/tecnicas/questionario/#anchor_QNF), [OBS17](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [OBS18](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [IS14](../../../elicitacao/tecnicas/introspeccao/#anchor_IS)                                                                                                                                                              | Não           |
| <a id="NF04" href="#anchor_NF04">RNF04</a> | O app não deve ter tempo de resposta superior a 200 ms.                       | [Q12](../../../elicitacao/tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |
| <a id="NF05" href="#anchor_NF05">RNF05</a> | O app deve permitir a filtragem dos eventos cadastrados no banco de dados.    | [Q13](../../../elicitacao/tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/mathonaut">Matheus Henrique</a> e <a href="https://github.com/caioduart3">Caio Duarte</a></p></font>

A Tabela 13 lista os Requisitos Não-Funcionais elicitados pelo NFR Framework.

<center>
<b>Tabela 13</b> - Requisitos Elicitados NFR

|  ID  | Descrição |
|------|---------|
|NFR01| O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. |
|NFR02| O sistema deve possuir uma infraestrutura para processar os dados.|
|NFR03| O sistema deve possuir servidores para perdurar os dados.|
|NFR04| O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura.|
|NFR05| O sistema deve possuir uma limitação do espaço ocupado.|
|NFR06| O sistema deve exibir as informações do evento específico.|
|NFR07| O sistema deve disponibilizar as informações.|
|NFR08| O sistema deve ser adaptativo às atividades do usuário.|

Fonte: [Caio Duarte](https://github.com/caioduart3)
</center>

## Fontes Externas

Por fim, a Tabela 14 explicita as Fontes Externas como revisão na literatura.

<center>
<b>Tabela 14</b> - Fontes Externas

| ID  | Autores | Título |
|-----|---------|--------|
| <a id="FE1" href="#anchor_FE1">FE1</a> |  SILVA  | NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados |
| <a id="FE2" href="#anchor_FE2">FE2</a> |  PAIM, et al | Enhancing Data Warehouse Design with the NFR Framework |
| <a id="FE3" href="#anchor_FE3">FE3</a> |  CHUNG, et al | Non-functional requirementsin software engineering |

Fonte: [Caio Duarte](https://github.com/caioduart3)
</center>  -->

## 4. Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2023.

> <a id="REF2" href="#anchor_2">2.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## 5. Histórico de Versões 

<font size="3"><p style="text-align: center">Tabela X: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento com introdução e bibliografia| [Caio Duarte](https://github.com/caioduart3)| 28/05/2025 | [Mayara Marques](https://github.com/maymarquee) |


<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 