## BSC Reth Fullnode Snapshot Usage

Get the latest BSC Reth fullnode snapshot from the [Reth Snapshots](../README.md) page.

## Download
```bash
wget ${DOWNLOAD_LINK} -O bsc-reth.tar.lz4
```

## Verify
```bash
md5sum bsc-reth.tar.lz4
```

## Extract
```bash
tar -I lz4 -xvf bsc-reth.tar.lz4 -C ${PATH_TO_RETH_DATA}
```

## Start Node
```bash
bsc-reth node \
    --datadir=${PATH_TO_RETH_DATA}/server-reth \
    --chain=${network} \
    --http \
    --http.api="eth, net, txpool, web3, rpc" \
    --full
```