#Linux Prerequisites

sudo apt update && sudo apt upgrade && sudo apt install && sudo apt autoremove 

sudo sed  -i '6i vm.max_map_count=262144' /etc/sysctl.conf # auto adds persistent vm max for when system is restarted
sudo sysctl -p

sudo apt install curl
sudo apt install git
sudo apt install net-tools
sudo apt install docker
sudo apt install docker-compose

