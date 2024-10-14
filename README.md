# Reth Snapshots

This repository provides snapshot files for the [Reth](https://github.com/bnb-chain/reth) network, enabling faster node synchronization.

## Available Snapshots

| Network       | Type        | Frequency | Size (Compressed) | Size (Decompressed) | Download Link                                                                                     | CheckSum                                                                 |
|---------------|-------------|-----------|-------------------|---------------------|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| BSC Mainnet   | FullNode    | Monthly   | 2.7TB             | 3.81TB              | [Download](https://pub-c0627345c16f47ab858c9469133073a8.r2.dev/bsc-reth-20241011.tar.lz4)             | c5be7be4defd37788d4acbe1a1fcf67b(MD5)                                    |
| BSC Mainnet   | ArchiveNode | Monthly   | 5.1TB             | 6.9TB               | [Download](https://pub-c0627345c16f47ab858c9469133073a8.r2.dev/bsc-reth-archive-20241011.tar.lz4) | c5be7be4defd37788d4acbe1a1fcf67b(MD5)                                                                  |
| OPBNB Mainnet | FullNode    | Monthly   | 410GB             | 789GB               | [Download](https://opbnb-snapshot-mainnet.bnbchain.org/geth-reth-full-20241008.tar.gz)            | 945720671d518dde84dd0027671fa398c78a8ed7ea12cb91d9e2fdc0cec7b1a8(SHA256) |
| OPBNB Mainnet | ArchiveNode | Monthly   | 617GB             | 1.16TB              | [Download](https://opbnb-snapshot-mainnet.bnbchain.org/geth-reth-archive-20240822.tar.gz)         | 4683e637eb0bf566d9513cb9521118a15ae3d5013faa604c4144b561abfa9aba(SHA256) |

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
