# Comandos de GIT
* ``` git init <nome do repositorio> ``` // Criar repositório
*  ``` git add <nome do Ficheiro> ``` //ou// ```git add . ```// Todos os ficheiros
* ``` git status ``` // Verificar se o estado do git add e do Commit
* ``` git commit -m <messagem> ``` // Tem sempre que conter uma messagem
* ``` git log ``` // Mostra tudos os commits 
* ``` git push ``` // envia para o servidor 
* ``` git diff ``` // mostra a diferença entre commits
* ``` git checkout ``` // poder navegar na linha do tempo para outro commit 
    * ``` git checkout -- <nomeFicheiro> ``` // Desfaz o que foi feito - mas sem fazer "git add" -
    * ``` git checkout HEAD -- <nomeFicheiro> ``` // Desfaz o que foi feito - se fez "git add" -
* ``` git reverse <commit> ``` // Reverte para o commit selecionado
* ``` git branch <nome> ``` // Novo Branch
    * ``` git branch  ``` // Ver todos os Branchs
    * ``` git checkout  <nomeBranch> ``` // Mudar de Branch
* ``` git merge <nomeBranch> ``` // Juntar ambos os branch's !- deve evitar -!  - deve ser usado para o master
* ``` git rebase <nomeBranch> ``` // Juntar ambos os branch's - deve ser usado no branch dev onde tens muito trabalho
    * ``` git add . + git rebase --continue``` // Para o proximo commit ! se Existir !
* ``` git fetch  ```
