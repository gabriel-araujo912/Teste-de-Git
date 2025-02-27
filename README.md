Para inicializar o Git no repositório
`git init`

Para verificar o status:
`git status`

Para adicionar um arquivo no sistema de vercionamento:
`git add .`

Para dar um commit nos arquivos adicionados e criar um commit:
`git commit -a -m "primeiro commit"`
>`-a` (adicionar os arquivos no commit)
>`-m` (adicionar mensagem ao commit)

Para conectar o git ao github:
`git remote add origin https://....git `

Para dizer qual o branch principal:
`git branch -M main`
>`-M` (fala o nome do branch principal, pareando os branchs principais de cada repositório)

Para enviar o código atual para um repositório remoto
`git push -u origin main`

Para colocar o token:
> Ir no GitHub -> settings -> developer settings -> tokens (classic)
> 
> Depois só colar ela como Password no terminal

Para criar e trabalhar com uma nova Branch:
`git checkout -b "teste"`
Para criar uma branch no repositório remoto tbm:
`git push --set-upstream origin NovaBranch `

Para mudar para um outro branch:
`git checkout main`

Para pegar a alteração de uma outra branch e colocar na principal(local):
`git merge NovaBranch`

Para puxar as alterações do repositório externo para o local:
`git pull`

Para clonar um projeto para uma pasta:
`git clone https://....git testeclone`

Para excluir um arquivo untracked:
`git clean -f`

Para voltar uma alteração em algum arquivo expecífico para o ultimo commit(local):
`git checkout ./arquivo`