*** Olá, esse projeto ensina você a usar o Git ***
git --version 
git init
git add nome_do_aquivo.com_extensao
git status
git commit -m "primeiro commit"
git status

*** Mudar o nome de master para main ***
git branch -M "main"

*** Depois de criar o repositório no GitHub ***
git remote add origin < link do Git > 

* O remote só cria uma vez. Na segunda vez não precisa mais usar o remote * 

git push -u origin main

*** Versionamento *** 
 Isso é uma alteração

 git add . 
 * o ponto significa que todos os arquivos que estiverem disponíveis vão para a área de stage *
* se for somente uma alteração no arquivo local usar o mesmo código da primeira vez: *
git add nome_do_aquivo.com_extensao

git status
git commit -m "criacao do Projeto" (cria o commit no repositório da máquina)
git push origin main (mandar para o git Hub - todas as modificações foram agora adicionadas.)


*** Conceito de branch (Ramificações) ***
01) Criar primeiro a branch para depois fazer as edições ;
git checkout -b "botão" ( criando uma nova branch e com o checkout saindo da branch principal até aqui nomeada main)
02) Criar um novo arquivo  botao.md

git add . 
git commit -m "botao"
git push origin botao