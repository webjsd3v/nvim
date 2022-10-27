# Конфигаруционный pack Neovim

Проект написан в рамках изучения конфигурирования Neovim

## Установка Neovim

Ubuntu
```
sudo apt install neovim
```

## Установка Node/NVM

Установка Wget 
```
 sudo apt install wget
```

### Установка NVM
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
```
```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
bash:
``` 
source ~/.bashrc
```

### Устновка Node

#### Список версий узла, установленных в данный момент (на данный момент их не должно быть):
```
nvm ls
```

#### Установите как текущую, так и стабильную LTS-версии Node.js :
```
nvm install --lts
```
#### Установите текущую версию Node.js : 
```
nvm install node
```

## Установка Plug

Unix/Linux
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

## Запуск 

```
 :PlugInstall 
```
