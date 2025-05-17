# Diagrama de Casos de Uso

## 1. Introdução

Neste documento, apresentamos os diagramas de casos de uso para o aplicativo IBGE, que tem como objetivo fornecer informações sobre a população brasileira e suas características.

## 2. Descrição do Diagrama de Caso de Uso

O diagrama de casos de uso do aplicativo IBGE é uma ferramenta que representa, de forma gráfica e simplificada, as funcionalidades oferecidas pelo sistema sob a perspectiva dos usuários (atores). Segundo a DevMedia, esse tipo de diagrama permite visualizar as principais interações entre os atores e o sistema, contribuindo para a identificação dos requisitos funcionais. Assim, é possível compreender o que o sistema deve fazer a partir das ações que os usuários desejam realizar, facilitando a comunicação entre desenvolvedores, analistas e stakeholders.

## 3. Atores

Os atores representam os papéis exercidos pelos usuários que interagem com o sistema, sejam pessoas ou sistemas externos. Segundo a DevMedia, os atores simbolizam entidades externas que se comunicam com o sistema para realizar uma ação ou receber um serviço. Eles são fundamentais na modelagem dos casos de uso, pois ajudam a identificar os objetivos dos usuários e as funcionalidades que o sistema deve oferecer.

### 3.1 Usuário

Ator principal que representa o cidadão comum. Ele:

- Visualiza notícias, dados demográficos e mapas (estados/municípios).
- Analisa indicadores estatísticos e compara informações por período.
- Consulta o calendário de eventos/coletas.
- Compartilha informações em redes sociais (WhatsApp, Instagram).
- Acessa fontes e referências dos dados apresentados.
- Configura preferências, como ativar/desativar notificações, acessa canais de atendimento e redes sociais do IBGE e compartilha o aplicativo com amigos.

### 3.2 Portal IBGE

Ator secundário representando um sistema externo. Ele:

- Fornece dados e referências oficiais ao aplicativo.
- Permite a atualização e validação das informações consultadas.

#### Figura 1: Versão 1.0 do diagrama de Casos de uso – app IBGE

![Diagrama de Casos de uso](./../assets/images/modelagem/IBGE-casosDeUso.drawio.svg)

