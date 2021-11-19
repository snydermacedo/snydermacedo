+++
title = "Lançado o Proxmox 7.1"
date = "2021-11-18T19:17:21-04:00"
author = "Snyder Macedo"
cover = "/img/proxmox.png"
tags = ["proxmox", "virtualization"]
keywords = ["proxmox", "virtualization"]
description = "Proxmox 7.1 - Lançado"
showFullContent = false
readingTime = false
+++

Olá pessoal nesta última quarta-feira (17/11/2021), foi o lançamento do Proxmox 7.1, trazendo várias atualizações para os principais softwares **Open Source** na área da **Virtualização**, sendo eles: QEMU 6.1, LXC 4.0, Ceph Pacific 16.2.6 e ZFS 2.1.
Outra novidade é que está nova versão é baseada no Debian Bullseye 11.1, combinada com o kernel **Linux** 5.13 mais recente.

**Abaixo a lista de algumas novidades:**

* Definir a retenção de backup por trabalho de backup via GUI: isso permite que os usuários configurem políticas de backup inteligentes para cada trabalho de backup, não apenas da API e CLI, mas também da interface da web.
* Opções de agendamento avançadas para tarefas de backup: as tarefas de backup no Proxmox VE agora são executadas por um novo daemon de agendador, chamado pvescheduler, que oferece suporte a opções de agendamento mais flexíveis.
- Para máquinas virtuais, esta versão inclui suporte para adicionar o Trusted Platform Module (TPM) 2.0 a qualquer VM. Entre outras coisas, isso permite aos usuários instalar e executar o Windows 11.
- Os contêineres no Proxmox VE 7.1 agora oferecem suporte ao Fedora 35 e ao Ubuntu 21.10, bem como às distribuições AlmaLinux e Rocky Linux, incluindo modelos.

---

Agora é prepara o laboratório para os testes. ☢️

💾 **[Link para Download](https://www.proxmox.com/en/downloads/item/proxmox-ve-7-1-iso-installer)** 💾

Pessoal para mais informação segue o **[Link](https://www.proxmox.com/en/news/press-releases/proxmox-virtual-environment-7-1-released)** para a matéria completa.

Abaixo o vídeo do Canal Proxmox mostrando as novidades.

{{< youtube NLV6QPaHVFY >}}

Valeu galera!
-
