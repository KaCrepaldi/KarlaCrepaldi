Curso Front-End

# GIT
## versinamento
- Histórico
- Controle de versão
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Istalação do Git
https://git-scm.com/

 Windows: https://git-scm.com/download/win
Linux (apt-get): sudo apt-get install git
Mac (brew): brew install git

## Criar conta no GitHub

## Clonar o projeto

## Commits
Informação de alteração
- após testado todo seu código
- git add*
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
- git pull (puxar / trazer alterações do GitHub para sua máquina)


## Gitflow
Fluxo do Git


...

### Branchs
 são ramificações / versões paralelas

 - main / master (vai para proudção, quando o projeto é publicado)
 - develop 
 - DDD definition of Done: critérios de aceite
 - versionamento 1.0.0

 git checkout -b dev (cria uma branch)
 git checkout master (mudar de branch)

...

### Merge
Mescla de branchs
Você pode precisa resolver conflitos manualmente

git merge main
...

### Pull Request
Mescla de branchs no repositório 
Permite code review
O repositório resolve os conflitos automaticamente

...

### configura o GitFlow
git flow init
git flow feature start{nome-da-facture}



## Commits
Informação de alteração
- após testado todo seu código 

