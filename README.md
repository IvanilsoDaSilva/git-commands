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

<h2 align="right">1.4.3 BASIC</h2>

<!-- Create -->
📌 COPY A REMOTE REPOSITORY
```
git clone {remote repository link}
```

📌 SYNCHRONIZE THE LOCAL REPOSITORY TO THE REMOTE
```
git remote add origin {remote repository link}
```

📌 INITIATE GIT
```
git init
```

📌 ADD CHANGES FROM A LOCAL REPOSITORY
```
git add {path of the files to be added separated by space, or use "*" and also "." to add all changes}
```

📌 REMOVE CHANGES FROM A LOCAL REPOSITORY ✨
```
git reset HEAD {path of the files to be added separated by space, or use "*" and also "." to add all changes}
```

📌 PACK CHANGES FROM A LOCAL REPOSITORY INTO A COMMIT
```
git commit -m {commit description}
```

📌 ADD COAUTHOR ✨
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

📌 UPDATE REMOTE REPOSITORY FROM LOCAL REPOSITORY
```
git push
```

📌 UPDATE ALL REMOTE REPOSITORY FROM LOCAL REPOSITORY
```
git push --all
```

<!-- Read -->
📌 SHOW THE COMMIT HISTORY OF A REPOSITORY
```
git log
```

<!-- Update -->
📌 UPDATE LOCAL REPOSITORY FROM REMOTE REPOSITORY
```
git pull
```

<!-- Delete -->
📌 UNDO ALL CHANGES
```
git checkout .
```

<h2 align="right">1.4.3 BRANCHS</h2>

<!-- Create -->
📌 CREATE A LOCAL BRANCH
```
git checkout -b {branch name}
```

<!-- Read -->
📌 SHOW LOCAL REPOSITORY BRANCHES
```
git branch
```

📌 SHOW UNCOMMITTED CHANGES FROM A BRANCH ✨
```
git status
```

📌 SHOWS DETAILED INFORMATION ABOUT A BRANCH ✨
```
git show
```

<!-- Update -->
📌 SWITCH BETWEEN LOCAL BRANCHES
```
git checkout {branch name}
```

📌 RENAME A LOCAL BRANCH ✨
```
git branch -m {branch name} {branch name to rename}
```

📌 UPDATE LOCAL REPOSITORY BRANCHS FROM REMOTE REPOSITORY ✨
```
git fetch --prune --all
```

📌 BRING THE UPDATE FROM A COMMIT TO THE CURRENT BRANCH ✨
```
git cherry-pick {commit hash}
```

📌 UPDATES THE CURRENT BRANCH FROM ANOTHER BRANCH ✨
```
git merge {branch name}
```

<!-- Delete -->
📌 DELETE A REMOTE BRANCH
```
git push origin :{branch name}
```

📌 DELETE A LOCAL BRANCH
```
git branch -d :{branch name}
```

📌 DELETE A LOCAL BRANCH (FORCED)
```
git branch -D :{branch name}
```

<h2 align="right">1.4.3 OTHERS</h2>

<!-- Others -->
📌 SHOW GIT USER NAME ✨
```
git config user.name
```

📌 SHOW GIT USER EMAIL
```
git config user.email
```

📌 COPY A REMOTE REPOSITORY (EXACT COPY)
```
git clone --mirror {remote repository link}
```

📌 UPDATE LOCAL REPOSITORY FROM REMOTE REPOSITORY (EXACT COPY)
```
git push --mirror {remote repository link}
```

<h2 align="right">1.5. GIT WORKFLOW COMMANDS 💡</h2>
<p align="right">Use the following commands (if there are commands) by <kbd>CTRL</kbd>+<kbd>V</kbd> where necessary</p>

Gitflow is an alternative Git branching model that consists of using resource branches and several primary branches. It was first published and popularized by Vincent Driessen on nvie. Compared to trunk-based development, Gitflow has more long-lived branches and larger commits. Under this model, developers create a feature branch and delay the merge with the main trunk branch until the feature is complete.

<!-- Example img -->
<img width=100% src="https://ivanilsodasilva.github.io/git-commands/assets/gitflow-example.png"/>

📌 INITIATE GIT WORKFLOW
```
git flow init
```

📌 STARTS A NEW BRANCH (feature, bugfix, realese, hotfix, support) ✨
```
git flow {branch type} start {branch name}
```

