# Reth Snapshots

This repository provides snapshot files for the [Reth](https://github.com/bnb-chain/reth) network, enabling faster node synchronization.

## Available Snapshots

| Network       | Type        | Frequency | Size (Compressed) | Size (Decompressed) | Download Link                                                                                     | CheckSum                                                                 |
|---------------|-------------|-----------|-------------------|---------------------|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| BSC Mainnet   | FullNode    | Monthly   | 3.3TB             | 4.5TB              | [Download](https://snapshot.bsc-snapshot.workers.dev/bsc-reth-20241223.tar.lz4)             | 9f59cdcbea5a9fa2c5e61221e20a0e91(MD5)                                    |
| BSC Mainnet   | ArchiveNode | Monthly   | 5.47TB             | 8.6TB               | [Download](https://snapshot.bsc-snapshot.workers.dev/bsc-reth-archive-20241223.tar.lz4) | 65145fe358a5a5492c8691431b166d71(MD5)                                                                  |
| OPBNB Mainnet | FullNode    | Monthly   | 410GB             | 789GB               | [Download](https://opbnb-snapshot-mainnet.bnbchain.org/geth-reth-full-20241008.tar.gz)            | 945720671d518dde84dd0027671fa398c78a8ed7ea12cb91d9e2fdc0cec7b1a8(SHA256) |
| OPBNB Mainnet | ArchiveNode | Monthly   | 800GB             | 1.6TB              | [Download](https://opbnb-snapshot-mainnet.bnbchain.org/geth-reth-archive-20241031.tar.gz)         | d353c2ee686a2cabfe936e8b1c61a82834e32557b0e7f636d8b1dce1c7127736(SHA256) |

## Usage

### 1. BSC Mainnet FullNode/ArchiveNode

For detailed instructions on using the BSC Mainnet FullNode snapshot, refer to the [documentation](./guild/bsc-reth-snapshot.md).

### 2. opBNB Mainnet FullNode/ArchiveNode

For detailed instructions on using the opBNB Mainnet FullNode/ArchiveNode snapshot, refer to the [documentation](./guild/opBNB-reth-snapshot.md).

## Instructions

1. **Download:** Choose the desired snapshot from the table above and download the compressed file.
2. **Verify:** Use the provided checksum to ensure the file downloaded correctly.
3. **Extract:** Unzip the downloaded file to your Reth node's data directory.
4. **Start Node:** Configure your Reth node to use the extracted snapshot data.

## Disclaimer

These snapshots are provided as-is, with no guarantees of accuracy or completeness. Use at your own risk.
