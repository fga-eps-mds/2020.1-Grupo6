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
Para fornecer produtos e serviços que atendam às necessidades das partes interessadas e dos usuários, você deve identificar e envolver todas as partes interessadas como parte do processo de definição dos requisitos. Você deve também identificar os usuários do sistema e assegurar que a comunidade das partes interessadas os represente adequadamente.

Esta seção fornece um perfil das partes interessadas e usuários que estão envolvidos no projeto. Esta seção também identifica os principais problemas que as partes interessadas e os usuários consideram que a solução proposta deva tratar. Esta seção não descreve as solicitações ou requisitos específicos; um artefato separado de solicitações da parte interessada captura esses itens. A descrição do principal problema fornece o plano de fundo e a justificação para os requisitos.

####	3.1 Demográficos de Mercado:
 Resume os principais demográficos de mercado que motivam suas decisões sobre o produto. Descrevem e posicionam os segmentos do mercado alvo. Estime o tamanho e o crescimento do mercado usando o número de usuários potenciais. Como alternativa, estime a quantia de dinheiro que seus clientes gastam tentando atender às necessidades que seu produto ou aprimoramento preencheria. Revise as principais tendências do segmento de mercado e tecnologias. Responda estas questões estratégicas:
- Qual é a reputação de sua organização nesses mercados?
- O que você gostaria que a reputação fosse?
- Como esse produto ou serviço suporta seus objetivos?
####	3.2 Resumo da Parte Interessada:
 Lista todas as partes interessadas identificadas. Para cada tipo de parte interessada, forneça estas informações:
- Nome: Nome do tipo da parte interessada.
- Representa: Descreve brevemente quais pessoas, equipes ou organizações esse tipo de parte interessada representa.
- Função: Descreve brevemente a função que esse tipo de parte interessada desempenha no esforço de desenvolvimento.
####	3.3 Resumo do Usuário:
 Lista todos os tipos de usuários identificados. Para cada tipo de usuário, forneça estas informações:
- Nome: Nome do tipo de usuário
- Descrição: Descreve brevemente o relacionamento desse tipo de usuário com o sistema que está em desenvolvimento.
- Parte Interessada: Lista qual tipo de parte interessada representa esse tipo de usuário.
####	3.4 Ambiente do Usuário:
 Detalha o ambiente de trabalho do usuário alvo. Aqui estão algumas sugestões:
- Quantas pessoas estão envolvidas na conclusão da tarefa? Está sendo alterado?
- Quanto tempo leva um loop de tarefa? Quanto tempo os usuários gastam em cada atividade? Está sendo alterado?
- Quais restrições de ambiente exclusivas afetam o projeto? Por exemplo, os usuários requerem dispositivos remotos, trabalham externamente ou trabalham durante as viagens?
- Quais plataformas de sistema estão em uso atualmente? Existem plataformas futuras planejadas?
- Que outros aplicativos estão em uso? Seu aplicativo precisa se integrar a eles?
Nesta seção, você pode incluir extrações do modelo de negócio para descrever a tarefa e os trabalhadores envolvidos.
####	3.5 Perfis das Partes Interessadas: 
Descreve cada parte interessada no projeto, preenchendo a seguinte tabela para cada parte interessada. Lembre-se: os tipos de partes interessadas podem ser usuários, departamentos estratégicos, departamentos jurídicos ou de conformidade, desenvolvedores técnicos, equipes de operação, entre outros. Um perfil completo abrange os seguintes tópicos para cada tipo de parte interessada:

- Representante: Determina quem representa a parte interessada para o projeto (Essa informação será opcional se estiver documentada em algum outro lugar.) Insira os nomes dos representantes.
- Descrição: Descreve brevemente o tipo de parte interessada.
- Tipo: Qualifica o conhecimento da parte interessada, como "usuário avançado", "especialista em negócios", ou "usuário informal". Essa designação pode sugerir a experiência técnica e o grau de sofisticação.
- Responsabilidades: Lista as principais responsabilidades da parte interessada no sistema em desenvolvimento; lista seus interesses como uma parte interessada.
- Critérios de Sucesso: Determina como a parte interessada define o sucesso. Como a parte interessada é recompensada?
- Envolvimento - Descreve como a parte interessada está envolvida no projeto. Onde possível, relate o envolvimento nas funções do processo; por exemplo, uma parte interessada pode ser um revisor de requisitos.
- Entregas: Identifica as entregas adicionais que a parte interessada requer. Esses itens podem ser entregas do projeto ou saída a partir do sistema em desenvolvimento.
- Comentários ou Problemas: Determina os problemas que interferem com o sucesso e quaisquer outras informações relevantes.
####	3.6 Perfis do Usuário
 Descreve cada usuário do sistema aqui, preenchendo a seguinte tabela para cada tipo de usuário. Lembre-se que os tipos de usuário podem ser especialistas e novatos; por exemplo, um especialista pode precisar de uma ferramenta sofisticada e flexível com suporte para várias plataformas, enquanto um novato pode precisar de uma ferramenta que seja fácil de usar. Um perfil completo abrange esses tópicos para cada tipo de usuário:
