# Reth Snapshots

This repository provides snapshot files for the [Reth](https://github.com/bnb-chain/reth) network, enabling faster node synchronization.

## Available Snapshots

| Network           | Type           | Frequency | Size (Compressed) | Download Link                               | MD5  |
|-------------------|----------------|-----------|-------------------|-------------------|-----------------------------------|
| BSC Mainnet       | FullNode       | Monthly   | 2.7TB             | [Download](https://pub-c0627345c16f47ab858c9469133073a8.r2.dev/reth-20240819.tar.lz4)    | bbb325df85ed4cb9ee4c65c4102fc12d               |
| OPBNB Mainnet     | FullNode       | Monthly   | TBD               | [Download](https://...)  | TBD               |

## Usage

### 1. BSC Mainnet Fullnode

For detailed instructions on using the BSC Mainnet FullNode snapshot, refer to the [documentation](./guild/bsc-reth-fullnode-snapshot.md).

## Instructions

1. **Download:** Choose the desired snapshot from the table above and download the compressed file.
2. **Verify:** Use the provided MD5 checksum to ensure the file downloaded correctly.
3. **Extract:** Unzip the downloaded file to your Reth node's data directory.
4. **Start Node:** Configure your Reth node to use the extracted snapshot data.

## Disclaimer

These snapshots are provided as-is, with no guarantees of accuracy or completeness. Use at your own risk.