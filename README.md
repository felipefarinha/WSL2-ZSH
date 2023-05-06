# WSL2-ZSH
Instalar ``WSL2`` e o terminal ``ZSH`` no Windows



> 
```
https://docs.microsoft.com/en-us/windows/wsl/install-win10
```

### Passo 1 (PowerShell Admin): 

digite: 
```
wsl --install
```
e depois 
```
wsl --set-default-version 2
```

<details>
  <summary>Pc mais velhos use:</summary>
  
```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart 
```
```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

</details>

### Passo 2
REINICIE O COMPUTADOR

### Passo 3 (Download the Linux kernel update package):
```
https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
```

### Passo 4 (PowerShell Admin):
```
wsl --set-default-version 2
```

### Passo 5 (Instale o docker):

Tutorial: 
```
https://docs.docker.com/docker-for-windows/install/
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
