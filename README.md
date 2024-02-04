# debian_wireguard_docker
*Installs docker and the linuxserver/wireguard container. Creates 2 different docker networks called **vpn** (internet connection) and **local** (no internet connection) for split-tunneling. Wireguard connects to both networks to allow access of local services over the VPN connection. New docker containers should only be added to the **local** network to block public access. Script should be run by a sudo user that owns all the docker containers. Container is created in `~/docker/wireguard`.*
### To run:
`wget -O script.sh https://raw.githubusercontent.com/leonb033/debian_wireguard_docker/main/script.sh && bash script.sh`
