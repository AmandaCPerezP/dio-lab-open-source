# Como Conectar o GitHub com o VS Code

## 1. Instale o VS Code e o Git

Antes de começar, você precisa garantir que tem as ferramentas necessárias instaladas:

- **Visual Studio Code (VS Code):** https://code.visualstudio.com/
- **Git:** Baixe aqui](https://git-scm.com/

Para verificar se o Git está instalado no seu computador, siga os passos abaixo:

1. Abra o terminal ou prompt de comando.
2. Digite o comando:
   ```bash
   git --version
Se aparecer algo como git version x.x.x, o Git está instalado corretamente.

## 2. Configure o Git no seu Computador
Depois de instalar o Git, você precisa configurá-lo com seu nome e e-mail. Esses dados serão usados para identificar os commits.

No terminal, configure seu nome e e-mail com os comandos abaixo:

copy
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
Para verificar se as configurações foram salvas corretamente, use:

copy(opcional)
git config --list

## 3. Faça Login no GitHub pelo VS Code
Abra o VS Code.
No menu lateral esquerdo, clique no ícone de Conta (ícone de boneco).
Clique em Sign in to GitHub.
Uma janela do navegador será aberta. Faça login na sua conta do GitHub.
Autorize o VS Code clicando em Authorize Visual Studio Code.

## 4. Clone um Repositório do GitHub
Se você já tem um repositório no GitHub e deseja trabalhar nele no VS Code, siga os passos abaixo:

Acesse o repositório no GitHub e copie o link HTTPS:

Clique no botão verde Code e copie o link (exemplo: https://github.com/usuario/repositorio.git).
No VS Code:

Clique no ícone de Fonte de Código (Source Control) no menu lateral esquerdo.
Clique em Clone Repository.
Cole o link copiado e pressione Enter.
Escolha a pasta onde deseja salvar o repositório localmente.
O repositório será baixado e aberto automaticamente no VS Code.

## 5. Inicialize um Novo Repositório
Se você ainda não tem um repositório no GitHub, siga os passos abaixo para criar um:

No GitHub:

Acesse github.com.
Clique em New Repository.
Preencha o nome do repositório e clique em Create Repository.
No VS Code:

Crie uma pasta para o projeto e abra-a no VS Code.
Inicialize o Git na pasta usando o terminal:
copy
git init
Conecte o repositório local ao GitHub com o comando:
copy
git remote add origin https://github.com/usuario/repositorio.git
Faça o primeiro commit e envie-o para o GitHub:

copy
git add .
git commit -m "Primeiro commit"
git branch -M main
git push -u origin main

## 6. Trabalhe no VS Code e Envie Alterações para o GitHub
Faça alterações no código no VS Code.
No menu lateral esquerdo, clique no ícone de Fonte de Código (Source Control).
Adicione os arquivos ao stage clicando no ícone + ao lado dos arquivos modificados.
Escreva uma mensagem de commit no campo superior e clique no ícone ✓ Commit.
Para enviar as alterações para o GitHub, clique no ícone de Sincronizar Alterações (ícone de setas circulares) ou use o terminal:
copy
git push

## 7. Sincronize Alterações do GitHub para o VS Code
Se alguém fizer alterações no repositório remoto, você pode baixá-las para o seu repositório local:

No terminal do VS Code, use o comando:
copy
git pull
Ou clique no ícone de Sincronizar Alterações no menu lateral.

## Dica Extra
Instale a extensão GitHub Pull Requests and Issues no VS Code para gerenciar pull requests e issues diretamente no editor.
Use o terminal integrado do VS Code para rodar comandos Git, caso prefira utilizar a linha de comando.
Agora você está conectado ao GitHub pelo VS Code e pronto para colaborar em seus projetos! 🚀

copy

Esse texto está pronto para ser usado em um README ou qualquer documento em Markdown! 😊
