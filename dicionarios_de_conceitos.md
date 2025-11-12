## Dicionario de Conceitos

- Git: Software de versionamento, que cria uma linha do tempo. Anota as alteraçoes em documentos e scripts em uma linha do tempo.

- GitHub: Backup da linha do tempo

## Notas sobre o commit


- **Por quê** houve uma mudança
- **Como** o problema foi resolvido
- **Efeitos** causados pelas alteraçoes
- **Limitaçoes** das atualizaçoes feitas

## Conceitos 

1. Area de desenvolvimento: ambiente ou pasta que o projeto esta inserido 
2. Staging Area: uma área intermediária de armazenamento, entre os dados originais e o repositório (GitHub). Nesta área, os dados são transformados, integrados e preparados para o carregamento no
3. Repositorio Local: É o proprio git, a parte que administra o versionamnto do codigo (i.e linha do tempo) ou a pasta oculta ".git" que fica oculta dentro do seu diretorio 
4. Repositorio Remoto, GitHub (cria um diretorio no repositorio e acrescenta ao projeto)

## Boas praticas 

1. Voce nao deve salvar dados. Git foi pensado para scripts e textos, e nao armazenamento de dados. 
2. Staging antes de salvar: para manipulacao diaria de muitos arquivos, é uma boa pratica acrescentar os arquivos na staging area para que todos sejam "comitados" ao mesmo tempo, e também entender o historico da linha do tempo. 
    Staging all documents, pode ser insuficiente e gerar um historico confuso
    Staging one at time, pode gerar um historico repetitivo 
    Stagin arquivos relacionados, cria um historico logico e com melhor acompanhamento
3. Apos a configuracao do git remoto, associar o git local ao remoto pelo comando 
    `git remote add origin <endereco_do_git_remoto>`
5. .gitignore - lista todos os arquivos e diretorios, dentro do gitlocal, que nao serao carregados ou transmitidos via push para o git remoto
6. README.md, cria o arquivo com instrucoes para o usuario ou developer configurar os primeiros passos ou guia-lo para execucacao da analise. 
7. Para sincronizar novos arquivos entre diferentes maquinas, git pull e git push, podem ser utilizados para essa tarefa. 

`git push` - envia do git local para o git remoto
`git pull` - tras do git remoto para o git local




________________Break Page___________________________

**Negrito** __Italico__

# Titulo

## subtitulo

### subsubtitulo

- topicos

* topicos