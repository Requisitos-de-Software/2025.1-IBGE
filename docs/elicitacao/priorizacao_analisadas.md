# Técnicas de Priorização de Requisitos Analisadas

<div style="text-align: justify; text-indent: 2cm;">
Priorizar requisitos significa definir o que é mais importante para ser desenvolvido primeiro, com base no valor que cada item traz ao projeto. A priorização é fundamental em projetos ágeis (WIEGERS; BEATTY, 2013). Diversos stakeholders precisam participar desta etapa: clientes, patrocinadores, gerência de projeto, desenvolvimento e outras perspectivas.
</div>
<div style="text-align: justify; text-indent: 2cm;">
Alan Davis (2005) indica que uma priorização bem-sucedida requer entendimento de seis questões:
</div>

<ol style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
    <li>As necessidades dos clientes
    <li>A importância relativa dos requisitos para os clientes
    <li>O momento em que as funcionalidades precisam ser entregues
    <li>Requisitos que são predecessores de outros requisitos e outros relacionamentos
    <li>Quais requisitos precisam ser implementados como um grupo
    <li>O custo para satisfazer cada requisito
</ol>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/introducaoPriorizacao.png)

<div style="text-align: justify; text-indent: 2cm;">
A seguir, serão apresentadas algumas das principais técnicas de priorização utilizadas por profissionais da área:
</div>


## 1.0 Timeboxing

<div style="text-align: justify; text-indent: 2cm;">
Prioriza requisitos em projetos com recursos fixos, como tempo ou orçamento. Existem três formas principais de decidir o que entra nesses limites(“caixas fixas de recursos"):
</div>

<ul style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
<li><b>Tudo dentro:</b> começa com todos os requisitos e vai removendo os menos importantes até caber no tempo ou orçamento.
<li><b>Tudo fora:</b> começa com a caixa vazia e vai adicionando os requisitos mais importantes até atingir o limite.
<li><b>Seletivo:</b> escolhe os de maior prioridade e ajusta-se o escopo com adições ou remoções até que ele se encaixe no prazo ou orçamento disponível.
</ul>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/timeboxing.png)

## 2.0 Votação
<div style="text-align: justify; text-indent: 2cm;">
De acordo com Vazquez e Simões, a priorização por votação distribui recursos (como votos ou dinheiro) entre os participantes, que os aplicam nos requisitos que consideram mais importantes. Essa técnica é comum em empresas que desenvolvem software como produto, usando o feedback dos clientes para decidir quais melhorias incluir nas próximas versões, já que nem todas podem ser implementadas devido a limitações de recursos. Conhecida por ser democrática, pode envolver todas as partes interessadas(stakeholders).
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/votacao.png)

## 3.0 First Thing First

<div style="text-align: justify; text-indent: 2cm;">
A técnica de priorização de requisitos "First Things First" tem como objetivo estabelecer uma ordem estratégica para a implementação das funcionalidades, considerando critérios que impactam diretamente sua disponibilização aos usuários finais da aplicação.
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/firstThingsFirst.jpg)

## 4.0 ROI - Return On Investment

<div style="text-align: justify; text-indent: 2cm;">
A técnica de priorização de requisitos baseada em ROI (Retorno sobre o Investimento) avalia cada funcionalidade considerando o valor que ela entrega ao negócio e o custo necessário para implementá-la. A fórmula usada é:
</div>

<div style="text-align: justify; text-indent: 2cm;">
<b>ROI = Benefício / Custo</b>
</div>

<div style="text-align: justify; text-indent: 2cm;">
Funcionalidades com maior ROI são priorizadas, pois oferecem mais retorno com menos esforço. A técnica é objetiva e útil para projetos com recursos limitados, mas exige boas estimativas e pode não capturar bem fatores qualitativos.
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/roi.png)


## 5.0 QFD - Quality Function Deployment

<div style="text-align: justify; text-indent: 2cm;">
Por meio de uma matriz chamada Casa da Qualidade, a QFD relaciona o que o cliente deseja ("Whats") com como a empresa pode atender essas demandas ("Hows"), atribuindo pesos às relações. Também avalia a concorrência e analisa interações entre requisitos técnicos. O principal objetivo é garantir que o projeto foque no que realmente importa para o cliente, promovendo qualidade e alinhamento com suas expectativas.
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/qfd.png)


## 6.0 TQM - Total Quality Management

<div style="text-align: justify; text-indent: 2cm;">
 É uma abordagem focada na melhoria contínua da qualidade em todos os processos da organização, com envolvimento de todos os colaboradores e foco na satisfação do cliente.
 </div>

<ol style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
<li>Os principais pilares da TQM são:

<li>Orientação ao cliente

<li>Medição e análise da qualidade

<li>Melhoria contínua

<li>Empoderamento dos funcionários

<li>Trabalho em equipe

<li>Liderança comprometida
</ol>

<div style="text-align: justify; text-indent: 2cm;">
Seu objetivo é garantir que produtos e serviços atendam ou superem as expectativas dos clientes, promovendo eficiência e excelência organizacional.
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/tqm.png)

## 7.0 MoScoW

