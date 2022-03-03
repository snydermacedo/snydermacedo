+++
title = "OpenMediaVault | Overview"
date = "2022-03-01T00:05:46-04:00"
author = "Snyder Macedo"
cover = "/img/omv01.jpg"
tags = ["nas", "openmediavault"]
keywords = ["nas", "openmediavault"]
description = "Visão geral do OpenMediaVault"
readingTime = true
+++

# OpenMediaVault | Overview

Olá, pessoal!

Apresento o OpenMediaVault (OMV para os íntimos)    

---

Este sistema operacional se trata de um NAS, baseado no Linux Debian.

> **NAS - Network Attached Storage**
*Um sistema NAS é um dispositivo de armazenamento conectado a uma rede que possibilita o armazenamento e a recuperação de dados de um local centralizado para usuários autorizados da rede e clientes heterogêneos.*[^1]

O OMV trata-se de uma solução pronta para uso (out-of-the-box), simples e fácil de usar, graças a sua Interface Web. Primariamente foi projetado para atuar em ambiente doméstico ou pequenos escritórios, mas não se limita só a esses cenários, podendo atuar também em ambiente corporativo. 

O sistema é construído em um design modular e pode ser facilmente estendido com Plugins disponíveis logo após a instalação do sistema básico.

![OMV Plugins](http://www.openmediavault.org/wp-content/uploads/2021/11/omv6_plugins.png)

Destaques:

- Disponível para plataformas x86-64 e ARM (sim pode ser instalando no seu Raspberry).
- Possui Interface Web bastante rica, para sua administração
- Pode ser controlado via SSH (se ativado)
- O acesso aos protocolos: FTP, SMB/CIFS ou NFS
- Gerenciamento de direitos de acesso para usuários e grupos.

### História                  

![OMV historia](https://www.openmediavault.org/wp-content/uploads/2021/11/omv6_login.png)

> A história do Openmediavault começou com Volker Theile, que foi o único desenvolvedor ativo do projeto FreeNAS no final de 2009. Volker ficou interessado em reescrever completamente o FreeNAS, para uso no Linux. Inicialmente, ele nomeou o pacote reescrito coreNAS . Pouco tempo depois, Volker descartou o nome coreNAS em favor de openmediavault . O lançamento inicial do Openmediavault foi em 17 de outubro de 2011. Ele é construído sobre camadas de software muito maduras e comprovadas e está em constante desenvolvimento. O Openmediavault depende do projeto Debian e usa seu sistema e repositórios como base. O foco do projeto é criar e manter um sistema NAS estável e extensível que seja intuitivo e fácil de usar.

---

### Hardware | Requisitos Mínimos
Para operações básicas do Servidor de Arquivos - 1 ou 2 usuários:
- Processador Intel Core 2 Duo ou AMD equivalente               
- 1 GB de RAM 
- Armazenamento:        
  - Disco para o OS: capacidade minima 4 GB
  - Disco para Dados: capacidade conforme a sua necessidade  

> **Observação**
*É necessário 2 discos, um exclusivo para o Sistema Operacional e outro para o Dados.*

![OMV End](http://www.openmediavault.org/wp-content/uploads/2021/11/omv6_dashboard.png)

Pessoal, vou ficando por aqui, nos próximos posts (sobre o OMV) trarei um guia de instalação mas, para quem já queira testar, aqui está o [link]([https://www.openmediavault.org/](https://www.openmediavault.org/))

Valeu, até a próxima.

[^1]: [NAS](https://www.seagate.com/br/pt/tech-insights/what-is-nas-master-ti/)                                                                