**Fonte**: [Caio Duarte](https://github.com/caioduart3) e [Mayara Marques](https://github.com/maymarquee), 2025.

## 4. Pré-condições

No processo de modelagem de sistemas com UML, uma pré-condição é um estado necessário do sistema antes que um Caso de Uso possa ser executado. Ela representa uma regra de consistência ou um requisito técnico/funcional que deve estar satisfeito para que o fluxo de execução inicie corretamente.

- O usuário deve ter acesso à internet.
- O aplicativo deve estar instalado em um dispositivo compatível (smartphone ou tablet).

## 5. Pós-condições

As pós-condições representam os estados possíveis do sistema após a conclusão de um caso de uso, descrevendo o que muda ou permanece como resultado da interação com o usuário. Elas são úteis para validar os efeitos de uma funcionalidade no sistema e garantir que o comportamento esperado foi atingido.

Exemplos de pós-condições:

- O usuário visualiza as informações atualizadas no aplicativo.  
- O usuário compartilha informações com sucesso nas redes sociais.  

## 6. Fluxo de Eventos

O Fluxo de Eventos descreve como o ator interage com o sistema durante a execução de um caso de uso e é dividido em três partes. O Fluxo Básico mostra o caminho principal e bem-sucedido da interação, sempre começando com uma ação do ator e finalizando com o objetivo do caso de uso alcançado. Já os Fluxos Alternativos representam variações opcionais do fluxo básico, ocorrendo quando o ator faz uma escolha diferente, como compartilhar uma informação ou acessar uma fonte externa. Por fim, os Fluxos de Exceção tratam erros ou falhas funcionais, como dados indisponíveis ou tempo de resposta excedido. Nesses casos, o sistema informa o problema ao usuário e, sempre que possível, permite a retomada do fluxo principal.

### Tabela 1: Fluxo de Eventos

| Caso de Uso                      | Fluxo Básico                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Fluxos Alternativos                                                                                                                                                                                                                                                                                                                                                                                                                   | Fluxos de Exceção                                                                                                                                                                                                                                                                      |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Analisar Indicadores**         | **FB1.** O sistema apresenta filtros (indicador, região, período).**FB2.** O usuário seleciona indicador.<br>**FB3.** O sistema apresenta regiões.<br>**FB4.** O usuário seleciona regiões.<br>**FB5.** O sistema apresenta períodos.<br>**FB6.** O usuário seleciona período.<br>**FB7.** O sistema valida conexão com internet. \[FA1]<br>**FB8.** O sistema consulta base e apresenta indicadores.<br>**FB9.** O sistema permite comparação.<br>**FB10.** O usuário pode compartilhar. \[FA2]<br>**FB11.** Finaliza caso de uso. | **FA1. Sem conexão:**<br>FA1.1. Sistema informa ausência de conexão.<br>FA1.2. Retorna ao passo FB1 após reconexão.<br>FA1.3. Finaliza fluxo.<br><br>**FA2. Compartilhar:**<br>FA2.1. Exibe opções de compartilhamento.<br>FA2.2. Usuário escolhe rede.<br>FA2.3. Sistema compartilha.<br>FA2.4. Retorna ao FB11.<br>FA2.5. Finaliza fluxo.                                                                                           | **FE1. Indicadores indisponíveis:**<br>FE1.1. Exibe mensagem “dados não encontrados”.<br>FE1.2. Retorna ao passo FB2.<br>FE1.3. Finaliza fluxo.<br><br>**FE2. Tempo excedido:**<br>FE2.1. Exibe “tempo excedido. Tente novamente”.<br>FE2.2. Retorna ao FB6.<br>FE2.3. Finaliza fluxo. |
| **Visualizar Notícias**          | **FB1.** O sistema valida conexão com internet. \[FA1]<br>**FB2.** O sistema acessa base de notícias.<br>**FB3.** Exibe lista com título, data e resumo.<br>**FB4.** Usuário seleciona notícia.<br>**FB5.** Sistema exibe notícia completa.<br>**FB6.** Usuário pode acessar fonte externa. \[FA2]<br>**FB7.** Usuário pode compartilhar notícia. \[FA3]<br>**FB8.** Finaliza caso de uso.                                                                                                                                              | **FA1. Sem conexão:**<br>FA1.1. Sistema informa ausência de conexão.<br>FA1.2. Retorna ao início após reconexão.<br>FA1.3. Finaliza fluxo.<br><br>**FA2. Acessar fonte:**<br>FA2.1. Abre link no navegador.<br>FA2.2. Permite retorno.<br>FA2.3. Finaliza fluxo.<br><br>**FA3. Compartilhar:**<br>FA3.1. Exibe opções (WhatsApp, Instagram).<br>FA3.2. Usuário escolhe rede.<br>FA3.3. Sistema compartilha.<br>FA3.4. Finaliza fluxo. | **FE1. Falha ao carregar notícia:**<br>FE1.1. Exibe mensagem de erro.<br>FE1.2. Retorna à lista de notícias.<br>FE1.3. Finaliza fluxo.                                                                                                                                                 |
| **Consultar Dados Demográficos** | **FB1.** Sistema valida conexão com internet. \[FA1]<br>**FB2.** Sistema exibe filtros (região, sexo, idade).<br>**FB3.** Usuário define filtros.<br>**FB4.** Sistema processa consulta e carrega dados.<br>**FB5.** Sistema exibe gráficos e tabelas.<br>**FB6.** Usuário pode compartilhar. \[FA2]<br>**FB7.** Finaliza caso de uso.                                                                                                                                                                                                  | **FA1. Sem conexão:**<br>FA1.1. Sistema informa ausência de internet.<br>FA1.2. Retorna ao início após reconexão.<br>FA1.3. Finaliza fluxo.<br><br>**FA2. Compartilhar:**<br>FA2.1. Sistema exibe opções.<br>FA2.2. Usuário escolhe rede.<br>FA2.3. Sistema compartilha.<br>FA2.4. Finaliza fluxo.                                                                                                                                    | **FE1. Nenhum dado para filtro:**<br>FE1.1. Exibe mensagem “nenhum dado encontrado”.<br>FE1.2. Retorna ao FB2.<br>FE1.3. Finaliza fluxo.                                                                                                                                               |

**Fonte**: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.

## 7. Relacionamentos

Os relacionamentos entre os casos de uso e os atores são fundamentais para entender como o sistema interage com os usuários e outros sistemas. Eles ajudam a identificar as dependências e as interações necessárias para o funcionamento do sistema. Os relacionamentos podem ser classificados em três tipos principais: associação, generalização e inclusão.

- **Generalização:** Indica que um ator ou caso de uso é uma especialização de outro. Isso significa que o ator ou caso de uso herda as características do elemento pai. No diagrama, é representada por uma linha sólida com um triângulo na extremidade do elemento pai.
- **Inclusão:** Representa um relacionamento entre dois casos de uso, onde um caso de uso (caso de uso pai) inclui o comportamento de outro caso de uso (caso de uso filho). Isso significa que o caso de uso pai invoca o caso de uso filho. No diagrama, é representada por uma linha pontilhada com uma seta apontando para o caso de uso incluído.
- **Associação:** Representa uma interação ou comunicação simples entre os atores com casos de uso. É representado por uma linha sólida que liga os atores aos casos de uso. 

### 7.1 Pontos de Extensão

- **PE1. IBGE_UC001_VisualizarNotícias – Compartilhar informação por WhatsApp, Instagram**  
Permite ao usuário compartilhar a notícia visualizada, se desejar.
- **PE2. IBGE_UC001_VisualizarNotícias – Acessar referências de indicadores**  
Permite que o usuário acesse fontes e referências da notícia.
- **PE3. IBGE_UC003_AnalisarIndicadores – Comparar indicadores em espaço de tempo, mensal ou anual**  
Extensão ativada caso o usuário deseje realizar comparações detalhadas por período.

### 7.2 Pontos de Inclusão

- **PI1. IBGE_UC002_VisualizarDadosDemográficos – Validar conexão com a internet**  
A consulta aos dados depende da verificação da conexão.
- **PI2. IBGE_UC003_AnalisarIndicadores – Validar conexão com a internet**  
A análise dos indicadores exige conexão ativa.
- **PI3. IBGE_UC004_VisualizarMapaDeRegiões – estados**  
Visualizar estados faz parte da navegação no mapa.
- **PI4. IBGE_UC004_VisualizarMapaDeRegiões – municípios**  
Visualizar municípios também está incluído na funcionalidade de mapa.

## 8. Informações Complementares

Esta seção apresenta os parâmetros utilizados nos casos de uso que envolvem consultas estatísticas, como Analisar Indicadores. Esses parâmetros são recebidos pelo sistema como entrada do usuário e são fundamentais para filtrar os dados retornados, permitindo visualizações específicas por tipo de indicador, região e período.

Como esse processo não envolve uma interface de cadastro, os dados são tratados como parâmetros funcionais utilizados internamente no sistema.

### Tabela 2: Tabela de Parâmetros

| Parâmetro | Tipo       | Tamanho | Obrigatório (S/N) | Descrição                                                |
|-----------|------------|---------|--------------------|------------------------------------------------------------|
| Indicador | Alfabético | 50      | S                  | Tipo de indicador estatístico (ex: desemprego, renda).     |
| Estado    | Alfabético | 50      | S                  | Unidade da federação selecionada para a análise.           |
| Período   | Data       | 10      | S                  | Intervalo de tempo da análise (mensal, anual).             |

**Fonte**: [Gabriel Pinto](https://github.com/GabrielSPinto), 2025.

## 9. Requisitos Especiais

Esta seção apresenta detalhamentos técnicos específicos que não se enquadram diretamente nos fluxos de eventos, mas que precisam ser observados para garantir a correta execução dos casos de uso. Tais requisitos estão relacionados, principalmente, ao formato dos dados transferidos ou parâmetros especiais usados durante a execução de funcionalidades específicas do sistema.

Nos casos de uso do aplicativo IBGE, foi identificado um requisito especial aplicável ao compartilhamento de informações com usuários externos, através de redes sociais como WhatsApp e Instagram.

###  9.1 - RE1. Formato de compartilhamento de dados em redes sociais

Durante os fluxos de extensão que envolvem o compartilhamento de informações (casos de uso: *Analisar Indicadores*, *Visualizar Notícias*, *Consultar Dados Demográficos*), o sistema deve gerar uma **mensagem padronizada** para envio em plataformas externas, como WhatsApp e Instagram. A mensagem deve seguir o seguinte layout:

**Exemplo de mensagem gerada para compartilhamento:**

- **Indicador:** Nome do indicador  
- **Estado:** UF selecionado  
- **Período:** Mês/ano  
- **Valor:** Dado estatístico  
- **Fonte:** IBGE  
- **Link:** [https://www.ibge.gov.br](https://www.ibge.gov.br)

Observações:

- Cada campo deve estar em uma **nova linha**.
- O campo **Valor** deve incluir a **unidade de medida** (%, R$, habitantes, etc.).
- O campo **Link** deve sempre estar presente como referência institucional.

Este requisito garante a padronização das informações compartilhadas, assegurando clareza e confiabilidade dos dados transmitidos pelo sistema.

## 10. Referências

> DEVMEDIA. O que é UML e diagramas de caso de uso – Introdução prática à UML. Disponível em: <https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408>. Acesso em: 13 maio 2025.  

**Figura 1:** Referência Casos de Uso  
![Diagrama de Casos de Uso](./../../assets/images/entrega3_fontes/fonte_CasosDeUso.png)  
 **Fonte:** Artigo Devmedia  

## 11. Histórico de Versões

| Versão | Descrição               | Autor                                       | Data       | Revisor                                  |
|--------|-------------------------|---------------------------------------------|------------|------------------------------------------|
| 1.0    | Criação do documento     | [Caio Duarte](https://github.com/caioduart3) | 06/04/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
| 1.1    | Adiciona diagrama de casos de uso | [Caio Duarte](https://github.com/caioduart3) | 06/04/2025 | [Gabriel Pinto](https://github.com/GabrielSPinto) |
| 1.2    | Adiciona demais itens do artefato | [Gabriel Pinto](https://github.com/GabrielSPinto) | 06/04/2025 | [Mayara Marques](https://github.com/maymarquee) |

**Fonte**: [Caio Duarte](https://github.com/caioduart3), [Gabriel Pinto](https://github.com/GabrielSPinto), [João Félix](https://github.com/joaofmoreiraa), [Larysssa Felix](https://github.com/felixlaryssa), [Letícia Monteiro](https://github.com/LeticiaMonteiroo), [Ludmila Nunes](https://github.com/ludmilaaysha) e [Mayara Marques](https://github.com/maymarquee), 2025.
