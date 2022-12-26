# Aprendendo a usar o Git 
* git init -> `Inicializa o repositório.`
* git add . -> `Adiciona os arquivos.`
* git status -> `Mostra os arquivos que serão commitados.`
* git commit -m "Titulo" -> `Mensagem do Commit.`
* git remote add origin "https://github.com/RafaelGustavoPierre/CursoGit.git" -> `Adiciona o link do repositório ao projeto Git.`
* git push -u origin master -> `Commita o código ao GitHub.`

# Atualizando o projeto no GitHub
* git add . -> `Adiciona os arquivos.`
* git status -> `Mostra os arquivos que serão commitados.`
* git commit -m "Titulo" -> `Mensagem do Commit.`
* git push origin (master/main) -> `Não precisa colocar o *remote* pois o remote é para fazer a conexão com o repositório Git.`

# Alterando a branch
* git checkout -b "Novo-botão" -> `Sai da branch atual, qualquer alteração será alterada somente na branch "Novo-botão".`
* git add 
* git commit -m "Novo Botão"
* git push origin Novo-botão
* git checkout NomeDaBranch -> `Altera a branch.`
* git merge Noto-botão -> `Uni os arquivos da branch Novo-botão <-> a branch selecionada.`

# Clonar um Repositório
* git clone "Link do Repositório" -> `Baixa o repositório.`
* git pull -> `Baixa as alterações que teve em um Commit do repositórios.`