# Oracle-VMBox-no-Debian-10
Documentação da instalação e configuração do OracleVirtualBox no Debian 10

Instalando VirtualBox-6.1 no Debian 10


Para instalar o VirtualBox-6.1 no Debian 10 Buster, siga os passos abaixo.

1. Edite sua sources.list e adicione o repositório do programa

deb [arch=amd64] https://download.virtualbox.org/virtualbox/debian buster contrib

2. Adicione as chaves do novo repositório:

wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add -

3. Instale o VirtualBox 6.1:

sudo apt update && sudo apt install virtualbox-6.1
