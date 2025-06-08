
# My Setup

## Terminal
- Terminal: Ghostty
- Shell: ZSH
- File Manager: Yazi (plain)
- Text Editor: Neovim + NVChad + :TSInstall cpp

## ZSH Configuration
1. In `~/.zshrc` only code below and trash from prompt setup
    ```sh
    source ~/.config/zsh/zshrc
    ```
2. Some handy things:
    ```sh
    brew install zsh-completions zsh-autosuggestions zsh-syntax-highlighting
    ```
3. Powerlevel10k prompt:
    ```sh
    brew install powerlevel10k
    echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >> ~/.zshrc
    ```
