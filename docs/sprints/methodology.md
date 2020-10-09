## Estrutura da Sprint

## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|11/09/2020|   0.1    | Criação do Documento        |   Mateus Sousa   |
|09/10/2020|   1.0    | Adiciona a metodologia   |   Gabriel Filipe   |


## Metodologia
<hr>

A metodologia aplicada no projeto Over26 consiste na junção de aspectos e princípios do framework Scrum, Extreme Programming e kanban. As técnicas selecionadas para dar origem à metodologia híbrida utilizada, foram:  

1. Papéis
2. Rituais
3. Planejamento
4. Gerenciamento

## 1. Papéis

### Scrum Master

Responsável por remover impedimentos relacionados ao desenvolvimento; Minimizar riscos do projeto; Garantir a disseminação de contéudo entre os membros da equipe; Monitorar e aperfeiçoar a produtividade da equipe utilizando métricas bem definidas; Garantir que a metodologia seja aplicada.


### Product Owner

Responsável por trazer a visão de produto às decisões do time; Analisar e priorizar os pontos mais valiosos, do ponto de vista dos stakeholders; E Definir critérios de aceitação considerando visão do cliente. 

### DevOps

Responsável por garantir a disponibilidade dos ambientes de desenvolvimento, homologação e produção; E Configurar integração e deploy contínuo; 

### Quality Assurance

Decidir métricas para avaliar o produto de software e seu desenvolvimento;
Coletar e Analisar as métricas do produto de software;
Garantir as melhorias das métricas que necessitam dessas melhorias e manter a qualidade, tanto em termos de código, quanto em usabilidade, do produto de software.

### Arquiteto

Responsável por modelar a arquitetura do sistema e garantir que ela está sendo seguida no desenvolvimento; E monitorar qualidade do código.

### Desenvolvedor

Responsável por programar as histórias de usuário; Seguir técnicas de programação; E realizar testes no código produzido. 

## 2. Rituais

* Sprints
    - Duração de 7 dias : Início na terça e término na segunda da outra semana.
    - Poderão ser menores devido as releases : Mais curtas ou longas, conforme decisão do Scrum Master.

* Daily Meeting
    - As dailies da equipe serão realizadas diariamente por meio do telegram, prioritariamente no período da noite. Todos os membros têm como obrigação informar a respeito do andamento das suas atividades.

* Sprint Planning
    - Ocorrem às segundas, iniciando às 19:30h

    Nesta reunião são planejados quais os próximos passos a serem realizados no projeto, mudanças, distribuição de tarefas rotação de papéis.

* Sprint Review
    - Ocorrem às segundas, iniciando às 20:00h

    Nesta Reunião são colhidos os feedbacks dos membros do time e apresentados entregas e pendências, são levantadas questões do que pode ser melhorado, quais foram os pontos negativos e positivos da sprint passada.

* Sprint Restropective
    - Ocorrem às segundas, iniciando às 20:30h


## 3. Planejamento

* Issues 
    - As issues serão criadas para todos os tipos de contribuição com o projeto, a fim de registrar o trabalho da equipe. Ainda com esse objetivo, o uso de labels servirão identificar facilmente : O responsável e o tipo de atividade relacionada. 
    - As labels utilizadas até o momento, são: 
        - Ata
        - Bug
        - Desenvolvimento
        - Documentação
        - EPS
        - MDS
        - Hotfix
        - Organização
        - Refatoração
        - Technical Story
        - Test
        - Treinamento 
        - User Story
        - Sprints (0, 1, 2, 3, 4, 5, 6, 7, ...)
        
* Milestones

    - As milestones serão utilizadas para identificar as sprints, visto que considera-se que a cada sprint tem-se uma entrega de funcionalidades/incrementos, é possível caracterizá-las como macros do projeto. Assim, as issues planejadas devem ser mapeadas para as milestones referentes.

