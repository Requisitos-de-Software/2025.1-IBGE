## 1. Introdução 

Nem todo requisito de um sistema pode ser descrito apenas por meio dos casos de uso. Muitos aspectos essenciais, como desempenho, confiabilidade, segurança ou até restrições legais, ficam de fora desse formato. Por isso é necessária a Especificação Suplementar, um documento dedicado a reunir tudo aquilo que o sistema precisa atender além das interações funcionais com o usuário.

Essa especificação serve como uma camada complementar, responsável por organizar e detalhar requisitos que envolvem desde restrições técnicas até atributos de qualidade, padrões regulatórios e exigências específicas de ambiente e compatibilidade. Em vez de focar no "o que o sistema faz", ela ilumina o "como ele deve ser".

Para estruturar esse conjunto de informações de forma clara e abrangente, é comum adotar o modelo FURPS+, que categoriza os requisitos em grupos como Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade e outros aspectos adicionais. Assim, a Especificação Suplementar se consolida como peça-chave para garantir que o sistema final seja robusto, aderente às expectativas e pronto para operar em seu contexto real.

## 2. Finalidade

A especificação suplementar tem como objetivo documentar todos os requisitos do sistema que não são capturados nos casos de uso, especialmente os requisitos não-funcionais, regras de negócio, restrições técnicas ou legais e condições de qualidade. Ela existe para garantir que o sistema não atenda apenas às funcionalidades esperadas,
mas também seja eficiente, seguro, compatível, legalmente adequado e utilizável, assegurando que todos os aspectos essenciais à qualidade e ao funcionamento do sistema sejam considerados no seu desenvolvimento.

## 3. Metodologia

A descrição dos requisitos foi elaborada com base no modelo FURPS+, uma abordagem utilizada para classificar os requisitos de um sistema (QUALIDADEBR, 2008). O acrônimo FURPS+ representa cinco categorias principais de requisitos, além de outras considerações adicionais indicadas pelo sinal de “+”. São elas:

- F - Functionality (Funcionalidade): engloba os aspectos funcionais do software, isto é, os comportamentos e serviços que ele deve fornecer. Nesta categoria, estão incluídos os requisitos já detalhados por meio dos casos de uso.

- U - Usability (Usabilidade): refere-se à qualidade da interação do usuário com o sistema. Leva em conta princípios de usabilidade como os propostos por Nielsen (PREECE; ROGERS; SHARP, 2005, p. 48-49), questionando, por exemplo, "quão fácil é para o usuário realizar suas tarefas com o software?"

- R - Reliability (Confiabilidade): diz respeito à robustez e integridade do sistema, incluindo requisitos como frequência e severidade de falhas, tempo médio entre falhas, capacidade de recuperação, e interoperabilidade.

- P - Performance (Desempenho): abrange os requisitos relacionados ao desempenho do sistema, como tempo de resposta, uso de recursos (memória, CPU), disponibilidade e escalabilidade.

- S - Supportability (Suportabilidade): agrupa características que facilitam o suporte e a manutenção do sistema, incluindo testabilidade, adaptabilidade, compatibilidade, escalabilidade, manutenibilidade, localizabilidade, entre outras.

- “+” - Outros requisitos não funcionais: esta categoria contempla restrições adicionais que não se enquadram nas anteriores, como:

    - Requisitos de design: imposições sobre ferramentas, padrões ou estilos de desenvolvimento.

    - Requisitos de implementação: especificações relacionadas ao código, como uso obrigatório de determinadas linguagens ou frameworks.

    - Requisitos de interface: restrições específicas sobre como o sistema deve interagir com o usuário.

    - Requisitos físicos: limitações de hardware, como dimensões, materiais ou peso.


## 4. Especificação Suplementar

### 5.1 Funcionalidades 



### 5.2 Usabilidade

| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                       |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RNF11  | O sistema deve manter um padrão de cores, fontes, botões e posicionamento dos elementos da interface em todas as telas, garantindo consistência visual. |
| RNF13  | Toda ação realizada pelo usuário deve gerar um feedback visual ou sonoro imediato, para garantir que o usuário compreenda o resultado da sua interação. |
| RNF14  | O sistema deve permitir a alteração do tamanho da fonte em toda a interface. |
| RNF15  | O sistema deve oferecer a opção de ativar o modo noturno, alterando o esquema de cores para tons escuros. |
| RNF16  | Um novo usuário deve ser capaz de realizar as tarefas principais em até 5 minutos de uso do aplicativo, sem necessidade de ajuda externa. |
| RNF17  | A interface do aplicativo deve se adaptar corretamente a diferentes tamanhos de tela e resoluções, garantindo boa visualização em smartphones, tablets e outros dispositivos. |
| RNF18  | O sistema deve informar o usuário, em tempo real, sobre o andamento de processos como carregamento de dados, envio de formulários ou sincronização, por meio de barras de progresso, ícones animados ou mensagens de status. |
| RNF19  | O usuário deve poder desfazer ou refazer ações como desfavoritar indicadores, redefinir filtros ou cancelar comandos, evitando que erros exijam reinício completo da interação. |
| RNF20  | O sistema deve alertar o usuário antes de realizar ações críticas, e evitar campos que possam ser preenchidos incorretamente sem validação. |

