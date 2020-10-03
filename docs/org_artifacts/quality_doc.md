#	Termo de Abertura do Projeto

## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|03/10/2020|   0.1    | Criação do Documento        |   Guilherme  |

## Sumário
[1. Objetivo](#1-Objetivo) <br>
[2. Planejamento](#2-planejamento) <br>
[3. Testes Unitários](#3-testes-unitarios) <br>
[4. Testes Estáticos](#4-testes-estaticos)<br>
[5. Testes de Usabilidade](#5-testes-de-usabilidade) <br>

###	1. Objetivo
<p align = "justify"> Este documento objetiva explicitar os critérios, ferramentas e o planejamento da qualidade de código do projeto, esclarecendo o como, quais e porquês das adoções de cada tipo de teste durante o desenvolvimento do produto.</p>

###	2. Planejamento
<p align = "justify"> Visando uma boa qualidade de código do projeto, alguns padrões de qualidade de corpos de conhecimentos e de normas foram definidos, tanto quanto as ferramentas que serão utilizadas para monitorar essa qualidade. Neste contexto, a qualidade será afirmada atravéz da aplicação de testes unitários, testes estáticos e testes de usabilidade.</p>

### 3. Testes Unitários
 <p align = "justify"> A aplicação de testes unitários se dá por meio da implementação de testes da menor parte testável de um programa.</p>

### 4. Testes Estáticos
 <p align = "justify">A análise estática de softwares, também conhecida como whitebox, trabalha diretamente com o código. Nesse caso, os componentes são verificados sem que o produto seja executado. No **Vamos Cuidar: Gestor** **foram** usadas ferramentas automatizadas no qual o principal objetivo dessa técnica é identificar erros de programação como práticas ruins, erros de sintaxe, identação entre outros. As ferramentas utilizadas são o  Codacy e o CodeClimate.</p>

### 4.1 Codacy

[![codady](img/codacy.png)](img/codacy.png)

 <p align = "justify">O Codacy permite que as organizações assumam o controle de sua qualidade de código, incorporando cobertura de teste totalmente configurável e dados de manutenção em todo o fluxo de trabalho de desenvolvimento.</p>
<p align = "justify">É partir do Codacy que são afirmados e monitorados os padrões de folha de estilo do projeto. Para o código em Javascript utilizamos os padrões do linter ESLint 7.10.0 tanto no frontend (ReactJS), como no backend (NodeJS). No frontend também utilizamos o CSSLint 1.0.5 para arquivos css. </p>

### 4.2 Code Climate

[![code_climate](img/code_climate.png)](img/code_climate.png)

 <p align = "justify">O Code Climate ajuda sua equipe a fazer um código melhor e mais rápido, incorporando análise estática totalmente configurável e dados de cobertura de teste em seu fluxo de trabalho de desenvolvimento.</p>
 <p align = "justify">O code climate é oferece á equipe, no escopo de frontend e backend, o poder de identificar métricas de manutenabilidade, duplicação de código, complexidade clicomática entre outras.  </p>

### 5. Testes de Usabilidade
 <p align = "justify">O cumprimento de testes de usabilidade baseia-se na aplicação da técnica de validação utilizada para avaliar um produto ou serviço. Os testes são realizados com usuários representativos do público-alvo. No caso da plataforma **Vamos Cuidar: Gestor**, os testes são feitos com o funcionário do DAF da UnB.</p>


