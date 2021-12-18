# Git e GitHub Course
Repositório de anotações do curso de Git e GitHub do João Rubens Marchete Filho.


## 001 - O Básico do Git

### 001 - Introdução
- Git != GitHub!
- Git e GitHub trabalham juntos com o objetivo de versionar projetos.

### 002 - O que é o Git e o GitHub?
- O Git é um sistema de controle de versões (VCS).
- O GitHub é uma plataforma de hospedagem de projetos versionados com o Git.

### 003 - Instalar o Git é super fácil
- O site para baixar o Git é o [git-scm.com](https://git-scm.com).
- O site para baixar o VS Code é o [code.visualstudio.com](https://code.visualstudio.com).

### 004 - Início dos trabalhos
- `git init` inicializa um repositório git vazio em uma pasta chamada .git.
- `git config` é usado para realizar configurações de uso do git.
- `git config --system` é usado para alterar as configurações do git para todos os usuários do sistema.
- `git config --global` é usado para alterar as configurações do git para o usuário atual em todos os projetos do git.
- `git config --local` é usado para alterar as configurações do git apenas em um projeto especifico.
- `git config --global user.name felipesantoos` altera o nome do usuário que está usando o git.
- `git config --global user.email felipedssantos.dev@gmail.com` altera o e-mail do usuário que está usando o git.
- `git config --global -l` lista as configurações globais do git.
- `git config --global core.editor notepad` define o editor de texto padrão do Git como o notepad.

### 005 - Fluxo de trabalho
- Quando você digita `git init` na linha de comando dentro de uma pasta você vai estar indicando que o git vai controlar as alterações feitas naquela pasta e em suas subpastas.
- O estado de "untracked" é o estado de "não rastreado". Esse é o estado dos arquivos que você acabou de criar.
- O estado de "untracked" pode ser usado em arquivos que você não quer fazer o controle de versões.
- `git add` é o comando git que indica que você quer fazer o controle de versão de um arquivo.
- "Stage area" é o estado que vem após o "untracked".
- A stage area é onde os arquivos que você deseja rastrear estão esperando para receber um código de rastreamento. É tipo uma área de transferência. Como se você tivesse dado Ctrl + c e estivesse esperando dar o Ctrl + v.
- "Commited" é o estado que vem após a stage area.
- O estado "commited" é quando você "tira uma foto" dos arquivos que estavam na stage area e dá a elas um código de rastreamento que nos permite controlar as versões dos arquivos. Nesse ponto as alterações feitas no arquivos são gravadas como uma nova versão.
- O hashcode é o código de rastreamento dos arquivos controlados pelo git. É esse código que diferencia as versões dos seus arquivos.
- O estado "modified" é quando o seu arquivo já está sendo rastreado, mas sofreu alterações que ainda não passaram pelo commit.
![Screenshot from 2021-12-18 19-45-49](https://user-images.githubusercontent.com/49795183/146657431-df49e561-1412-42ec-8c47-cb739348444b.png)
