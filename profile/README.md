# MeNabung

> **Your AI-Powered DeFi Savings Buddy** — Chat, split, grow. Effortlessly.

**Built for [Base Indonesia Hackathon 2025](https://base-indonesia.devfolio.co/)**

---

## The Problem

DeFi yields are everywhere, but most users:

- Don't know **where** to put their money
- Don't know **how much** to allocate to each strategy
- Forget to **rebalance** when yields shift

**Result?** Missed opportunities and decision paralysis.

---

## The Solution: MeNabung

MeNabung ("saving" in Indonesian) is your **AI financial buddy** that makes DeFi simple:

### 1. AI Advisor — Tell it your goals

Chat naturally. The AI understands your risk tolerance and recommends a personalized strategy.

> *"I want to save 1M IDRX, I'm okay with some risk"*
>
> AI: *"Based on your profile, I recommend: 40% Options, 40% LP, 20% Staking for ~11.2% APY"*

### 2. Smart Fund Splitting — One deposit, multiple strategies

Your IDRX is automatically split across three yield sources:

| Strategy | Protocol  | APY  | Risk        |
| -------- | --------- | ---- | ----------- |
| Options  | Thetanuts | ~8%  | Medium      |
| LP       | Aerodrome | ~12% | Medium-High |
| Staking  | IDRX      | ~15% | Low         |

### 3. Auto-Rebalancing Notifications — Never miss a yield shift

The AI monitors your portfolio 24/7 and alerts you:

> *"LP yields up 50%! Move 10% from Options → LP for +0.8% APY boost?"*
>
> **[One-tap rebalance]**

---

## Features

| Feature                  | Description                                                 |
| ------------------------ | ----------------------------------------------------------- |
| **AI Chat Advisor**      | Natural language risk profiling & strategy recommendations  |
| **Multi-Strategy Vault** | Single deposit splits across options, LP, and staking       |
| **Smart Rebalancing**    | AI-powered suggestions when yields shift                    |
| **Gamification**         | Streaks, missions, and achievements to build savings habits |
| **Mobile-First**         | Farcaster Mini-App for on-the-go access                     |
| **Base L2**              | Sub-cent fees, instant transactions                         |

---

## How It Works

```text
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   DEPOSIT   │────▶│  AI SPLITS  │────▶│   YIELDS    │
│   IDRX      │     │  YOUR FUNDS │     │   GROW      │
└─────────────┘     └─────────────┘     └─────────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │  REBALANCE  │
                    │  ALERTS     │
                    └─────────────┘
```

---

## Repositories

| Repo                                                 | Description                           |
| ---------------------------------------------------- | ------------------------------------- |
| [`miniapp`](https://github.com/MeNabung/miniapp)     | Farcaster Mini-App (mobile-first PWA) |
| [`ui`](https://github.com/MeNabung/ui)               | Next.js 16 web app with AI advisor    |
| [`contracts`](https://github.com/MeNabung/contracts) | Foundry smart contracts on Base       |

---

## Tech Stack

**Frontend:** Next.js 16, React 19, Tailwind CSS 4, Motion, Wagmi, OnchainKit

**Smart Contracts:** Solidity 0.8.20, Foundry, OpenZeppelin

**AI:** OpenAI GPT-4o-mini with custom DeFi prompts

**Chain:** Base L2 (Mainnet)

---

## Roadmap

### Hackathon MVP (Now)

- [x] AI advisor with natural language risk profiling
- [x] Smart vault with automatic fund splitting
- [x] Gamification (streaks, missions, badges)
- [x] Farcaster Mini-App integration
- [x] Base L2 deployment

### Phase 1: Real Integrations

- [ ] Live Thetanuts vault integration
- [ ] Live Aerodrome LP positions
- [ ] On-chain portfolio tracking
- [ ] Push notification rebalance alerts

### Phase 2: Growth

- [ ] Bahasa Indonesia support
- [ ] Referral rewards program
- [ ] Social savings pools
- [ ] Additional yield sources

---

## Deployed Contracts (Base Mainnet)

| Contract             | Address                                                                                                                 | Description                                    |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **MeNabungVault**    | [`0x6313640dcf1f30449b80867ffa6ec2da112b6ae8`](https://basescan.org/address/0x6313640dcf1f30449b80867ffa6ec2da112b6ae8) | Main vault — splits deposits across strategies |
| **ThetanutsAdapter** | [`0xa5b686f20164dcb551088af94589fa37fd34899d`](https://basescan.org/address/0xa5b686f20164dcb551088af94589fa37fd34899d) | Options strategy (~8% APY)                     |
| **AerodromeAdapter** | [`0xfc6da968585ef7093b6a4efd07a4f42543dde3ef`](https://basescan.org/address/0xfc6da968585ef7093b6a4efd07a4f42543dde3ef) | LP strategy (~12% APY)                         |
| **StakingAdapter**   | [`0xd96e327a9db80c287e0720e789d7382973d7dfe5`](https://basescan.org/address/0xd96e327a9db80c287e0720e789d7382973d7dfe5) | Staking strategy (~15% APY)                    |

### External Contracts

| Contract       | Address                                                                                                               |
| -------------- | --------------------------------------------------------------------------------------------------------------------- |
| **IDRX Token** | [`0x18Bc5bcC660cf2B9cE3cd51a404aFe1a0cBD3C22`](https://basescan.org/token/0x18Bc5bcC660cf2B9cE3cd51a404aFe1a0cBD3C22) |

---

## License

MIT
