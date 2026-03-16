<h1 align="center">💻 Minhas Configurações do VS Code + Extensões</h1>

## Este guia explica como configurar o visual do meu VS Code e a integração com o Git/GitHub conforme as capturas de tela.

---

## 🎨 1. Personalização Visual (Background)

Para deixar o editor com imagens de fundo personalizadas, utilizo a extensão **Background**.

### Passo a Passo:
1. Instale a extensão **Background** (criada por Katsute) na Marketplace do VS Code.

   <img src="Images/Background.png" width="500">

2. Pressione `CTRL + SHIFT + P`, digite **"Background: Configuration"** e selecione a opção que aparecer.

   <img src="Images/Background2.png" width="500">

3. No menu de configuração, navegue até a aba **Window** e selecione-a .

   <img src="Images/Background3.png" width="500">

4. Vá na seção **File**.

   <img src="Images/Background4.png" width="500">

5. Depois clique em **Add a File ou em Add a URL** e adicione o caminho do arquivo da imagem no seu PC ou uma URL...

    <img src="Images/Background5.png" width="500">

6. No canto Direito Inferior vai aparecer um botão ***(Install and Reload)*** para reniciar e aplicar o Wallpaper.

    <img src="Images/Background6.png" width="500">


*Dica: Para imagens em alta definição, use um site de **UPSCALE** antes de colocar a imagem no VS Code.*

---

## 🛠️ 2. Configurando o Git e Terminal (Git Bash)

Esta configuração permite realizar **commits** diretamente pelo VS Code, garantindo que seu repositório seja atualizado em tempo real no GitHub sem a necessidade de comandos externos complexos.

OBS: FAÇA LOGIN NO GITHUB PARA EVITAR ERROS, BASTA IR NO CANTO INFERIOR ESQUERDO - - - PARA CONFIRMAR QUE FEZ O LOGIN, VEJA SE APARECE SEU NOME + (GITHUB). 

   <img src="Images/Github6.png" width="300">

### Passo a Passo para Instalação e Inicialização:

### Instalação e Inicialização:
1. Baixe o Git para Windows em: [git-scm.com/download/win](https://git-scm.com/download/win).

   <img src="Images/Github.png" width="200">

2. No VS Code, abra a aba de **Source Control** (ícone de ramificação na lateral) e clique em **Initialize Repository**.

   <img src="Images/Github1.png" width="200">

### Configuração de Identidade (Resolvendo Erros):

    Erro:

<img src="Images/Github4.png" width="450">


Se ao tentar dar um **Commit** aparecer um erro pedindo `user.name` e `user.email`, abra o seu terminal (Git Bash) e digite os seguintes comandos (um por vez mudando os dados para os da sua conta do Github):

<img src="Images/Github2.png" width="400">

```bash
git config --global user.name "SEU_NOME_AQUI"
git config --global user.email "SEU_EMAIL_DO_GITHUB@exemplo.com"
```

<img src="Images/Github3.png" width="500">

*Após rodar os comandos (uma linha por vez, dando Enter), feche o Visual Studio Code e abra-o novamente. Tente fazer o commit mais uma vez.*

---

## 🚀 3. Conectando com o GitHub e Publicando

Com a identidade configurada e confirmada, você já pode enviar seu repositório para a nuvem.

1. Na aba de Source Control, clique em **Publish Branch**.

   <img src="Images/Github5.png" width="300">

2. O VS Code pode pedir permissão para acessar o GitHub com a mensagem *"The extension 'GitHub' wants to sign in using GitHub"*. Clique em **Allow**.

   <img src="Images/Github7.png" width="400">

3. Na barra superior que aparecer, escolha se o repositório será **Público** ou **Privado**.

   <img src="Images/Github8.png" width="400">

4. Provavel que abra uma aba no navegador pedindo para autorizar. Clique em **Sign in with your browser** e faça o login.

   <img src="Images/Github9.png" width="400">

5. Vá no site do GitHub, acesse seu perfil em seus repositórios e verifique se o repositório foi criado certinho.

   <img src="Images/Github10.png" width="400">

### ⚠️ Verificação de Perfil (Caso dê erro)
Vá no ícone de Conta/Perfil no canto inferior esquerdo do VS Code e confira se a sua conta do GitHub aparece logada.

   <img src="Images/Github6.png" width="300">

Se não estiver e estiver dando erro, vá na aba de extensões, pesquise e instale separadamente a extensão **GitHub Pull Requests and Issues**.

   <img src="Images/Github11.png" width="400">


## 🔄 4. Commitando e Sincronizando Alterações (Push)

Depois de realizar o commit localmente, você precisa enviar essas mudanças para o servidor do GitHub para que outras pessoas (ou você em outro PC) possam ver.

1. No canto inferior esquerdo ou na aba de Source Control, clique no ícone de setas circulares ou no botão **Sync Changes**.
   > ![COLOQUE_A_IMAGEM_BOTAO_SYNC_CHANGES_AQUI]

2. Se aparecer um aviso sobre o "Push" e "Pull", clique em **OK**. Isso fará com que o VS Code envie suas fotos/códigos novos e baixe qualquer coisa que tenha mudado no site.
   > ![COLOQUE_A_IMAGEM_AVISO_PUSH_PULL_AQUI]

---

**Feito com ❤️ por B4_Lord**