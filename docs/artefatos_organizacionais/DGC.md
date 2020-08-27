# Documento de Gestão e Configuração de Software

## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
|27/08/2020|   0.1    | Criação do Documento        |   Guilherme  |

## Sumário

[1. Introdução](#1-introducao)

[2. Itens de Configuração](#2-itens-de-configuracao)

[3. Políticas](#3-politicas)

[4. Uso de Issues](#4-uso-de-issues)

[5. Repositório de Documentação](#5-repositorio-de-documentacao)

[6. Referências](#6-referencias)

## 1. Introdução

* <p align = "justify">O documento tem como finalidade mostrar quais são procedimentos para contribuir com o repositório, visando instruir sobre o ambiente de desenvolvimento e qualquer atividade de configuração necessária.</p>

## 2. Itens de Configuração

Serão tratados como itens de configuração para este projeto o código e a documentação que o acompanha. Descrimina-se abaixo os itens de configuração para os quais faremos a manutenção e gerenciamento.

* Documento: Arquivo de texto contendo planejamentos, descrição do produto e projeto, relatos de reunião ou do fluxo de projeto.
* Código: Artefato composto por um conjunto de arquivos de texto, contendo código de uma ou mais linguagens de programação ou marcação.

## 3. Políticas

### 3.1 Política de Commits

* <p align = "justify">Os commits devem ser criados após alterações relevantes feitas em relação ao material original e devem ser descritos forma sucinta e atômica. O texto deve descrever o que foi produzido, de forma resumida e em português, com o tempo verbal no particípio. Como no seguinte formato:

   ```<Texto começando com letra maiúscula e com o verbo no particípio>.```

* Exemplo:

   ```Criado estrutura de login```

</p>

* Commits devem ser redigidos no idioma inglês
* Devem ser simples e concisos, possuindo títulos curtos
* Commits devem descrever o que está sendo alterado, se houver mais de uma alteração (pertinente ao commit) ela deve ser adicionada na descrição do commit
* Devem iniciar com letras maiúsculas.
* Devem iniciar com um verbo no particípio informando seu objetivo. Ex: "Created new main page"

### 3.2 Política de Branches

<br>

[![PoliticaBranchs.png](img/branches.png)](img/branches.png)

<br>

* <p align = "justify">O repositório do projeto terá uma branch principal, sendo ela a branch estável, a <i>Master</i>.</p>

* <p align = "justify">A <i>Master</i> será a branch estável do projeto, sendo ela proveniente da develop quando o pull request for aprovado, ao fim de cada release ou quando houver necessidade. Nenhum membro será autorizado a fazer commits diretamente na <i>Master</i>.</p>

* <p align = "justify">As branches auxiliares são para a criação das funcionalidades ou correções de erro. Cada issue de feature terá sua própria branch, criada a partir da develop, e terá como nomenclatura o seguinte padrão: </p>

   ```[ID da Issue]-[Nome representativo da Issue] ou``` <br>
   ```fix-[ID da issue a ser resolvida]-[Nome representativo da issue] ``` <br>


* As branches develop e master têm papel importante no fluxo seguido. Portanto, nenhuma dessas deve receber um commit diretamente pelo time de desenvolvimento de nenhuma Feature ou Correção.

* Para cada Feature uma nova branch deve ser criada com base no último commit da develop. De acordo com o modelo acima.
  
* Para branches de Correção de algum defeito ou configuração de ferramentas, estas deverão estar de acordo com o modelo acima.

#### 3.2.1 Conflitos

Se um pull request causar algum tipo de conflito, deve ser resolvido primeiro pela equipe que desenvolveu o que está causando conflito, prezando pela integridade e organização do histórico de commits, e então deve ser refeito o pedido para avaliação do merge.

### 3.3 Política de Aprovação do Código

* <p align = "justify"> Para a aprovação do código, este deve ser aprovado por ao menos um dos integrantes do time de EPS</p>

## 4. Uso de Issues

* <p align = "justify">As issues serão criadas com o objetivo de mapear as histórias de usuário, histórias técnicas e bugs, tendo assim um maior controle sobre eles. Com isso, conseguiremos manter o rastro dos commits com suas respectivas issues.</p>


## 5. Repositório de documentação

O repositório de documentação é encontrado na [wiki](#https://fga-eps-mds.github.io/2020.1-Grupo6/) do projeto. Seu objetivo é armazenar a documentação proveniente do projeto, bem como, as práticas adotadas pela equipe de desenvolvimento. Este repositório segue especificações semelhantes ao repositório de código. Os commits devem seguir o mesmo padrão. Porém, os documentos devem ser mantidos na branch master e não há instruções a respeito da criações de novas branches.

## 6. Referências

* QueroCultura. Plano de Gerenciamento de Configuração. Disponível em <https://github.com/fga-eps-mds/2017.2-QueroCultura/wiki/Plano-de-Gerenciamento-de-Configura%C3%A7%C3%A3o>

* UniGrade. Plano de Gestão e Configuração de Software. Disponível em <https://ads-unigrade-2019-1.github.io/Wiki/dinamica02/GCS/>

* Como fazer bons commits no Git, Ruan Brandão. Disponível em <https://ruanbrandao.com.br/2020/02/04/como-fazer-um-bom-commit/>

* Git branch naming conventions, Sanket. Disponível em <https://deepsource.io/blog/git-branch-naming-conventions/>