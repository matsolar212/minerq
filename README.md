RTEEJJeExFWaE9sZsqty4aJ5vZF8NAMi5W

yes | pkg update && pkg upgrade
yes | pkg install libjansson wget nano
mkdir ccminer && cd ccminer

wget https://raw.githubusercontent.com/Darktron/pre-compiled/generic/ccminer
wget https://raw.githubusercontent.com/Darktron/pre-compiled/generic/config.json
wget https://raw.githubusercontent.com/Darktron/pre-compiled/generic/start.sh
chmod +x ccminer start.sh


Configurasi

nano config.json


Menjalankan

~/ccminer/start.sh




nano ../usr/etc/bash.bashrc

cd ccminer/&&./start.sh


