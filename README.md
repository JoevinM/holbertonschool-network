# Networking Basics #0

## Table of Contents
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Resources](#resources)
- [Project Structure](#project-structure)
- [Tasks Overview](#tasks-overview)

---

## Project Overview

This project introduces the **fundamental concepts of computer networking**.  
It focuses on how devices communicate over networks, how data is transported, and how to troubleshoot connectivity issues using common networking tools.

The project mainly covers:
- The **OSI model**
- **LAN, WAN, and Internet**
- **IP addressing**
- **TCP vs UDP**
- **Ports and sockets**
- **Network diagnostics using ICMP and ping**

You will also write simple **Bash scripts** to inspect and test network behavior on a Linux system.

---

## Learning Objectives

By the end of this project, you should be able to explain to anyone, **without the help of Google**:

### OSI Model
- What the OSI model is
- How many layers it has
- How it is organized
- Why it is a conceptual (theoretical) model

### Networking Concepts
- What a LAN is
  - Typical usage
  - Typical geographical size
- What a WAN is
  - Typical usage
  - Typical geographical size
- What the Internet is

### IP Addressing
- What an IP address is
- The two types of IP addresses (private and public)
- What localhost is
- What a subnet is
- Why IPv6 was created

### Transport Layer
- The two main data transfer protocols used by IP
- The main difference between TCP and UDP
- What a port is
- Common port numbers:
  - SSH → 22
  - HTTP → 80
  - HTTPS → 443

### Network Diagnostics
- What ICMP is
- What tool/protocol is commonly used to check if a device is connected to a network

---

## Requirements

### General
- Language: **Bash**
- Allowed editors: `vi`, `vim`, `emacs`
- Operating System: **Ubuntu 22.04**
- All files must end with a new line
- A `README.md` file at the root of the project folder is mandatory

---

## Resources

### Read or watch:
- [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [Different types of networks](https://www.lifewire.com/lans-wans-and-other-area-networks-817376)
- [LAN network](https://en.wikipedia.org/wiki/Local_area_network)
- [WAN network](https://en.wikipedia.org/wiki/Wide_area_network)
- [Internet](https://en.wikipedia.org/wiki/Internet)
- [MAC address](https://whatismyipaddress.com/mac-address)
- [What is an IP address](https://www.bleepingcomputer.com/tutorials/ip-addresses-explained/)
- [Private and public IP addresses](https://www.iplocation.net/public-vs-private-ip-address)
- [IPv4 and IPv6](https://www.webopedia.com/insights/ipv6-ipv4-difference/)
- [Localhost](https://en.wikipedia.org/wiki/Localhost)
- [TCP and UDP](https://www.howtogeek.com/190014/htg-explains-what-is-the-difference-between-tcp-and-udp/)
- [TCP/UDP ports list](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [What is ping / ICMP](https://en.wikipedia.org/wiki/Ping_%28networking_utility%29)
- [Positional parameters](https://github.com/rawiriblundell/wiki.bash-hackers.org/blob/main/scripting/posparams.md)

### Manuals:
- [`man netstat`](https://man7.org/linux/man-pages/man8/netstat.8.html)
- [`man ping`](https://man7.org/linux/man-pages/man8/ping.8.html)

---

## Project Structure

holbertonschool-network/
└── basics_0/
    ├── 0-OSI_model
    ├── 1-types_of_network
    ├── 2-MAC_and_IP_address
    ├── 3-UDP_and_TCP
    ├── 4-TCP_and_UDP_ports
    ├── 5-is_the_host_on_the_network
    └── README.md

---

## Tasks Overview

| # | Task Name                  | Description                                                    | File                           |
| - | -------------------------- | -------------------------------------------------------------- | ------------------------------ |
| 0 | OSI model                  | Understand the OSI conceptual model and its layer organization | `0-OSI_model`                  |
| 1 | Types of network           | Identify LAN, WAN, and Internet usage scenarios                | `1-types_of_network`           |
| 2 | MAC and IP address         | Understand MAC and IP addressing concepts                      | `2-MAC_and_IP_address`         |
| 3 | UDP and TCP                | Compare reliability (TCP) vs speed (UDP)                       | `3-UDP_and_TCP`                |
| 4 | TCP and UDP ports          | Display listening ports and associated processes               | `4-TCP_and_UDP_ports`          |
| 5 | Is the host on the network | Check network connectivity using ICMP and ping                 | `5-is_the_host_on_the_network` |

---
