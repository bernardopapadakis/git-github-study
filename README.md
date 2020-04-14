# Github Course

Arquivo da aula de Git e Github para iniciantes.

Este é um repositório teste para aprender a usar Git e Github.

## Configurações

```git config --global user.name <seu_nome>```// configurar seu nome

```git config --global user.email <seu_email>``` // configurar seu e-mail

```git config --global core.editor <seu_editor>```// configurar editor

```git config --list ```// listar configurações

# Repositório local


```git init```// criar um repositório local 

```git status```// verificar status dos arquivos 

```git add <nome_do_arquivo>```// adicionar um arquivo

```git commit -m "<comentário>"```// comitar 

# Logs


```git log```// ver todos commit's

```git log --decorate```// ver todos commit's com mais informações

```git log --author="<nome_da_pessoa>"```// filtrar para ver os commit's de um certa pessoa

```git shortlog```// ver em ordem alfabetica, todas pessoas que fizeram commit's, quantos commit's, e quais 

```git shortlog -sn```// ver a quantidades de commit's de cada pessoa

```git log --graph```// ver de forma gráfica o que está acontecendo nas branch's

```git show <código_do_commit>```// ver as modificações de um commit específico

# Diff


```git diff ```// ver mudanças antes de commitar 
```git diff --name-only ```// ver nome do arquivo que foi modificado

# Desfazendo coisas


```git checkout <nome_do_arquivo> ```// desfazer última mudança antes de adicionar arquivo no repositório local

```git reset HEAD <nome_do_arquivo> ```// desfazer última mudança de um arquivo que foi adicionado no repositório local

```git reset --soft <código_do_commit> ```// voltar para um commit e apagar os commit's a partir dele 

```git reset --mixed <código_do_commit> ```// voltar para um commit e apagar os commit's e mudanças adicionadas no repostório local a partir dele

```git reset --hard <código do commit> ```// voltar o commit e apagar os comit's, os arquivo adicionados no repositório local e as mudanças nos arquivos a partir del 