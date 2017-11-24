# TAGS #

* `git tag -a v1.0 -m "Versão 1.0"`
(cria uma tag anotada (-a) do último commit)

* `git tag -a v1.0 (colar aqui chave do commit) -m "Versão 1.0"`
(cria tag anotada para um commit específico com base na chave)

* `git tag`
(lista tags)

* `git show v1.0`
(mostrar detalhes específicos sobre a tag)

* `git checkout v1.0`
(vai para versão v1.0 do projeto)

* `git checout master`
(volta para branch master)

* `git tag -d v1.0`
(deletar tag criada)

* `git push origin nomeDaTag`
(envia a tag especifica)

* `git push --tags`
(envia todas as tags) 

* `git pull`
(puxar as tags)

* `git tag -d nomeDaTag` + `git push origin :refs/tags/nomeDaTag`
(Para deletar a tag enviada pro remoto)
