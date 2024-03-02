<!-- Caracter Icon -->

──────▄▀▄─────▄▀▄  
─────▄█░░▀▀▀▀▀░░█▄  
─▄▄──█░░░░░░░░░░░█──▄▄  
█▄▄█─█░░▀░░┬░░▀░░█─█▄▄█

<!-- Animated img -->
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=FF00FF&height=120&section=header"/>

<!-- Animated text -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=FF00FF&size=35&center=true&width=290&lines=GIT;COMMANDS"/>
</div>

<h2 align="right">1.1. INTRODUCTION 📰</h2>

Welcome to the "git-commands" repository. Here, I aim to create a valuable resource for all beginner developers, who want to improve their skills in using Git, one of the most essential tools for version control.

<h2 align="right">1.2. DESCRIPTION 📝</h2>

This Git repository was created for the purpose of storing and documenting a collection of common Git commands. Here, you'll find a variety of commands frequently used during project development with Git, from basic operations to more advanced tasks.

<h2 align="right">1.3. TECHNOLOGIES 💻</h2>

<div style="display: inline_block">
  
  <!-- Cloud hosting and databases -->
  ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=FFFFFF&color=FF00FF)&nbsp; 
  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=FFFFFF&color=FF00FF)&nbsp;

  <!-- Languages -->

![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=FFFFFF&color=FF00FF)&nbsp;

  <!-- Frameworks -->

  <!-- Softwares -->

  <!-- Others -->

</div>

<h2 align="right">1.4. GIT COMMANDS 💡</h2>
<p align="right">Use the following commands (if there are commands) by <kbd>CTRL</kbd>+<kbd>V</kbd> where necessary</p>

📌 INITIATE GIT

```
git init
```

📌 COPY A REMOTE REPOSITORY ✨

```
git clone {remote repository link}
```

📌 ADD CHANGES FROM A LOCAL REPOSITORY ✨

```
git add {path of the files to be added separated by space, or use "*" and also "." to add all changes}
```

📌 REMOVE CHANGES FROM A LOCAL REPOSITORY ✨

```
git reset HEAD {path of the files to be added separated by space, or use "*" and also "." to add all changes}
```

📌 PACK CHANGES FROM A LOCAL REPOSITORY INTO A COMMIT ✨

```
git commit -m {description}
```

📌 UPDATE REMOTE REPOSITORY FROM LOCAL REPOSITORY ✨

```
git push --set-upstream {remote repository link} {remote branch name}
```

📌 UPDATE LOCAL REPOSITORY BRANCHS FROM REMOTE REPOSITORY ✨

```
git fetch --prune --all
```

📌 SHOW LOCAL REPOSITORY BRANCHES ✨

```
git branch
```

📌 SHOW REMOTE REPOSITORY BRANCHES

```
git branch -a
```

📌 SWITCH BETWEEN LOCAL BRANCHES ✨

```
git checkout {branch name}
```

📌 CREATE A LOCAL BRANCH ✨

```
git checkout -b {branch name}
```

📌 SHOWS DETAILED INFORMATION ABOUT A BRANCH

```
git show
```

📌 SHOW THE COMMIT HISTORY OF A REPOSITORY

```
git log
```

📌 SHOW UNCOMMITTED CHANGES FROM A BRANCH ✨

```
git status
```

📌 UPDATE LOCAL REPOSITORY FROM REMOTE REPOSITORY ✨

```
git pull
```

📌 DELETE A REMOTE BRANCH

```
git push origin :{branch name}
```

📌 DELETE A LOCAL BRANCH ✨

```
git branch -d :{branch name}
```

📌 DELETE A LOCAL BRANCH (FORCED)

```
git branch -D :{branch name}
```

📌 UNDO ALL CHANGES

```
git checkout .
```

📌 SHOW GIT USER NAME

```
git config user.name
```

📌 SHOW GIT USER EMAIL

```
git config user.email
```

📌 ADD COAUTHOR

```
git commit -m "Commit name.


Co-authored-by: {COAUTHOR NAME} <{COAUTHOR EMAIL}>
```

📌 UNDO THE LAST COMMIT (WITHOUT LOSING CHANGES) ✨

```
git reset --soft HEAD~{number of commits back}
```

📌 UNDO THE LAST COMMIT (LOSING CHANGES)

```
git reset --hard HEAD~{number of commits back}
```

📌 COPY A REMOTE REPOSITORY (EXACT COPY)

```
git clone --mirror {remote repository link}
```

📌 UPDATE LOCAL REPOSITORY FROM REMOTE REPOSITORY (EXACT COPY)

```
git push --mirror {remote repository link}
```

📌 BRING THE UPDATE FROM A COMMIT TO THE CURRENT BRANCH

```
git cherry-pick {commit hash}
```

