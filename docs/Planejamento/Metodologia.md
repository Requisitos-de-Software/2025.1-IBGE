# Metodologia

Segundo o *Guide to the Software Engineering Body of Knowledge* (SWEBOK), **metodologia** é definida como um conjunto estruturado de práticas, técnicas e princípios utilizados para conduzir atividades de engenharia de software de forma sistemática e organizada. Conforme apresentado no SWEBOK, as metodologias podem ser classificadas em:

- **Métodos heurísticos**: baseados em práticas consolidadas da indústria;
- **Métodos formais**: fundamentados em notações matemáticas rigorosas;
- **Métodos de prototipação**: que permitem o desenvolvimento de versões preliminares de um sistema;
- **Métodos ágeis**: que priorizam entregas contínuas, colaboração com stakeholders e adaptação a mudanças.

## Aplicação no Projeto do IBGE

Neste projeto, que visa a prototipação dos requisitos do aplicativo do IBGE, adotaremos **Metodologias Ágeis** e **Métodos de Prototipação** como abordagens principais.

### Metodologias Ágeis

As metodologias ágeis serão adotadas para organizar o desenvolvimento do sistema em ciclos iterativos, com foco em entregas frequentes e adaptabilidade às mudanças nos requisitos. Em particular, utilizaremos o modelo de sprints do **framework Scrum**, com ciclos semanais de desenvolvimento.

Para o gerenciamento das sprints, será utilizada a plataforma GitHub, onde as **issues** representarão as tarefas do projeto. O acompanhamento e a organização das atividades ocorrerão por meio do recurso de **projetos Kanban** do GitHub, estruturado com colunas que indicam o status das tarefas: *To Do*, *Doing* e *Done*.

As sprints serão organizadas com reuniões de **Planning** ao início de cada sprint, seguindo a estrutura clássica de **Retrospectiva**, **Revisão** e **Planejamento**. Esses encontros têm como objetivo avaliar o progresso da sprint anterior, revisar as entregas realizadas e planejar as próximas tarefas com base nas prioridades do projeto.

A equipe analisou a disponibilidade de seus integrantes por meio de um mapa de calor, com o objetivo de organizar melhor as atividades do grupo e identificar os horários mais adequados para a realização das reuniões.

<div align="center">
  <p>Imagem 1 – Heatmap de Disponilidade</p>
  <img src="../assets/images/Heatmap_Disponilidade.png" alt="Imagem 1 – Mapa de calor" width="600px">
  <p>Fonte: Google Planilhas</p>
</div>

Com base nessa análise, foi definido que os melhores horários para as reuniões seriam na quarta-feira, das 21h às 22h. Sempre que possível, as reuniões são realizadas por meio da plataforma Microsoft Teams, onde também são gravadas e documentadas para fins de registro e consulta futura.

### Métodos de Prototipação

O **Modelo de Prototipação**, também conhecido como **Modelo Evolucionário**, é caracterizado por uma abordagem cíclica que permite o acompanhamento da evolução dos requisitos do projeto. A principal vantagem desse modelo é a significativa participação do cliente, o que possibilita uma aproximação gradual ao produto final a cada ciclo. Além disso, destaca-se pela rapidez em apresentar resultados ao cliente, mesmo que inacabados.

O método de prototipação será empregado para criar versões exploratórias do sistema, facilitando a comunicação com os usuários e a validação precoce das funcionalidades.

<div align="center">
  <p>Imagem 2 – Ciclo da Metodologia de Prototipação</p>
  <img src="../assets/images/Ciclo_Prototipacao.png" alt="Imagem 2 – Ciclo da Metodologia de Prototipação" width="400px">
  <p>Fonte: Curso Projetos de Sistemas da Fundação Bradesco</p>
</div>

As etapas do Modelo de Prototipação são:

1. **Levantamento de Requisitos:** Ocorre o entendimento das expectativas e das necessidades do cliente, bem como o levantamento dos requisitos.
2. **Modelagem Rápida:** Criação de uma versão inicial do sistema que representa as funcionalidades desejadas. Não há preocupação com detalhes que possam tomar tempo, já que o objetivo não é construir algo que será mostrado ao cliente.
3. **Construção do Protótipo:** É construído um protótipo para ser mostrado ao cliente. O protótipo pode ou não ser funcional.
4. **Entrega e Avaliação:** Nessa etapa, o protótipo é apresentado ao cliente, que fará uma avaliação. A partir da avaliação, surgem ajustes nos requisitos e novas solicitações.

Este ciclo é repetido até que o sistema atenda satisfatoriamente aos requisitos dos usuários.

Essa abordagem mista é recomendada pelo SWEBOK para projetos em que a interação com usuários e o refinamento incremental dos requisitos são fatores-chave para o sucesso.


## Política de Revisão

Para que nenhum arquivo fique com alguma informação faltando ou errada, foi definido que, a cada nova modificação feita nos arquivos, será escolhido pelo autor um outro membro da equipe para executar a revisão e apontar os pontos que precisarão ser modificados, caso necessário. Torna-se, assim, **obrigatória** a requisição de um revisor desde a Sprint 1, onde foi acordado tal exigência.

## Referências

IEEE COMPUTER SOCIETY. *Guide to the Software Engineering Body of Knowledge (SWEBOK)*: Version 4.0. Los Alamitos, CA: IEEE, 2024. Disponível em: <https://www.computer.org/education/bodies-of-knowledge/software-engineering>. Acesso em: abr. 2025.

FUNDAÇÃO BRADESCO. Curso Projetos de Sistemas de TI. Tópico: Modelo de Prototipação. Disponível em: <https://lms.ev.org.br/mpls/Custom/Cds/COURSES/2510-PROJ_SIST_TI/pag/1_2_8.html>. Acesso em: abr. 2025.

---

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento|[Gabriel Pinto](https://github.com/GabrielSPinto)| 13/04/2025 | [Mayara Marques](https://github.com/maymarquee)|