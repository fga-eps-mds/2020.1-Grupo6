#	A Estrutura de Tópicos do Documento de Visão

## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|20/03/2020|   0.1    | Criação do Documento        |   Hércules  |
|29/08/2020|   0.2   | Restruturação do Documento     |   Guilherme  |
|01/08/2020|   0.3   | Restruturação do Documento     |   Guilherme  |
|10/09/2020|   0.4   | Inserção do tópico 1     |   Hércules  |
|10/09/2020|   0.5   | Atualização da Visão Geral do Produto    |  Bruno  |
|13/09/2020|   0.7   | Atualização do tópico de recursos    |  Vitor  |
|14/09/2020|   0.8   | Atualização do tópico Descrição da Parte Interessada e do Usuário    |  Hércules  |
|18/09/2020|   0.9   | Atualização do item 4.2    |  Bruno  |


## Sumário
[1. Introdução](#1-introducao) <br>
[2. Posicionando](#2-posicionando) <br>
[3. Descrições da Parte Interessada e do Usuário](#3-descricoes-da-parte-interessada-e-do-usuario) <br>
[4. Visão Geral do Produto](#4-visao-geral-do_produto) <br>
[5. Recursos do Produto](#5-recursos-do-produto) <br>
[6. Restrições](#6-restriçoes) <br>
[7.  Referências](#7-referencias) <br>


###	1: Introdução
Esta introdução fornece uma visão geral de todo o documento de visão. Ela inclui o propósito, escopo, definições, acrônimos, abreviações, referências e visão geral de todo o documento.

####	1.1 Propósito:
 Este documento visa definir o escopo e o propósito geral do projeto do sistema de gerenciamento do aplicativo "Vamos Cuidar", especificando o posicionamento em relação ao problema a ser resolvido, descrevendo as partes interessadas, dando uma visão geral do produto, definindo quais serão os recursos do produto, e por fim elencando as possíveis restrições atreladas a este projeto.

####	1.2 Escopo:
 Este projeto é parte do desenvolvimento do aplicativo "Vamos Cuidar", e tem como objetivo desenvolver um sistema gerenciador para o aplicativo. Este aplicativo é feito em parceria com o DAF da UnB, e tem como objetivo fornecer uma interface para que pessoas vinculadas a UnB possam relatar problemas no ambiente da UnB e assim ter esses relatos entregues aos departamentos responsáveis. O sistema gerenciador, dentro do projeto, visa fornecer uma interface para que se possa gerenciar o conteúdo do aplicativo.

####	1.3 Definições, acrônimos e abreviações:
 UnB - Universidade de Brasília

 DAF - Decanato de Administração

 PO - Product Owner (Dono do produto)

####	1.4 Referências:
 **Vision document.** Disponível em:
  <https://www.ibm.com/support/knowledgecenter/en/SSWMEQ_4.0.6/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.html>. Acessado em: 10 de Setembro de 2020.

####	1.5 Visão geral:
 Este documento traz o escopo e propósito geral deste projeto, e está dividido em 7 tópicos: <br>
 1. Introdução: fornece uma visão geral do documento de visão.<br>
 2. Posicionando: Descreve o propósito do produto e a importância deste para as partes envolvidas.<br>
 3. Descrições da Parte Interessada e do Usuário: Descreve todas as partes interessadas no produto e usuários.<br>
 4. Visão Geral do Produto: Essa seção fornece uma visão geral das capacidades, interfaces com outras aplicações, e configurações do sistema.<br>
 5. Recursos do Produto: Lista e descreve as funcionalidades do produto.<br>
 6. Restrições: Busca elencar quaisquer restrições de projeto externas, ou internas.<br>
 7.  Referências: Lista todas as referências que foram utilizadas para elaborar este documento.<br>

###	2: Posicionando
####	2.1 Oportunidade de Negócios:
Com a pandemia do vírus COVID-19, surge a necessidade de se obter rapidamente informações sobre o vírus para se instrumentalizar formas de combatê-lo, desta forma é necessário uma forma de levantar dados e achar as correlações necessárias para trazer as devidas soluções ao problema.
####	2.2 Instrução do Problema:
O problema da pandemia do vírus COVID-19 gera a necessidade de análise de dados sobre este vírus para encontrar correlações importantes ao caso, tal problema afeta a população mundial. O impacto do problema se extende na morte de milhares de pessoas, principalmente idosos, e pessoas com doenças crônicas, e pessoas com imunidade baixa. Uma solução bem sucedida para o problema dos dados incluiria uma plataforma de fácil acesso a dados do relativos ao vírus; outros dados que possam gerar corelações como renda e escolaridade de pessoas afetadas, lugares onde pessoas foram infectadas, entre outros; possibilidade de comparar os dados na plataforma. 

####	2.3 Instrução de Posição do Produto:
Para o população que necessita de uma solução que minimize os efeitos da pandemia. O (nome do produto) é uma aplicação que permite a visualização de dados do COVID-19 em forma de mapa de calor. Há aplicações que disponibilizam a visualização de casos de COVID-19 em forma de mapa de calor, nosso produto no entanto se diferencia pela capacidade de cruzar diversos dados de diferentes fontes para se observar possíveis correlações.

###	3: Descrições da Parte Interessada e do Usuário
Esta seção fornece um perfil das partes interessadas e usuários que estão envolvidos no projeto. Esta seção também identifica os principais problemas que as partes interessadas e os usuários consideram que a solução proposta deva tratar.


####	3.1 Resumo da Parte Interessada:

| Nome      |Descrição | Responsabilidades
|-----------|----------|------------------|
| Cliente.   |DAF da UnB| Administrar a plataforma, criando posts, analisando os dados, e providenciando soluções para problemas postados pelos usuários|
|Usuário do aplicativo |Alunos, professores, ou quaisquer servidores da universidade| Utilizar a plataforma, postando eventuais problemas na universidade, fornecendo informações como por exemplo o local do problema, e uma foto. |
| Equipe de Desenvolvimento| Equipe formada por alunos das disciplinas de métodos de desenvolvimento de software, e engenharia do produto de software| Desenvolver a plataforma |

####	3.2 Resumo do Usuário:

| Nome      |Descrição | Parte Interessada
|-----------|----------|------------------|
| Administrador do aplicativo   |Este usuário administra o aplicativo, postando notícias, editando possíveis benefícios para os usuários, e editando anúncios de empresas parceiras, além de ter acesso a relatórios dos posts dos usuários.| Cliente |

####	3.3 Ambiente do Usuário:
 A aplicação é em forma de aplicação web, e será utilizada em escritório dentro da UnB, no DAF.

####	3.4 Perfis das Partes Interessadas: 

| Representante| Fernando|
|:-:|:-:|
|Descrição | Coordenador de contratos|
|Tipo| Especialista de negócios |
|Responsabilidades|Administra o aplicativo, postando notícias, analisando dados, e solucionando os problemas elencados por usuários|
|Critérios de Sucesso|Ter uma plataforma que facilite a administração e a manutenção dos contratos da faculdade|
|Envolvimento|PO|
|Entregas||
|Comentários ou Problemas||

| Representante|  |
|:-:|:-:|
|Descrição | Comunidade acadêmica|
|Tipo| Usuário casual |
|Responsabilidades| Fornece dados para o aplicativo|
|Critérios de Sucesso| Manutenção adequada da universidade |
|Envolvimento| Usuário do aplicativo |
|Entregas||
|Comentários ou Problemas| Não possui um representante real |

| Representante| Renata |
|:-:|:-:|
|Descrição | Responsável pelo hackathon, de qual o projeto foi vencedor|
|Tipo| Especialista em negócios |
|Responsabilidades| Fornece requisitos e informações para fazer a integração do sistema de gestão com o aplicativo|
|Critérios de Sucesso| Integração bem sucedida do sistema gerenciador com o projeto |
|Envolvimento| Integração do projeto |
|Entregas||
|Comentários ou Problemas||

| Representante| Bruno |
|:-:|:-:|
|Descrição | Equipe de desenvolvimento do aplicativo para celular|
|Tipo| Equipe de desenvolvimento |
|Responsabilidades| Trabalhará na parte do aplicativo para celular, que será gerenciado pelo sistema gerenciador, que é o objeto deste documento|
|Critérios de Sucesso| Integração bem sucedida do sistema gerenciador com o projeto |
|Envolvimento| Integração do projeto |
|Entregas| Interface para comunicação entre o aplicativo e o sistema gerenciador |
|Comentários ou Problemas||

| Representante| Carla |
|:-:|:-:|
|Descrição | Orientadora do projeto do aplicativo para smartphone|
|Tipo| Orientador |
|Responsabilidades| Orientará a equipe de desenvolvimento do aplicativo|
|Critérios de Sucesso| Integração bem sucedida do sistema gerenciador com o projeto |
|Envolvimento| Integração do projeto |
|Entregas| Interface para comunicação entre o aplicativo e o sistema gerenciador |
|Comentários ou Problemas||


| Representante| Hilmer |
|:-:|:-:|
|Descrição | Orientador do projeto do sistema gerenciador |
|Tipo| Orientador |
|Responsabilidades| Orientará a equipe de desenvolvimento sistema |
|Critérios de Sucesso| Aplicativo funcional e bem documentado, aplicando as metodologias de desenvolvimento de software |
|Envolvimento| Orientação |
|Entregas| Documentação |
|Comentários ou Problemas||

| Representante| Guilherme Aguiar, Mateus Augusto, Gabriel Filipe |
|:-:|:-:|
|Descrição | Equipe de desenvolvimento|
|Tipo| Desenvolvedor |
|Responsabilidades|Desenvolver o produto de software|
|Critérios de Sucesso|Atender à necessidade das partes interessadas|
|Envolvimento|Desenvolvimento e gestão do projeto|
|Entregas| Documentação |
|Comentários ou Problemas||

####	3.5 Perfis do Usuário

| Representante| Fernando|
|:-:|:-:|
|Descrição | Coordenador de contratos|
|Tipo| Usuário avançado |
|Responsabilidades|Administra o aplicativo, postando notícias, analisando dados, e solucionando os problemas elencados por usuários|
|Critérios de Sucesso|Ter uma plataforma que facilite a administração e a manutenção dos contratos da faculdade|
|Envolvimento|PO|
|Entregas||
|Comentários ou Problemas||

####	3.6 Principais Necessidades da Parte Interessada ou do Usuário:

|Necessidade|Prioridade|Interesses|Solução atual|Solução proposta|
|-|-|-|-|-|
| Monitorar problemas relacionados a UnB | 1 | Melhorar o monitoramento dos contratos | Monitoramento por servidores | Utilizar o aplicativo para ter uma melhor e mais ampla visualização dos dados |

 	 	 	 	 
####	3.7 Alternativas e Concorrência:
 A principal alternativa ao nosso produto, que é a alternativa utilizada atualmente, é a de dispor do trabalho de servidores para inspecionar a universidade procurando por defeitos na infraestrutura, ou quaisquer outras falhas no funcionamento da universidade. E além disso, dispor do feedback da comunidade acadêmica que se disponham a relatar problemas, diretamente para o decanato.

###	4: Visão Geral do Produto

####	4.1 Perspectiva do Produto:
 O produto possui aplicações semelhantes , de uma maneira análoga, de um relatório sobre o uso das funcionalidade de um aplicativo com o gerenciamento de informações do mesmo. O sistema gerenciador do Vamos Cuidar, é independente e auto contido.

####	4.2 Resumo das Capacidades:

|Benefício para o Cliente|Recursos de Suporte|
|-|-|
| Geração de relatórios sobre o uso das funcionalidades.| O usuário tem acesso e pode tirar informações adicionais sobre as funcionalidades, como por exemplo: número de posts, categorias, votos, metas e rankings.  	|
| Avaliação dos problemas citados.|  Ao receber a notificação de um problema, o gestor pode avaliar a situação, tendo a opção de modificar o estado da situação. 	|
| Criação de conteúdo informativo. | Com a criação de notícias tem-se a possibilidade de avisar os usuários do aplicativo mobile, informações referentes aos dados recebidos pelo sistema ou informações da própria rede da UnB	|
| Sistema de recompensa por postagens e avaliações 	| Com a colaboração de pessoas por meio do aplicativo, temos então a possibilidade de gerenciar recompensas fornecidas pela própria UnB ou empresas parceiras. |
| Gerenciamento de anúncios. | Após ter um firmamento com empresas parceiras, terá a criação de anúncios da mesma. Com isso, o usuário pode criar e deletar de uma forma fácil suas propagandas. |

</br>

####	4.3 Suposições e Dependências

 O sistema de gerenciamento do Vamos Cuidar, tem é independente sobre o aplicativo mobile, pois terá um API para as trocas de informações sendo que não prejudicará o funcionamento da mesma. Já a parte onde será disponibilizada o uso do sistema (Aplicação web) não necessita de um sistema de hardware robusto.

####	4.4 Custo e Precificação
  O custo único seria a localização onde o site será hospedado. 

####	4.5 Licenciamento e Instalação 
  Não há necessidade de instalação, pois a plataforma é uma aplicação web. Já temos como o licenciamento a GNU General Public License v3.0.

###	5: Recursos do Produto
Os recursos do produto são listados abaixo.
####	5.1 Sistema de Login.

O Sistema deve Permitir que o usuário seja capaz de efetuar login, comprovando sua identidade podendo realizar operações de acordo com sua permissão. Toda notícia deve possuir título, imagem, texto, autor, e tags.

####	5.2 CRUD de Notícias.

A aplicação deve permitir que o usuário seja capaz de criar, visualizar, ler e excluir notícias. Estas notícias estarão disponíveis para o público geral visualizar e reagir.

####	5.3 Gestão de Benefícios.

Os usuários do sistema de gestão devem ser capazes de criar e excluir benefícios. Os usuários do aplicativo comprarão estes benefícios atravez de ponto adiquiridos por participação e engajamento. Os benefícios devem possuir titulo, nome da empresa e custo de pontos.


####	5.4 Disponibilização de Relatórios.
Deve-se permitir que os usuários visualizem relatórios de quatro classes, listados abaixo
#####	5.4.1 Relatórios de Localização
Relatório com mapa de incidencia de posts por região.
#####	5.4.2 Relatórios de Metas
Os usuários devem visualizar como está a situação das metas estabelecidas, como meta de novos usuários e post resolvidos por periodo de tempo.
#####	5.4.3 Relatórios de Usuário
Estatística de Novos Usúarios por periodo de tempo.
#####	5.4.4 Relatórios de Posts
Os usuários do sistema devem conseguir visualizar com clareza as estatísticas dos posts, visualizando as categorias de posts com maior engajamento, post mais votados e números de post por local, por categoria, anonimos, recebidos, Por periodo e dados como esolvidos.

#### 5.5 Gerenciameto de Anúncios

O usuário deve ser capaz de criar e excluir anúncios que serão exibidos para os usuários do aplicativo.

###	6: Restrições
Observe todas as restrições de design, restrições externas, como requisitos operacionais ou regulamentares) ou outras dependências.

### 7: Referências

 Seção de referencias