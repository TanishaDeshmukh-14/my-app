# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`9627ffcf`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`6e176151`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`6e176151`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`74be6d21`)
  
