# BSC Reth Fullnode Snapshot Usage

Follow these steps to get and set up the latest BSC Reth fullnode snapshot from the [Reth Snapshots](../README.md) page.

## Download Snapshots and Extract to Reth Path

You have two options to download and extract the snapshot data.

### Option 1: Download, Verify, and Extract

1. **Download the snapshot file:**

```bash
wget ${DOWNLOAD_LINK} -O bsc-reth.tar.lz4
```

2. **Verify the file's integrity using md5sum:**

```bash
md5sum bsc-reth.tar.lz4
```

3. **Extract the data to the Reth path:**

```bash
tar -I lz4 -xvf bsc-reth.tar.lz4 -C ${PATH_TO_RETH_DATA}
```

### Option 2: Download and Extract in a Single Step

Use this option to download and extract the data in one step via piping:

```bash
wget ${DOWNLOAD_LINK} -O- | tar -I lz4 -xvf - -C ${PATH_TO_RETH_DATA}
```

## Start the Node

After the data has been extracted, you can start your BSC Reth node with the following command:

### FullNode

```bash
bsc-reth node \
    --datadir=${PATH_TO_RETH_DATA}/server-reth \
    --chain=bsc \
    --http \
    --http.api="eth, net, txpool, web3, rpc" \
    --full
```

### ArchiveNode

```bash
bsc-reth node \
    --datadir=${PATH_TO_RETH_DATA}/server-reth \
    --chain=bsc \
    --http \
    --http.api="eth, net, txpool, web3, rpc"
```
