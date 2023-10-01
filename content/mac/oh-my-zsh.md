---
title: "Oh My Zsh"
date: 2023-10-01T11:57:47+02:00
draft: false
---

- install [oh-my-zsh](https://ohmyz.sh)
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## useful plugins

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions \
     ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git \
     ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

- adjust `~/.zshrc`:
```bash
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```
- apply: `source ~/.zshrc`
