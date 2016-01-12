Un tutorial para instalarlo:
https://www.digitalocean.com/community/tutorials/how-to-install-node-js-with-nvm-node-version-manager-on-a-vps

Menos la ultima parte que te lo pone como sudo

Luego añadir la version actual de node con alias default

Finalmente, ejecutar en consola:

vim ~/.bashrc 

Añadir en el fichero:
source ~/.nvm/nvm.sh
nvm use default
