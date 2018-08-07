### 使用说明
1. 首次使用
geth --datadir ./datadir init ./genesis.json
2. 日常开发 
geth --datadir ./datadir --networkid 1114 --mine --minerthreads 1 --rpc --rpcapi="db,eth,net,web3,personal,miner,admin,shh,txpool,debug" --rpcaddr="0.0.0.0" --rpccorsdomain "*" --unlock=0,1,2,3,4 --password=./datadir/password console 2>> private_net1.log
3. 增加节点
修改目录位置(datadir)和监听端口(port)，其它同上

### 参考
https://medium.com/mercuryprotocol/how-to-create-your-own-private-ethereum-blockchain-dad6af82fc9f