# Desafio de Projeto Git/Github da DIO
Repositório do primeiro desafio de Projeto sobre Git/Github, para o Bootcamp Unimed-BH Cência de Dados :sparkles:

## Instalação do Git

Crie uma conta no GitHub e depois faça o download do Git através do próprio site oficial https://git-scm.com/downloads e escolha seu sistema operacional.

## Primeiros passos

Após a instalação execute o Git Bash, esse e o terminal usado para executar os comandos. É bem parecido com o prompt de comando do windows.

#### Configuração de nome de usuário e e-mail

Execute os comandos a seguir no Git Bash:

> $ git config --global user.name "Coloque aqui seu nickname do Github"
>
> $ git config --global user-email "Coloqe aqui o seu email do Github"

#### Criando, atualizando e sincronizando um repositório

Crie uma pasta, entre nela e clique com o botão direito do mouse a opção "Git Bash Here".

Use o comando `$ git init` para poder inicializar e possibilitar que o Git possa gerenciar e versionar o código;

Use o comando `$ git add *` ou `$ git add .` para adicionar os arquivos que você adicionou a área de staging (unidade de armazenamento intermediaria);

Use o comando `$ git commit -m "texto explicando suas modificações"`para fazer o commit e adicionar os arquivos no repositório local;

Crie um novo repositório no Github e copie a url gerada.

Pra sincronizar com o Github use o comando `$ git remote add origin url` . Depois a cada modificação use o comando `$ git push origin master`.
