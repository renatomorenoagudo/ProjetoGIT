projeto vai ser desenvolvido ao longo do tempo aqui
abaixo o que deve ser digitado e aparecer para commitar no github

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