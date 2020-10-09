## Histórico de Revisão

|Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 29/08/2020 | 0.1 | Correção na política de branch       |   Guilherme  |
| 02/09/2020 | 1.0 | Criação do documento de polílica de pull requests  | Gabriel Filipe |
| 02/09/2020 | 1.1 | Adiciona referências  | Gabriel Filipe |
| 03/09/2020 |   1.2   | Revisão | Mateus Augusto |
| 07/10/2020 | 1.3 | Concerta imagens  | Gabriel Filipe |

# Criação de _Pull Request_

Considere uma situação hipotética onde estamos querendo criar um PR de uma _branch_ chamada **Sprints** para a _master_.

#### Nota:

- A criação do PR deve ser feita logo após o início do trabalho em uma issue. Para isso trabalhamos com a flag de _status_ **WIP**.

## Para a criação de um _pull request_ direcionado a branch _master_, deve-se seguir os seguintes passos:


### 1) Adicione a flag de _status_

* Titule o PR com a tag **WIP** (ou seja _work in progress_) 

### 2) Adicione uma descrição

* Utilize o _template_ de _issue_ destinada ao _pull request_.
* Lembrando que o _pull request_ tem a _branch_ base a **_master_** e a _compare_ a branch que se deseja juntar.
* **Lembrando**: assim que for realmente finalizado as alterações referentes ao _pull request_, deve-se retirar a tag **WIP**.

[<img src="https://raw.githubusercontent.com/fga-eps-mds/2020.1-Grupo6/master/docs/policies/img/pr_template.png" width="500">](./img/pr_template.png)
 
### 3) Adicione os _reviewers_ 

* Assinale os _reviewers_, ou seja, aqueles responsáveis à análise do _pull request_. Por exemplo, caso sua _feature_ esteja relacionada a arquitetura do projeto, assinale o **EPS** que desempenha esse papel.

[<img src="https://raw.githubusercontent.com/fga-eps-mds/2020.1-Grupo6/master/docs/policies/img/pr_reviewers.png" width="300">](./img/pr_reviewers.png)


### 4) Adicione os _assignees_

* Assinale os colaboradores do _pull request_

[<img src="https://raw.githubusercontent.com/fga-eps-mds/2020.1-Grupo6/master/docs/policies/img/pr_assign.png" width="300">](./img/pr_assign.png)

### 5) Adicione as devidas _labels_

* Marque as _labels_ relacionadas ao _pull request_. Geralmente será as mesmas assinaladas na issue referente.

[<img src="https://raw.githubusercontent.com/fga-eps-mds/2020.1-Grupo6/master/docs/policies/img/pr_labels.png" width="300">](./img/pr_labels.png)

### 6) Adicione a devida _milestone_

* Marque a _Milestone_, ou seja, a _sprint_ ou _release_ atual.

[<img src="https://raw.githubusercontent.com/fga-eps-mds/2020.1-Grupo6/master/docs/policies/img/pr_milestone.png" width="300">](./img/pr_milestone.png)

### 7) Explicite a _issue_ relacionada ao PR

* Conecte a _issue_ trabalhada neste _pull request_ por meio de _closing keywords_.


| Issue a ser _linkada_ | Sintaxe | Examplo |
|:----------:|:------:|:--------------------:|
|Issue dentro deste repositório|KEYWORD #ISSUE-NUMBER|**Closes #10**|

#### Conflitos

* Se um pull request causar algum tipo de conflito, deve ser resolvido primeiro pela equipe que desenvolveu o que está causando conflito, prezando pela integridade e organização do histórico de commits, e então deve ser refeito o pedido para avaliação do merge.

### Política de Aprovação do Código

* Para a aprovação do código, este deve ser aprovado por ao menos um dos integrantes do time de gestão (_EPS_)

### Referências

* Lino. Disponível em <https://github.com/BotLino/Lino>

* Como fazer bons commits no Git, Ruan Brandão. Disponível em <https://ruanbrandao.com.br/2020/02/04/como-fazer-um-bom-commit/>

* Git branch naming conventions, Sanket. Disponível em <https://deepsource.io/blog/git-branch-naming-conventions/>
