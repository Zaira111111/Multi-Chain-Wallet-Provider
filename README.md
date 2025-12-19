# 💳 Multi-Chain Wallet Provider

A non-custodial web-based wallet dashboard that allows users to manage assets across multiple EVM-compatible chains.

## 🚀 Features
- **Multi-Chain Support:** Connect to Ethereum, Polygon, Arbitrum, and Optimism.
- **Unified Balance View:** See your ETH and ERC20 token balances across all networks.
- **Network Switcher:** Switch between chains with a single click.
- **Transaction History:** View recent on-chain activities.
- **Safe & Secure:** Uses RainbowKit and Wagmi for secure wallet connections.

## 🛠️ Tech Stack
- **Frontend:** Next.js / React.js
- **Wallet Connection:** RainbowKit & Wagmi
- **Blockchain Interaction:** Viem / Ethers.js
- **Styling:** Tailwind CSS

## ⚙️ How to Use
1. Clone the repo: `git clone [Your-Repo-Link]`
2. Install: `npm install`
3. Add your Alchemy/Infura ID in `.env.local`
4. Start: `npm run dev`

## 💡 Architecture
The app uses a **Provider-Consumer** pattern where the Wallet Provider wraps the entire application, allowing any component to access the user's address and balance safely.
