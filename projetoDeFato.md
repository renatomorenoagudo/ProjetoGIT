projeto vai ser desenvolvido ao longo do tempo aqui
abaixo o que deve ser digitado no GIT BASH (TERMINAL) OU MESMO NO TERMINAL DO VS CODE OU OUTROS DE PREFERENCIA...e a sequencia que vai aparecer no terminal  para inserir o commit no github:

Renato@DESKTOP-RL03AUD MINGW64 /d/OneDrive/Área de Trabalho/ProjetoGIT (main)
$ git add .

//o comando "git add ." serve para adicionar todos os arquivos adicionados ou alterados, mas pode ser feito tambem por nome de arquivo, só digitar o nome do arquivo separadamente nesse caso, senao usa o ponto que engloba todos.// 

Renato@DESKTOP-RL03AUD MINGW64 /d/OneDrive/Área de Trabalho/ProjetoGIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   projetoDeFato.md
        modified:   readme.md


Renato@DESKTOP-RL03AUD MINGW64 /d/OneDrive/Área de Trabalho/ProjetoGIT (main)
$ git commit -m "criação do projeto"
[main 66822bc] criação do projeto
 2 files changed, 3 insertions(+), 1 deletion(-)
 create mode 100644 projetoDeFato.md

Renato@DESKTOP-RL03AUD MINGW64 /d/OneDrive/Área de Trabalho/ProjetoGIT (main)
$ git push origin main

....após posso ver no github que foi inserido o novo commit e as alteraçoes feitas nesse codigo

entao sempre será essa sequencia:
1) git add .
2)git status (para ver o arquivo que foi modificado)
3) git commit -m "" (nome do commit)
4) git push origin main

obs: o "git remote" usa somente uma vez quando vai colar o link do github e posteriormente logar com email e senha,,,,apos isso feito usa somente o "push origin main".

agora vou criar uma "BRANCH" como por exemplo para criar um novo botao.
abre o terminal git bash
digito: git checkout -b "novo botão"

com isso voce ira sair do local principal que esta desenvolvendo e criar um novo dentro...ou seja, tudo que voce alterar agora sera dentro desse novo ramo e nao mais na principal.

agora vamos criar um arquivo com o nome botao.md e vamos escrever nele: aqui será criado o botao do projeto
obs: não necessariamente precisamos criar um novo arquivo, qualquer alteração ja serve para criar um comit dentro da branch botao...mas um novo arquivo fica melhor para visualizarmos

agora segue o padrao...
$ git add . 
$ git commit -m"novo botao"
$ git push origin novo-botao

no push tem que lembrar que nao estamos mais no main(principal) por isso tem q substitui main pelo nome da branch criada (novo-botao)

para voltar a modificar algo la na main tem que dar o comando CHECKOUT MAIN no terminal bash
para que mude a pasta a ser modificada no github
apos observe que a pasta entre parenteses voltou a ficar com o nome main e nao mais (novo-botao)
pode ocorrer do terminal perguntar pra qual arquivo dentro do principal,,,assim de outro checkout com o nome do arquivo e depois novo checkout com main...q ai ele entrara no main
******************************
marge
 agora vamos aprender a funçao do comando marge 
 digitamos :  git merge novo-botao

 
