---
permalink: /guides/
title: "Guides"
author_profile: true
redirect_from: 
  - /md/
  - /guides.html
---

# Installing Python

## Linux

### Debian-based (e.g., Ubuntu, Pop OS, Kali, Mint)

Install Python and necessary packages using the following command:

```bash
sudo apt update && apt upgrade
sudo apt install python3-scipy python3-matplotlib
```

### RPM-based (e.g., Red Hat, Fedora, CentOS)

To install Python and necessary packages, use the following command:

```bash
sudo dnf install python3-scipy python3-matplotlib
```

## macOS

To install Python and necessary packages on macOS, follow these steps:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" # install brew
xcode-select --install # install XCode Command Line Tools
brew update && brew upgrade && brew cleanup
brew install python3-scipy python3-matplotlib 
```

If you find working with the command line too complicated, you can alternatively use [Anaconda](https://anaconda.com/products/distribution) and [VS Code](https://code.visualstudio.com). These tools are compatible with [Github Copilot](https://github.com/features/copilot).

## Other useful Linux packages

Here is a list of other interesting Linux packages that you might find helpful:

- vim
- meld
- htop
- terminator
- gimp
- inkscape
- gmsh

## Windows

With [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install), you can now install a Linux terminal environment on Windows without the need for virtual machines.

- [Install Ubuntu on WSL for Windows 10 >](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview)
- [Install Ubuntu on WSL for Windows 11 >](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#1-overview)

# Paraview

You can download the latest version of Paraview at [paraview.org](https://www.paraview.org/download) or try [VisIt](https://visit-dav.github.io/visit-website/index.html) as an alternative.

For Linux users, you can unzip the content in your *$HOME* folder and add an alias to your *.bashrc*:

```bash
unzip ParaView-5.11.0-MPI-Linux-Python3.9-x86_64.tar.gz # then move it to your $HOME
sudo vi $HOME/.bashrc
alias paraview="$HOME/ParaView-5.11.0-MPI-Linux-Python3.9-x86_64/bin/paraview"
```
