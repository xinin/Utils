brew update
brew install nvm
mkdir ~/.nvm
vim ~/.bash_profile
          export NVM_DIR=~/.nvm
          source $(brew --prefix nvm)/nvm.sh
source ~/.bash_profile
nvm --version        
 
______________

Un tutorial para instalarlo:
https://www.digitalocean.com/community/tutorials/how-to-install-node-js-with-nvm-node-version-manager-on-a-vps

Menos la ultima parte que te lo pone como sudo

Luego:

$ nvm alias default 4.4.7

Añadir en el fichero "vim ~/.bashrc" :
source ~/.nvm/nvm.sh nvm use default
