# shell-map

## Setup 

```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
git clone https://github.com/OIEIEIO/shell-map.git
cd shell-map
npm install
node ./node_modules/geoip-lite/scripts/updatedb.js
```
* Node.js must be installed to use app
* The app can be launched with `node init.js`
* Settings are in config.js, and the default port it runs on is 8080

## inspired by:

https://github.com/Karbovanets/karbo-nodes-map

Many thanks to the awesome d3 library and d3 community contributions, as well as the turtlecoin community.


