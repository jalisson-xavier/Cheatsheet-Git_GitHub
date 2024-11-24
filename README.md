# **Cheatsheets - Com Dicas Rápidas para Uso do Git e GitHub**

Bem-vindo ao repositório de Cheatsheets! Aqui você encontrará uma coleção de dicas rápidas e úteis para o uso do Git e GitHub, ideal para desenvolvedores que desejam aumentar sua produtividade.


## 📒Introdução

Este repositório contém uma série de cheatsheets para ajudar desenvolvedores a trabalharem de maneira eficiente com Git e GitHub. A ideia é fornecer comandos e dicas rápidas para facilitar o uso dessas ferramentas.


## ⚙️Configurações Iniciais

```
git config --global user.name "Seu Nome"	# Definição de usuário global
git config --global user.email "seuemail@example.com"	# Definição de conta global
```

## 🛠️Comandos Básicos

```
git init	# Inicializa um repositório Git
git clone <url>	# Clona um repositório remoto
git status	# Mostra o status dos arquivos no repositório
git add <arquivo>	# Adiciona um arquivo ao índice
git commit -m "mensagem"	# Comita as mudanças com uma mensagem
git push	# Envia os commits para um repositório remoto
git pull	# Atualiza o repositório local com mudanças do remoto
git log	# Exibe o histórico de commits 
```

## 🗂️Trabalhando com Branches

```
git branch	# Lista todas as branches
git branch <nome>	# Cria uma nova branch
git checkout <nome>	# Muda para a branch especificada
git merge <nome>	# Faz o merge da branch especificada na branch atual
git branch -d <nome>	# Deleta a branch especificada
```

## ♻️Revertendo Mudanças

```
git reset --hard 	# Reseta o índice e a árvore de trabalho para o último commit
git revert <commit>	# Cria um novo commit que reverte as mudanças do commit especificado
```

## 📒Convenção de Commits 

| Tipo de Commit |Descrição                                                          	| Exemplo								|
| ---------------|----------------------------------------------------------------------|---------------------------------------|
| `feat`         | Adiciona uma nova funcionalidade ao projeto.                         | `feat: add USENAME.md profile`        |
| `fix`          | Corrige um bug ou problema no projeto.                               | `fix: fixed issue fix#IssueNumber`    |
| `docs`         | Altera a documentação do projeto.									| `docs: update README.md`              |
| `style`        | Realiza mudanças na aparência, sem alterar a funcionalidade.         | `style: add EFFECTNAME to COMPONENT`  |
| `refactor`     | Realiza mudanças no código que não alteram a funcionalidade.         | `refactor: refactor at CLASSNAME`     |
| `test`         | Adiciona ou modifica testes no projeto.                              | `test: add unit test for UserService` |

## 🤝Colaborando no Git

```
git fork	# Cria uma cópia do repositório em sua conta do GitHub
git pull request	# Solicita a incorporação de mudanças no repositório original
git issues	# Reporta problemas ou solicitações de funcionalidade
```

## 🔗Links e repositórios úteis

[Git SCM](https://git-scm.com)
[Git Docs](https://docs.github.com)
[Git Blog](https://github.blog)
[Readme](https://readme.so/)



### 🔎Onde me encontrar
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=0E76A8)](https://www.linkedin.com/in/jalisson-xavier/)
[![Github](https://img.shields.io/badge/Github-000?style=for-the-badge&logo=github)](https://github.com/jalisson-xavier)

