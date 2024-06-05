# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Critérios de Sucessos](#critérios-de-sucesso)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos Preliminares](#requisitos-preliminares)
- [Partes Interessadas](#partes-interessadas)
- [Estimativa de Custo e Prazo](#estimativa-de-custo-e-prazo)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
- [Documentos](#documentos)
  - [Declaração de Escopo](#declaração-de-escopo)
  - [Registro de Partes Interessadas](#registro-de-partes-interessadas)
  - [Termo de Abertura do Projeto (TAP)](#termo-de-abertura-do-projeto-tap)

# Introdução

## Problema

O problema a ser solucionado pelo projeto de monitoramento cardíaco é o aumento significativo das doenças cardíacas e o risco crescente de ataques cardíacos na sociedade atual. Diversos fatores, como estilos de vida sedentários, dietas inadequadas e estresse, contribuem para o desenvolvimento de problemas cardíacos. Muitas vezes, as pessoas não estão cientes de condições cardíacas até que seja tarde demais.
> O projeto visa abordar as seguintes questões:
>  Detecção Precoce de Anomalias na Frequência Cardíaca:
>  Muitas condições cardíacas podem ser assintomáticas em estágios iniciais. O monitoramento contínuo da frequência cardíaca permite a detecção precoce de anomalias, possibilitando intervenções médicas antes que problemas mais graves ocorram.
> Acesso Limitado a Monitoramento Contínuo:
> As tecnologias tradicionais de monitoramento cardíaco geralmente estão disponíveis apenas em ambientes hospitalares. O projeto busca proporcionar às pessoas a capacidade de monitorar sua saúde cardíaca de forma contínua, mesmo no conforto de casa.
> Resposta Rápida em Situações de Risco:
> Em casos de variações perigosas na frequência cardíaca, a intervenção médica rápida é crucial. O sistema proposto busca alertar imediatamente profissionais de saúde e familiares para que medidas adequadas possam ser tomadas.
> Falta de Consciência e Educação sobre Saúde Cardíaca:
> Muitas pessoas não têm consciência dos fatores de risco associados às doenças cardíacas e não adotam práticas preventivas. O projeto visa aumentar a conscientização e promover a educação sobre a importância do monitoramento cardíaco regular.

## Objetivos

Enviar um alerta ao identificar frequência cardíaca irregular para o usuário.
> Objetivos específicos: 
> 1- Capacitar os usuários a tomar medidas proativas em relação à sua saúde cardíaca, fornecendo ferramentas de monitoramento acessíveis que promovam o autocuidado e a prevenção.
> 2- Minimizar os riscos associados a problemas cardíacos através da detecção precoce de anomalias na frequência cardíaca e da notificação imediata a profissionais de saúde e familiares.
> 3- Desenvolver um sistema de alerta que seja capaz de notificar imediatamente médicos e familiares em caso de leituras irregulares na frequência cardíaca, com a opção de personalizar os parâmetros de alerta.
 
# Especificações do Projeto

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para
realizar as especificações do projeto.

## Critérios de Sucesso

......  COLOQUE AQUI O SEU TEXTO ......

> Os critérios de sucesso de um projeto fornecem uma estrutura clara para avaliar o êxito do trabalho e analisar se o projeto realmente alcançou os objetivos estabelecidos. 
> Esses critérios geralmente abrangem diversas dimensões, incluindo a entrega dentro do prazo e orçamento estipulados, a satisfação do cliente, a qualidade do produto ou serviço final, e a eficiência na utilização de recursos. 
> Além disso, a capacidade de atender aos requisitos e expectativas das partes interessadas, bem como a gestão eficaz de riscos, são considerados aspectos importantes para determinar o sucesso de um projeto. 
 
## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Paciente            | Monitorar meus batimentos cardíacos em tempo real | Acompanhar minha saúde de forma contínua |
|Médico       | Acessar o histórico de batimentos cardíacos dos pacientes | Analisar tendências e ajustar tratamentos |
|Paciente      | Receber alertas de anomalias cardíacas | Tomar ações preventivas em casos de emergência |
|Cuidador       | Ser notificado se o paciente tiver anomalia cardíaca | Prestar assistência imediata ao paciente |
|Administrador do Sistema | Configurar alertas personalizados para pacientes | Garantir que os alertas sejam relevantes |
|Paciente       | Visualizar relatórios semanais dos meus batimentos | Entender melhor minha condição cardíaca |
|Médico      |Configurar parâmetros de alerta para cada paciente               | Personalizar o monitoramento conforme a necessidade |
|Paciente       |Compartilhar meus dados cardíacos com meu médico                | Facilitar o acompanhamento médico à distância |
|Pesquisador       |Acessar dados anônimos dos pacientes              | Realizar estudos e pesquisas sobre saúde cardíaca |
|Paciente      | Sincronizar os dados do sensor com o aplicativo móvel  | Manter os dados atualizados em todos os dispositivos |
|Médico       | Receber alertas em tempo real de anomalias dos pacientes              | Intervir rapidamente em situações de risco |
|Paciente      | Ver dicas de saúde com base nos meus dados cardíacos                | Melhorar minha saúde e bem-estar |
|Administrador do Sistema      | Gerenciar os usuários e seus níveis de acesso  | Controlar a segurança e a privacidade dos dados |
|Paciente       | Acessar meus dados mesmo sem conexão à internet    | Consultar meu histórico a qualquer momento |
|Médico       | Agendar consultas com base nas anomalias detectadas              | Planejar intervenções de forma proativa |
|Paciente      | Definir metas de saúde e acompanhar meu progresso                 | Manter a motivação e monitorar meu progresso |
|Administrador do Sistema       | Realizar backup regular dos dados dos pacientes              | Evitar perda de informações importantes |
|Paciente      | Receber notificações sobre a bateria do sensor        | Garantir que o sensor esteja sempre funcionando |
|Médico      | Consultar relatórios gráficos dos dados dos pacientes        | Visualizar informações de forma mais compreensível |
|Paciente     | Integrar os dados do sensor com outros apps de saúde        | Consolidar minhas informações de saúde em um único lugar |

## Requisitos Preliminares

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 20) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Permitir que o paciente visualize seus batimentos cardíacos em tempo real | ALTA | 
|RF-002| Permitir que o médico acesse o histórico de batimentos cardíacos dos pacientes | ALTA |
|RF-003| Enviar alertas de anomalias cardíacas ao paciente | ALTA |
|RF-004| Notificar cuidadores em caso de anomalia cardíaca do paciente | ALTA |
|RF-005| Configurar alertas personalizados para cada paciente | MÉDIA |
|RF-006| Gerar relatórios semanais dos batimentos cardíacos dos pacientes | MÉDIA |
|RF-007| Configurar parâmetros de alerta específicos para cada paciente | MÉDIA |
|RF-008| Permitir que o paciente compartilhe seus dados cardíacos com o médico | ALTA |
|RF-009| Permitir acesso a dados anônimos dos pacientes para pesquisas | BAIXA |
|RF-010| Sincronizar dados do sensor com o aplicativo móvel | ALTA |
|RF-011| Enviar alertas em tempo real ao médico sobre anomalias dos pacientes | ALTA |
|RF-012| Fornecer dicas de saúde baseadas nos dados cardíacos do paciente | MÉDIA |
|RF-013| Gerenciar usuários e seus níveis de acesso | ALTA |
|RF-014| Acessar dados dos pacientes mesmo offline | MÉDIA |
|RF-015| Agendar consultas com base nas anomalias detectadas | MÉDIA |
|RF-016| Definir metas de saúde e acompanhar progresso do paciente | MÉDIA |
|RF-017| Realizar backup regular dos dados dos pacientes | ALTA |
|RF-018| Enviar notificações sobre o estado da bateria do sensor | ALTA |
|RF-019| Gerar relatórios gráficos dos dados dos pacientes | MÉDIA |
|RF-020| Integrar dados do sensor com outros aplicativos de saúde | BAIXA |

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s             | BAIXA     | 


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RE-002| Emitir um relatório de tarefas no mês   | MÉDIA |

# Partes Interessadas

......  COLOQUE AQUI O SEU TEXTO ......

> Relacione as partes interessadas no seu projeto. 
> Você deve descrever as partes interessadas e indicar qual o nível de influência em relação ao projeto.
> Indique as principais pessoas (clientes, fornecedores, etc), indicando possíveis expectativas, nível de influência e possível importância para o sucesso do projeto.

# Estimativa de Custo e Prazo

## Estimativa de Custo

> Aqui apresentamos a analise de estimativa de custo, visando o melhor desempenho do nosso produto

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |            |              |             |
| Hardware                |           |            |              |             |
| Serviços de Rede        |           |            |              |             |
| Hospedagem e Nuvem      |           |            |              |             |
| Software de terceiros   |           |            |              |             |
| Serviços e treinamento  |           |            |              |             |
| **Total Geral**         |           |            |              |             |


## Estimativa de Prazo
> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * 
> * Data de início
> * Data de término

# Metodologia

Para manter a ordem e eficiência no projeto, utilizamos métodos ágeis, evitando o modelo em cascata, o que proporcionou uma maior interação com o cliente. Primeiramente, realizamos uma divisão clara de papéis, evitando a sobreposição de atividades entre os membros da equipe. A utilização de ferramentas amplamente adotadas no mercado, como repositórios do GitHub, quadros Kanban, Microsoft Word, Figma, entre outras, foi um fator crucial para a organização e sucesso do projeto.

Para a aplicação do framework Scrum, formamos uma equipe pequena, composta por quatro participantes, todos localizados na mesma cidade, o que facilitou o comprometimento e colaboração igualitária de todos. Dividimos o trabalho em "sprints" semanais, garantindo entregas regulares de cada integrante. Além disso, realizamos reuniões rápidas diárias, com duração de 5 a 15 minutos, para alinhar o progresso e resolver eventuais impedimentos. Foi também realizado o backlog das sprints, assegurando que todas as tarefas necessárias fossem planejadas e executadas de acordo com as prioridades do projeto.


## Divisão de Papéis

Seguindo o framework Scrum, os papéis foram divididos em três categorias: Scrum Master, Product Owner e time de desenvolvimento. Ana Beatriz assumiu a função de Scrum Master, sendo responsável por promover e suportar o Scrum conforme definido no Guia Scrum. Bárbara Sampaio, por sua vez, foi designada como Product Owner, encarregada de maximizar o valor do produto através da definição clara das suas características, além de gerenciar o backlog do produto. Finalmente, Rodrigo Rocha e Eron Arthur compõem o time de desenvolvimento, responsáveis por entregar incrementos do produto "Pronto" ao final de cada Sprint.


## Ferramentas

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/orgs/ICEI-PUC-Minas-PMG-EC-GPS/projects/5/views/1 | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/ICEI-PUC-Minas-PMG-EC-GPS/pmg-ec-2024-01-gps-92470101-time-card-gp-6 | Armazenamento de codigo collaboração conjunta|
| Ferramentas de design da interface  | Canva  | https://canva.com  |  Pre familiariedade do desenvolvedor|
| Documentos Textuais   | Microsoft Word | N/A                        |  Pre familiariedade do desenvolvedor|
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
|IDE de desenvolvimento| Visual Studio Code  |   N/A                     |Pre familiariedade do desenvolvedor |
|Distro da Linguagem de desenvolvimento     | Java development kit         |N/A |Capacidade Multiplataforma |
| Gerenciador de projeto | ProjectLibre | N/A  |Pre familiariedade do desenvolvedor|
| Diagramas | DrawIO |https://app.diagrams.net  |Pre familiariedade do desenvolvedor|

# Documentos

> Esta seção deve ser utilizada para armazenamento e listagem dos documentos e artefatos produzidos durante as aulas.
> Atualize os documentos nos respectivos links.

## Declaração de Escopo

- [Declaração de Escopo](artefatos/declaracao_de_escopo.pdf)

## Registro de Partes Interessadas

> Você deve preencher o seguinte documento:
- [Registro de Partes Interessadas]()

## Termo de Abertura do Projeto (TAP)

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> - [Termo de Abertura do Projeto]()
