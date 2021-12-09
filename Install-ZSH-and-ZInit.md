# Install ZSH and ZInit

- Download the ZSH
 
 ` apt install zsh -y` or ` dnf install zsh`

- Check if it has been installed correctly

` zsh --version`

- Download the ZInit

`sh -c "$(curl -fsSL https://git.io/zinit-install)"`

- Add after the line `### End of ZInit's installer chunk` in the file `~/.zshrc`

`zinit light zdharma-continuum/fast-syntax-highlighting 
zinit light zsh-users/zsh-autosuggestions 
zinit light zsh-users/zsh-completions`

- Reload the file

` source .zshrc `