### 5.3 Confiabilidade

### 5.4 Desempenho

### 5.5 Suportabilidade
| **ID** | **Descrição do Requisito Não Funcional**                                                                                                                       |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RNF01  | O sistema deve estar em conformidade com a LGPD (Lei nº 13.709/2018), assegurando o tratamento seguro, legal e transparente dos dados pessoais coletados.      |
| RNF02  | O sistema deve criptografar todos os dados pessoais transmitidos utilizando TLS 1.2 ou superior.                                                               |
| RNF03  | O sistema deve criptografar todos os dados pessoais armazenados utilizando algoritmos robustos como AES-256.                                                   |
| RNF04  | O sistema deve exibir uma política de privacidade clara ao usuário antes do início do preenchimento do Censo.                                                  |
| RNF05  | O sistema deve registrar o consentimento explícito do usuário para o uso de seus dados pessoais.                                                               |
| RNF06  | O sistema deve permitir que o usuário solicite a exclusão ou correção de seus dados pessoais conforme previsto na LGPD.                                        |
| RNF07  | O sistema deve registrar logs detalhados dos eventos de autenticação e envio de dados, incluindo data/hora, IP, status da operação e identificador do usuário. |
| RNF08  | Os logs do sistema devem ser armazenados de forma segura e imutável por no mínimo 5 anos para fins de auditoria.                                               |
| RNF09  | O acesso aos logs deve ser restrito a usuários autorizados com controle de acesso baseado em perfis.                                                           |
| RNF10  | O sistema deve permitir a geração de relatórios de auditoria sob demanda.                                                                                      |




### 5.6 Restrições de Design

### 5.7 Requisitos de Implementação

### 5.8 Requisitos de Sistema de Ajuda e de Documentação de Usuário Online

### 5.9 Requisitos de Licenciamento

### 5.10 Observações Legais, de Copyright e Outras

### 5.11 Padrões Aplicáveis

| ID     | Padrão Aplicável | Descrição |
|--------|------------------|-----------|
| PAD01  | eMAG             | O Modelo de Acessibilidade de Governo Eletrônico define diretrizes para garantir que o sistema seja acessível a todas as pessoas, inclusive com deficiência. |
| PAD02  | WCAG 2.1 (AA)    | As Diretrizes de Acessibilidade para Conteúdo Web garantem que o sistema possa ser utilizado por usuários com diferentes necessidades, incluindo leitores de tela. |
| PAD03  | LGPD             | A Lei Geral de Proteção de Dados regula o tratamento de dados pessoais e deve ser integralmente seguida pelo sistema. |
| PAD04  | ISO/IEC 27001    | Padrão internacional para gestão da segurança da informação, recomendável para proteger dados sensíveis do sistema. |
| PAD05  | ABNT NBR 9241    | Norma brasileira que trata de ergonomia na interação humano-computador, aplicável à interface do sistema. |
| PAD06  | Material Design ou Bootstrap | Padrões de design visual para manter consistência na interface do usuário. |
| PAD07  | Licenças de Código Aberto (MIT, GPL, etc.) | O uso de bibliotecas e frameworks deve respeitar suas respectivas licenças de uso e distribuição. |

### 5.12 Requisitos Físicos

## 6. Bibliografia

## 7. Histórico de Versões 

<font size="3"><p style="text-align: center">Tabela 3: Histórico de versões</p></font>

| Versão |Descrição     |Autor                                       |Data    |Revisor|
|:-:     | :-:          | :-:                                        | :-:        |:-:|
|1.0     |Criação do documento| [Laryssa Felix](https://github.com/felixlaryssa)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|2.0     |Tópico de introdução| [João Félix](https://github.com/joaofmoreiraa)| 14/05/2025 | [Laryssa Felix](https://github.com/felixlaryssa) |
|3.0     |Tópicos de finalidade e metodologia| [Laryssa Felix](https://github.com/felixlaryssa)| 14/05/2025 | [João Félix](https://github.com/joaofmoreiraa) |
|4.0     |Adição de RNF de suportabilidade| [Caio Duarte](https://github.com/caioduart3) | 17/05/2025 | [Ludmila Nunes](https://github.com/ludmilaaysha) |
|4.1     |Adição de RNF de usabilidade| [Ludmila Nunes](https://github.com/ludmilaaysha) | 17/05/2025 | [Caio Duarte](https://github.com/caioduart3) |
|4.2     |Adição de Padrões Aplicáveis| [Gabriel Pinto](https://github.com/GabrielSPinto) | 17/05/2025 | [Letícia Monteiro](https://github.com/LeticiaMonteiroo) |

<font size="2"><p style="text-align: center">Fonte: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Laryssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.</p></font> 