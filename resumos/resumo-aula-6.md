## aula 06

- baixa as alterações sem mesclar com o repositório local

```
$ git fetch origin main
```

- Mostra as diferenças entre arquivos de duas branches distintas
```
$ git diff main(1) origin/main(2)
```
-------------------------------------------------------

- Clona uma branch específica desejada(caso o nome da branch não seja especificado, irá clonar apenas a branch main)
```
$ git clone https://github.com/marcoguarato15/dio-resumos-git-e-github.git --branch teste(nome da branch desejado) --single-branch
```
-------------------------------------------------------

- Arquiva uma ação na area de produção
```
$ git stash
```

- Visualizar as stashes realizadas(em pilhas)
```
$ git stash list
```

- Caso deseje utilizar o arquivo que foi arquivado
```
$ git stash pop
```

- Caso deseje não utilizá-lo neste commit
```
$ git stash apply
```
