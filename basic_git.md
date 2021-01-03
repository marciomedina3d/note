#### Lista de comandos básicos Git

Version 1.0.0

------

Lembrete dos comandos Git principais

[TOC]

Segue os comandos na sequência que não tem como errar...

###### Iniciar um repositório

```
git init
```

###### Verificar configurações locais

```
git config --list
```

###### Verificar o nome do usuario

```
git config --global user.name
```

###### Verificar email usuario

```
git config --global user.email
```

###### Alterar usuario local

```
git config --global user.name "MEDINA M. R. B."
```

###### Alterar email usuario local

```
git config --global user.email "marcio.medina@fatec.sp.gov.br"
```

###### Alterando o editor de texto no commit para vim

```
git config --global core.editor vim
```

###### Alterando o editor para vim diff/merges

```
git config --global merge.tool vimdiff
```

###### Adicionar o caminho do servidor

```
git remote add origin https://github.com/marciomedina3d/note.git
```

###### Criando uma branch

```
git branch -M main
```

###### Trocando de branch ou git checkout

```
git checkout main
```

###### Lista as branches

```
git branch
```

###### Cria uma branch e já realiza o checkout

```
git checkout -b main
```

###### Simples commit

```
git acommit -m "Commit inicial"
```

###### Adicionar tudo 

```
git add
```

###### Commit adicionando tudo e incluindo a mensagem de commit

```
git commit -am "Inclusão das notas mentais"
```

###### Criar uma tag

```
git tag
```

###### Criar uma tag com mensagem de anotada

```
git tag -a 1.0.1 -m "Version 1.0.0"
```

###### Verificar oque foi realizado

```
git status
```

###### Verificar oque foi alterado

```
git diff
```

###### Enviando branch para o servidor

```
git push -u origin main
```

###### Log, exibe o histórico 

```
git log
```

Log de maneira resumida

```
git log --pretty=oneline
```

Exemplo de Comandos recomentados Github

```
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/marciomedina3d/Test.git
git push -u origin main
```