- Representante: Indica quem representa o usuário para o projeto. (Essa informação será opcional se estiver documentada em algum outro lugar.) Esse representante, geralmente refere-se à parte interessada que representa o conjunto de usuários; por exemplo, Parte Interessada: Parte Interessada1.
- Descrição: Descreve brevemente o tipo de usuário.
- Tipo: Qualifica o conhecimento do usuário, como "usuário avançado" ou "usuário informal." Essa designação pode sugerir a experiência técnica e o grau de sofisticação.
- Responsabilidades: Lista as principais responsabilidades do usuário com respeito ao sistema; por exemplo, determina quem captura os detalhes do cliente, produz relatórios e coordena trabalho, etc.
- Critérios de Sucesso: Determina como o usuário define o sucesso. Como o usuário é recompensado?
- Envolvimento: Descreve como o usuário está envolvido no projeto. Onde possível, relate o envolvimento nas funções do processo; por exemplo, uma parte interessada pode ser um revisor de requisitos.
- Entregas: Identifica as entregas que o usuário produz e para quem.
- Comentários ou Problemas: Determina os problemas que interferem com o sucesso e quaisquer outras informações relevantes. Descreve as tendências que tornam a tarefa do usuário mais fácil ou mais difícil.
####	3.7 Principais Necessidades da Parte Interessada ou do Usuário:
 Lista os principais problemas com soluções existentes como observadas pela parte interessada. Esclarece estas questões para cada problema:
- Quais são os motivos para esse problema?
- Como o problema é resolvido agora?
- Quais soluções a parte interessada deseja?
Você deve entender a importância relativa que a parte interessada coloca na solução de cada problema. A classificação e técnicas de votos acumulativos indicam os problemas que devem ser resolvidos versus os problemas que as partes interessadas gostariam de tratar. Use esta tabela para capturar as necessidades da parte interessada.
Tabela 1. Necessidades da Parte Interessada

|Necessidade|Prioridade|Interesses|Solução atual|Solução proposta|
|-|-|-|-|-|
| | | | | |
 	 	 	 	 
####	3.8 Alternativas e Concorrência:
 Identifica as alternativas que a parte interessada percebe como disponíveis. Essas alternativas podem incluir a compra do produto de um concorrente, a criação de uma solução desenvolvida internamente ou manter o status quo. Listam todas as opções disponíveis e conhecidas. Elas incluem os principais pontos fortes e fracos de cada concorrente como observados pela parte interessada.

###	4: Visão Geral do Produto

####	4.1 Perspectiva do Produto:
 O produto possui aplicações semelhantes , de uma maneira análoga, de um relatório sobre o uso das funcionalidade de um aplicativo com o gerenciamento de informações do mesmo. O sistema gerenciador do Vamos Cuidar, é independente e auto contido.

####	4.2 Resumo das Capacidades:

|Benefício para o Cliente|Recursos de Suporte|
|-|-|
| Geração de relatórios sobre o uso das funcionalidades.| O usuário tem acesso e pode tirar informações adicionais sobre as funcionalidades, como por exemplo: número de posts, categorias, votos, metas e rankings.  	|
| Criação de conteúdo informativo. | Com a criação de notícias tem-se a possibilidade de avisar os usuários do aplicativo mobile, informações referentes aos dados recebidos pelo sistema ou informações da própria rede da UnB	|
| Sistema de recompensa por postagens e avaliações 	| Com a colaboração de pessoas por meio do aplicativo, temos então a possibilidade de gerenciar recompensas fornecidas pela própria UnB ou empresas parceiras. |
|Equipes de suporte distribuídas podem trabalhar juntas para resolver problemas.	|Com um servidor de replicação, as informações do banco de dados podem ser compartilhadas em toda a empresa.|
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