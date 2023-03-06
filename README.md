# CRUD (20230306)
> O que é CRUD? CRUD é um acrônimo para Create, Read, Update e Delete, que são as quatro operações básicas (criação, consulta, atualização e destruição de dados) utilizadas em bases de dados relacionais ou em gerenciamento de conteúdo.

> Alteração feita remotamente, para escrever nesse arquivo use markdown https://www.markdownguide.org/cheat-sheet/

Nosso projetinho feito com amor e carinho 💜

> Inicializa o processo de monitorar as mudanças no projeto
```
git init
```

> Adicionar as alterações feitas nos arquivos para uma "caixinha", essa caixinha é lida como "staging area/staged changes (dentro do VSCode)"
```sh
git add
```
```
# adiciona todos os arquivos
git add .
```sh
```sh
git add <nome do arquivo>.<extensão>
```

> Pega essa "caixinha" e SELA ela com um nome explicando o que tem nessa caixa
```
git commit -m "nome do commit"
```
```
git commit
# Se você cair na janela do VIM, aperte `a` e depois insira a mensagem, após isso para salvar aperte `esc` e depois `:wq`, após isso dê `ENTER` e o commit será feito normalmente
```

```
# Nos permite ver quais são os commits que temos no nosso repositório
git log
```

```
# EMPURRA tudo o que temos localmente, para o remoto
git push
```

```
# PUXA tudo o que temos no remoto, para o local
git pull
```


## O que é uma branch
- É uma linha do tempo, onde cada commit é um ponto nessa linha do tempo

## O que é um repositório
- Um repositório é um lugar onde você guarda as branches com os commits do seu projeto
- Você pode ter um repositório LOCAL que está LINKADO a um repositório REMOTO no GitHub
  - Para linkar projetos usamos o `git remote` `git remote add origin git@github.com:omariosouto/crud-20230306.git`
  - Para atualizar a branch de um repositório, usamos o `git push` para mandar as alterações locais


## Referencias
- [Visulizando o Git](https://git-school.github.io/visualizing-git/)
