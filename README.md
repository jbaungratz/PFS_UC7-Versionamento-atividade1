# PFS_UC7-Versionamento-atividade1
Necessidade de criar um login para ação de cadastrar mercadorias

Essa atividade serve para desenvolver habilidades na utilização do Git e Github, no versionamento e compartilhamento de repositório online para trabalhos em equipe.

Abaixo indicaremos os principais comandos do git.
É fundamental que façamos os comandos no terminal, pois na maioria dos trabalhos, não contaremos com interfaces para realizarmos as funções.


git status: informa os arquivos que tenho para commit
git add: adiciona o projeto para comitar
git commit -a -m: editar uma mudança que eu me 'responsabilizei'(salvar a nova versão), descrevendo objetivamente o que fiz.
git config --global user.email “jose.baungratz”
git config --global user.mail “jose1ab@hotmail.com"
git log identificar o commit
git reset --hard HEAD^ (dá para fazer o retorno com o ID da commit)
git diff: visualizar modificação
git checkout -b 'nome do arquivo': cria uma branch

APÓS CRIAR A BRANCH:

git push origin 'nome da branch': publica as alterações no repositóorio remoto
git pull: baixa as alterações no repositório remoto

git merge origin/develop: escolhe a correção das publicações entre os repositórios local e remoto.
