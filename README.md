# Youjian （游鉴） — Mobile App

![Status](https://img.shields.io/badge/status-launching%20Nov%202026-f0b429?style=flat-square)
![Platform](https://img.shields.io/badge/platform-mobile%20web-2f81f7?style=flat-square)
![Founder](https://img.shields.io/badge/founder--operated-solo-3fb950?style=flat-square)

**Youjian is a game-asset trading platform — accounts, items, rentals, boosting and companionship services — and this is its mobile app: a five-tab mobile web experience built end to end by the founder.**

The desktop platform runs on Tencent Cloud. The mobile app was designed, built and verified solo: product spec, UI, data model and launch checks, 0 → 1.

## The halls

| Hall | What happens there |
|---|---|
| Marketplace （交易市场） | Buy and sell game accounts and assets |
| Auctions （竞拍） | Timed bidding on listed accounts |
| Buy orders （求购） | Post what you're looking for; sellers come to you |
| Rentals （租号） | Rent accounts by the session or day |
| Boosting （代练） | Rank and progression services |
| Companions （陪玩） | Play-with-you services |
| Items （道具） | In-game items and equipment |

## The mobile app (v1)

Five bottom tabs — **Home · Halls · Publish · Orders · Mine** — covering the full trading loop:

- **Publish** a listing with photos, pricing and game details — saved to the real database and displayed in the halls
- **Order** flow with bargaining （砍价） built in
- **Drafts** that survive leaving the page
- **Account login** with per-user data

The publish → save → display chain was probe-tested end to end before this repo opened.

## Status

- Desktop platform: live on Tencent Cloud, halls open progressively
- Mobile app v1: **complete**, shipping with the platform's full launch in **November 2026**
- Source for the production deployment is private; this repository carries the product documentation, changelog and roadmap

## Docs

- [Product overview](docs/product-overview.md) — who it's for, how the halls connect, operating model
- [Changelog](CHANGELOG.md)

---

*Built and operated by [BizAnyE](https://github.com/bizanye8) — founder, Youjian. Previously: Web3 gaming operations across 200+ accounts, ≈ ¥1.62M realized.*
