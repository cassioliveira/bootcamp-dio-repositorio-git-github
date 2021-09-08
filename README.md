# bootcamp-dio-repositorio-git-github

Este repositório foi criado apenas com o intuito de praticar os comandos git para o curso **Criando seu primeiro repositório no Github para compartilhar seus projetos**

Basicamente foi criado o projeto, clonado localmente, alterado e as novas modificações enviadas, tudo através dos comandos abaixo:

## Clone do projeto
`git clone https://github.com/cassioliveira/bootcamp-dio-repositorio-git-github`

## Criação do arquivo README.md
`touch README.md`

## Adicionando as modificações ao Stage
`git add README.md`

## Fazendo commit das modificações localmente
`git commit -m "primeiro commit"`

## Enviando as modificações para o repositório no github
`git push -u origin main`

PAra este último comando, só foi preciso executá-lo desta forma por ser a primeira vez. Nos próximos envios, basta digitar `git push`


# [UPDATE]

Alguns comandos úteis:

- Criar nova branch baseada na branch atual: `git checkout -b nome_da_nova_branch`
- Trocar de branch: `git checkout nome_da_branch_que_sera_trabalhada`
- Fazer merge de branches. Na branch que vai receber as modificações da nova branch, execute: `git merge nome_da_branch_com_os_dados_novos` 
