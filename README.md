cryptonote-nodejs-pool
======================

High performance Node.js (with native C addons) mining pool for CryptoNote based coins. Comes with lightweight example front-end script which uses the pool's AJAX API. Support for Cryptonight (Original, Monero v7, Stellite v7), Cryptonight Light (Original, Aeon v7, IPBC) Cryptonight Fast (Electronero/Crystaleum), and Cryptonight Heavy (Sumokoin) algorithms.


````
sudo apt-get install build-essential libsodium-dev libboost-all-dev libgmp3-dev node-gyp libssl-dev -y

sudo apt-get update
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
source ~/.profile
nvm install 12.22.6
sudo apt-get install redis-server

git clone https://github.com/cbunting99/cryptonote-nodejs-pool.git pool
cd pool

npm update
````