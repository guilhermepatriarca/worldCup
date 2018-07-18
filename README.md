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
* ``` git merge <nomeBranch> ``` // Juntar ambos os branch's