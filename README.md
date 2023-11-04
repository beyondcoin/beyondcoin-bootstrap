# beyondcoin-bootstrap

This repository contains the most recent bootstrap chain files for the Beyondcoin blockchain before the seednodes went offline. The blockchain/bootstrap files are current as of the last time the chain was active (11-11-2021).

**Note:** checkout the release page for the blockchain bootstrap files, don't download the repo source zip.

---


## Instructions

1. Download the latest bootstrap files.
   - [Download Bootstrap Files Here](https://github.com/beyondcoin/bootstrap/releases)

2. After the download is complete, locate the downloaded bootstrap.zip or bootstrap.tar and double-click it. This will extract the contents and display the folders: blocks and chainstate.

3. Move the blocks and chainstate folders to the Beyondcoin data directory.
   - For Windows: `C:\Users\[YourUsername]\AppData\Roaming\Beyondcoin`
   - For macOS: `~/Library/Application Support/Beyondcoin`
   - For Linux: `~/.beyondcoin`

4. Download the latest Beyondcoin Core wallet.
   - [Beyondcoin Core Download](https://github.com/beyondcoin/beyondcoin/releases/tag/v0.17.1)

5. Install and run the wallet. It should start syncing from the point where the bootstrap file left off.


## Checksums

### bootstrap.tar
- md5: d8937934512cb280106a30fd331be5dc
- sha256: f567b8672014df2daf92c20c4258dabd0d8e07c8fcc5871934c7d44a2487ae9a

### bootstrap.zip
- md5: 955fe3343eb05dc1a92555570194556f
- sha256: 0dccf51b7c9c0ef1ff1f1bbf8b0d1e2d7b31930741fd35d61828d701284498fd
