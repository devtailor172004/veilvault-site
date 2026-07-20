# 👑 VeilVault — The Royal Treasury of the Digital Age

**VeilVault** is a private tipping platform on **Base Sepolia** that lets you send ETH to any ENS name or wallet address — no accounts, no middlemen, no tracking.

> *Renaissance-inspired private banking for the blockchain era.*

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔒 **Private Dispatches** | Direct wallet-to-wallet transactions. No custody, no middlemen. |
| 🌐 **ENS Resolution** | Send tips to `vitalik.eth` instead of copying hex addresses. |
| 🏦 **Royal Treasury Dashboard** | Real-time balance, transaction history, activity heatmap, treasury health. |
| ⚡ **Base Sepolia** | Built on Base for low fees (~$0.01) and fast confirmations (~2 sec). |
| 🎨 **Renaissance Design** | Warm ivory, gold, brass — a premium financial institution experience. |
| 🔍 **Creator Search** | Find any ENS name or wallet address instantly. |

---

## 🚀 Live Demo

**→ [veilvault.vercel.app](https://veilvault.vercel.app)**

No installation needed. Just connect your MetaMask wallet on **Base Sepolia** testnet (Chain ID: 84532) and send your first dispatch.

> **Note:** This app uses Base Sepolia testnet. Get free test ETH from a [Base Sepolia faucet](https://www.alchemy.com/faucets/base-sepolia).

---

## 🏛️ The Royal Treasury Experience

```
┌─────────────────────────────────────┐
│         👑 VEILVAULT                │
│    The Royal Treasury               │
├─────────────────────────────────────┤
│                                     │
│   💰 Treasury Balance              │
│   0.0100 ETH                        │
│                                     │
│   📜 Book of Transactions          │
│   ├─ Dispatch to vitalik.eth       │
│   ├─ Dispatch to jesse.base.eth    │
│   └─ View all on BaseScan          │
│                                     │
│   📊 Treasury Health               │
│   ├─ Activity Heatmap              │
│   ├─ Volume Chart                  │
│   └─ Network Status                │
│                                     │
└─────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **[Next.js 15](https://nextjs.org/)** | React framework with App Router |
| **[wagmi](https://wagmi.sh/) + [viem](https://viem.sh/)** | Wallet connection & blockchain interaction |
| **[Framer Motion](https://www.framer.com/motion/)** | Animations & transitions |
| **[Base Sepolia](https://base.org/)** | L2 blockchain (Chain ID: 84532) |
| **[ENS](https://ens.domains/)** | Name resolution via `api.ensideas.com` |
| **[Tailwind CSS](https://tailwindcss.com/)** | Styling |
| **[Lenis](https://lenis.discourse.team/)** | Smooth scrolling |

---

## 📦 Getting Started

### Prerequisites

- **Node.js 18+** and **npm**
- **MetaMask** (or any WalletConnect-compatible wallet)
- **Test ETH** on Base Sepolia (get from a [faucet](https://www.alchemy.com/faucets/base-sepolia))

### Installation

```bash
# Clone the repository
git clone https://github.com/devtailor172004/veilvault.git
cd veilvault

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Environment Variables

Create a `.env.local` file (optional — app works without it):

```env
NEXT_PUBLIC_BASESCAN_API_KEY=your_basescan_api_key
```

---

## 🧭 How to Use

### 1. Open Your Treasury
Click **"Open Treasury"** to connect your MetaMask wallet. Ensure you're on **Base Sepolia** testnet.

### 2. Search for a Creator
Enter an ENS name like `vitalik.eth` or paste a `0x` wallet address.

### 3. Dispatch Payment
Choose an amount (0.001, 0.005, 0.01, 0.05, 0.1, 0.5 ETH or custom) and confirm in MetaMask.

### 4. View Your Royal Ledger
Navigate to the **Royal Ledger** dashboard to see your balance, transaction history, and treasury health.

---

## 📸 Screenshots

| Page | Description |
|------|-------------|
| **Hero** | Royal Treasury landing with animated vault door |
| **Dashboard** | Balance display, activity timeline, charts, treasury health |
| **Dispatch** | Creator search, amount presets, dispatch form |
| **FAQs** | Royal Decrees — common questions answered |

---

## 🌐 Social

- **GitHub**: [github.com/devtailor172004](https://github.com/devtailor172004)
- **Twitter / X**: [x.com/SoulBrook23825](https://x.com/SoulBrook23825)
- **Live App**: [veilvault.vercel.app](https://veilvault.vercel.app)

---

## 📄 License

MIT © 2026 VeilVault

---

> *"Private transactions on Base. Send dispatches through the Royal Treasury — no accounts, no tracking, no middlemen."*