📌 FINALIZE A BRANCH (feature, bugfix, realese, hotfix, support)
```
git flow {branch type} finish -m {merge description} {branch name}
```

📌 PUBLISHES THE BRANCH TO THE REMOTE REPOSITORY (feature, bugfix, realese, hotfix, support)
```
git flow {branch type} publish {branch name}
```

<h2 align="right">1.6. GIT SEMANTIC 💡</h2>

Semantic Git is an approach to code version control that aims to bring more meaning and structure to the changes made in a software development project. Unlike traditional versioning, where versions are just sequential numbers, Semantic Git uses a versioning system based on meaning and semantics.

The central idea of Semantic Git is to assign a clear meaning to the changes made to the code. This is achieved through the use of semantic versioning rules, which define a standard for version numbering based on the impact of the changes.

<!-- Example img -->
<img width=100% src="https://ivanilsodasilva.github.io/git-commands/assets/gitsemantic-example.png"/>

📌 STRUCTURE
```
{type}({scope: optional}): {commit description}
{body: optional}
{footer: optional}
```

📌 EXAMPLE
```
FEAT(api):Impedir a corrida de solicitações

Introduza um ID de solicitação e uma referência à solicitação mais recente. Demitir
respostas recebidas que não sejam da última solicitação.

Remova os tempos limite que foram usados para mitigar o problema de corrida, mas são
obsoletos agora.

Revisado por: Z
Referências: #123
```

📌 FEAT  
Indicates the addition of a new feature to the project. Use this prefix when the commit introduces a new capability or feature into the software.

📌 BUGFIX  
As the name implies, it's a BUG and needs to be fixed immediately, as soon as possible. In another article I'll explain more about the use of this guy and the main branches.

📌 HOTFIX  
Sometimes this term can be used in other ways, even in place of bugfix. However, I prefer to separate them, to leave them with different semantics. It's very similar to bugfix/, but it's not a BUG, it's a correction, whether it's to color, text, or not-so-urgent changes that don't mean BUGs.

📌 REFAC  
Used when there are changes to the code that do not add new functionality or fix bugs, but improve the structure, readability or efficiency of the existing code.

📌 CHORE  
This refers to tasks related to configuration adjustments, dependency updates, minor refactorings, etc. This prefix is used for commits that are not directly linked to features or bug fixes, such as adding a package to gitignore.

📌 DOC  
Indicates changes to the project documentation, such as README updates, code comments, examples, guides or any other form of documentation.

📌 TEST  
Used for test-related commits, such as adding or modifying unit tests, integration tests or automated tests in general.

📌 STYLE  
This refers to changes in formatting, spacing, indentation or any change related to the aesthetics of the code, without affecting its operation.

📌 REVERT  
Used to revert a previous commit, canceling the changes introduced by it.

📌 BUILD  
Indicates changes related to the build process, compilation or packaging of the project, such as build scripts, CI/CD configurations, or updates to build dependencies.

📌 INIT  
Used for the first commit of a project, marking the start of the Git repository.

<h2 align="right">1.7. OTHER REPOSITORIES 📘</h2>

<div>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=sistema-bancario-frontend&bg_color=FF00FF&title_color=FFFFFF&text_color=FFFFFF&icon_color=FFFFFF&border_color=FFFFFF"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=sistema-bancario-backend&bg_color=FFFFFF&title_color=FF00FF&text_color=FF00FF&icon_color=FF00FF&border_color=FF00FF"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=iff-bsi&bg_color=FFFFFF&title_color=FF00FF&text_color=FF00FF&icon_color=FF00FF&border_color=FF00FF"/>
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=IvanilsoDaSilva&repo=udemy-introducao-python&bg_color=FF00FF&title_color=FFFFFF&text_color=FFFFFF&icon_color=FFFFFF&border_color=FFFFFF"/>
</div>
<a href="https://github.com/IvanilsoDaSilva?tab=repositories">More...</a>

<h2 align="right">1.8. FONTS 📚</h2>
<a href="https://www.conventionalcommits.org/en/v1.0.0/">www.conventionalcommits.org</a>
<a href="https://blog.betrybe.com/git/git-flow/">www.betrybe.com</a>
<a href="https://www.linkedin.com/pulse/git-sem%C3%A2ntico-aumentando-efici%C3%AAncia-e-colabora%C3%A7%C3%A3o-marco-antonio/?originalSubdomain=pt">https://www.linkedin.com</a>

<!-- Animated img -->
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=FF00FF&height=120&section=footer"/>
