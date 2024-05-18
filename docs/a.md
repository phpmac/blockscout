# A

```sh


docker compose -f docker-compose/docker-compose.yml up

docker compose -f docker-compose/geth.yml up


geth --datadir data0 --http --http.addr 0.0.0.0 --http.port 26153 --ws --ws.addr "0.0.0.0" --ws.port 26156 --http.corsdomain "*" --http.vhosts "*" --http.api "debug,db,eth,net,web3,personal,web3,miner,txpool" --port 30305 -allow-insecure-unlock  --nat extip:65.49.196.244 --miner.etherbase 0x51282275dfa31d8063fdc5f3e41dd18c1dceb5e7 --mine --miner.threads 2 --rpc.enabledeprecatedpersonal

/root/data0/geth.ipc

geth --datadir data0 --miner.etherbase 0x51282275dfa31d8063fdc5f3e41dd18c1dceb5e7 --mine --miner.threads 2 --rpc.enabledeprecatedpersonal




```
