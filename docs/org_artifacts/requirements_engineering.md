#	Engenharia de Requisitos

## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|09/09/2020|   0.1    | Criação do Documento e Elicitação Adicionada        |   Guilherme  |


# Sumário
----------------
 1. [Introdução](#1)
2. [Elicitação](#2)
    * 2.1 [Brainstorm](#2_1)
    * 2.2 [Introspecção](#2_2)
3. [Requisitos](#3)

## 1. <a name="1"> Introdução</a>

<p align = "justify">A fase de levantamento de requisitos, em um projeto, representa a parte de negócio, ou seja, O QUE exatamente o cliente está precisando. Nessa fase, buscamos informações como: funcionalidades que o sistema deve ter, as regras de negócio dessas funcionalidades, restrições, usabilidade do software, e assim por diante. Neste documento vamos iniciar na fase de elicitação, modelagem e criação do backlog do produto.</p>

## 2. <a name="2"> Elicitação</a>

<p align = "justify"> O termo elicitar significa definir, tornar explicito, obter o máximo de informação sobre o objeto em questão. Nessa atividade precisamos ser cuidadosos, tudo é orientado à satisfação do cliente, então temos que aprender a entender o cliente, seu conhecimento e suas reais necessidades. O tripé da elicitação é identificação de fontes de informação, coleta de fatos e comunicação.</p>
<p align = "justify">As técnicas de elicitação empregadas pelo grupo foram brainstorming e instrospecção.</p>

### 2.1 <a name="2_1">Brainstorm</a>

<p align = "justify">Brainstorming é a técnica de elicitação de novas e velhas ideias sobre determinado dominio para gerar soluções e ou levantar requisitos sobre o assunto. O tema do Brainstorming foi o de visão geral das funcionalidades do projeto</p>

#### 2.1.1 Mapa Mental das funcionalidades do Vamos Cuidar

![mind_map](img/mind_map.png)

### 2.2 <a name="2_2">Instrospecção</a>

<p align = "justify">A instrospecção é uma técnica muito rica e profunda. Consiste em entender quais propriedades o sistema deve possuir para que seja um sucesso. Demanda o Engenheiro de Requisitos imaginar o que ele gostaria, se ele tivesse que desempenhar uma dada tarefa, com os equipamentos disponiveis e demais recursos.</p>
<p align = "justify">Decidimos fazer a instrospecção nos colocando no papel do funcionário do DAF que ficará responsável por analisar os relatórios do App do Vamos Cuidar e inserir noticias, gerencias anuncios e beneficios.</p>


## 3. <a name="3"> Requisitos</a>
### 3.1 Requisitos Funcionais
ID|Requisito
-|-
RF001| A aplicação deve permitir que o usuário efetue o login mediante suas credênciais.
RF002| A aplicação deve permitir que permitir que o usuário navegue por meio do meun lateral.
RF003| A aplicação deve permitir que o usuário visualize o relatório geral.
RF004| A aplicação deve permitir que o usuário visualize o relatório por área
RF005| A aplicação deve permitir que o usuário visualize o relatório por dia
RF006| A aplicação deve permitir que o usuário visualize o relatório por localização
RF007| A aplicação deve permitir que o usuário visualize o relatório geral
RF008| A aplicação deve permitir que o usuário visualize posts mais votados
RF009| A aplicação deve permitir que o usuário visualize categorias mais apoiadas
RF010| A aplicação deve permitir que o usuário visualize o número de posts por intervalos de tempo
RF011| A aplicação deve permitir que o usuário visualize os posts por localidade
RF012| A aplicação deve permitir que o usuário visualize os posts por categoria
RF013| A aplicação deve permitir que o usuário visualize os posts criados
RF014| A aplicação deve permitir que o usuário visualize os posts criados anonimamente
RF015| A aplicação deve permitir que o usuário visualize os posts resolvidos
RF016| A aplicação deve permitir que o usuário visualize o número de novos usuários
RF017| A aplicação deve permitir que o usuário visualize o status das metas
RF018| A aplicação deve permitir que o usuário visualize o uso do App por intervalos de tempo
RF019| A aplicação deve permitir que o usuário visualize os posts com ocorrências semelhantes
RF020| A aplicação deve permitir que o usuário crie notícias
RF021| A aplicação deve permitir que o usuário edite notícias
RF022| A aplicação deve permitir que o usuário delete notícias
RF023| A aplicação deve permitir que o usuário liste notícias
RF024| A aplicação deve permitir que o usuário crie benefícios
RF025| A aplicação deve permitir que o usuário delete benefícios
RF026| A aplicação deve permitir que o usuário crie anúncios
RF027| A aplicação deve permitir que o usuário delete anúncios
RF028| A aplicação tem que permitir que o usuário entre nela apenas se efetuar o login.
RF029| A aplicação tem que guardar as informações de login do usuário.
RF030| O usuário deve criar uma notícia com titulo, texto, imagem e tags.
RF031| O usuário deve criar um benefício com titulo, nome da empresa e custo de pontos.

</br>

### 3.1 Requisitos Não Funcionais
ID|Requisito
-|-
RNF001| A aplicação deve armazenar com segurança os dados cadastrais do usuário.
RNF002| A aplicação deve ter boa usabilidade e tempo rápido de resposta.