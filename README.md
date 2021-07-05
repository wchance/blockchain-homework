

## Intructions to start Node1
./geth --datadir node1 --unlock "1E9Fc469FfE285228107CA63A98d7869A93BF189" --mine --miner.threads 1

## Intructions to start Node2
./geth.exe --datadir node2 --unlock "B1F8B855dD47239Ef8eC38304753E9Bc75DB2212" --port 30304 --http --bootnodes "enode://f018ba3233571c075037548d5d2946b47f31dff2f6173acf172e1312c914bd572c0c2dcbc21ce83dc413a4e7721d9342592256804b9b9656c0343f2b41061a6a@127.0.0.1:30303"  --ipcdisable --allow-insecure-unlock --mine --miner.threads 1

## Data directory for the databases and keystore
--datadir value

## Comma separated list of accounts to unlock
--unlock value

## Enable mining
--mine

## Number of CPU threads to use for mining (default: 0)
--miner.threads value

## Network listening port (default: 30303)
--port value

## Enable the HTTP-RPC server (deprecated and will be removed June 2021, use --http)
--rpc

## Enable the HTTP-RPC server
--http

## Comma separated enode URLs for P2P discovery bootstrap
--bootnodes value

## Disable the IPC-RPC server
--ipcdisable

## Allow insecure account unlocking when account-related RPCs are exposed by http
--allow-insecure-unlock
