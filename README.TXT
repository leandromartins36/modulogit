
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
mudar para outro branch: git checkout teste (nome do branch destino)
