# MeNabung

> DeFi savings for Indonesian users — making yield accessible through AI guidance and gamification.

**Built for [Base Indonesia Hackathon 2025](https://base-indonesia.devfolio.co/) — Thetanuts Track**

## What is MeNabung?

MeNabung ("saving" in Indonesian) helps users grow their IDRX savings through automated DeFi strategies. An AI advisor guides users through risk profiling and recommends personalized allocations across yield sources.

### Features

- **AI Savings Advisor** — Chat-based onboarding with risk assessment
- **Multi-Strategy Vault** — Splits deposits across options, LP, and staking
- **Gamification** — Streaks, missions, and achievements to build habits
- **Base L2** — Low fees, fast transactions

## Repository

| Repo                                               | Description               |
| -------------------------------------------------- | ------------------------- |
| [`menabung`](https://github.com/MeNabung/menabung) | Monorepo (UI + Contracts) |

## Architecture

```text
menabung/
├── ui/                 # Next.js 16 frontend
│   └── src/
│       ├── app/        # Pages (chat, dashboard, quiz)
│       ├── components/ # UI + gamification
│       └── lib/        # AI, wagmi, hooks
└── contracts/          # Foundry smart contracts
    └── src/
        ├── MeNabungVault.sol    # Main vault
        └── adapters/            # Strategy adapters
```

## Yield Strategies

| Strategy | Protocol  | Target APY |
| -------- | --------- | ---------- |
| Options  | Thetanuts | ~8%        |
| LP       | Aerodrome | ~12%       |
| Staking  | IDRX      | ~15%       |

*Note: Current adapters are mock implementations for hackathon demo.*

## Roadmap

### Now (Hackathon MVP)

- [x] AI advisor with risk profiling
- [x] Smart vault with allocation splits
- [x] Gamification system
- [x] Base L2 contracts

### Phase 1: Real Integrations

- [ ] Thetanuts vault integration
- [ ] Aerodrome LP positions
- [ ] On-chain balance tracking

### Phase 2: Production UX

- [ ] Push notifications
- [ ] Bahasa Indonesia
- [ ] Mobile PWA

### Phase 3: Growth

- [ ] Referral rewards
- [ ] Social savings pools
- [ ] Additional yield sources

## Tech Stack

**Frontend:** Next.js 16, React 19, Tailwind, Motion, Wagmi, OnchainKit

**Contracts:** Solidity 0.8.20, Foundry, OpenZeppelin

**AI:** OpenAI GPT-4o-mini

## Links

- **IDRX Token:** [`0x18Bc5bcC660cf2B9cE3cd51a404aFe1a0cBD3C22`](https://basescan.org/token/0x18Bc5bcC660cf2B9cE3cd51a404aFe1a0cBD3C22)
- **Thetanuts on Base:** [`0xd58b814C7Ce700f251722b5555e25aE0fa8169A1`](https://basescan.org/address/0xd58b814C7Ce700f251722b5555e25aE0fa8169A1)

## License

MIT
