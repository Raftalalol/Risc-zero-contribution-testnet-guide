# Risc-zero-contribution-testnet-guide
Risc Zero Contributed | Phase 1: Trusted Setup Ceremony

## Install Bahan Bahan di VPS Kalian :

sudo apt-get update && sudo apt-get install -y ca-certificates curl gnupg
curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
NODE_MAJOR=20
echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list
sudo apt-get update && sudo apt-get install nodejs -y

apt install screen

curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | sh -
source ~/.profile
mkdir p0tion-tmp
cd p0tion-tmp
nvm install 16.20
nvm use 16.20
npm install @p0tion/phase2cli

## Authenticate Github account

npx phase2cli auth

➖ Copy Code 
➖ Open : https://github.com/login/device
➖ Masukan Code
➖ Autorize and Done

## Create New Screen :

screen -S risc

npx phase2cli contribute

➖ Klik Enter Enter Saja Sampai Ketemu You will have to wait for xxx contributors (~xx:xx:xx:00 (dd/hh/mm/ss)

➖ Klik CTRL A + D
➖ Done, Untuk Melihat Screen : screen -r risc
➖ Waiting Antirian > Kalo Dah Selesai Bagikan Tweet

Details Event : https://www.risczero.com/blog/ceremony-contribution-public-instructions

Details Tutorial : https://p0tion.super.site/ce8f7047468b41239dc512919644535c
