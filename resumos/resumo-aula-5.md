## aula 05

- troca para uma nova branch (cria a mesma ao trocar)
```
$ git checkout -b teste(nome da branch)
```

- Mover entre as branches do projeto (sem -b atalho para criar a branch ao trocar)
```
$ git checkout main
```

- Lista as branches do projeto
```
$ git branch
```

- Lista o ultimo commit de cada branch
```
$ git branch -v
```

- Mescla a branch citada com a branch atual
```
$ git merge teste(nome da branch)
```

- Deleta uma branch específica
```
$ git branch -d teste(nome da branch)
```

###### Resolvendo conflitos

conflitando devemos excluir um dos problemas e comitar novamente para arrumar, isso irá alterar ambos arquivos resultando na resolução do conflito inicial.


