# Github Course

Arquivo da aula de Git e Github para iniciantes.

Este é um repositório teste para aprender a usar Git e Github.

OBS: quando for usar um código, e algo estiver entre ( ), ignore os ( ) e escreva o significado do que estiver escrito, da seguinte forma, se estiver escrito (arquivo) escreva o nome do arquivo de verdade, como exemplo Readme.md.

## Códigos GIT:

### Configurações
    - git config --global user.name "(seu nome)" // configurar seu nome

    - git config --global user.email "(seu email)" // configurar seu e-mail

    - git config --global core.editor (seu editor preferido) // configurar editor

    - git config --list // listar configurações

### Repositório local

    - git init // criar um repositório local 

    - git status // verificar status dos arquivos 

    - git add (arquivo) // adicionar um arquivo 

    - git commit -m "(comentário do commit)" // comitar 

### Logs

    - git log // ver todos commit's

    - git log --decorate // ver todos commit's com mais informações

    - git log --author="(nome da pessoa)" // filtrar para ver os commit's de um certa pessoa

    - git shortlog // ver em ordem alfabetica, todas pessoas que fizeram commit's, quantos commit's, e quais 

    -  git shortlog -sn // ver a quantidades de commit's de cada pessoa

    - git log --graph // ver de forma gráfica o que está acontecendo nas branch's

    - git show (código do commit) // ver as modificações de um commit específico

### Diff

    - git diff // ver mudanças antes de commitar 

    - git diff --name-only // ver nome do arquivo que foi modificado 

### Desfazendo coisas

    - git checkout (arquivo) // desfazer última mudança antes de adicionar arquivo no repositório local

    - git reset HEAD (arquivo) // desfazer última mudança de um arquivo que foi adicionado no repositório local

    - git reset --soft (código do commit)` // voltar para um commit e apagar os commit's a partir dele 
    
    - git reset --mixed (código do commit) // voltar para um commit e apagar os commit's e mudanças adicionadas no repostório local a partir dele
    
    - git reset --hard (código do commit)` // voltar o commit e apagar os comit's, os arquivo adicionados no repositório local e as mudanças nos arquivos a partir dele

## Conectando com o Github