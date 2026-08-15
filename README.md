# dotfiles

My zsh configuration, version-controlled with git.

## Contents

- `zsh/zshrc` → symlinked to `~/.zshrc`
- `zsh/zshenv` → symlinked to `~/.zshenv`
- `zsh/dircolors` → symlinked to `~/.dircolors`
- `zsh/oh-my-zsh-custom` → symlinked to `~/.oh-my-zsh/custom`

## Setup on a new machine

```sh
git clone <repo-url> ~/dotfiles
ln -sf ~/my-zsh-config/zsh/zshrc ~/.zshrc
ln -sf ~/my-zsh-config/zsh/zshenv ~/.zshenv
ln -sf ~/my-zsh-config/zsh/dircolors ~/.dircolors
ln -sf ~/my-zsh-config/zsh/oh-my-zsh-custom ~/.oh-my-zsh/custom
```

(Oh My Zsh must be installed first: https://ohmyz.sh/)
