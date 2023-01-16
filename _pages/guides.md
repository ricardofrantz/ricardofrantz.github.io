---
permalink: /guides/
title: "Guides"
author_profile: true
redirect_from: 
  - /md/
  - /guides.html
---

Installing Python:
----

Linux Deb (\textit{e.g.,} Ubuntu, Pop OS, Kali, Mint):
```bash
sudo apt update && apt upgrade
sudo apt install python3-scipy python3-matplotlib
```

Linux Rpm (\textit{e.g.,} Red Hat, Fedora, CentOS):
```bash
sudo dnf install
```

macOS:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" # install brew
xcode-select --install # install XCode Command Line Tools
brew update && brew upgrade && brew cleanup
brew install python3-scipy python3-matplotlib 
```

Too complicated with bash? Try instead...   
[Anaconda](https://anaconda.com/products/distribution) and [VS Code](https://code.visualstudio.com}{code.visualstudio.com) (works with [Github Copilot](https://github.com/features/copilot))

Other interesting Linux packages:
----
- _vim_
- _meld_
- _htop_
- _terminator_
- _gimp_
- _inkscape_
- _gmsh_

Windows
=====
You can now install an Linux terminal environment in Windows via [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install) without the need for virtual machines.
- [Install Ubuntu on WSL for Windows 10 >](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview)
- [Install Ubuntu on WSL for Windows 11 >](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#1-overview)



Paraview
=====
Get the latest version at [paraview.org](https://www.paraview.org/download) or also try [VisIt](https://visit-dav.github.io/visit-website/index.html) instead. 

For Linux users you can unzip the content in your *$HOME* folder and add an alias your *.bashrc*
```bash
unzip ParaView-5.11.0-MPI-Linux-Python3.9-x86_64.tar.gz # then move it to your $HOME
sudo vi $HOME/.bashrc
alias paraview="$HOME/ParaView-5.11.0-MPI-Linux-Python3.9-x86_64/bin/paraview"
```

