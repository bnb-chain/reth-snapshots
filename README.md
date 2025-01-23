# ‼️ IMPORTANT NOTE ‼️

**BNB Reth Client: Temporary Suspension of Development**

We are announcing that the BNB Reth client will suspend development and maintenance. Our team has released the final maintenance version [v1.1.1](https://github.com/bnb-chain/reth/releases/tag/v1.1.1) as the last supported release.

Key Points:
  - The final maintenance release includes stability improvements and minor bug fixes.
  - Existing users can continue running BSC-reth and op-reth until the BSC/opBNB Pectra upgrade.
  - The BSC Pectra upgrade is scheduled for testnet on February 21st, 2025, with mainnet upgrade expected in mid-March 2025

While the Reth client will remain functional until the Pectra upgrade, we recommend users to gradually transition to other supported BSC clients, like [Geth](https://github.com/bnb-chain/bsc) and [Erigon](https://github.com/node-real/bsc-erigon). Please ensure you have the latest version installed for optimal performance during the remaining operational period.

**We sincerely thank our community for their continued support throughout BNB Reth's development journey.**

*January 22nd, 2025*

-------

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

-------

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
