
# Daemon

Daemon is a next-generation decentralized finance (DeFi) platform that leverages Anduro’s sidechain technologies to create a revolutionary trading system. The platform allows users to buy NFTs representing real US company stocks, providing an innovative way to collateralize and trade these assets in a decentralized manner. Users can leverage these assets for borrowing, lending, or selling them on a peer-to-peer (P2P) market, all while enjoying enhanced scalability and reduced transaction fees.

## Inspiration

The rapid evolution of DeFi has unlocked new financial innovations. We envisioned a system where stocks could be represented as NFTs on the blockchain, enabling global access to stock trading without cumbersome paperwork. This idea combines the transparency and efficiency of blockchain technology with the traditional financial market, facilitating seamless transactions and asset management.

## What It Does

Daemon provides a platform for creating and trading NFTs backed by real US company stocks. This allows users to:

- **Buy NFTs**: Acquire NFTs representing ownership of real stocks.
- **Collateralize Assets**: Use NFTs as collateral for borrowing or lending.
- **Trade P2P**: Engage in peer-to-peer trading of NFTs, leveraging the decentralized nature of the platform.

## How We Built It

We built Daemon on the Alys sidechain by Anduro, chosen for its promising Bitcoin Layer 2 scalability and EVM compatibility. The tech stack includes:

- **Smart Contracts**: Developed using Solidity, deployed on the Alys sidechain.
- **Application**: Built with Next.js, utilizing wagmi/viem for seamless blockchain interactions.

### Challenges

- **Chainlink Support**: Limited support for Chainlink price feeds posed difficulties in obtaining accurate stock prices.
- **Data Integrity**: Ensuring the accuracy of data from third-party APIs while maintaining decentralization was a complex task.

### Accomplishments

- Successfully minted asset NFTs and facilitated their trade in the P2P market.
- Achieved a functional DeFi platform that balances decentralization with user experience.

### What We Learned

- The importance of balancing decentralization with user experience in financial applications.
- The need for rigorous testing and simulation to ensure reliability and performance in automated financial systems.

### What's Next

- **Cross-Chain Expansion**: Integrate additional blockchain networks to enhance the platform’s versatility.
- **Price Feeds**: Implement Chainlink price feeds and CCIP support for improved pricing accuracy and interoperability.

With Daemon, we aim to redefine the DeFi landscape by creating a platform that empowers users to manage their financial assets with unprecedented control and efficiency.

## Built With

- Foundry
- Next.js
- React
- Solidity
- Viem
- Wagmi

## Usage

### Build

```bash
forge build
```

### Test

```bash
forge test
```

### Format

```bash
forge fmt
```

### Gas Snapshots

```bash
forge snapshot
```

### Anvil

```bash
anvil
```

### Deploy

```bash
forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```bash
cast <subcommand>
```
