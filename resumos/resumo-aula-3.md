## aula 03

- Mostra o log de commits realizados
```
$ git log
```

- restaura o arquivo para como estava no commit anterior (perde todas alterações feitas)
```
$ git restore README.md(nome arquivo)
```

- Altera a ultima mensagem do commit
```
$ git commit --ammend -m "(mensagem)"
```

- Pega os arquivos dos commits posteriores ao indicado pelo rash e os coloca na área de preparação
```
$ git reset --soft (Hash do commit que deseja voltar)
```

- Pega todos arquivos e diretórios e os adiciona novamente na área de preparação
```
$ git reset --mixed(Opcional) (Hash do commit que deseja voltar)
```

- Retorna para o commit e exclui todos os arquivos dos commits anteriores
```
$ git reset --hard (Hash do commit)
```

- mostra todos as alterações realizadas no projeto git
```
$ git reflog
```

- remove arquivos da área de preparação (staging area)
```
$ git restore --staged (nome do arquivo)
```
