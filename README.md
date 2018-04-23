# whisper-demo  

### geth start

- geth --shh --networkid 1114 --nodiscover --maxpeers 2 --datadir /home/sooyoung/data --rpc --rpcaddr "0.0.0.0" --rpcport 8545 --rpccorsdomain "*" --rpcapi "admin,db,eth,debug,miner,net,shh,txpool,personal,web3" console 2>> /home/sooyoung/data/geth.log

### node.js server start
 
- npm install express

- node app_express.js
