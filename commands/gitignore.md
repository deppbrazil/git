### Ignorar arquivos no controle do git ###

* criar um arq com extensão .gitignore e dentro dele colocar nome e extenção do arquivo que não quer ser controlado, ou ate mesmo uma pasta, sendo 1 por linha.

> Exemplo:
* Dentro do arq. do `.gitignore`
* Linha 1 = .gitignore `vai ignorar o próprio arq. .gitignore`
* Linha 2 = nomedoaquivo.txt `vai ignorar o arq. .txt`
* Linha 3 = `temp/` ou `.temp` ou `/temp` `isso oculta toda a pasta do controle de versão`