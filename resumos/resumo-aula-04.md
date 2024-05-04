## aula 04

-  Adiciona um repositório remoto vazio ao repositório local
```
$ git add remote (link do repositório)
```

- Altera o nome da branch para Main forçosamente (antigo master)
```
$ git branch -M main
```

- Envia o projeto para o repositório remoto (-u abreviação para --set-upstream)
```
$ git push -u origin main
```

- Atualiza o repositório local com as alterações que o remoto possui
```
$ git pull
```
