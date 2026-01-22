# Networking Basics #1

## Table of Contents
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Resources](#resources)
- [Project Structure](#project-structure)
- [Tasks Overview](#tasks-overview)

---

## Project Overview

This project continues the introduction to **computer networking fundamentals**, with a focus on **localhost behavior**, **IP address resolution**, and **basic network debugging tools**.

You will learn how local name resolution works, how network interfaces are configured on a Linux system, and how to test network connectivity and port listening using standard command-line utilities.

The project mainly covers:
- **localhost and loopback addresses**
- **0.0.0.0**
- **The `/etc/hosts` file**
- **Network interfaces and IP addresses**
- **Basic network testing with telnet and netcat**
- **Listening to ports on localhost**

You will also write **Bash scripts** to configure and inspect networking behavior on an Ubuntu system.

---

## Learning Objectives

By the end of this project, you should be able to explain to anyone, **without the help of Google**:

### General Concepts
- What **localhost** is
- What **127.0.0.1** represents
- What **0.0.0.0** means
- What the **`/etc/hosts`** file is and how it works
- How hostname resolution works locally

### Networking Tools
- How to display your machine’s **active network interfaces**
- How to retrieve attached **IPv4 addresses**
- How to test connectivity using **ping**, **telnet**, and **netcat**
- How to listen on a specific **TCP port** on localhost

---

## Requirements

### General
- Language: **Bash**
- Allowed editors: `vi`, `vim`, `emacs`
- Operating System: **Ubuntu 22.04**
- All files must end with a new line
- A `README.md` file at the root of the project folder is mandatory
- All Bash scripts must be **executable**
- All Bash scripts must pass **Shellcheck** (version 0.7.0 via `apt-get`) without any errors
- The first line of all Bash scripts must be exactly:

---

## Resources

### Read or watch:
- [What is localhost](https://en.wikipedia.org/wiki/Localhost)
- [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)
- [What is the hosts file](https://www.makeuseof.com/tag/modify-manage-hosts-file-linux/)
- [Netcat examples](https://www.thegeekstuff.com/2012/04/nc-command-examples/)

### Manuals:
- [`man ifconfig`](https://man7.org/linux/man-pages/man8/ifconfig.8.html)
- [`man telnet`](https://linux.die.net/man/1/telnet)
- [`man nc`](https://linux.die.net/man/1/nc)
- [`man cut`](https://man7.org/linux/man-pages/man1/cut.1.html)

---

## Project Structure

holbertonschool-network/
└── basics_1/
├── 0-change_your_home_IP
├── 1-show_attached_IPs
├── 2-port_listening_on_localhost
└── README.md

---

## Tasks Overview

| # | Task Name                   | Description                                         | File                            |
| - | --------------------------- | --------------------------------------------------- | ------------------------------- |
| 0 | Change your home IP         | Modify local hostname resolution using `/etc/hosts` | `0-change_your_home_IP`         |
| 1 | Show attached IPs           | Display all active IPv4 addresses on the machine    | `1-show_attached_IPs`           |
| 2 | Port listening on localhost | Listen on TCP port 98 on localhost using netcat     | `2-port_listening_on_localhost` |

---
