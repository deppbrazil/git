# ATUALIZANDO SEUS FORKS # 

## Peguei como referência o [blog](https://www.raphaelfabeni.com.br/updating-your-fork/) maravilhoso do [Raphael Fabeni](https://www.raphaelfabeni.com.br/) ##

* `git remote add upsteam [link do repositório original]` (isso vai add um remoto de upstream)
* `git fetch upstream` (vai atualizar o upstream)
* `git merge upstream/master master` (vai dar o merge com seu ramo master local)
* `git push origin master` (para atualizar seu repositório do Github com seu projeto local e repositório original do autor)