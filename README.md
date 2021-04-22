# ZSH
Just my ZSH Config 

## Install required packages in Arch Linux
```
$ paru -S zsh zsh-syntax-highlighting zsh-autosuggestions
```

## Setup
Fetch zsh config:
```
$ wget https://gitlab.com/Nelox/zsh/-/raw/master/.zshrc -O ~/.zshrc
```
Download powerlevel10k:
```
$ git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
```

Finish the conversion by changing the shel for your user:
```
$ sudo chsh -s /bin/zsh <user>
```

## Install recommended Font
https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf
______________________________________________________________________________
