# opBNB Reth FullNode/ArchiveNode Snapshot Usage

Follow these steps to get and set up the latest opBNB Reth FullNode/ArchiveNode snapshot from the [Reth Snapshots](../README.md) page.

## Download Snapshots and Extract to Reth Path

You have two options to download and extract the snapshot data.

### Option 1: Download, Verify, and Extract

1. **Download the snapshot file:**

```bash
wget ${DOWNLOAD_LINK} -O opBNB-reth.tar.gz
```

2. **Verify the file's integrity using sha256sum:**

```bash
sha256sum opBNB-reth.tar.gz
```

3. **Extract the data to the Reth path:**

```bash
tar -zxvf opBNB-reth.tar.gz -C ${PATH_TO_RETH_DATA}
```

### Option 2: Download and Extract in a Single Step

Use this option to download and extract the data in one step via piping:

```bash
wget ${DOWNLOAD_LINK} -O- | tar -zxvf - -C ${PATH_TO_RETH_DATA}
```

## Start the Node

After the data has been extracted, you can start your opBNB Reth node with the following command:

### FullNode

```bash
export network=mainnet
export L2_RPC=https://opbnb-mainnet-rpc.bnbchain.org

op-reth node \
    --datadir=${PATH_TO_RETH_DATA} \
    --chain=opbnb-${network} \
    --rollup.sequencer-http=${L2_RPC} \
    --authrpc.addr="0.0.0.0" \
    --authrpc.port=8551 \
    --http \
    --http.api="eth, net, txpool, web3, rpc" \
    --full
```

### ArchiveNode

```bash
export network=mainnet
export L2_RPC=https://opbnb-mainnet-rpc.bnbchain.org

op-reth node \
    --datadir=${PATH_TO_RETH_DATA} \
    --chain=opbnb-${network} \
    --rollup.sequencer-http=${L2_RPC} \
    --authrpc.addr="0.0.0.0" \
    --authrpc.port=8551 \
    --http \
    --http.api="eth, net, txpool, web3, rpc"
```
