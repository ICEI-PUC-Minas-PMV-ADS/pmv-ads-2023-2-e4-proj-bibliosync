# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foram consolidados com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram afirmados na forma de personas e histórias de usuários.

## Personas

Seguem demonstradas por meio dos quadros apresentados o levantamento feito das personas e suas características durante o processo de entendimento do problema:


|    Persona    | Idade |           Ocupação           |                        Aplicativos                       |                      Motivações                     |                           Frustrações                          |                           Hobbies                          |
|:-------------:|:-----:|:---------------------------:|:--------------------------------------------------------:|:--------------------------------------------------:|:----------------------------------------------------------------:|:---------------------------------------------------------:|
| Maria Aparecida ![reacoes-sentimentos-e-emocoes-humanas-positivas-mulher-charmosa-e-elegante-de-meia-idade-de-sessenta-anos-de-idade-cabelos-curtos-e-grisalhos-com-sorriso-satisfeito](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t1-pmv-ads-2023-2-e4-proj-bibliosync/assets/103579574/49cfcc5e-e06d-407f-a916-0c261cf68869) |   58  | Bibliotecária de escola | WhatsApp, Instagram, jogos    | Trabalhar visando proporcionar uma boa qualidade de vida para a família. | Não conseguir ter um bom controle dos livros de sua biblioteca. | Gosta de ler, Ouvir música |
| Gabriel Martins ![o-jovem-com-uma-camisa-trabalhando-em-um-laptop-em-lilas](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t1-pmv-ads-2023-2-e4-proj-bibliosync/assets/103579574/aea66113-9f26-45c4-bc7e-e5af89014a0a) |   29  |     Técnico em Informática   | WhatsApp, Instagram, Twitch, Youtube, Discord           | Conseguir ler pelo menos dois livros no mês. | Nãp saber onde encontrar livros que ele deseja ler. | Assistir séries, jogar jogos online e ler |
| Samara Rodrigues ![edward-cisneros-_H6wpor9mjs-unsplash](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t1-pmv-ads-2023-2-e4-proj-bibliosync/assets/103579574/2b522301-5b55-4a3a-bbc8-1cc0469436e7)| 45 |         Dona de biblioteca na cidade          | WhatsApp, Youtube, Instagram                           | Atrair mais pessoas para sua biblioteca. | Ter que fazer controle de alugueis de livro manualmente. | Ler, ir ao teatro e à museus. |

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`         |PARA ... `MOTIVO/VALOR`                               |
|--------------------|--------------------------------------------|------------------------------------------------------|
|Maria Aparecida         |Econtrar um sistema que ajude na organização de livros.                      |Facilitar o controle de livros       |
|Gabriel Martins      |Encontrar livros para empréstimo com mais facilidade.                          |Ler em maior quantidade com mais acessibilidade|
|Samara Rodrigues        |Fazer um controle dos livros de sua biblioteca        |Ajudar a ela e seus funcionários para que não tenham que fazer o controle manualmente |

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Os usuários devem ser capazes de cadastrar informações sobre os livros, incluindo título, autor, data de publicação e gênero. | ALTA | 
|RF-002| Sistema deve permitir aos usuários registrar empréstimos de livros para terceiros, incluindo data de empréstimo, data de devolução e biblioteca de origem.   | ALTA |
|RF-003| Oferecer uma funcionalidade de pesquisa avançada que permita aos usuários localizar livros com base em vários critérios, como autor, título, gênero, entre outros.   | MÉDIA |
|RF-004| Enviar notificações automáticas aos usuários para lembrar devoluções de livros emprestados e fornecer atualizações sobre eventos relacionados a seus livros e bibliotecas favoritas.   | MÉDIA |
|RF-005| Integrar um sistema de pesquisa que permita aos usuários encontrar livros disponíveis em bibliotecas próximas à sua localização.   | ALTA |
|RF-006| Permitir aos usuários reservar livros em bibliotecas próximas, especificando um período de reserva.   | ALTA |
|RF-007| Manter um registro de histórico de todas as reservas e empréstimos realizados pelos usuários.   | BAIXA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Garantir que o aplicativo seja responsivo e rápido, mesmo com grandes volumes de dados e ao lidar com pesquisas em bibliotecas próximas. |  ALTA | 
|RNF-002| Proteger os dados do usuário por meio de criptografia e práticas seguras de armazenamento, especialmente quando se trata de informações de localização. |  ALTA | 
|RNF-003| Respeitar regulamentações de privacidade de dados, especialmente ao lidar com informações de localização dos usuários, e obter consentimento adequado para coleta e uso desses dados. |  ALTA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| A solução deve ser utilizável offline em certa medida, devido a possíveis limitações de conectividade dos usuários. |
|02| Aplicação web e mobile devem ser desenvolvidas utilizando React e React Native, respectivamente       |

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
