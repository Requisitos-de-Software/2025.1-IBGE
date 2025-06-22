## 1. Introdução 

<div style="text-align: justify; text-indent: 2cm;">
Nem todo requisito de um sistema pode ser descrito apenas por meio dos <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/useCases">casos de uso</a>. Muitos aspectos essenciais, como desempenho, confiabilidade, segurança ou até restrições legais, ficam de fora desse formato. Por isso é necessária a Especificação Suplementar, um documento dedicado a reunir tudo aquilo que o sistema precisa atender além das interações funcionais com o usuário.
</div>

<div style="text-align: justify; text-indent: 2cm;">
Essa especificação serve como uma camada complementar, responsável por organizar e detalhar requisitos que envolvem desde restrições técnicas até atributos de qualidade, padrões regulatórios e exigências específicas de ambiente e compatibilidade. Em vez de focar no "o que o sistema faz", ela ilumina o "como ele deve ser".
</div>

<div style="text-align: justify; text-indent: 2cm;">
Para estruturar esse conjunto de informações de forma clara e abrangente, é comum adotar o modelo FURPS+, que categoriza os requisitos em grupos como <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#met)">Funcionalidade</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#met)">Usabilidade</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#met)">Confiabilidade</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#met)">Desempenho</a>, <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#met)">Suportabilidade</a> e outros aspectos adicionais. Assim, a Especificação Suplementar se consolida como peça-chave para garantir que o sistema final seja robusto, aderente às expectativas e pronto para operar em seu contexto real.
</div>

## 2. Finalidade

<div style="text-align: justify; text-indent: 2cm;">
A especificação suplementar tem como objetivo documentar todos os requisitos do sistema que não são capturados nos casos de uso, especialmente os requisitos não-funcionais, regras de negócio, restrições técnicas ou legais e condições de qualidade. Ela existe para garantir que o sistema não atenda apenas às funcionalidades esperadas,
mas também seja eficiente, seguro, compatível, legalmente adequado e utilizável, assegurando que todos os aspectos essenciais à qualidade e ao funcionamento do sistema sejam considerados no seu desenvolvimento.
</div>

## 3. Metodologia <a id="met"></a>

<div style="text-align: justify; text-indent: 2cm;">
A descrição dos requisitos foi elaborada com base no modelo FURPS+, uma abordagem utilizada para classificar os requisitos de um sistema. O acrônimo FURPS+ representa cinco categorias principais de requisitos, além de outras considerações adicionais indicadas pelo sinal de “+”. São elas:
</div>

<div style="text-align: justify; padding-left: 4em; margin-top: 1em;">
<ul>
<li>F - Functionality <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#4-especificacao-suplementar">(Funcionalidade)</a>: engloba os aspectos funcionais do software, isto é, os comportamentos e serviços que ele deve fornecer. Nesta categoria, estão incluídos os requisitos já detalhados por meio dos casos de uso.
<li>U - Usability <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem//#42-usabilidade">(Usabilidade)</a>: refere-se à qualidade da interação do usuário com o sistema. Leva em conta princípios de usabilidade como os propostos por Nielsen (PREECE; ROGERS; SHARP, 2005, p. 48-49), questionando, por exemplo, "quão fácil é para o usuário realizar suas tarefas com o software?"
<li>R - Reliability <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#43-confiabilidade">(Confiabilidade)</a>: diz respeito à robustez e integridade do sistema, incluindo requisitos como frequência e severidade de falhas, tempo médio entre falhas, capacidade de recuperação, e interoperabilidade.
<li> P - Performance <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#44-desempenho">(Desempenho)</a>: abrange os requisitos relacionados ao desempenho do sistema, como tempo de resposta, uso de recursos (memória, CPU), disponibilidade e escalabilidade.
<li> S - Supportability <a href="https://requisitos-de-software.github.io/2025.1-IBGE/modelagem/especificacaoSuplementar/#45-suportabilidade">(Suportabilidade)</a>: agrupa características que facilitam o suporte e a manutenção do sistema, incluindo testabilidade, adaptabilidade, compatibilidade, escalabilidade, manutenibilidade, localizabilidade, entre outras.
<li>“+” - Outros requisitos não funcionais: esta categoria contempla restrições adicionais que não se enquadram nas anteriores, como:
    <ul>
    <li>Requisitos de design: imposições sobre ferramentas, padrões ou estilos de desenvolvimento.
    <li>Requisitos de implementação: especificações relacionadas ao código, como uso obrigatório de determinadas linguagens ou frameworks.
    <li>Requisitos de interface: restrições específicas sobre como o sistema deve interagir com o usuário.
    <li>Requisitos físicos: limitações de hardware, como dimensões, materiais ou peso.
    </ul>
