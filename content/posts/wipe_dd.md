+++
title = "Wipe Disk | dd"
date = "2023-02-21T20:58:57-04:00"
author = "Snyder Macedo"
cover = "https://pplware.sapo.pt/wp-content/uploads/2013/04/imagem_limpar_pc-600x400.jpg"
tags = ["Wipe", "dd"]
keywords = ["Wipe", "dd"]
description = "Wipe - Limpando discos"
readingTime = true
+++

# Wipe Disk com dd

Olá, pessoal!

Neste post vou mostra a vocês como fazer:

```
Wipe Disk | Limpeza de Disco
```

Diferente de uma formatação, o Wipe sobrescreve os bits do seu dispositivo com zer0s, dificultando e muito a recuperação dos dados.
Esse procedimento é recomendado quando vamos fazer uma doação ou venda.

Bem, para executar o wipe vou usar a ferramenta ‘dd', o comando vai ficar assim:

```sh:
# dd if=/dev/zero of=/dev/sdX bs=4096 status=progress
```

Vamos a explicação:

 - if     – origem | vamos usar o arquivo especial /dev/zero
 - of     – destino | informamos o disco que queremos limpar (se atente ao X)
 - bs     -  a quantidade de bytes lido ou escrito por vez
 - status – mostra estatísticas periódicas de transferência.

---

Como exemplo, vou executar o comando em um pendrive.  
Para descobrir o caminho do pendrive vou usar o comando:

```sh:
sudo fdisk -l
```
Retornando a informação:

```
Disco /dev/sdb: 3,61 GiB, 3880452096 bytes, 7579008 setores
Modelo de disco: USB DISK 2.0    
Unidades: setor de 1 * 512 = 512 bytes
Tamanho de setor (lógico/físico): 512 bytes / 512 bytes
Tamanho E/S (mínimo/ótimo): 512 bytes / 512 bytes
Tipo de rótulo do disco: gpt
Identificador do disco: 7D7473EA-FCE2-4E11-B09B-A49D0A25CE4C
```

Na primeira linha já informa o caminho "/dev/sdb"

Pronto, vamos fazer "Wipe" neste pendrive, o nosso comando vai ficar assim:

```sh:
% sudo dd if=/dev/zero of=/dev/sdb bs=4096 status=progress
```

Ao término, o processo vai ficar assim:

![Wipe Red Drive](/img/wipe-red-drive.png)

---

Caso queria assistir todo o procedimento, só ficou um pouco extenso:

<script async id="asciicast-560449" src="https://asciinema.org/a/560449.js"></script>

---

Pessoal, vou ficando por aqui, valeu!
