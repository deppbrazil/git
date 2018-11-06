# REPOSITÓRIOS REMOTOS #

* `git remote` (lista repositórios adicionados)
* `git remote -v` (lista seus remotos e seus caminhos para `fetch` e `push`)
> Por padrao ele ira retornar origin, pois é o repositório de origem
* `git push origin master` ou `git push` (envia seu projeto da branch master ao repositorio remoto principal)
* `git pull origin master` ou `git pull` (puxa atualizações do remoto principal)
* `git push [apelido do repo]` ou `git pull [apelido do repo]` (envia e puxa do repo especifico)
* `git remote rename origin [novo nome]` (renomeia o orign)
* `git remote add [apelido do repo] [link ssh]` (adicioando repositório)
* `git fetch origin branch + [o nome da branch]` (com isso ele puxa do repositório remoto e joga dentro da branch)
> Se caso precisarmos mudar o nome da pasta raiz do projeto no repositório do Gihutb e local para eliminarmos os conflitos teremos que remover o `origin` com `rm` e adiciona-lo novamente com o novo link ssh: 
* `git remote rm origin`
* `git remote add origin [link ssh]`
> Em seguida aparece segestões como `git rebase --edit-todo` para ver e editar ou `git rebase --continue` para arrumar todos os conflitos, então: 
* `git rebase --continue`
> Você vai notar que agora o readme.md está fazendo comparações com um possível conflito, pelo menos no meu caso aconteceu isso, então elimine o que não é mais util e edite o readme.md como quiser, em seguida de um `git add .` e depois o commit e pronto agora os `push` vão sem erro =D
> Se quando você der o `git status` e aparecer uma mensagem que você ainda precisa dar o rebase ou edit todo, como você já deu o push e os arquivos já foram pro remoto, delete a pasta raiz local e cole ela denovo com `git clone [link do repo]` e já é ;)