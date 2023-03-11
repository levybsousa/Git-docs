##  Git docs

### Annotations:

----------------------------------------------------------------
 * Branch:
> **git branch new-branch**: cria com o nome new branch

>**git checkout -b new-branch**: Criar e mudar o código para o branch 
new-branch 

> **git checkout new-branch**: Muda o código atual e a referência
para a branch new-branch

> **git checkout main** : Muda o código para a branch principal 
main

> **git branch:** Lista todos os branchs criados

> **git branch -v** : Listar os branchs criados com logs de commit

> **git push origin new-branch:** Criando um branch remoto
com o mesmo nome

>**git push origin new branch:new-branch:** Criando um branch remoto
com nome diferente

> **git pull origin main**: Dowload de todos os arquivos do repositorio
remoto para o local

> **git fetch origin**: Download de todas as branchs remotas 

> **git checkout -b new-branch origin/new-branch:** Baixar um branch
remoto para edição

> **git merge new-branch:** Realize o merge entre os branchs, ou seja
juntar o ramo na árvore principal
-----------------------------------------------------------
* Arquivos:

> **git add . :** adiciona todos os arquivos ou diretorios modificados

 > **git add meu_programa.py**: Adiciona somente o arquivo
 meu_programa.py
 
> **git add meu_diretorio:** Adiciona somente o diretorio 
meu_diretorio

> **git add -f meu_programa_gitignore.py :** Adiciona um arquivo
que está no .gitignore

> **git rm meu-arquivo.txt** : Remover arquivo

> **git rm -r diretorio** : Remover diretório

> **git commit meu_programa.py** : Comitar um arquivo

> **git commit file1.txt file2.txt**: Comitar vários arquivos

> **git commit meuarquivo.txt -m "minha mensagem de commit":** Commitar
informando  mensagem