<div style="text-align: justify; text-indent: 2cm;">
O método MoSCoW é uma técnica de priorização de requisitos que classifica itens em quatro categorias:
</div>

<ul style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
<li><b>Must</b> (Deve): Essencial para o sucesso do projeto.
<li><b>Should</b> (Deveria): Importante, mas não essencial.
<li><b>Could</b> (Poderia): Desejável, mas opcional, se houver tempo e recursos.
<li><b>Won’t</b> (Não será): Não será implementado agora, mas pode ser no futuro.
</ul>

<div style="text-align: justify; text-indent: 2cm;">
Embora amplamente usado, o texto critica o MoSCoW por ser ambíguo quanto ao tempo de entrega e por não oferecer critérios claros para definir prioridades. Além disso, em práticas reais, muitos times focam quase exclusivamente nos requisitos marcados como "Must", ignorando os demais, o que compromete a real utilidade da categorização.
(A fonte não recomenda o MoSCoW, sugerindo que outras abordagens, como uma escala baseada em importância e urgência, são mais eficazes)
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/moscow.png)


## 8.0 100$

<div style="text-align: justify; text-indent: 2cm;">
O método dos 100 dólares é uma técnica de priorização em que cada participante recebe 100 dólares fictícios para "gastar" nos requisitos que considera mais importantes. Quanto mais importante o requisito, mais dólares ele recebe. Ao final, somam-se os valores atribuídos para definir as prioridades coletivas.
</div>

<ul style="text-align: justify; padding-left: 4em; margin-top: 0.5em;">
    <li><b>Vantagens:</b> 
    <ul>
        <li>Torna a priorização mais tangível e fácil de visualizar.
        <li>Estimula o pensamento crítico sobre valor e prioridade.
    </ul>
    <li><b>Desvantagens:</b>
    <ul>
        <li>Pode ser manipulado (por exemplo, alguém aloca os 100 dólares em um único item).
        <li>Não considera o esforço ou custo real de implementação dos requisitos.
        <li>Pode ignorar o valor relativo entre múltiplos requisitos com esforço semelhante.
    </ul>

</ul>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/100.png)

## 9.0 In or out
<div style="text-align: justify; text-indent: 2cm;">
O método In or Out (Entra ou Sai) é uma abordagem simples de priorização em que os stakeholders decidem, para cada requisito, se ele será incluído ou não no próximo ciclo de desenvolvimento. A ideia é reduzir a lista ao mínimo necessário para a próxima entrega, e os itens deixados de fora são reconsiderados em ciclos futuros. A principal vantagem desse método é sua simplicidade e rapidez na tomada de decisão. Um exemplo interessante foi quando um stakeholder tornou o processo mais leve fazendo um som de explosão toda vez que um requisito era descartado, como se estivesse “explodindo” o item.
</div>

[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/inOut.png)


## 10.0 Três níveis

<div style="text-align: justify; text-indent: 2cm;">
A escala de três níveis é uma técnica comum que classifica os requisitos em categorias como alta, média e baixa prioridade, combinando critérios de importância e urgência. Os requisitos são organizados em uma matriz com quatro quadrantes: os altamente prioritários são os que são importantes e urgentes; os prioritários médios são importantes, mas não urgentes; os "não faça isso" são urgentes, mas não importantes; e os de baixa prioridade não são nem importantes nem urgentes.
</div>
<div style="text-align: justify; text-indent: 2cm;">
Essa abordagem ajuda stakeholders a tomar decisões mais conscientes, mas exige alinhamento sobre o que cada nível realmente significa. É útil incluir a prioridade como atributo nos documentos dos requisitos para facilitar a comunicação.
</div>
[**Imagem da Fonte**](../assets/images/priorizacao_analisadas/tresNiveis.png)


##  Bibliografia

> WIEGERS, Karl; BEATTY, Joy. Software Requirements, Third Edition. Washington: Microsoft Press, 2013. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096091/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf>. Acesso em: 2 maio 2025.

>  Carlos Eduardo Vazquez, Guilherme Siqueira Simões  *Engenharia de Requisitos Software Orientado ao Negócio*. Copyright© 2016 por Brasport Livros e Multimídia Ltda. Disponível em: <https://analisederequisitos.com.br/wp-content/uploads/2023/06/engenharia-de-requisitos-software-orientado-ao-negocio.pdf>. Acesso em: 2 maio 2025.

>  SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 07. [Apresentação de aula]. Universidade de Brasília – FGA. Gama: UnB/FGA. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 2 maio 2025.




## Histórico de Versões 
<font size="3"><p style="text-align: center">Tabela 1: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação da documento|[Laryssa Felix](https://github.com/felixlaryssa)| 02/05/2025 | [Caio Duarte](https://github.com/caioduart3)  |
|2.0     |Edição do documento|[Laryssa Felix](https://github.com/felixlaryssa)| 03/05/2025 | [Caio Duarte](https://github.com/caioduart3)  |
|2.1     |Mudanças na bibliografia e formatação do texto|[Mayara Marques](https://github.com/maymarquee)| 06/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa)  |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font>