</ul>
</div>

!!! info
    Os requisitos não funcionais presentes buscam ser mensuráveis, a fim de satisfazer o critério de aceitação/verificabilidade.


## 4. Especificação Suplementar

<div style="text-align: justify; text-indent: 2cm;">
As especificações do documento podem ser observadas nas tabelas de 1 a 13.
</div>

### 4.1 Funcionalidades 

<div style="text-align: justify; text-indent: 2cm;">
Os requisitos funcionais estão localizados na seção de Elicitação dentro da página de <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">Requisitos Elicitados</a>, especificamente na <a href="https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#3-requisitos-elicitados">tabela 1</a>.
</div>



### 4.2 Usabilidade

<font size="3"><p style="text-align: center">Tabela 1: Requisitos não funcionais de Usabilidade</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                       |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [RNF01](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial) | O sistema deve manter um padrão de cores, fontes, botões e posicionamento dos elementos da interface em todas as telas, garantindo consistência visual. |
| [RNF02](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial) | Toda ação realizada pelo usuário deve gerar um feedback visual ou sonoro imediato, para garantir que o usuário compreenda o resultado da sua interação. |
| [RNF03](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve permitir a alteração do tamanho da fonte em toda a interface. |
| [RNF04](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve oferecer a opção de ativar o modo noturno, alterando o esquema de cores para tons escuros. |
| [RNF05](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | Um novo usuário deve ser capaz de realizar as tarefas principais em até 5 minutos de uso do aplicativo, sem necessidade de ajuda externa. |
| [RNF06](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | A interface do aplicativo deve se adaptar corretamente a diferentes tamanhos de tela e resoluções, garantindo boa visualização em smartphones, tablets e outros dispositivos. |
| [RNF07](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve informar o usuário, em tempo real, sobre o andamento de processos como carregamento de dados, envio de formulários ou sincronização, por meio de barras de progresso, ícones animados ou mensagens de status. |
| [RNF08](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O usuário deve poder desfazer ou refazer ações como desfavoritar indicadores, redefinir filtros ou cancelar comandos, evitando que erros exijam reinício completo da interação. |
| [RNF09](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve alertar o usuário antes de realizar ações críticas, e evitar campos que possam ser preenchidos incorretamente sem validação. |

<font size="2"><p style="text-align: center">Fonte: [Ludmila Nunes](https://github.com/ludmilaaysha), 2025.</p></font>

### 4.3 Confiabilidade

<font size="3"><p style="text-align: center">Tabela 2: Requisitos não funcionais de Confiabilidade</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                                   |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [RNF10](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve apresentar tempo médio entre falhas (MTBF - Mean Time Between Failures) superior a 100 horas de uso contínuo.                                                                            |
| [RNF11](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O aplicativo deve ser capaz de recuperar automaticamente sessões interrompidas devido a quedas de conexão ou falhas inesperadas.                                           |
| [RNF12](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | Em caso de falha, o sistema deve registrar o erro localmente e sincronizar com o servidor assim que houver conexão, para fins de diagnóstico e correção.                   |
| [RNF13](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O aplicativo deve manter a integridade dos dados mesmo em casos de encerramento abrupto ou desligamento inesperado do dispositivo.                                         |
| [RNF14](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve oferecer mensagens de erro compreensíveis e orientações claras para o usuário em caso de falhas, sem exibir códigos técnicos confusos.                      |
| [RNF15](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | A comunicação entre o aplicativo e os servidores do IBGE deve utilizar protocolos seguros (ex: HTTPS), garantindo a confiabilidade na transferência de dados.              |
| [RNF16](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O aplicativo deve passar por testes de estresse e de carga para garantir seu funcionamento estável mesmo com picos de acesso simultâneo.                                   |
| [RNF17](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve garantir interoperabilidade com diferentes versões dos principais sistemas operacionais móveis (Android e iOS), mantendo a estabilidade entre atualizações. |

<font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>


### 4.4 Desempenho

<font size="3"><p style="text-align: center">Tabela 3: Requisitos não funcionais de Desempenho</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                                               |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [RNF18](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve apresentar tempo de resposta inferior a 2 segundos para carregamento de telas principais, como visualização de notícias, dados e gráficos.                              |
| [RNF19](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O aplicativo deve utilizar no máximo 40% da CPU do dispositivo durante operações de uso intenso, como filtros de dados ou geração de gráficos.                                         |
| [RNF20](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O consumo de memória RAM pelo aplicativo não deve ultrapassar 250 MB em uso comum, garantindo desempenho mesmo em smartphones intermediários.                                          |
| [RNF21](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O aplicativo deve estar disponível para acesso 99,5% do tempo ao longo do mês, considerando atualizações, falhas e manutenções.                                                        |
| [RNF22](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve suportar pelo menos 5.000 acessos simultâneos sem degradação perceptível de desempenho.                                                                                 |
| [RNF23](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O tempo de sincronização de dados com o servidor não deve ultrapassar 5 segundos em redes 4G ou superiores.                                                                            |
| [RNF24](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | A navegação entre seções do app (como estatísticas, indicadores e notícias) deve ocorrer com transições de no máximo 1 segundo para garantir fluidez na experiência do usuário.        |
| [RNF25](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve realizar compressão de dados para reduzir o tempo de carregamento de conteúdo, principalmente em conexões móveis com baixa velocidade.                                  |
| [RNF26](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O desempenho do aplicativo deve ser validado em pelo menos três modelos diferentes de smartphones (baixo, médio e alto desempenho), garantindo funcionalidade mínima em cada um deles. |

 <font size="2"><p style="text-align: center">Fonte: [Laryssa Felix](https://github.com/felixlaryssa), 2025.</p></font>

### 4.5 Suportabilidade

<font size="3"><p style="text-align: center">Tabela 4: Requisitos não funcionais de Suportabilidade</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                       |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [RNF27](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve estar em conformidade com a LGPD (Lei nº 13.709/2018), assegurando o tratamento seguro, legal e transparente dos dados pessoais coletados.      |
| [RNF28](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve criptografar todos os dados pessoais transmitidos utilizando TLS 1.2 ou superior.                                                               |
| [RNF29](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve criptografar todos os dados pessoais armazenados utilizando algoritmos robustos como AES-256.                                                   |
| [RNF30](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve exibir uma política de privacidade clara ao usuário antes do início do preenchimento do Censo.                                                  |
| [RNF31](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve registrar o consentimento explícito do usuário para o uso de seus dados pessoais.                                                               |
| [RNF32](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O sistema deve permitir que o usuário solicite a exclusão ou correção de seus dados pessoais conforme previsto na LGPD.                                        |
| [RNF33](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | O sistema deve registrar logs detalhados dos eventos de autenticação e envio de dados, incluindo data/hora, IP, status da operação e identificador do usuário. |
| [RNF34](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)  | Os logs do sistema devem ser armazenados de forma segura e imutável por no mínimo 5 anos para fins de auditoria.                                               |
| [RNF35](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial)   | O acesso aos logs deve ser restrito a usuários autorizados com controle de acesso baseado em perfis.                                                           |
| [RNF36](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial) | O sistema deve permitir a geração de relatórios de auditoria sob demanda.                                                                                      |
| [RNF37](https://requisitos-de-software.github.io/2025.1-IBGE/elicitacao/Requisitos/#1-versao-oficial) 	 | O sistema deve realizar backups automáticos dos dados críticos diariamente, com retenção mínima de 30 dias e possibilidade de restauração em até 24 horas.

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), 2025.</p></font>

### 4.6 Restrições de Design

<font size="3"><p style="text-align: center">Tabela 5: Requisitos não funcionais de Restrições de Design</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                                   |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RNF38  | O design visual do aplicativo deve preservar a identidade visual do IBGE, incluindo uso das cores institucionais e logotipo oficial.                               |
| RNF39  | O sistema deve seguir o princípio da responsividade, adaptando-se automaticamente a diferentes tamanhos e orientações de tela.                                             |
| RNF40  | Todas as decisões de design devem priorizar a **simplicidade e clareza na interação com dados estatísticos**, evitando sobrecarga cognitiva no usuário.                    |
| RNF41  | A experiência do usuário deve ser priorizada, com foco em **fluxos intuitivos e navegação direta**, minimizando a quantidade de cliques até a informação desejada.         |
| RNF42  | O design da informação deve facilitar a interpretação de gráficos, mapas e tabelas, com **uso de legendas claras, cores contrastantes e ícones intuitivos**.               |
| RNF43  | O sistema deve prever escalabilidade de design para inclusão futura de novos tipos de dados, filtros e relatórios sem comprometer a estrutura atual.    
| RNF44  | O aplicativo deve estar apto a funcionar de forma offline para consulta de dados previamente sincronizados, com atualização automática quando a conexão for restabelecida. |    

<p style="text-align: center; font-size: 14px;">Fonte: <a href="https://github.com/felixlaryssa"> Laryssa Felix</a>, 2025.</p>

### 4.7 Requisitos de Implementação

<font size="3"><p style="text-align: center">Tabela 6: Requisitos não funcionais de Implementação</p></font>

| ID    | Descrição do Requisito Não Funcional                                                                                      |
|-------|----------------------------------------------------------------------------------------------------------------------------|
| RNF45 | O aplicativo deve ser desenvolvido utilizando tecnologias compatíveis com dispositivos Android e iOS.                     |
| RNF46 | O código-fonte deve seguir boas práticas de programação, com uso de versionamento (ex: Git) e documentação de métodos.    |
| RNF47 | O sistema deve ser compatível com bibliotecas gráficas modernas para renderização de gráficos estatísticos.               |
| RNF48 | O aplicativo deverá utilizar frameworks responsivos que permitam adaptação automática a diferentes tamanhos de tela.      |
| RNF49 | O tempo de inicialização do aplicativo não deve ultrapassar 3 segundos em dispositivos de entrada compatível.             |
| RNF50 | O aplicativo deve ser projetado com arquitetura modular, facilitando futuras manutenções e atualizações.                  |

<font size="2"><p style="text-align: center">Fonte: [Joao Felix](https://github.com/joaofmoreiraa), 2025.</p></font>

### 4.8 Requisitos de Sistema de Ajuda e de Documentação de Usuário Online

<font size="3"><p style="text-align: center">Tabela 7: Requisitos não funcionais de Ajuda e de Documentação Online</p></font>

| ID    | Descrição do Requisito Não Funcional                                                                                       |
|-------|-----------------------------------------------------------------------------------------------------------------------------|
| RNF51 | O aplicativo deve conter uma seção de ajuda acessível a partir do menu principal, com instruções claras de uso.            |
| RNF52 | A documentação do usuário deve estar disponível online e acessível por meio de link no próprio aplicativo.                 |
| RNF53 | A seção de ajuda deve conter tópicos de perguntas frequentes (FAQ) e tutoriais passo a passo ilustrados.                   |
| RNF54 | O conteúdo de ajuda deve ser escrito em linguagem simples, adequada ao público-alvo geral e não técnico.                   |
| RNF55 | A documentação online deve ser responsiva e acessível em diferentes dispositivos (mobile, tablet e desktop).               |
| RNF56 | O sistema deve permitir atualizações periódicas da documentação, sem necessidade de atualização do aplicativo principal.   |

<font size="2"><p style="text-align: center">Fonte: [Joao Felix](https://github.com/joaofmoreiraa), 2025.</p></font>


### 4.9 Requisitos de Licenciamento

<font size="3"><p style="text-align: center">Tabela 8: Requisitos não funcionais de licenciamento</p></font>

| ID    | Descrição do Requisito Não Funcional                                                                                   |
|-------|-------------------------------------------------------------------------------------------------------------------------|
| RNF57 | O aplicativo deve exibir os termos de uso e política de privacidade no primeiro acesso do usuário.                     |
| RNF58 | Todo o conteúdo de dados estatísticos deve respeitar as licenças de uso e atribuição do IBGE.                          |
| RNF59 | O software deve ser disponibilizado sob uma licença de código aberto compatível com uso governamental (ex: MIT, GPL).  |
| RNF60 | Componentes de terceiros utilizados no aplicativo devem estar devidamente licenciados e creditados.                    |
| RNF61 | O uso do aplicativo será gratuito e restrito apenas a fins informativos e educacionais, conforme normas institucionais.|

<font size="2"><p style="text-align: center">Fonte: [Joao Felix](https://github.com/joaofmoreiraa), 2025.</p></font>

### 4.10 Observações Legais, de Copyright e Outras

<div style="text-align: justify; text-indent: 2cm;">
Os direitos autorais do produto pertencem ao IBGE e são protegidos pela legislação de direitos autorais do Brasil e por tratados internacionais. 
</div>
<div style="text-align: justify; text-indent: 2cm;">
Qualquer empréstimo, locação, cópia ou comercialização parcial do produto é vedado. Caso queira comercializar os dados presentes no produto, é necessária autorização expressa por escrito do IBGE.
</div>
<div style="text-align: justify; text-indent: 2cm;">
É possível observar o documento de termo de compromisso na íntegra pelo <a href="https://seculoxx.ibge.gov.br/apresentacao-seculoxx/termo-de-compromisso/">link</a>.
</div>

<font size="3"><p style="text-align: center">Tabela 9: Requisitos de Observações Legais e de Copyright</p></font>

| ID      | Descrição do Requisito Não Funcional |
|---------|----------------------------------------|
| RNF62   | O sistema deve respeitar as leis brasileiras vigentes relacionadas à proteção de dados, propriedade intelectual, acessibilidade digital e direitos do consumidor. |
| RNF63   | Todos os conteúdos exibidos (textos, imagens, gráficos e dados estatísticos) devem conter as devidas citações e fontes. |
| RNF64   | O código-fonte e os componentes do sistema devem respeitar as licenças de software utilizadas, evitando o uso de bibliotecas sem permissão legal. |
| RNF65   | A distribuição do aplicativo deve incluir os termos de uso e a política de privacidade acessíveis diretamente na tela inicial e dentro do menu de configurações. |
| RNF66   | O sistema deve garantir a acessibilidade mínima conforme, conforme exigido pela legislação brasileira. |
| RNF67   | O uso do nome, logotipo e identidade visual do IBGE deve seguir as diretrizes institucionais. |
| RNF68   | O aplicativo deve ser registrado junto ao órgão responsável, quando aplicável, garantindo proteção contra uso indevido ou cópia não autorizada. |
| RNF69   | Qualquer coleta de dados estatísticos anônimos para fins de melhoria do sistema deve ser previamente autorizada pelo usuário, com opção clara de recusa. |

<p style="text-align: center; font-size: 14px;">Fonte: <a href="https://github.com/LeticiaMonteiroo">Letícia Monteiro</a>, 2025.</p>

### 4.11 Padrões Aplicáveis

<font size="3"><p style="text-align: center">Tabela 10: Padrões Aplicáveis</p></font>

| ID     | Padrão Aplicável | Descrição |
|--------|------------------|-----------|
| RNF70  | eMAG             | O Modelo de Acessibilidade de Governo Eletrônico define diretrizes para garantir que o sistema seja acessível a todas as pessoas, inclusive com deficiência. |
| RNF71  | WCAG 2.1 (AA)    | As Diretrizes de Acessibilidade para Conteúdo Web garantem que o sistema possa ser utilizado por usuários com diferentes necessidades, incluindo leitores de tela. |
| RNF72  | LGPD             | A Lei Geral de Proteção de Dados regula o tratamento de dados pessoais e deve ser integralmente seguida pelo sistema. |
| RNF73  | ISO/IEC 27001    | Padrão internacional para gestão da segurança da informação, recomendável para proteger dados sensíveis do sistema. |
| RNF74  | ABNT NBR 9241    | Norma brasileira que trata de ergonomia na interação humano-computador, aplicável à interface do sistema. |
| RNF75  | Material Design ou Bootstrap | Padrões de design visual para manter consistência na interface do usuário. |
| RNF76  | Licenças de Código Aberto (MIT, GPL, etc.) | O uso de bibliotecas e frameworks deve respeitar suas respectivas licenças de uso e distribuição. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel Pinto](https://github.com/GabrielSPinto) , 2025.</p></font>

### 4.12 Requisitos de Interface

<font size="3"><p style="text-align: center">Tabela 11: Requisitos de Interface</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                        |
| ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RNF77  | A interface do aplicativo deve seguir as diretrizes de design responsivo, garantindo usabilidade adequada em dispositivos móveis e tablets.                     |
| RNF78  | Os elementos de navegação (menus, botões, ícones) devem ser intuitivos, com rótulos descritivos e acessíveis em no máximo dois toques a partir da tela inicial. |
| RNF79  | Todas as telas devem possuir contraste mínimo de 4.5:1 entre texto e plano de fundo, conforme as diretrizes WCAG 2.1 de acessibilidade digital.                 |
| RNF80  | O sistema deve apresentar feedback visual e/ou sonoro para todas as ações do usuário, como cliques, carregamentos e envios de formulários.                      |
| RNF81  | Os textos exibidos na interface devem ser redigidos em linguagem clara e objetiva, adequada ao público geral, evitando jargões técnicos.                        |
| RNF82  | Os formulários devem apresentar mensagens de erro específicas e orientativas, posicionadas próximas aos campos com problemas.                                   |
| RNF83  | A interface deve ser compatível com leitores de tela, permitindo navegação e interpretação completa do conteúdo por pessoas com deficiência visual.             |
| RNF84  | Os gráficos e mapas exibidos devem possuir alternativas textuais ou descrições acessíveis para garantir entendimento a todos os usuários.                       |

<p style="text-align: center; font-size: 14px;">Fonte: <a href="https://github.com/felixlaryssa"> Laryssa Felix</a>, 2025.</p>

### 4.13 Requisitos Físicos

<font size="3"><p style="text-align: center">Tabela 12: Requisitos Físicos</p></font>

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                    |
| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RNF85  | O aplicativo deve ser compatível com dispositivos móveis que atendam aos requisitos mínimos de hardware, como memória RAM de 2GB e Android 8.0 ou superior. |

<p style="text-align: center; font-size: 14px;">Fonte: <a href="https://github.com/felixlaryssa"> Laryssa Felix</a>, 2025.</p>



## 5. Bibliografia

> BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações. Secretaria-Executiva. Diretoria de Tecnologia da Informação. Coordenação Geral de Sistemas. Especificação Suplementar: Sigla do Projeto – Nome do Projeto. Versão 1.0. Brasília: MCTIC. Disponível em: <https://aprender3.unb.br/pluginfile.php/3096129/mod_resource/content/2/SiglaProjeto_EspecificacaoSuplementar.pdf >. Acesso em: 14 maio 2025.

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025, p. 28,29 e 30. Disponível em: [<https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf>](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 14 maio 2025.

<center>

<img src="../../assets/images/modelagem/fonte_es.png" width="380"/>
<img src="../../assets/images/modelagem/fonte_es2.png" width="380"/>
</center>


## 6. Histórico de Versões 

<font size="3"><p style="text-align: center">Tabela 13: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento| [Laryssa Felix](https://github.com/felixlaryssa)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.2     |Tópico de introdução| [João Félix](https://github.com/joaofmoreiraa)| 14/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|1.3     |Tópicos de finalidade e metodologia| [Laryssa Felix](https://github.com/felixlaryssa)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.4     |Adição de RNF de suportabilidade| [Caio Duarte](https://github.com/caioduart3) | 17/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|1.5     |Adição de RNF de usabilidade| [Ludmila Nunes](https://github.com/ludmilaaysha) | 17/05/2025 | [Caio Duarte](https://github.com/caioduart3) |
|1.6     |Adição de Padrões Aplicáveis| [Gabriel Pinto](https://github.com/GabrielSPinto) | 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |
|1.7     |Adição de RNF de confiabiliadade, desempenho e restrições de Design | [Laryssa Felix](https://github.com/felixlaryssa)| 17/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|1.8     |Adição de RNF de Implementação, Sistema de Ajuda e de Documentação de Usuário Online, Licenciamento | [Joao Felix](https://github.com/joaofmoreiraa)| 17/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|1.9     |Adição de RNF de Observações Legais, de Copyright e Outras  | [Letícia Monteiro](https://github.com/LeticiaMonteiroo)| 18/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|2.0     |Adição de RNF de Requisitos de Interface e Requisitos Físicos  | [Laryssa Felix](https://github.com/felixlaryssa)| 18/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|2.1     |Adição da bibliografia | [Laryssa Felix](https://github.com/felixlaryssa)| 17/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|2.2     |Adição de bibliografia | [Mayara Marques](https://github.com/maymarquee)| 17/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|2.3     |Revisa artefato | [Mayara Marques](https://github.com/maymarquee)| 18/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|2.4     | Correção dos  IDs | [Laryssa Felix](https://github.com/felixlaryssa)| 18/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|2.5     | Adicionando Rastreabilidade e Corrigindo IDs | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) | 18/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa)| 18/05/2025 |


<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 