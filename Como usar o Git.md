# Como usar o Git

## Criar e verificar um repositório

* Para transformar qualquer diretório em um repositório GIT, o simples comando `git init <directory>`
* se você já tem um diretório e deseja verificar (clone-lo), você pode usar o comando git clone. Se você estiver tentando verificar um repositório local, use o seguinte comando: git clone /path/to/local/repository
* Se você pretende verificar um repositório armazenado remotamente, use: git clone user.name@host:/path/to/remote/repository

##  Comandos Add e Commit

* Para adicionar qualquer arquivo, o comando é: git add <nome_do_arquivo>
* Para "commitar" : git commit –m “Adicionar qualquer mensagem sobre o commit aqui”

## Dando continuidade com as mudanças

* Depois de confirmar as alterações, você pode usar o comando push: git push origin master.]
* um repositório existente ainda não tiver sido clonado e você pretende estabelecer uma ligação entre o seu repositório e um servidor remoto, execute o seguinte comando: git remote add origin <servidor>

## Branches

* Um novo *branch* pode ser criado usando o seguinte comando: git checkout -b feature_n *

* Se você deseja retornar ao *master* branch, o seguinte comando pode ser usado: git checkout master

* Qualquer *branch* pode ser excluído usando o seguinte comando: git checkout -b feature_n

* Para tornar o *branch* disponível para outros usuários, você terá que movê-lo para o repositório remoto. Para fazer isso, use o seguinte comando: git push origin feature_n

  