### 使用说明
1. geth --datadir ./datadir init ./genesis.json (首次)
2. geth --datadir ./datadir --networkid 1114 --mine --rpc --rpcapi="db,eth,net,web3,personal,miner,admin,shh,txpool,debug" --rpcaddr="0.0.0.0" --rpccorsdomain "*" --unlock=0,1,2,3,4 --password=./datadir/password console 2>> private_net1.log
