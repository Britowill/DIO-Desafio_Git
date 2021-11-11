# Git e Github

## Introdução

​	O Git foi criado por Linus Torvalds, para o controle de versões do kernel do Linux e hoje é o versionador mais usado do mercado! 

​	[Git](https://git-scm.com/) é um sistema de versionamento que foi projetado com foco em versionamento de código. Basicamente, nos ajuda a lidar com a modificação de arquivos de uma maneira fácil.

​	Github, por outro lado, é uma empresa que implementou um sistema que permite que você use git para criar uma versão de seu código enquanto o armazena em sua nuvem. O Github, no entanto, não é a única empresa. Bitbucket e Gitlab são outros exemplos de empresas que possuem sistemas que permitem armazenamento e interação de grupo enquanto você pode fazer tudo usando git!

## Lista de Comandos

##### Git Init

Inicializar do projeto, informa ao projeto a inicialização da linha do tempo,criando também a conexão com um repositório.

##### Git Add

Adicionar um arquivo ao projeto, criando um ponto na história com esse evento.

##### Git Commit

Responsável por levar a minha alteração no ponto da história, usualmente utilizado com ‘’ -m ‘’ para adicionar uma mensagem ao git add que você colocou na linha de comando anterior.

###### A distinção entre `add` e `commit` é importante. O `add` marca os arquivos que serão adicionados ao commit enquanto o `commit` realmente fecha as mudanças em um único commit e o deixa pronto para ser enviado!

##### Git log

Responsável por exibir os pontos na história criados assim como as mudanças.

##### Git Status

Responsável por mostrar como está a linha do tempo do meu projeto no github.

##### Git Show

Neste comando é necessário utilizar o git commit e posteriormente utilizar o git show com o código do commit para mostrar o que aquele git commit realizou.

##### Git Branch

Usualmente, todo repositório inicia-se com a branch master, porém, seguindo nossa analogia, a branch seria uma linha do tempo alternativa, ou seja essa linha de comando cria os mesmos arquivos da branch master porém com alterações específicas para aquela branch

##### Git Checkout

Responsável por alternar entre as branches.

##### Git Merge

Responsável por unir as branches já criada na branch principal(master), necessário também colocar qual branch deseja-se unir.

##### Git remote add origin

Usado juntamente com o link do seu repositório criado manualmente dentro da plataforma do github para informar ao git qual repositório as suas alterações locais deve ser enviadas para a plataforma. 

##### Git push

Responsável por mandar as alterações feitas no projeto para a plataforma(git push -u origin master(caso não tenha nenhuma branch criada).

##### Git clone

Esta linha de comando é responsável por pegar um projeto já iniciado para trabalhar com a equipe, ressalta-se que é necessário o link do repositório.

##### Git pull

Responsável por puxar atualizações diretamente da nuvem para o sua máquina