<h2 align="right">1.5. GIT WORKFLOW COMMANDS 💡</h2>
<p align="right">Use the following commands (if there are commands) by <kbd>CTRL</kbd>+<kbd>V</kbd> where necessary</p>

O Gitflow é um modelo alternativo de ramificação do Git que consiste no uso de ramificações de recursos e várias ramificações primárias. Ele foi publicado pela primeira vez e popularizado por Vincent Driessen no nvie. Comparado ao desenvolvimento baseado em troncos, o Gitflow tem mais ramificações de vida longa e commits maiores. Sob este modelo, os desenvolvedores criam uma ramificação de recurso e retardam o merge com a ramificação de tronco principal até que o recurso esteja completo.

<!-- Example img -->
<img width=100% src="https://ivanilsodasilva.github.io/git-commands/assets/gitflow-example.png"/>

📌 INITIATE GIT WORKFLOW

```
git flow init
```

📌 STARTS A NEW BRANCH (feature, bugfix, realese, hotfix, support)

```
git flow {branch type} start {branch name}
```

📌 FINALIZE A BRANCH (feature, bugfix, realese, hotfix, support)

```
git flow {branch type} finish {branch name}
```

<h2 align="right">1.6. GIT SEMANTIC 💡</h2>

O Git Semântico é uma abordagem para controle de versão de código que visa trazer mais significado e estrutura para as alterações realizadas em um projeto de desenvolvimento de software. Ao contrário do versionamento tradicional, em que as versões são apenas números sequenciais, o Git Semântico utiliza um sistema de versionamento baseado em significado e semântica.

A ideia central do Git Semântico é atribuir um significado claro às alterações feitas no código. Isso é alcançado através da utilização de regras de versionamento semântico, que definem um padrão para a numeração das versões com base no impacto das alterações.

<!-- Example img -->
<img width=100% src="https://ivanilsodasilva.github.io/git-commands/assets/gitsemantic-example.png"/>

📌 FEAT

Indica a adição de uma nova funcionalidade ao projeto. Use este prefixo quando o commit introduzir uma nova capacidade ou recurso no software.

📌 BUGFIX

Como o próprio nome já diz, é um BUG e precisa ser corrigido de forma imediata, o quanto antes. Num outro artigo eu explico melhor a utilização desse cara e branches principais.

📌 HOTFIX

Às vezes esse termo pode ser usado de outras formas, até mesmo para usar no lugar do bugfix. Porém, eu prefiro separar, deixar com semânticas diferentes.  

Ele é bem similar ao bugfix/, porém, ele não é um BUG, mas sim uma correção, seja ela de cor, textos, alterações não tão urgentes, que não signifiquem BUG's.

📌 REFAC

Utilizado quando há alterações no código que não adicionam nova funcionalidade nem corrigem bugs, mas melhoram a estrutura, legibilidade ou eficiência do código existente.

📌 CHORE

Refere-se a tarefas relacionadas a ajustes de configuração, atualizações de dependências, refatorações menores, entre outros. Esse prefixo é usado para commits que não estão diretamente ligados a funcionalidades ou correções de bugs, como por exemplo adicionar um pacote no gitignore.

📌 DOCS

Indica alterações na documentação do projeto, como atualizações de README, comentários de código, exemplos, guias ou qualquer outra forma de documentação.

📌 TEST

Utilizado para commits relacionados a testes, como adição ou modificação de testes unitários, testes de integração ou testes automatizados em geral.

📌 STYLE

Refere-se a alterações de formatação, espaçamento, indentação ou qualquer mudança relacionada à estética do código, sem afetar seu funcionamento.

📌 REVERT

Utilizado para reverter um commit anterior, cancelando as alterações introduzidas por ele.

📌 BUILD

Indica alterações relacionadas ao processo de build, compilação ou empacotamento do projeto, como scripts de build, configurações de CI/CD, ou atualizações de dependências de build.

📌 INIT

Utilizado para o primeiro commit de um projeto, marcando o início do repositório Git.

<h2 align="right">1.7. OTHER REPOSITORIES 📘</h2>

<div>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=sistema-bancario-frontend&bg_color=FF00FF&title_color=FFFFFF&text_color=FFFFFF&icon_color=FFFFFF&border_color=FFFFFF"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=sistema-bancario-backend&bg_color=FFFFFF&title_color=FF00FF&text_color=FF00FF&icon_color=FF00FF&border_color=FF00FF"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=iff-bsi&bg_color=FFFFFF&title_color=FF00FF&text_color=FF00FF&icon_color=FF00FF&border_color=FF00FF"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=udemy-introducao-python&bg_color=FF00FF&title_color=FFFFFF&text_color=FFFFFF&icon_color=FFFFFF&border_color=FFFFFF"/>
</div>
<a href="https://github.com/IvanilsoDaSilva?tab=repositories">More...</a>

<!-- Animated img -->
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=FF00FF&height=120&section=footer"/>
