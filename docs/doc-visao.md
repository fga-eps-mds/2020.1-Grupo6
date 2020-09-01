#	A Estrutura de Tópicos do Documento de Visão

## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|20/03/2020|   0.1    | Criação do Documento        |   Hercules  |
|29/08/2020|   0.2   | Restruturação do Documento     |   Guilherme  |

## Sumário
[1. Introdução](#1-introducao) <br>
[2. Posicionando](#2-posicionando) <br>
[3. Descrições da Parte Interessada e do Usuário](#3-descricoes-da-parte-interessada-e-do-usuario) <br>
[4. Visão Geral do Produto](#4-visao-geral-do_produto) <br>
[5. Recursos do Produto](#5-recursos-do-produto) <br>
[6. Restrições](#6-restriçoes) <br>
[7. Faixas de Qualidade](#7-faixas-de-qualidade) <br>
[8. Precedência e Prioridade](#8-precedencia-e-prioridade) <br>
[9. Outros Requisitos do Produto](#9-outros-requisitos-do-produto) <br>
[10.  Requisitos de Documentação](#10-requisitos-de-documentacao) <br>
[11.  Referências](#11-referencias) <br>


###	1: Introdução
Esta introdução fornece uma visão geral de todo o documento de visão. Ela inclui o propósito, escopo, definições, acrônimos, abreviações, referências e visão geral de todo o documento.

####	1.1 Propósito:
 Determina o propósito deste documento de visão.

####	1.2 Escopo:
 Descreve brevemente o escopo deste documento de visão, incluindo a quais programas, projetos, aplicativos e processos de negócios o documento está associado. Inclui qualquer outra coisa que este documento afete ou influencie.

####	1.3 Definições, acrônimos e abreviações:
 Define todos os termos, acrônimos e abreviações necessários para interpretar a visão corretamente. Essas informações podem ser fornecidas por referência ao glossário do projeto, que pode ser desenvolvido online no repositório do RM.

####	1.4 Referências:
 Lista todos os documentos aos quais o documento de visão faz referência. Identifique cada documento por título, número de relatório (se aplicável), data e organização de publicação. Especifique as origens a partir das quais os leitores podem obter as referências; as origens estão disponíveis de maneira ideal no RM ou em outros repositórios online. Essas informações podem ser fornecidas por referência para um apêndice ou para outro documento.

####	1.5 Visão geral:
 Descreve o conteúdo do documento de visão e explica como o documento é organizado.

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
Esta seção fornece uma visualização de alto nível das capacidades do produto, interfaces para outros aplicativos e configurações dos sistemas. Esta seção, em geral, consiste em três subseções:
- Perspectiva do Produto
- Funções do Produto
- Suposições e Dependências
####	4.1 Perspectiva do Produto:
 Coloca o produto em perspectiva com respeito a outros produtos relacionados e ao ambiente do usuário. Se o produto for independente e totalmente autocontido, indique-o aqui. Se o produto for um componente de um sistema maior, relacione como esses sistemas interagem e identificam as interfaces relevantes entre os sistemas. Uma maneira de exibir os principais componentes do maior sistema, interconexões e interfaces externas é usar um processo de negócios ou diagrama de casos de uso.

####	4.2 Resumo das Capacidades:
 Resume os principais benefícios e recursos que o produto fornecerá. Por exemplo, um sistema de suporte ao cliente pode usar essa parte para endereçar a documentação do problema, o roteamento e o relato de status sem elaborar em detalhes o que essas funções requerem. Organize as funções de modo que a lista seja compreensível para o cliente ou para qualquer outra pessoa que leia o documento pela primeira vez. Uma simples tabela que lista os principais benefícios cujos recursos de suporte são suficientes, como no exemplo a seguir.
Tabela 2. Exemplo de Benefícios e Recursos

|Benefício para o Cliente|Recursos de Suporte|
|-|-|
|A nova equipe de suporte pode aprender rapidamente como usar o produto.|	A base de conhecimento ajuda a equipe de suporte a identificar rapidamente as correções e soluções alternativas conhecidas.|
|A satisfação do cliente é melhorada porque não há falhas.|	Os problemas são exclusivamente detalhados em itens, classificados e controlados em todo o processo de resolução. A notificação automática ocorre para quaisquer problemas anteriores.|
|O gerenciamento pode identificar as áreas com problema e calibrar a carga de trabalho da equipe.	|Os relatórios de tendência e distribuição permitem a revisão de alto nível do status do problema.|
|Equipes de suporte distribuídas podem trabalhar juntas para resolver problemas.	|Com um servidor de replicação, as informações do banco de dados podem ser compartilhadas em toda a empresa.|
|Os clientes podem se ajudar, reduzindo os custos de suporte e melhorando o tempo de resposta.|	A base de conhecimento pode ficar disponível na Internet. A base de conhecimento inclui recursos de pesquisa de hipertexto e um mecanismo de consulta gráfica.|
####	4.3 Suposições e Dependências
 Lista cada um dos fatores que afeta os recursos que o documento de visão inclui. Lista as suposições que, se modificadas, alterarão o documento de visão. Por exemplo, uma suposição pode indicar que um sistema operacional específico fique disponível para o hardware designado para o produto de software. Se o sistema operacional não estiver disponível, será necessário alterar o documento de visão.

####	4.4 Custo e Precificação
 Registra os impactos e restrições relevantes de custo e precificação. Por exemplo, os custos de distribuição (o número de CDs e CD principal) ou outras restrições de custo de mercadorias vendidas (manuais e embalagem) podem ser material para o sucesso dos projetos, ou irrelevantes, dependendo da natureza do aplicativo.

####	4.5 Licenciamento e Instalação 
- Os problemas de licenciamento e instalação também podem impactar diretamente o esforço de desenvolvimento. Por exemplo, a necessidade de suportar a serialização, a segurança da senha ou o licenciamento da rede criarão requisitos adicionais do sistema que devem ser considerados no esforço de desenvolvimento. Os requisitos de instalação também podem afetar a codificação ou criar a necessidade de separar o software de instalação.

###	5: Recursos do Produto
Lista e descreve brevemente os recursos do produto. Os recursos são capacidades de alto nível do sistema que são necessários para entregar benefícios aos usuários. Cada recurso é um serviço solicitado que, em geral, requer uma série de entradas para alcançar o resultado desejado. Por exemplo, um recurso de um sistema de rastreamento de problemas pode ser a capacidade de fornecer relatórios de tendências. À medida que o modelo de casos de uso toma forma, atualize a descrição para fazer referência aos casos de uso.

Como o documento de visão é revisado por uma ampla variedade de equipes envolvidas, mantenha o nível de detalhes gerais suficiente para que todos possam entender. No entanto, ofereça detalhes suficientes para fornecer à equipe as informações que ela precisa para criar um modelo de casos de uso ou outros documentos de design.

Para gerenciar a complexidade do aplicativo, para um novo sistema ou uma mudança incremental, liste os recursos em um alto nível para que você possa incluir aproximadamente 25 a 99 recursos. Esses recursos fornecem a base para a definição do produto, gerenciamento de escopo e gerenciamento do projeto. Cada recurso será expandido mais detalhadamente no modelo de casos de uso.

Em toda esta seção, torne cada recurso relevante para usuários, operadores ou outros sistemas externos. Inclua uma descrição de funções e problemas de usabilidade que devem ser tratados. As seguintes diretrizes se aplicam:
- Evite design. Mantenha as descrições do recurso em um nível geral. Foque nas capacidades necessárias e por que (não como) elas devem ser implementadas.
- Designe todos os recursos como requisitos de um tipo de recurso específico para fácil referência e rastreamento.
####	5.1 Recurso 1.

####	5.2 Recurso 2.

###	6: Restrições
Observe todas as restrições de design, restrições externas, como requisitos operacionais ou regulamentares) ou outras dependências.
###	7: Faixas de Qualidade
Defina as faixas de qualidade para desempenho, robustez, tolerância a falhas, usabilidade e características similares que o conjunto de recursos não descreve.
###	8: Precedência e Prioridade
Define a prioridade dos diferentes recursos do sistema.
###	9: Outros Requisitos do Produto
Em um alto nível, lista os padrões aplicáveis, os requisitos de hardware ou plataforma, os requisitos de desempenho e os requisitos ambientais.

####	9.1 Padrões Aplicáveis:
 Lista todos os padrões que o produto deve estar em conformidade. A lista pode incluir estes padrões:
- Padrões jurídicos e regulamentares (FDA, UCC)
- Padrões de comunicações (TCP/IP, ISDN)
- Padrões de conformidade da plataforma (Windows, UNIX, etc.)
- Padrões de qualidade e segurança (UL, ISO, CMM)
####	9.2 Requisitos do Sistema:
 Define os requisitos do sistema para o aplicativo. Eles incluem os sistemas operacionais do host suportados e as plataformas de rede, configurações, memória, dispositivos periféricos e software de parceiros.

####	9.3 Requisitos de Desempenho:
 Detalha os requisitos de desempenho. Os problemas de desempenho podem incluir itens como fatores de carga do usuário, largura de banda ou capacidade de comunicação, rendimento, exatidão, confiabilidade ou tempos de resposta em uma variedade de condições de carregamento.

####	9.4 Requisitos Ambientais:
 Detalha os requisitos ambientais conforme necessário. Para sistemas baseados em hardware, os problemas ambientais podem incluir temperatura, choque elétrico, umidade e radiação. Para aplicativos de software, os fatores ambientais podem incluir condições de uso, ambiente do usuário, disponibilidade do recurso, problemas de manutenção, manipulação de erros e recuperação.

###	10: Requisitos de Documentação
Esta seção descreve a documentação que deve ser desenvolvida para suportar a implementação bem sucedida do aplicativo.
####	10.1 Notas sobre a liberação, arquivo Leia-me:
 As notas sobre a liberação ou um arquivo Leia-me abreviado podem incluir uma seção "O que Há de Novo", uma discussão sobre problemas de compatibilidade com liberações anteriores, e alertas de instalação e atualização. O documento pode também conter ou vincular correções na liberação e quaisquer problemas ou soluções alternativas conhecidos.
####	10.2 Ajuda On-line:
 Muitos aplicativos fornecem um sistema de ajuda on-line para ajudar o usuário. A natureza desses sistemas é exclusiva para desenvolvimento de aplicativo, pois eles combinam aspectos de programação (centros de informações pesquisáveis e navegação do tipo Web) com aspectos de composição técnica (organização, apresentação). Muitas equipes consideram que o desenvolvimento do sistema de ajuda on-line é um projeto dentro de um projeto que se beneficia do gerenciamento de escopo e planejamento no início do projeto.
####	10.3 Guias de Instalação:
 Um documento que inclui instalação, configuração e instruções de atualização como parte da oferta de solução integral.
####	10.4 Rótulo e Embalagem:
 Uma aparência consistente começa com a embalagem do produto e se aplica aos menus de instalação, telas iniciais, sistemas de ajuda, caixas de diálogo de GUI e assim por diante. Esta seção define as necessidades e tipos de rótulos a serem incorporados no código. Os exemplos incluem copyright e avisos de patentes, logotipos corporativos, ícones padronizados e outros elementos gráficos.

### 11: Referências

 Seção de referencias