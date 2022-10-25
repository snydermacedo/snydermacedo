+++
title = "Vim - Comentar & DEScomentar"
date = "2022-10-24T00:58:04-04:00"
author = "Snyder Macedo"
cover = "/img/neovim.png"
tags = ["vim", "comment"]
keywords = ["vim", "comment"]
description = "Vim - Comentário em várias linhas"
readingTime = true
+++

# Comentar e DEScomentar | VIM

Olá, pessoal!

Deixando a piada _“como sair do vim”_ um pouco de lado... [^1]

Nesses últimos dias estou revisando alguns arquivos de configuração no servidor e me deparei com a seguinte situação: **“Comentar várias linhas no VIM”**.

---

Vamos ao passo a passo:

1. Precisamos acessar o modo VISUAL/BLOCO.\
Para isso usamos o comando **CTRL + V** no VIM ou **CTRL + Q** para as derivações (gVim ou NeoVim). No meu caso, estou usando o NeoVim.
2. Agora mova o cursor até o ponto que você deseja comentar e pressione **SHIFT + I**.
3. Neste ponto é um pouco confuso mesmo, porém, vai funcionar.\
Pressione **# + ESPAÇO** e para finalizar pressione **ESC**.\
A mágica está feita. Abaixo deixarei um vídeo mostrando o processo.

><script id="asciicast-529636" src="https://asciinema.org/a/529636.js" async></script>

Agora vamos DEScomentar!

1. Novamente vamos acessar o modo VISUAL/BLOCO - **CTRL + V** ou **CTRL + Q**.
2. Selecione o local que vamos remover o comentário.
3. Para finalizar pressione **X** - Vídeo abaixo

><script id="asciicast-529647" src="https://asciinema.org/a/529647.js" async></script>

Pessoal, vou ficando por aqui, valeu!

[Fonte](https://gist.github.com/ultim8k/d8326a0cd7646356acf0dc3baf8e78ff)

[^1]: [exit to vim](https://cdn.thenewstack.io/media/2022/08/0ae25624-exit-vim-the-arrival-way-6n632sipjag61-1024x692.jpg)
