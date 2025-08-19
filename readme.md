# Packages to Install

## Essential Packages

```bash
sudo apt update && sudo apt install unzip zsh stow tmux
```

## Tmux plugin manager

https://github.com/tmux-plugins/tpm

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Oh-my-zsh

https://ohmyz.sh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## OMZ plugins

### zsh-syntax-highlighting

https://github.com/zsh-users/zsh-syntax-highlighting

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

### zsh-autosuggestions

https://github.com/zsh-users/zsh-autosuggestions

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

## Starship

https://starship.rs

```bash
curl -sS https://starship.rs/install.sh | sh
```

## Fzf

https://github.com/junegunn/fzf

```bash
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

## Tmuxifier

https://github.com/jimeh/tmuxifier

## Lazygit

https://github.com/jesseduffield/lazygit/releases

## Lazydocker

https://github.com/jesseduffield/lazydocker/releases

## NvChad

https://nvchad.com/docs/quickstart/install

```bash
sudo apt update && sudo apt install unzip ripgrep gcc make
```

https://nodejs.org/en/download