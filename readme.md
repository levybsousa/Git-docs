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
-------------------------------------------------------------
* Mudanças 

> **gitk** : Mostra as modificações totais do projeto

 > **git diff** : Modificações antes de enviar as modificações 
 para o repositório remoto (commit).
 > **git status** : Estados dos arquivos/ diretorio
 > **git commit --amend -m "Minha nova mensagem"**: Alterando mensagens
 de commit já realizado
 > **git rebase -i HEAD-3:** Alterar últimos commits, modificando 
 mensagens 
 --------------------------------------------------------------
* Log

> **git log** : Exibe o histórico dos últimos commits.

> **git log -p**: Exibe o histórico com diff dos últimos 3 commits.

> **git log -- <caminho do arquivo>**: Exibir histórico no 
caminha_do_arquivo.

> **git log --pretty--oneline:** Exiibe o histórico de commit com 
informações resumidas em uma linha.

> **git log --diff-filter--M <caminho_do_arquivo>**: Exibe o histórico
de modificações de um arquivo

> **git log --author-usuario**: Exibir histórico de um determinado autor.

----------------------------------------------------------------
*  Cherry-Pic 

> **git cherry-pick <commit-id>** Copias as informações desse commit.

> **git cherry-pick A^...B**: Copia todos os commits entre
o commit A e o commit B, inclusive A e B.

> **git cherry-pick A...B:** Copia todos os commits entre o commit
A e o commit B, excluindo.

--------------------------------------------------------------
* Stash 

> **git stash** : Cria um stash, salva temporiariamtente as 
modificações.

> **git stash list**: Lista os stashes criados.

> **git stash apply**: Voltou ao último stash.

> **git stash apply stash@(2)**: Voltou ao Stash com índice 2.

> **git stash branch meu_branch**: Criar um branch a partir de um
stash 