# Reth Snapshots

This repository provides snapshot files for the [Reth](https://github.com/bnb-chain/reth) network, enabling faster node synchronization.

## Available Snapshots

| Network           | Type           | Frequency | Size (Compressed) | Size (Extracted) | Path                               | Checksum (SHA256)  |
|-------------------|----------------|-----------|-------------------|-------------------|-----------------------------------|-------------------|
| BSC Mainnet       | FullNode       | Monthly   | TBD               | TBD               | `/snapshots/bsc/mainnet/<date>`    | TBD               |
| OPBNB Mainnet     | FullNode       | Monthly   | TBD               | TBD               | `/snapshots/opbnb/mainnet/<date>`  | TBD               |

**Note:**

* `<date>` will be replaced with the snapshot creation date (e.g., `2024-08-01`).
* Checksums will be provided to verify the integrity of the downloaded files.

## Instructions

1. **Download:** Choose the desired snapshot from the table above and download the compressed file.
2. **Verify:** Use the provided SHA256 checksum to ensure the file downloaded correctly.
3. **Extract:** Unzip the downloaded file to your Reth node's data directory.
4. **Start Node:** Configure your Reth node to use the extracted snapshot data.

## Disclaimer

These snapshots are provided as-is, with no guarantees of accuracy or completeness. Use at your own risk.