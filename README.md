# git-commands
## Comandos Git mais utilizados

Descobrir quais branchs estão disponíveis remotamente, ou seja, todos do projeto.
```
git branch -r
```

Descobrir qual branch você está logado

```
git branch
```

Fazer login no Branch
```
git checkout ＜branchname＞ 
```



## Fazer upload das alterações ##

Esse comando irá adicionar todos os arquivos novos e/ou modificados à fila para serem submetidos a um commit posteriormente
```
git add *
```
Executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log.

```
git commit -m "sua descrição aqui"
```

Adiciona e realiza o commit em um só comando
```
git commit -a -m "sua descrição aqui"
```

O comando git push envia e salva suas confirmações no repositório remoto
```
git push origin <branchname＞
```

Cria um novo Branch e realiza o checkou nele
```
git checkout -b <branchname＞ 
```

git status
