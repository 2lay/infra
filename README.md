# 2lay/infra

Welcome to my infra repository! Here, you'll find the configuration files *(dotfiles)* I use across my servers.

## Overview

- **Production Servers**: I run the latest stable version of Debian to ensure its reliability.
- **Build Server**: I use Alpine Linux to build Docker containers due to its lightweight nature.

### Debian

Debian is my go-to for production environments. It's known for its:

- **Stability**: It’s rigorously tested, which means fewer surprises.
- **Package Management**: With APT, installing and managing software is a breeze.
- **Community Support**: There's a vast community behind it, making help and resources easy to find.

### Alpine Linux

When it comes to building and running containers, Alpine Linux is fantastic. Here’s why I like it:

- **Minimal Size**: Smaller images lead to faster downloads and less resource usage.
- **Musl libc**: This lightweight alternative to glibc can be a plus for many applications.
- **Security**: Designed with security in mind, it’s a great choice for any server setup.

## Contents WIP 

In this repo, you’ll find:

- `etc/ssh/sshd_config.d/`: My SSH server configurations.
- `bashrc`: Custom settings for a better Bash experience.
- `vimrc`: My Vim editor configuration.
- `gitconfig`: Handy Git settings and aliases.
- `tmux.conf`: Tmux configuration for better terminal management.
- Plus more dotfiles will be added as I go!

## Setup Instructions

To get started with these dotfiles, just follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/2lay.git ~/.dotfiles
   cd ~/.dotfiles
