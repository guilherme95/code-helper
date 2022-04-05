# git-helper

Repositório criado com o objetivo de ter agrupado os principais comandos do Git para servir de auxílio em questão de estudos e trabalho.

## comandos

- **git config --global user.name 'username'** -> configura o nome de usuario global
- **git config --global user.email 'email'** -> configura o email de usuario global
- **git config --global color.ui auto** -> configura a coloração do terminal para o git

- **git init** -> inicializa um repositório git local
- **rm -rf .git** -> para remover repositório git localmente
- **git branch** -> mostra a branch atual
- **git status** -> mostra o estado atual dos arquivos (se estão ou não na _stage area_, modificados ou se já foram commitados)
- **git add .** -> adiciona todos os arquivos para _stage area_ do diretório atual
- **git add -A** -> adiciona todos os arquivos para _stage area_ independente do diretório, ou seja, todos os arquivos do projeto
- **git rm --cached 'arquivo'** -> para remover o arquivo da _stage area_
- **git rm -r --cached .** -> remove todos os arquivos da _stage area_
- **git commit -m " 'comentario' "** -> commita um arquivo que está _stage area_, isto é, adiciona um comentário em relação àquele arquivo modificado para então, ser transferido para o diretório remoto
- **git log** -> mostra os logs em relção aos commits realizados
- **git show 'hash do commit'** -> mostra detalhes do commit (diff, data, autor...) 
- **git restore 'arquivo'** -> restaura o arquivo ao seu estado normal (último commit)
- **git commit --ammend -m " 'nova mensagem' "** -> renomeia a mensagem do último commit 
- **git remote add origin 'caminho remoto do repo'** -> configura repositório remoto no projeto inicializado localmente para devidos pushes
- **git branch -M 'novo nome'** -> renomear uma branch
- **git push -u origin 'branch'** -> envia para o repo remoto a branch especificada