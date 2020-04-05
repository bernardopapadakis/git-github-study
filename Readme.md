#Github Course

Arquivo da aula de Git e Github para iniciantes.

Este é um repositório teste para aprender a usar Git e Github.

Códigos:

- Configurar seu nome: git config --global user.name "Seu nome"

- Configurar seu e-mail: git config --global user.email "seuemail@gmail.com"

- Configurar editor: git config --global core.editor seueditor

- Listar configurações: git config --list

- Criar um repositório local: git init

- Verificar status dos arquivos: git status

- Adicionar um arquivo: git add seuarquivo.tipodele

- Comitar: git commit -m "Comentário do commit"

- Ver todos os commit's: git log

- Ver os commit's com mais informações: git log --decorate

- Filtrar para ver os commit's de um certa pessoa: git log --author="nomedoautor"

- Ver  em ordem alfabetica, todas pessoas que fizeram commit's, quantos commit's, e quais : git shortlog

- Ver a quantidades de commit's de cada pessoa: git shortlog -

- Ver de forma gráfica o que está acontecendo branch's: git log --graph

- Ver as modificações de um commit específico: git show códigodocommit

- Ver mudanças antes de commitar: git diff

- Ver nome do arquivo que foi modificado: git diff --name-only

- Desfazer ultima mudança antes de commitar: git checkout nomedoarquivo.tipodoarquivo

- Como apagar uma mudança de um arquivo que foi adicionada: git reset HEAD nomedoarquivo.tipodoarquivo