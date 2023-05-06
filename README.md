# WSL2-ZSH
Instalar ``WSL2`` e o terminal ``ZSH`` no Windows

### Links referência

> https://learn.microsoft.com/en-us/windows/wsl/setup/environment#set-up-your-linux-username-and-password

> https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/

# 

### Digite no PowerShell Admin:

```
wsl --install
```
```
wsl --set-default-version 2
```
atualize o kernel ``wsl --update``

att pacotes Ubuntu ``sudo apt update && sudo apt upgrade``

<details open>
  <summary>Distro específica</summary>

  ``wsl --list --online``
  ``wsl --install -d DISTRO-NAME``
</details>

# 

### Habilitar a plataforma de máquina virtual
```
Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform
```

### Baixe e instale esta atualização do kernel WSL 2 (obrigatório).

> https://apps.microsoft.com/store/detail/windows-subsystem-for-linux/9P9TQF7MRM4R?hl=en-us&gl=us&activetab=pivot%3Aoverviewtab

para descobrir o nome da distro digite ``wsl --list --verbose``

### definir como arquitetura padrão
```
wsl --set-default-version 2
```

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
