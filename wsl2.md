# Setup Dev Environment with WSL2 on WIndows 11

Install WSL and Ubuntu

https://docs.microsoft.com/en-us/windows/wsl/install

https://docs.microsoft.com/en-us/windows/wsl/setup/environment

## On Ubuntu

### Setup ZSH

Install zsh: ```sudo apt install zsh```

Set zsh as default shell: ```chsh -s $(which zsh)```

Create a minimal .zshrc file https://gist.github.com/scottstanfield/fa1085c225069160225d18b1dc16ee1c

### Setup Starship prompt

Prerequisites
- install zip: ```sudo apt install zip```
- install fontconfig: ```sudo apt install fontconfig```

Install Nerd Font (FiraCode): ```sudo apt install fonts-firacode

(Manual installation)

- download a Nerd Font e.g. FiraCode ```wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/FiraCode.zip```
- unzip fonts to /usr/local/share/fonts ```sudo unzip  FiraCode.zip -d /usr/local/share/fonts```
- rebuild font cache ```sudo fc-cache -fv``` 

see https://askubuntu.com/questions/3697/how-do-i-install-fonts

Install starship prompt. Follow instructions on https://starship.rs/guide/

### Setup git

Install latest stable upstream version

```add-apt-repository ppa:git-core/ppa```

```apt update; apt install git```

See https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-git

## Windows

Install and configure VSCode. Follow instructions on https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-vscode
