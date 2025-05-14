# 🚀 Blink Factory: No-Code Dialect Blink Builder for Solana

Welcome to **Blink Factory**, a no-code platform for building and sharing interactive Blinks using [Dialect](https://www.dialect.to) on the Solana blockchain. This repository contains the full source code, configuration, and documentation for running and customizing the MVP of Blink Factory.

> ✨ Think: **Shopify for Solana Blinks** — Create, customize, and publish actionable UI cards without writing code.

---

## 🎯 Overview

**Blink Factory** enables anyone to:

- Use prebuilt or custom templates for actions like token transfers or NFT minting.
- Visually configure inputs and see live previews of Blinks.
- Share Blinks across Twitter/X, websites, or via direct links.
- Authenticate with Solana wallets and store Blinks offline or in JSON.

Built for creators, builders, and communities in Web3.

---

## 🧑‍💻 Development Environment

| Item | Details |
|------|---------|
| OS | Windows 10 |
| Blockchain | Solana Devnet/Testnet |
| Hosting | [Vercel](https://vercel.com) (Serverless-ready) |
| SDK | `@dialectlabs/blinks-sdk` |
| Frontend Design | Styled like [https://dial.to](https://dial.to) |
| Storage | JSON files only (no dynamic server/backend) |

---

## 🧰 Features

### 1. 📚 Template Library

- Categories: Token Transfers, NFT Minting, DAO Voting, Custom Blinks
- Filterable & searchable
- Each includes:
  - Thumbnail preview
  - Field schema (inputs)
  - Live Blink preview

### 2. 🔧 Visual Builder

- No-code interface
- Fill fields like NFT name, wallet address, image URL
- Customize CTA buttons
- Instant preview of:
  - `<Blink />` component
  - Twitter/X card (OpenGraph)

### 3. 📦 Publish & Share

- One-click “Publish”:
  - Generate public URL (`/blink/:id`)
  - Twitter card with `og:image`
  - Copyable embed snippet
  - QR Code for mobile

### 4. 💾 Save & Export

- Save Blinks to browser (`localForage`)
- Export JSON config
- Re-import or fork existing Blinks
- All config/state saved in `data/blinks.json`

### 5. 🔐 Wallet Auth

- Use Phantom or Backpack via Solana Wallet Adapter
- Authenticated users can:
  - Access private dashboard
  - View/edit saved Blinks

### 6. 🧠 Custom Blink Editor

- Developers can:
  - Submit new templates (form-based)
  - Write JSON or JavaScript config
  - Preview and publish

### 7. 📊 Analytics (MVP)

- Track:
  - Blink views
  - Clicks
  - Conversion counts (client-only)

---

## 🧪 Example: Mint NFT Blink

1. Choose the **NFT Minting** template
2. Fill in:
   - NFT Name
   - Image URL
   - Receiver Address
   - CTA: “Mint Now”
3. Preview Blink + Social Card
4. Publish to get:
   - URL: `bl.ink/mintnft/xyz123`
   - OG Preview
   - QR code
   - Embed script

---

## 🧱 MVP Checklist

| Feature | Status |
|--------|--------|
| Solana Wallet Auth | ✅ Phantom/Backpack |
| Dialect SDK Integration | ✅ `@dialectlabs/blinks-sdk` |
| Template Picker | ✅ Categories + Search |
| Visual Builder | ✅ Dynamic field generation |
| Share + Publish | ✅ URL + Embed + QR |
| JSON Export/Import | ✅ With validation |
| Developer Mode | ✅ JSON editor |
| OpenGraph Support | ✅ SEO & Twitter card |
| Analytics (Client-only) | ✅ Views & Clicks |
| Serverless JSON Storage | ✅ Static overwrite-based |

---


## 📦 Installation

```bash
git clone https://github.com/NeoV55/Blinker.git
```
```
cd blink-factory
```
```
npm install
```
Start Development Server
```bash
npm run dev
```


---

## 🧩 Post-MVP: Roadmap & Future Features

### 🔮 Cutting-Edge Plans

| Feature | Description |
|--------|-------------|
| 🤖 **AI Blink Generator** | GPT-powered natural language → Blink builder |
| 🔄 **Composable Blinks** | Flow editor (e.g., Mint → Transfer → Tweet) |
| 🎨 **Custom Skins** | Upload styles, themes, gradients |
| 📱 **Mobile PWA** | Offline-first Blink experience |
| 🧩 **Plugin Marketplace** | Devs can publish reusable templates |
| 📡 **Dynamic Behavior** | Show/hide based on wallet/NFT state |
| 🔬 **Smart Analytics** | Hover/click heatmaps, session replay |
| 💬 **Chat-Enabled Blinks** | Integrated GPT chat widgets |
| 🪙 **Monetization** | Stripe or Solana Pay to access premium Blinks |
| 🔐 **Encrypted Blinks** | Gated by DAO, NFT, or Lit Protocol |
| 🎁 **Airdrop GUI** | No-code interface for token drops |
| 🌐 **Multichain** | Add EVM, Cosmos with WalletConnect |
| 🛠️ **CLI & GitHub Sync** | BlinkFactory CLI + Git deploy |
| 📸 **Social Studio** | Design Tweet cards & OG images |
| 🧩 **Embed SDK** | `<script>` embed for websites |

---

## 📚 Resources

- [Dialect SDK Docs](https://docs.dialect.to)
- [Solana Wallet Adapter](https://github.com/solana-labs/wallet-adapter)
- [Vercel](https://vercel.com)
- [TailwindCSS](https://tailwindcss.com)
- [localForage](https://github.com/localForage/localForage)

---

## 🤝 Contributing

Want to add new templates or components?

1. **Fork** the repo
2. **Create a new branch**
3. **Add your template** to `/data/blinks.json`
4. **Submit a pull request** with a preview screenshot

---

## 📃 License

MIT License © 2025 
---

## 📬 Contact

For feedback or collaboration:

- Twitter: [@blinker](https://twitter.com/blinker)
- Email: hello@blinker.xyz

