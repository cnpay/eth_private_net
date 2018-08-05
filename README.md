geth --datadir ./datadir init ./genesis.json
geth --datadir ./datadir --networkid 1114 --mine --rpc --rpcapi="db,eth,net,web3,personal,miner,admin,shh,txpool,debug" --rpcaddr="0.0.0.0" --rpccorsdomain "*" console 2>> private_net1.log
