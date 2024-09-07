# Como fazer para subir as soluções?

## Passo 1: Criar uma Conta no GitHub

1. Acesse [GitHub.com](https://github.com/).
2. Clique em "Sign up" e siga as instruções para criar uma nova conta.
3. Confirme seu endereço de email para ativar a conta.

## Passo 2: Configurar Git

- Instale o Git em seu computador seguindo as instruções em [Git - Downloads](https://git-scm.com/downloads).
- Configure seu usuário e email no Git com os comandos:
  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seuemail@example.com"
  ```

## Passo 3: Clonar o Repositório

1. Navegue até a página deste repositório 
2. Clique no botão "Code" e copie o URL do repositório.
3. Abra um terminal ou prompt de comando e digite:
   ```bash
   git clone URL_DO_REPOSITÓRIO
   ```
   Substitua `URL_DO_REPOSITÓRIO` pela URL que você copiou.

## Passo 4: Criar uma Nova Branch

1. Navegue até a pasta do repositório clonado:
   ```bash
   cd nome-do-repositorio
   ```
2. Crie uma nova branch usando:
   ```bash
   git switch -c nome-da-sua-branch
   ```

## Passo 5: Adicionar Soluções

1. Crie uma pasta chamada `soluções` caso ela não exista.
2. Dentro da pasta `soluções: <seu nome>`, resolva os exercícios

## Passo 6: Commitar suas Mudanças

1. Adicione as mudanças ao Git:
   ```bash
   git add .
   ```
2. Faça um commit com uma mensagem explicativa:
   ```bash
   git commit -m "Adicionando soluções de <seu nome de usuário>"
   ```

## Passo 7: Subir sua Branch para o GitHub

1. Suba sua branch para o repositório:
   ```bash
   git push origin nome-da-sua-branch
   ```

## Passo 8: Criar uma Pull Request

1. Acesse o repositório no GitHub.
2. Você verá um botão para criar uma Pull Request da sua branch. Clique nele.
3. Adicione um título e descrição para sua Pull Request e submeta.
