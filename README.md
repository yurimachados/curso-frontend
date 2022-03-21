# GIT
## Conceitos de versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O quê alterou 
 - Quando alterou 
 - Todos os arquivos
 - Evolução contínua

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2

 ## Instalação do Git

  - Linux (apt-get): sudo apt-get install git
  - Mac (brew): brew install git

 ## Criar conta Github

 ## Clonar o Projeto

 ## Commits
 Informação de alteração
  - após testado todo seu código
  - git add *
  - git commit -m "mensagem"
  - git push (enviar alterações para o repositório)
  - git pull (puxar/trazer alterações)

 ## GitFlow
 Fluxo do Git

### Branchs
São ramificações / versões paralelas

 - main / master (vai para produção, quando o projeto é publicado)
 - develop
 - DOD definition of done: critérios de aceite
 - versionamento 1.0.0

 git checkout -b dev (cria uma branch)
 git checkout master (mudar de branch)

### Merge
mescla de branch
Você pode precisar resover conflitos manualmente

git merge main

### Pull Requests
Mescla de branches no repositório
Permite code review

### configurar o GitFlow
git flow init
git flow feature start (nome-da-feature)
