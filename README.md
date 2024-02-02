# install_equito_testnet_node
This repository contains a script to update the Equito TestNet Node on the server

## Requirements
There are no special requirements. The bash script will install all necessary software and perform all configuration automatically.

You just need to install the 'wget' tool to make the possibility run and install it:
```
sudo apt install wget -y
```

## Feauters
- No features

## Notes
- Please note: This script will update the Equito node with all necessary components and run it on behalf of "root" user.
 
## Installation
To configure and install the Equito Node please run:
```
sudo wget https://raw.githubusercontent.com/AntonMashnin/equito-testnet/main/equito-update.sh
sudo chmod +x equito-update.sh
sudo ./equito-update.sh
```
