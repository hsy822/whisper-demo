# whisper-demo
ethereum whisper-demo web application

### geth command

```
// --shh
 > geth --shh --networkid 1001 --nodiscover --maxpeers 0 --datadir /home/sooyoung/data --rpc --rpcaddr "0.0.0.0" --rpcport 8545 --rpccorsdomain "*" --rpcapi "admin,db,eth,debug,miner,net,shh,txpool,personal,web3" console 2>> /home/sooyoung/data/geth.log
```

### nodejs start

```
 > npm install express
 > node app_express.js
```
