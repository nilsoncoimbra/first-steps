# Git comands and Instructions 

## Rotina basica para adicionar versao na linha do tempo

1. git init  - dentro da pasta, que voce quer iniciar o projeto

`git init`

2. git add <file> - que voce quer adicionar ao seu projeto

`git add`

3. git commit -m <mensagem significativa>, nessa mensagem é importante deixar registrado as motivacoes para as alteracoes no arquivo - e quais estratégias que voce utilizou

`git commit -m`


3. git status - mostra o status do seu projeto (__uncommited__, __unstaged__, __untracked__)

`git status`

4. git log  - mostra o historico das modificacaoes feitas com o git commit 

`git log -n <#>` -git log --pretty=format onde # é o numero de commit

`git log --abbrev-commit` - menor ID possivel considerando o historico

Mais opçoes em git log

`-p` -  Mostra o patch introduzido com cada commit.

`--stat` - Mostra estatísticas de arquivos modificados em cada commit.

`--shortstat` - Exibe apenas a linha informando a alteração, inserção e exclusão do comando --stat.

`--name-only` - Mostra a lista de arquivos modificados após as informações de commit.

`--name-status` - Mostra também a lista de arquivos que sofreram modificação com informações adicionadas / modificadas / excluídas.

`--abbrev-commit` - Mostra apenas os primeiros caracteres da soma de verificação SHA-1 em vez de todos os 40.

`--relative-date` - Exibe a data em um formato relativo (por exemplo, ‘` 2 semanas atrás '’) em vez de usar o formato de data completo.

`--graph` - Exibe um gráfico ASCII do histórico de branches e merges ao lado da saída do log.

`--pretty` - Mostra os commits em um formato alternativo. As opções incluem oneline, short, full, fuller e format (onde você especifica seu próprio formato).

5. git diff - Mostra as diferencas entre os arquivos (combinados)

`git diff` <old_ID> <new_ID>`


6. git show - mostra os dois arquivos e as modificaçoes pareadas 

`git show <old_ID> <new_ID>`

7. git branch - cria/rennomeia a ramificacao principal do projeto

`git branch -M main``

8. git remote add origin <endereço do projeto remoto>, associa seu git local com o projeto remoto e depois pode passar os arquivos para o local de destino.

9. git push --set-upstream origin main, para alinhar o trackemento do git ao branch principal


9. git push - é comando para enviar os arquivos do git local para o git remoto, que foi configurado no passo acima 

`git push` 

10. Rotina e boas praticias do git

Checando _status_ dos arquivos, adicionando na _staging area_, fazer o _commit_ para salvar na linha do tempo e fazer o _push_ para enviar
ao GitHub

```
git status

git add <nome do arquivo>

git commit -m "Mensagem significativa"

git push

```

11. git pull - sincroniza os arquivos entre maquinas e instancias, para que o projeto seja atualizado -> envia do remoto ao local, enquanto que o push envia do local ao remoto

`git pull`
