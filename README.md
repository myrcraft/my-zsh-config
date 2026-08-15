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
ln -sf ~/dotfiles/zsh/zshrc ~/.zshrc
ln -sf ~/dotfiles/zsh/zshenv ~/.zshenv
ln -sf ~/dotfiles/zsh/dircolors ~/.dircolors
ln -sf ~/dotfiles/zsh/oh-my-zsh-custom ~/.oh-my-zsh/custom
```

(Oh My Zsh must be installed first: https://ohmyz.sh/)
