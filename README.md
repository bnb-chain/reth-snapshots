# Reth Snapshots

This repository provides snapshot files for the [Reth](https://github.com/bnb-chain/reth) network, enabling faster node synchronization.

## Available Snapshots

| Network           | Type           | Frequency | Size (Compressed) | Size (Decompressed) | Download Link                               | CheckSum  |
|-------------------|----------------|-----------|-------------------|-------------------|-------------------|-----------------------------------|
| BSC Mainnet       | FullNode       | Monthly   | 2.7TB             |  3.81TB             | [Download](https://pub-c0627345c16f47ab858c9469133073a8.r2.dev/reth-20240819.tar.lz4)    | bbb325df85ed4cb9ee4c65c4102fc12d(MD5)               |
| OPBNB Mainnet     | FullNode       | Monthly   | 410GB               | 789GB             | [Download](https://opbnb-snapshot-mainnet.bnbchain.org/geth-reth-full-20240822.tar.gz)  | 747e167cc129e8a158fe3cb227b059645e63dd63c8997773f3e835fce4711b6d(SHA256)               |
| OPBNB Mainnet     | ArchiveNode       | Monthly   | 617GB               | 1.16TB             | [Download](https://opbnb-snapshot-mainnet.bnbchain.org/geth-reth-archive-20240822.tar.gz)  | 4683e637eb0bf566d9513cb9521118a15ae3d5013faa604c4144b561abfa9aba(SHA256)               |

## Usage

### 1. BSC Mainnet FullNode

For detailed instructions on using the BSC Mainnet FullNode snapshot, refer to the [documentation](./guild/bsc-reth-fullnode-snapshot.md).

### 2. opBNB Mainnet FullNode/ArchiveNode

For detailed instructions on using the opBNB Mainnet FullNode/ArchiveNode snapshot, refer to the [documentation](./guild/opBNB-reth-snapshot.md).

## Instructions

1. **Download:** Choose the desired snapshot from the table above and download the compressed file.
2. **Verify:** Use the provided MD5 checksum to ensure the file downloaded correctly.
3. **Extract:** Unzip the downloaded file to your Reth node's data directory.
4. **Start Node:** Configure your Reth node to use the extracted snapshot data.

## Disclaimer

These snapshots are provided as-is, with no guarantees of accuracy or completeness. Use at your own risk.
