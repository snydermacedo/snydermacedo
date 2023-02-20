+++
title = "Iproute2"
date = "2023-01-31T20:53:32-04:00"
author = "Snyder Macedo"
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
readingTime = true
draft = true
+++

# Iproute2 | Net-Tools

Olá, pessoal!

Neste post quero mostra o Iproute2 o substituto do Net-Tools.

Ambos são utilitarios de linha de comandos para configura e solucionar problemas relacionados a Rede.
Entretanto o Net-Tools está obsoleto, e olha que já faz um tempo isso.
Mas ainda encontro tutorias usando comados do Net-Tools, então está é a ideia des post mostra o comandos novos com o Iproute2
Vamos lá!

---

Pessoal vou mostra uma tabela resumindo os comandos, mais abaixo predendo detalhos, blz.

| Comando Obsoleto | Comando Substituto |
| ---------------- | ------------------ |
| arp              | ip neighbor)      |
| ifconfig         | ip a (ip addr), ip link, ip -s (ip -stats) |
| iptunnel         | ip tunnel |
| iwconfig         | iw |
| nameif           | ip link, ifrename |
| netstat          | ss, ip route (for netstat-r), ip -s link (for netstat -i), ip maddr (for netstat-g) |
| route            | ip r (ip route)    |

