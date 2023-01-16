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
- 
