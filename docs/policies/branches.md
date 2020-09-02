## Histórico de Revisão

|   Data   |  Versão  |        Descrição       |          Autor(es)          |
|:--------:|:--------:|:----------------------:|:---------------------------:|
| 27/08/2020 |   0.1   | Criação do Documento            |   Guilherme  |
| 29/08/2020 |   0.2   | Correção na política de branch  |   Guilherme  |
| 02/09/2020 |   1.0   | Aprimoramento da política de branches | Gabriel Filipe |

# Criação de _Branches_

<br>

[![BranchPolicy.png](img/branches.png)](img/branches.png)

<br>

* <p align = "justify">O repositório do projeto terá uma branch principal e estável, a <i>master</i>. Ela será proveniente de um outra, a <i>devel</i>.</p>

* Nenhum integrante dos times (<i>EPS/MDS</i>.) é autorizado a fazer commits diretamente na <i>master</i>.

* Nenhum integrante do time de desenvolvimento (<i>MDS</i>.) é autorizado a fazer commits diretamente na <i>devel</i>.

* Os PRs passaram por revisões pelos integrantes do time de gestão (<i>EPS</i>) e, ao fim de cada release, ou em casos excepcionais, serão aceitos pelos mesmos.

* Deve-se ser criada uma nova branch para cada nova <i>feature, correção ou falha</i> a partir da branch <i>devel</i>. 

## Para a criação de _branches_ siga os passos e exemplos a seguir:


* O nome da _branch_ (NomeDaBranch) deverá ser uma abstração do nome da história de usuário (_US_), técnica (_TS_) ou correção (_HF_) a qual se refere.

* Caso não tenha _tag_.
```
NomeDaBranch
```

* Caso tenha _tag_, ela será o número da _issue_ a qual a se refere a história de usuário (_US_), técnica (_TS_) ou correção (_HF_) .
```
Numero_da_issue-NomeDaBranch
```

* O NomeDaBranch deverá ser escrito seguindo o padrão CamelCase
```
Numero_da_issue-NomeDaBranch
```

### Exemplo prático
* Sem _tag_
```
OurPolicies
```

* Com _tag_
```
Issue_01-CamelCase
```