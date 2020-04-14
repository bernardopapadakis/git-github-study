# Códigos GIT

Este é um repositório com os principais e mais importantes códigos que eu sei e aprendi por meio de cursos, leituras e estudo.

## Configurações locais

### Verificar configurações locais

```git config --list ```// listar todas configurações

```git config --global user.name ```// verificar o usuário

```git config --global user.email```// verificar email

### Alterar configurações locais

```git config --global user.name "<seu_nome>"```// configurar seu nome

```git config --global user.email "<seu_email>"``` // configurar seu e-mail

```git config --global core.editor "<seu_editor>"```// configurar seu editor

## Repositório local


```git init```// criar um repositório local 

```git clone <url_do_repositório>```// clonar um repositório

```git status```// verificar status dos arquivos 

```git add <nome_do_arquivo>```// adicionar arquivo para ser comitado

```git add .```// adicionar todas mudanças de uma vez

```git commit -m "<comentário_do_commiti>"```// comitar 

## Logs


```git log```// ver todos commit's

```git log --decorate```// ver todos commit's com mais informações

```git log --author="<nome_da_pessoa>"```// filtrar para ver os commit's de um certa pessoa

```git shortlog```// ver em ordem alfabetica, todas pessoas que fizeram commit's, quantos commit's, e quais 

```git shortlog -sn```// ver a quantidades de commit's de cada pessoa

```git log --graph```// ver de forma gráfica o que está acontecendo nas branch's

```git show <código_do_commit>```// ver as modificações de um commit específico

## Diff


```git diff ```// ver mudanças antes de commitar 

```git diff --name-only ```// ver nome do arquivo que foi modificado

## Desfazendo coisas


```git checkout <nome_do_arquivo> ```// desfazer última mudança antes de adicionar arquivo em staged

```git reset HEAD <nome_do_arquivo> ```// remover arquivo do staged

```git reset --soft <hash_do_commit>> ```// voltar para um commit e apagar os commit's a partir dele 

```git reset --mixed <hash_do_commit>> ```// voltar para um commit, apagar os commit's e arquivos em staged a partir dele

```git reset --hard <hash_do_commit>> ```// voltar para um commit, apagar os comit's, os arquivo em staged e as mudanças nos arquivos a partir dele

```git revert <5_primeiros_caracteres_do_hash_do_commit>```// apagar um commit específico 

## Repositórios remotos

```git remote add origin <url_do_repositório>```// conectar repositório local com repositório remoto

```git push -u <repositório> <branch>```// enviar arquivos, logs e todas configurações do repositório local para o remoto

```git pull -u <repositório> <branch>```// baixar os arquivos, logs e todas configurações do repositório remoto para o repositório local

```git remote -v```// ver caminho do servidor

```git remote set-url origin <url_do_repositório>```// adicionar/alterar o caminho do servidor