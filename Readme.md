Git é um sistema distribuído de controle de versão de código.

criar o repositório
#git init

baixar o código de um repositório remoto
#git clone <https://nome-do-link>

verificar se houve alguma alteração
#git status

adicionar/atualizar todos os arquivos
#git add.

comitar o código
#git commit -m "mensagem"

salvar e enviar as alterações para o repositório remoto (na branch master)
#git push

mostra o que foi modificado antes do ultimo commit
#git diff

adicionar/atualizar todos os arquivos e comitar o código com uma mensagem
#git commit -am "mensagem"

desfazer as alterações do arquivo
#git checkout <nome do arquivo>

receber as atualizações do repositório remoto
#git pull <remote>

pegando o número do hash
#git log -- oneline

desfazer o commit
#git revert 'número do hash'

para listar branchs
#git branch

deletar uma branch
#git branch -d <nome-da-branch>

juntar os commits de forma linear
#git rebase <nome-da-branch>

juntar os commits criando um novo commit
#git merge <nome-da-branch>

criar um arquivo chamdo .gitignore e colocar dentro dele as extensões que não são interessantes subir no Github
#vim .gitignore
Dentro do arquivo acima colocar os comandos abaixo
#*.json
#db.xls

criar novos atalhos para o Git
#git config --global alias.<letra> <comando>
#Ex: git config --global alias.s status