* Épicos

    - Os épicos serão utilizados para associar issues de um mesmo módulo ou para representar issues que possuam um alto nível de complexidade/dificuldade, a fim de facilitar o desenvolvimento.
    
* User Story

    - As user stories seguirão o seguinte padrão: Eu como [usuário] desejo [ação que será executada] para [justificativa];
    - Toda user story, associada à uma issue deve possuir critérios de aceitação a serem verificados a fim de definir uma tela como concluída;

* Planning Poker

    - Técnica aplicada para auxiliar na estimativa da dificuldade das atividades a serem realizadas nas sprints, a fim de conseguir mapear a capacide de produção da equipe;
    - Os pontos estimados para as issues devem constar no seu registro;
    - As pontuações consideradas são: 0, 1, 2, 3, 5, 8, 13 e 21;

* Priorização 
    - A priorização foi simplificada adotando-se os seguintes níveis: Baixa, média, alta.

* <i>Pair Programming</i>

    -  Ritual onde dois membros da equipe de Desenvolvimento, trabalham juntos para realizar uma tarefa.
    - A cada 15 minutos, um deles assume o papel de piloto, ou seja, escreve o código, e o outro assume o papel de co-piloto e dita a lógica para realizar a funcionalidade e também auxilia o piloto a pensar na melhor forma de desenvolver essa funcionalidade.

* Integração Contínua 

    - Prática de testar as modificações do código que foi submetida ao repositorio remoto do projeto.
    - Todo o funcionamento da integração continua é pensado e efeitvado pelo DevOps do projeto.

* Padrão de Código

    - É a definição de escrita do código, de maneira a manter a homogeniedade deste.
    -  A folha de estilo, documento que define esse padrão, é contruida pelo <i>Quality Assurence</i>.

* Testes

    - Toda a funcionalidade desenvolvida, deve ser testa, ou seja, deve ser implementados testes que prevêm funcionamento errôneo ou indesejado da funcionalidade. E esta funcionalidade deve passar em todos os testes escritos.

* <i>Kanban</i>

    - Metodologia que consistem em um quadro divido em <i><b>TO DO</b></i>, <i><b>DOING</b></i> e <i><b>DONE</b></i>, e em cada uma destas colunas é colocado as tarefas que devem ser feitas, as que estão no processo de ser feitas e as completas, respectivamente.

    - No projeto, utilizamos o <i><b>Zenhub</b></i> para contemplar esta metodologia.


## 4. Gerenciamento

* Velocity
    - O velocity atuará como ferramenta para análise da capacidade de desenvolvimento da equipe. Ele será elaborado ao fim de cada sprint e será consultado pelo Scrum Master no planejamento da sprint seguinte.

* Burndown
    - Para monitorar as atividades entregues, o Scrum Master utilizará também o burndown, gerado pelo kanban usado pela equipe. Ele irá utilizá-lo inclusive ao longo das sprints para garantir as entregas. 

* Burndown de Riscos
    - Para monitorar os riscos do projeto, a fim de evitar complicações e maiores problemas, o Scrum Master irá criar e monitorar o burndown de riscos ao longo das sprints.



### Referências Bibliográficas

> | [GLOSSARY Extreme Programming](https://www.agilealliance.org/glossary/xp/#q=~(filters~(postType~(~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'xp))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

> | [Extreme Programming - Conceitos e Práticas](https://www.devmedia.com.br/extreme-programming-conceitos-e-praticas/1498)

> | [What is Scrum](https://www.scrum.org/resources/what-is-scrum?gclid=Cj0KCQjwlK7cBRCnARIsAJiE3Mg-GBLapVDq-TPyx-wt0K0_8jLFjB14XaEjPZzMTJUJ5fPvZWmQmokaAs23EALw_wcB) 

> | [Dr. Down - Scrum Methodology](https://github.com/fga-eps-mds/2018.1-Dr-Down/blob/develop/docs/eps/SCRUM_METHODOLOGY_DRDOWN.md)