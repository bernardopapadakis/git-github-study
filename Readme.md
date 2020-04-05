# Github Course

Arquivo da aula de Git e Github para iniciantes.

Este é um repositório teste para aprender a usar Git e Github.

OBS: quando for usar um código que tiver (), ignore os () e escreva o que estiver dentro dele, da seguinte forma, se estiver escrito (arquivo) escreva o nome do arquivo de verdade, como exemplo Readme.md.

## Códigos GIT:

### Configurações
    - Configurar seu nome: git config --global user.name "(seu nome)"

    - Configurar seu e-mail: git config --global user.email "(seu email)"

    - Configurar editor: git config --global core.editor (seu editor preferido)

    - Listar configurações: git config --list

### Repositório local

    - Criar um repositório local: git init

    - Verificar status dos arquivos: git status

    - Adicionar um arquivo: git add (arquivo)

    - Comitar: git commit -m "(comentário do commit)"

### Logs

    - Ver todos os commit's: git log

    - Ver os commit's com mais informações: git log --decorate

    - Filtrar para ver os commit's de um certa pessoa: git log --author="(nome da pessoa)"

    - Ver  em ordem alfabetica, todas pessoas que fizeram commit's, quantos commit's, e quais : git shortlog

    - Ver a quantidades de commit's de cada pessoa: git shortlog -sn

    - Ver de forma gráfica o que está acontecendo branch's: git log --graph

    - Ver as modificações de um commit específico: git show (código do commit)

### Diff

    - Ver mudanças antes de commitar: git diff

    - Ver nome do arquivo que foi modificado: git diff --name-only

### Desfazendo coisas

    - Desfazer ultima mudança antes de commitar: git checkout (arquivo)

    - Apagar uma mudança de um arquivo que foi adicionado: git reset HEAD (arquivo)

    - Como voltar para um commit e apagar os commit's depois dele: git reset --soft (código do commit) / git reset --mixed (código do commit) / git reset --hard (código do commit) // o reset apaga somente o commit, o mixed apaga o commit e o arquivo do repositório, e o hard apaga o commit, o arquivo do repositório e as mudanças no arquivo