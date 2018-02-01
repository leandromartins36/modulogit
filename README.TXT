
Meu primeiro sistema no git.
alteraçao no read para outras coisas.

vefiricar log de commit : git log e a letra q para sair do log

lista os branch: git branch

verificar as mudanças efetudadas no git: git status

preparar novos arquivos e mudanças feitas em arquivos no git: git add -A

enviar os dados prparados para o git com comando -A incluido:
git commit -am "coloca os comentarios entre aspas duplas"

comando para voltar a versão anterior do arquivo ou projeto no git:
git reset --soft (soft volta com a possibilidade de voltar os arquivos ja hard apaga tudo)
 e a chave do log que se deseja voltar 
ex: 689e5297dacbb8cf0d6b5272fdb298e62a58112b

comando completo:git reset --soft 689e5297dacbb8cf0d6b5272fdb298e62a58112b

o comando git branch lista qual o branch atual.
criar um novo branch
git branch "criar novo branch"
mudar para outro branch: git checkout teste (nome do branch destino) e tambem
serve para voltar a versão de um arquivo especifico:
 git checkout HEAD --(NOME DO ARQUIVO SEM PARENTESES)

verifica o que esta no git em cada arquivo mostrar as alterações: git diff
e com este comando ve somente o nome dos arquivos modificados: git diff --name-only

enviando arquivo para o repositorio no site do GIT atraves do tutorial

comando para gerar a chave que é usada no site do github para envio dos arquivos 
no repositorio: ssh-keygen -t  rsa -b4096 -C "leoinfosiste@yahoo.com.br"

e o comando usado para enviar os dados para a nuvem do git é :
git remote add origin https://github.com/leandromartins36/modulogit.git

e este comando para enviar as modificações: git push -u origin master

enviando as alterações ao github online depois do repositorio criado com o comando:
git push origin master

quando tiver um novo arquivo para ser endiado ao repositorio local deve usar o comando:
git add -A
