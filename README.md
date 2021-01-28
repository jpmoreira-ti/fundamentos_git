# fundamentos_git

# Utilizado o git hub para criacao do projeto e armazenamento dos arquivos
# https://github.com/jpmoreira-ti/fundamentos_git

# git config --global user.name "joao.moreira"
# git config --global user.email "jpmoreira.ti@gmail.com"

# git init (Define a configuracao inicial de um repositorio git na branch principal)
# git clone <respositorio git> (Clona o repositorio git para o repositorio local)

# git add . (Adiciona todos os arquivos do Working Directory (repositorio local) para a Staging Area (sala de espera))
# git commit -m "mensagem do commit" (Confirma as mudancas para o repositorio do git (repositorio remoto)) 
# git commit -a -m "mensagem do commit" (Pula a etapa de colocar na staging area)
# git commit --amend -m "mensagem do commit" (Edita os dados do commit atual)

# git status (Verifica o status dos arquivos no alterados no repositório local)
# git diff (Verifica os arquivos alterados no repositorio local e que nao estao na staging area)
# git diff --staged (Verifica os arquivos alterados que estao na staging area)

# git log (Mostra o log de todos os commits do projeto)
# git log -p (Mostra os commits de forma decrescente com a diff dos commits)
# git log --pretty=oneline (Mostra o log das alteracoes contendo apenas as informacoes de codigo do commit e mensagem)

# git reset HEAD <nome do arquivo> (Remove o arquivo da staging area)

# git checkout (Altera as branchs)
# git checkout -b (Cria a branch e altera para a nova branch)
# git checkout -- <nome do arquivo> (Volta o arquivo ao status original)

# git rm <nome do arquivo> (Remove os arquivos desejados)

# git tag (Mostra todas as tags criadas)
# git tag -a -m "mensagem da tag" (Cria uma tag anotada e inclui uma mensagem)

# git show <nome da tag> (Mostra informacoes adicionais da tag)

# git branch <nome da branch> (Cria uma branch nova a partir da master)
# git branch (lista as branchs criadas)
# git branch -d <nome da branch> (Deleta a branch)

# git merge <branch de origem> - (Mescla as alteracoes de arquivos da branch de origem para a branch atual)

# git push (Commita as alteracoes da staging area para o repositorio do git)

# git pull (Atualiza o respositorio local com as alteracoes que estao no repositorio do git)

# git fetch (Busca as ultimas atualizacoes do repositorio do git porem nao altera a branch atual)