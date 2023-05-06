# WSL2-ZSH
Instalar ``WSL2`` e o terminal ``ZSH`` no Windows

> https://learn.microsoft.com/en-us/windows/wsl/setup/environment#set-up-your-linux-username-and-password


### PowerShell Admin: digite: 

```
wsl --install
```
```
wsl --set-default-version 2
```

att pacotes Ubuntu ``sudo apt update && sudo apt upgrade``

### ZSH

```
sudo apt install zsh -y
sudo apt-get install powerline fonts-powerline -y
git clone https://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
chsh -s /bin/zsh

# REBOOT
# sudo reboot
```


### Passo 5 (Instale o docker):

Tutorial: 
```
https://docs.docker.com/docker-for-windows/install/
```
