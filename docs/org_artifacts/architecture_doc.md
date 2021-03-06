# Documento de Arquitetura de Software

## Histórico de Revisão

| Data | Versão | Descrição | Autor(es) |
|:--------:|:--------:|:----------------------:|:------------------:|
| 14/09/2020 | 0.1 | Criação do Documento e Adição do template e do sumário | Guilherme Aguiar |
| 18/09/2020 | 0.2 | Criação da visão de casos de uso | Bruno Nunes |
| 21/09/2020 | 0.3 | Criação das Metas e Restrições Arquiteturais | Tomás Veloso |
| 14/12/2020 | 0.4 | Reestruturação Visão Lógica | Bruno e Hércules |

## Sumário

[1. Introdução](#1-introducao) <br>
[1.1 Objetivo](#11-objetivo) <br>
[1.2 Escopo](#12-escopo) <br>
[1.3 Definições, Acrônimos e Abreviações](#13-definicoes-acronimos-e-abreviacoes) <br>
[1.4 Referências](#14-referencias) <br>
[1.5 Visão Geral](#15-visao-geral) <br>
[2. Representação Arquitetural](#2-representacao-arquitetural) <br>
[2.1 Plataforma ReactJS](#21-plataforma-reactjs) <br>
[2.2 API](#22-api) <br>
[2.2.1 User](#221-user) <br>
[2.2.2 Resolution](#222-resolution) <br>
[2.2.3 Reports](#223-reports) <br>
[2.2.4 News](#224-news) <br>
[2.2.5 Benefits](#225-benefits) <br> 
[2.2.6 Adverts](#226-adverts) <br>
[2.3 Banco de Dados](#23-banco-de-dados) <br>
[3. Restrições e Metas Arquiteturais](#3-restricoes-e-metas-arquiteturais) <br>
[4. Visão Lógica](#4-Visão-Lógica) <br>
[4.2.1 Back-End](#421-back-end) <br>
[4.2.2 Front-End](#422-front-end) <br>
[4.3 Modelagem de dados](#43-modelagem-de-dados) <br>
[5. Visão de Implementação](#5-Visão-de-Implementação) <br>



## 1. Introdução

### 1.1 Objetivo

Este documento tem como finalidade fornecer uma visão arquitetural abrangente do sistema Vamos Cuidar Gestão, por meio de diversas visões arquiteturais para representar diferentes aspectos da aplicação. Com o propósito de demonstrar as decisões arquiteturais tomadas no desenvolvimento do Vamos Cuidar Gestão.

### 1.2 Escopo


### 1.3 Definições, Acrônimos e Abreviações

As Definições, Acrônimos e Abreviações para entendimento do documento são:

* UnB: Universidade de Brasília
* FGA: Faculdade do Gama - Campus da Universidade de Brasília
* API: Application Programming Interface (Interface de Programação de Aplicativos)
* REST: Representational State Transfer (Transferência de Estado Representacional)
* HTTP: Hypertext Transfer Protocol (Protocolo de Transferência de Hipertexto)
* IDE: Integrated Development Environment (Ambiente de Desenvolvimento Integrado)
* App: Application (Aplicativo)
* MVC: Model-View-Controller
* UC: Use Case (Caso de Uso)
* VCU: Vamos Cuidar Usuário: Plataforma desenvolvida pelo grupo de MDS da professora Carla, com a qual nossa aplicação irá se comunicar.
* VCG: Vamos Cuidar Gestão: A nossa plataforma

### 1.4 Referências

As referências aplicáveis são:

* [https://sce.uhcl.edu/helm/RationalUnifiedProcess/webtmpl/templates/a_and_d/rup_sad.htm#1.%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20Introduction](https://sce.uhcl.edu/helm/RationalUnifiedProcess/webtmpl/templates/a_and_d/rup_sad.htm#1.%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20Introduction)


* [https://ads-unigrade-2019-1.github.io/Wiki/dinamica06/DAS/](https://ads-unigrade-2019-1.github.io/Wiki/dinamica06/DAS/)

### 1.5 Visão Geral

Este documento visa detalhar as soluções arquiteturais desenvolvidas no sistema. Deste modo, neste documento serão abordados os seguintes aspectos:

* Representação Arquitetural
* Restrições e Metas Arquiteturais
* Visão de Casos de Uso
* Visão Lógica

## 2. Representação Arquitetural

[![architecture_diagram](img/architecture_diagram_3.jpg)](img/architecture_diagram_3.jpg)

O sistema é composto de três frentes:

* <p align='justify'>A frente da aplicação, será feita com em Javascript com a biblioteca **ReactJS**, que oferece ao usuário gestor as opções de interação com a plataforma feita da outra turma de MDS (VCU), tais como resolver uma postagem, relatórios sobre a plataforma e a criação de notícias e benefícios.</p>
* <p align='justify'> A frente das API's, também utilizaremos Javascript, mas no server usaremos o **NodeJS**. Baseando-se na arquitetura de microserviços, é composta por 5 serviços (pacotes), cada um com suas próprias responsabilidades e deveres. </p>
* <p align='justify'> A frente de dados, onde teremos um banco de dados **PostgreSQL**, hospedado na infraestrutura da Unb, onde serão persistidos os dados que iremos receber do VCU e onde iremos salvar os artefatos criados na nossa plataforma. Já no ambiente de desenvolvimento, usaremos o postgres localmente com o Docker. Para facilitar a criação das visualizações, optamos pela utilização da ferramenta Kibana.</p>



Cada frente possui sua própria arquitetura interna.

### 2.1 Plataforma ReactJS

[![reactjs](img/reactjs_1.png)](img/reactjs_1.png)


<p align='justify'> Em poucas palavras, o React é uma biblioteca JavaScript para criação de interfaces para o usuário, desenvolvida e mantida pelo Facebook, sua primeira release saiu em 2013. É  uma lib open-source com mais de 1k de colaboradores ativos no GitHub.</p>

<p align='justify'>Ela está presente no nosso dia-a-dia mais do que você imagina, em empresas grandes como Facebook, Instagram, AirBnB, NFL, Yahoo e muito mais. O mercado para essa biblioteca só cresce.</p>


### 2.2 API

[![architecture_diagram](img/architecture_diagram_2.jpg)](img/architecture_diagram_2.jpg)

Os microserviços da aplicação vão seguir o mesmo padrão, será usado o Nodejs para a lógica no back-end, seguindo a o padrão arquitetural MVC, onde a camada da View fica como o ReactJS. O padrão de organização dos elementos arquiteturais está representado no diagrama acima. 
f
### 2.3 Banco de dados

PostgreSQL é um sistema de banco de dados relacional de objeto de código aberto com mais de 30 anos de desenvolvimento ativo que lhe rendeu uma forte reputação de confiabilidade, robustez de recursos e desempenho. O banco é divido em schemas, cada microserviço irá interagir com um único esquema, o que contribui para a independência dos microserviços e a diminuição do acoplamento. A seguir serão representadas o diagrama dos esquemas.

## 3. Restrições e Metas Arquiteturais

<p align='justify'>A tomada de decisão pela arquitetura de pequena escala (software), foi tomada a partir da Engenharia de Requisitos conciliado com o levantamento de restrições para o desenvolvimento do software e o usuário de destino. Entretanto, existem restrições no funcionamento do software, restrições de design, operacionais e de compatibilidade. Sendo assim, para melhor atender os requisitos definidos e utilizar das melhores tecnologias disponíveis, foram selecionadas as metas e restrições de arquitetura.</p>

### 3.1 Metas

 A usabilidade da aplicação website, podendo ser acessada pelos navegadores modernos, terá interface de um dashboad para fácil entendimento de suas informações em dados visuais intuitivos. Por tanto, a eficiência do site será conceder os dados e suas informações de forma clara e rápida ao usuário, para que assim possa gerenciar e acompanhar os processos de forma imediata. Para que o usuário gestor cumpra o objetivo de visualizar os dados e operar suas informações de forma clara e simples, tendo como meta uma aplicação eficiente. A manutenibilidade do software será a capacidade de ser modificado para adequa-se a novos requisitos solicitados, para melhorias de funcionalidades ou incrementos de novas funções. Para a execução de suas funções de forma eficiente, as funcionalidades devem ser submetidas a testes, para verificação e validação do seu comportamento e assim possuir um produto de software eficiente e com qualidade.

### 3.2 Restrições

 As restrições de design estão relacionadas às ferramentas e tecnologias escolhidas para para o desenvolvimento do software. A elaboração do projeto, website, utilizando JavaScript, ReactJS, HTML, CSS, NodeJS, Docker e PostgreSQL. Existem restrições operacionais referentes à aplicação, o fato que a tecnologia desenvolvida para sua operação necessita da interação com um servidor de hospedagem disponibilizado por terceiros. A tecnologia será desenvolvida em parceria com outro desenvolvimento de software, portanto, o software deve está de acordo com outro projeto para consumir seus dados e gerá-los no site, em que a interação entre as tecnologias funcionem corretamente, sem problemas de compatibilidade entre elas.


## 4. Visão Lógica

### 4.1 Visão Geral

Mostra a seguir a hierarquia dos pacotes, onde tem-se a decomposição do back-end, e juntamente o front-end. Em conjunto, a distribuição dos microserviços.

### 4.2 Diagrama de pacotes
#### 4.2.1 Back-End

Para o back end, cada microserviço tem sua visão geral composta de quatro pacotes:

[![nodejs_package](img/nodejs_package.jpg)](img/nodejs_package.jpg)


* Controller <br>
Possui classes que são responsáveis pela execução de código que prepara os dados para sua exibição no React, também são responsáveis por controlar as chamadas à API e despachar o resultado para o local adequado, seja o React que esteja aguardando ou outros objetivos.
* Models <br>
Classes que fazem representação dos dados que o aplicativo deve persistir localmente, como os dados das postagens a aplicação deve listar. Essas classes também contém algumas operações específicas aos seus objetos.
* Routes <br>
A camada de roteamento define a maneira como as solicitações do cliente são tratadas pelos endpoints do aplicativo.
* Test <br>
Pacote da aplicação onde são realizados os testes unitários da lógica da aplicação (controllers) e da estrutura da model.


#### 4.2.2 Front-End

Para o front end, cada microserviço tem sua visão geral composta de quatro pacotes:

[![reactjs_package](img/reactjs_package.jpg)](img/reactjs_package.jpg)


* Public <br>
É onde residem seus arquivos estáticos. Se o arquivo não for importado por seu aplicativo JavaScript e precisar manter seu nome de arquivo, coloque-o aqui.
* Assets <br>
Na pasta assets ficam as dependências compartilhadas por seu aplicativo - como mixins SASS, imagens, etc. - podem ir para o diretório.
* Components <br>
A pasta onde ficam os componentes únicos do react. 
* Pages <br>
A pasta pages possuem componentes constituidos por vários componentes, que forman as páginas finais que são exibidas.
* Utils <br>
Esta é uma pasta cheia de funções auxiliares que são usadas globalmente. Mantenha seu código DRY (Don Don't Repeat Yourself) exportando a lógica repetida para um único local e importando-o onde for usado.

### 4.3 Modelagem de dados

[![DiagramaClasse](img/ClassDiagram.png)](img/ClassDiagram.png)

## 5. Visão de Implantação

