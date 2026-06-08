# Awesome Memecoin Trading [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**The most comprehensive curated list of memecoin trading tools, launchpads, sniper bots, trading terminals, scanners, smart-money trackers, rug detectors, AI agents, MCPs, and resources for on-chain memecoin trading in 2026.**

> **250+ tools** across Solana (Pump.fun, LetsBonk, Believe, Bags, Boop, Daos.fun, Moonshot), BNB Chain (Four.meme, PancakeSwap), Base, Tron (SunPump), Hyperliquid, and EVM. Plus the entire ecosystem of trading terminals, Telegram bots, snipers, copy-trading, MEV protection, bundle detection, holder analytics, AI agents, and infrastructure built on top of them.

> Awesome PRs Welcome — see [Contributing](#-contributing).

---

## ⭐ Featured: Bitquery — The Memecoin Data Layer

> **The fastest way to give your AI agent or trading bot real-time, decoded memecoin data — without running an indexer.**

[![Bitquery MCP](https://img.shields.io/badge/MCP-mcp.bitquery.io-blue?style=for-the-badge)](https://mcp.bitquery.io/)
[![Coverage](https://img.shields.io/badge/Coverage-Pump.fun%20%2B%20LetsBonk%20%2B%20Four.meme%20%2B%20SunPump-green?style=for-the-badge)](https://docs.bitquery.io/)
[![Streams](https://img.shields.io/badge/Streams-GraphQL%20%2B%20WebSocket%20%2B%20Kafka%20%2B%20gRPC-orange?style=for-the-badge)](https://docs.bitquery.io/)

**[Bitquery](https://bitquery.io/)** is the data layer behind hundreds of trading bots, alpha groups, dashboards, and analytics platforms in the memecoin space.

| Feature | Coverage |
| --- | --- |
| **Pump.fun** | Real-time + historical trades, OHLCV, bonding-curve progress, top traders, PumpSwap migrations |
| **LetsBonk.fun** | Trades, OHLCV, bonding-curve, Raydium graduations |
| **Believe / Boop / Moonshot / Bags** | Launch + trade events |
| **Four.meme (BSC)** | Bonding-curve, trades, PancakeSwap migrations |
| **SunPump (Tron)** | Trades, SunSwap migrations |
| **Solana DEXs** | Raydium, Pump.fun, Pump.swap, Meteora, Orca, Jupiter |
| **Streams** | GraphQL, WebSocket, Kafka, gRPC |
| **MCP** | [`mcp.bitquery.io`](https://mcp.bitquery.io/) — plain-English queries from Claude / Cursor / ChatGPT |

### What you can build with it

- *"Top 50 Solana tokens by 1h volume on Pump.fun, exclude wash-trades."*
- *"Stream every Pump.fun trade above $5K USD into my agent in real time."*
- *"List all wallets that bought BONK before $1M market cap and held >30 days."*
- *"Alert me when a Pump.fun token crosses 95% bonding-curve progress."*

🔗 **[Bitquery Pump.fun API](https://docs.bitquery.io/docs/blockchain/Solana/Pumpfun/Pump-Fun-API/)** · **[DEXrabbit dashboard](https://dexrabbit.bitquery.io/)** · **[Bitquery MCP for AI agents](https://mcp.bitquery.io/)** · **[Bitquery IDE](https://ide.bitquery.io/)**

---

## 📖 About

**Awesome Memecoin Trading** is a deeply-curated, comprehensive directory of every tool a serious memecoin trader needs in 2026 — from **launchpad scanners** that catch tokens at 0% bonding-curve, to **smart-money trackers** that follow profitable wallets in real time, to **AI trading agents** that execute strategies in plain English.

This list goes far beyond the generic "Photon vs BullX" comparisons you find elsewhere. It includes:

- 🚀 **20+ launchpads** across Solana, BSC, Base, Tron, Hyperliquid
- 💻 **20+ trading terminals** (web, mobile, Telegram, MCP)
- 🤖 **25+ trading bots** with affiliate-direct links where available
- 🐳 **20+ smart-money / wallet / PnL trackers** (Cielo, Nansen, GMGN, Padre Vision, Axiom Vision, Step, MadeOnSol, etc.)
- 🛡️ **15+ rug detection / bundle / sandwich tools** (RugCheck, Solsniffer, Bubblemaps, Trench Radar, GoPlus, Quick Intel, De.Fi)
- 🪂 **Trenches / pre-bonding curve scanners** that catch tokens before everyone else (Padre Trenches, PumpScope, Trench Bot, Trenchy, Trenchscan)
- 📊 **Scanners & charting** (DexScreener, DexTools, Birdeye, GeckoTerminal, Defined.fi, Photon Memescope)
- 🫧 **Holder visualization** (Bubblemaps, Arkham, GMGN, Solscan)
- 🤖 **AI memecoin tools** (Dexu, Quill, ChainGPT, Virtuals, Senpi, Minara)
- 🔌 **Infrastructure** (Bitquery, Helius, Triton, Shyft, Jupiter, QuickNode, Alchemy)
- 💸 **Tax tools** for memecoin traders (Awaken, CoinTracker, Koinly, CoinLedger)
- 📱 **Mobile apps & wallets** (Phantom, Solflare, Backpack, Trojan Wallet, Padre, Axiom mobile)
- 🤝 **MCPs for AI agents** (cross-link to [Awesome Crypto MCPs](https://github.com/buddies2705/awesome-crypto-mcp))
- 🐦 **Crypto Twitter alpha accounts**, **YouTube channels**, **Discord communities**

### What is a Memecoin?

Memecoins are community-driven crypto tokens — sometimes culturally meaningful, sometimes pure speculation, often both. Most memecoin trading happens on Solana via Pump.fun-style bonding-curve launchpads, where tokens go from launch to graduation (~$69K market cap) to PumpSwap or Raydium. From there, the lucky few become $BONK, $WIF, $POPCAT, $FARTCOIN, $TRUMP. The rest go to zero — usually within minutes. This is why traders rely on sniper bots, smart-money trackers, and rug detectors.

### What changed in 2025–2026

- **Web terminals beat Telegram bots** — Axiom (~56% Solana terminal share), GMGN, Padre/Trenches, Trojan Web all ship faster execution + better analytics than the Telegram era
- **Pump.fun acquired Padre** in 2025, vertically integrating launch → trade
- **Bags ($42K daily fees) and LetsBonk emerged as serious Pump.fun challengers**
- **Bonding-curve "trenches" tools went pro** — Padre Trenches, PumpScope, Trench Bot
- **AI agents went on-chain** — Senpi, Minara, Virtuals tokens
- **MCP became the new API** — Bitquery, Hyperliquid, Solana Agent Kit MCPs let LLMs trade memecoins in natural language

> **Disclaimer**: Memecoin trading is high-risk. Tools and platforms change weekly. Always verify on each project's official site before depositing funds. Nothing on this list is financial advice.

---

## 📑 Table of Contents

- [⭐ Featured: Bitquery — The Memecoin Data Layer](#-featured-bitquery--the-memecoin-data-layer)
- [📖 About](#-about)
- [🚀 Memecoin Launchpads (Solana, BSC, Base, Tron)](#-memecoin-launchpads-solana-bsc-base-tron)
- [💻 Memecoin Trading Terminals](#-memecoin-trading-terminals)
- [🤖 Telegram Memecoin Trading Bots](#-telegram-memecoin-trading-bots)
- [🎯 Sniper Bots & New Launch Detection](#-sniper-bots--new-launch-detection)
- [🪂 Trenches & Pre-Bonding-Curve Scanners](#-trenches--pre-bonding-curve-scanners)
- [📋 Copy Trading Platforms](#-copy-trading-platforms)
- [🐳 Smart Money & Wallet Trackers](#-smart-money--wallet-trackers)
- [📈 PnL Leaderboards & Wallet Performance](#-pnl-leaderboards--wallet-performance)
- [📊 Memecoin Scanners & Discovery](#-memecoin-scanners--discovery)
- [🫧 Holder Visualization & Bubble Maps](#-holder-visualization--bubble-maps)
- [💣 Bundle, Sandwich & Insider Detection](#-bundle-sandwich--insider-detection)
- [🛡️ Rug Detection & Token Safety](#-rug-detection--token-safety)
- [📈 Charting Tools for Memecoins](#-charting-tools-for-memecoins)
- [🤖 AI Memecoin Tools & Agents](#-ai-memecoin-tools--agents)
- [📰 Memecoin News & Sentiment](#-memecoin-news--sentiment)
- [🌐 DEXs Where Memecoins Trade](#-dexs-where-memecoins-trade)
- [📱 Mobile Apps for Memecoin Trading](#-mobile-apps-for-memecoin-trading)
- [👛 Wallets for Memecoin Traders](#-wallets-for-memecoin-traders)
- [🔍 Block Explorers (Solana, BSC, Base, Tron)](#-block-explorers-solana-bsc-base-tron)
- [💸 Tax Tools for Memecoin Traders](#-tax-tools-for-memecoin-traders)
- [🤝 MCPs for Memecoin Traders (AI Agents)](#-mcps-for-memecoin-traders-ai-agents)
- [🏗️ Infrastructure & Developer Tools](#-infrastructure--developer-tools)
- [🪙 Notable Memecoins to Know](#-notable-memecoins-to-know)
- [🐦 Crypto Twitter Accounts & KOLs to Follow](#-crypto-twitter-accounts--kols-to-follow)
- [▶️ YouTube Channels & Educational Content](#-youtube-channels--educational-content)
- [💬 Discord Servers & Telegram Communities](#-discord-servers--telegram-communities)
- [📚 Resources & Guides](#-resources--guides)
- [🔗 Related Awesome Lists](#-related-awesome-lists)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🔍 Related Searches](#-related-searches)
- [📈 Popular Use Cases](#-popular-use-cases)

> **Legend** — 🟢 Live · 🟡 Beta / Limited · 🔴 Inactive · ⚡ Top-volume · 🆕 Launched 2025/26 · 🎟️ Affiliate link

---

## 🚀 Memecoin Launchpads (Solana, BSC, Base, Tron)

The platforms where new memecoins are minted every minute. Bonding-curve launchpads dominate — tokens start at $0 and graduate at a fixed market cap to a DEX (PumpSwap, Raydium, PancakeSwap, SunSwap).

| Launchpad | Chain | Mechanism | Graduation MCap | Daily Fees | Status | Website |
| --- | --- | --- | --- | --- | --- | --- |
| ⚡ **Pump.fun** | Solana | Bonding curve → PumpSwap | ~$69K | ~$870K | 🟢 Live | [pump.fun](https://pump.fun) |
| ⚡ **Bags (bags.fm)** 🆕 | Solana | Bonding curve → DEX | TBD | ~$42K | 🟢 Live | [bags.fm](https://bags.fm) |
| ⚡ **LetsBonk.fun** 🆕 | Solana | Bonding curve (Raydium LaunchLab) | ~$69K | ~$18K | 🟢 Live | [letsbonk.fun](https://letsbonk.fun) |
| **Believe** | Solana | Tweet-to-launch, dynamic bonding curve → Meteora | ~$100K | — | 🟢 Live | [believe.app](https://believe.app) |
| **Boop.fun** | Solana | Bonding curve | — | — | 🟢 Live | [boop.fun](https://boop.fun) |
| **Moonshot** | Solana | Bonding curve, fiat onramp | — | — | 🟢 Live | [moonshot.com](https://moonshot.com) |
| **Raydium LaunchLab** 🆕 | Solana | Bonding curve → Raydium | — | ~$2K | 🟢 Live | [raydium.io/launchpad](https://raydium.io/launchpad) |
| **Daos.fun** | Solana | DAO-style memecoin launches | — | — | 🟢 Live | [daos.fun](https://daos.fun) |
| **DexScreener Moonshot** | Multichain | Built-in DexScreener launch (0.02 SOL) | — | — | 🟢 Live | [dexscreener.com](https://dexscreener.com) |
| **Vyper** (Pump.fun-owned) | Solana | Pre-launch / utility | — | — | 🟢 Live | [pump.fun ecosystem](https://pump.fun) |
| **Sun.fun / SunPump** | Tron | Bonding curve → SunSwap | — | — | 🟢 Live | [sunpump.meme](https://sunpump.meme) |
| **Four.meme** | BNB Chain | Bonding curve → PancakeSwap | ~$24K | — | 🟢 Live | [four.meme](https://four.meme) |
| **Ape.bond / Ape.pro** | Multichain | Discovery + curated launches | — | — | 🟢 Live | [ape.pro](https://ape.pro) |
| **Doge.fun** | BSC | Bonding curve | — | — | 🟢 Live | [doge.fun](https://doge.fun) |
| **clanker** | Base | AI-launched tokens via Farcaster | — | — | 🟢 Live | [clanker.world](https://www.clanker.world/) |
| **Wow.xyz** | Base | Bonding-curve launchpad | — | — | 🟢 Live | [wow.xyz](https://wow.xyz) |
| **Virtuals Protocol** | Base, Solana | AI-agent token launches | — | — | 🟢 Live | [virtuals.io](https://virtuals.io) |
| **DePin** (memecoin-flavored) | Multichain | Real-world incentive launchpads | — | — | 🟢 Live | (search depin protocols) |

---

## 💻 Memecoin Trading Terminals

The web terminals that replaced Telegram bots in 2025. Sub-second execution, MEV protection, smart-money integration, copy trading, and full charting.

| Terminal | Chain | Type | Notable Features | Status | Website |
| --- | --- | --- | --- | --- | --- |
| 🎟️ ⚡ **Axiom** | Solana, BSC | Web terminal | ~56% Solana terminal market share, Warp Engine, Tweet Monitor, Vision wallet ranking, perps, axiSOL | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| 🎟️ ⚡ **Photon** | Solana, ETH, Base, BSC, Tron, Blast | Web terminal | Sub-0.3s execution, Memescope, Smart MEV via Jito, fast/secure modes | 🟢 Live | [photon-sol.tinyastro.io/@coinmonks](https://photon-sol.tinyastro.io/@coinmonks) |
| 🎟️ ⚡ **GMGN** | SOL, ETH, Base, BSC, Tron, Monad | Web + Telegram | AI risk scans, smart money tracking (10K+ wallets), copy trade, anti-MEV, multi-chain | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| 🎟️ ⚡ **Trojan Terminal** | Solana | Web + Telegram | The Arena gamification, copy 40 wallets, perps, MetaMask integration, multi-chain bridge | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |
| 🎟️ **BullX Neo** | Sol, ETH, Base, BSC, Arb, Blast, Tron | Web + Telegram | Pump Vision, dual chain view, multi-chain breadth | 🟢 Live | [BullX Telegram](https://t.me/BullxBetaBot?start=access_ZH5O9XEG5XQ) · [bullx.io](https://bullx.io) |
| 🎟️ 🆕 **Padre / Terminal** | Solana, BSC, Base | Web terminal | Pump.fun-owned, Trenches, pre-trade simulation, Turnkey MPC | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Nova** | Solana | Web terminal | Trenches, AFK trading | 🟢 Live | [tradeonnova.io](https://tradeonnova.io) |
| 🎟️ **MEVx** | Solana | Web + Telegram + Chrome ext | MEV-aware sniping (single product, multiple surfaces) | 🟢 Live | [@Mevx](https://t.me/Mevx?start=coinmonks) |
| **DEX Screener Pro** | Multichain | Web terminal | Charts + native swap + trending | 🟢 Live | [dexscreener.com](https://dexscreener.com) |
| **Bullpen** | Solana + Hyperliquid | Web + Mobile + Telegram | Co-founded by Ansem, multi-platform | 🟢 Live | [bullpen.fi/@agile-yak](https://bullpen.fi/@agile-yak) |
| 🎟️ **Bloom Trading Bot** | Solana | Web + Telegram | Aggressive sniping presets | 🟢 Live | [Bloom Telegram](https://t.me/BloomSolana_bot?start=ref_4JW9MZKN3B) |
| **Vector** | Solana | Web terminal | Social-feed-style memecoin trading | 🟢 Live | [vector.fun](https://vector.fun) |
| **Pulse Terminal** | Solana | Web terminal | Pump.fun-focused interface | 🟢 Live | [pulse.run](https://pulse.run) |
| **DexScreener Pro** | Multichain | Web | Power-user DexScreener layout | 🟢 Live | [dexscreener.com](https://dexscreener.com) |
| **Defined.fi** | Multichain | Web terminal | High-resolution charts + token screener | 🟢 Live | [defined.fi](https://www.defined.fi) |
| **Birdeye Trading** | Solana + Multi | Web | Birdeye's built-in swap (via Jupiter) | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **Ape.pro / Ape.bond** | Multichain | Web | Curated discovery + trade | 🟢 Live | [ape.pro](https://ape.pro) |
| **Solanahub** | Solana | Web | Multi-tool Solana hub | 🟢 Live | [solanahub.app](https://solanahub.app) |

---

## 🤖 Telegram Memecoin Trading Bots

Telegram bots are still the fastest path for many memecoin traders — sub-second swaps, sniping, and copy trading from the chat you're already in.

| Bot | Chains | Type | Notable Features | Status | Link |
| --- | --- | --- | --- | --- | --- |
| 🎟️ ⚡ **Trojan** | Solana | Bot + Web | $25B+ lifetime volume (claimed), 2M+ users, Arena rewards | 🟢 Live | [@solana_trojanbot](https://t.me/solana_trojanbot?start=r-masakitokugawa) |
| 🎟️ ⚡ **BONKbot** | Solana | Bot | Simplest swap flow, beginner-friendly | 🟢 Live | [@bonkbot_bot](https://t.me/bonkbot_bot?start=ref_eyg8m) |
| 🎟️ ⚡ **GMGN Bot** | Sol, ETH, Base, BSC, Tron, Monad | Bot | Smart money + copy trade in Telegram | 🟢 Live | [@gmgnaibot](https://t.me/gmgnaibot?start=i_NdGvsXdB) |
| 🎟️ ⚡ **Maestro** | Sol, ETH, BSC, Base, ARB, AVAX, TON | Bot | Multi-chain, the original Telegram sniper | 🟢 Live | [@maestro](https://t.me/maestro?start=r-gaurav_zen) |
| 🎟️ **Banana Gun** | Sol, ETH, Base, BSC, MegaETH | Bot | Anti-rug, fast execution | 🟢 Live | [@BananaGunSniper_bot](https://t.me/BananaGunSniper_bot?start=ref_coinmonks) |
| 🎟️ **Bloom Bot** | Solana | Bot | Aggressive launch sniping presets | 🟢 Live | [@BloomSolana_bot](https://t.me/BloomSolana_bot?start=ref_4JW9MZKN3B) |
| 🎟️ **Pepeboost** | Solana | Bot | Multi-chain memecoin sniper | 🟢 Live | [@pepeboost_sol_bot](https://t.me/pepeboost_sol_bot?start=ref_0qlemf) |
| 🎟️ **Shuriken** | Solana | Bot | Solana-focused sniper | 🟢 Live | [@ShurikenTradeBot](https://t.me/ShurikenTradeBot?start=ref-gaurav_zen) |
| 🎟️ **Unibot** | Multichain | Bot | EVM-focused, classic Telegram sniper | 🟢 Live | [@unibotsniper_bot](https://t.me/unibotsniper_bot?start=coinmonks) |
| 🎟️ **MEVx Bot** | Solana | Bot | MEV-aware Telegram trading | 🟢 Live | [@Mevx](https://t.me/Mevx?start=coinmonks) |
| **Photon Telegram** | Solana | Bot | Photon's Telegram interface | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| **BullX Bot** | Multichain | Bot | BullX Neo via Telegram | 🟢 Live | [@BullxBetaBot](https://t.me/BullxBetaBot?start=access_ZH5O9XEG5XQ) |
| **Sol Trading Bot** | Solana | Bot | Cross-chain memecoin trading | 🟢 Live | [soltradingbot.com](https://soltradingbot.com) |
| **Fluxbot** | Solana | Bot | Lending + copy trading + swaps | 🟢 Live | [fluxbot.xyz](https://fluxbot.xyz) |
| **Rouge** | Solana | Bot | Sniper + copy trading | 🟢 Live | [rouge.fun](https://rouge.fun) |
| **Iagon Bot** | Solana | Bot | Privacy-focused memecoin trading | 🟢 Live | [iagon.com](https://iagon.com) |
| **Solana Trojan Web** | Solana | Web | Trojan's web companion | 🟢 Live | [trojan.com](https://trojan.com/@coincodecap) |
| **Phanes** | Solana | Bot | Solana memecoin sniper | 🟢 Live | [phanes.io](https://phanes.io) |
| **Apex Trading** | Multichain | Bot | EVM + Sol multi-chain | 🟢 Live | [apex.trading](https://apex.trading) |
| 🎟️ **Leap Trading Bot** | Solana | Bot | Solana memecoin TG bot | 🟢 Live | [@leaptrading_bot](https://t.me/leaptrading_bot?start=ref_gaurav_zen) |
| 🎟️ **CashCash** | Solana | Bot | Solana memecoin trading bot | 🟢 Live | [@CashCash_trade_bot](https://t.me/CashCash_trade_bot?start=ref_3d58ee71-5) |
| 🎟️ **Sigma Buy Bot** | Solana | Bot | Solana sniper / fast buy | 🟢 Live | [@Sigma_buyBot](https://t.me/Sigma_buyBot?start=ref=388733201) |
| 🎟️ **DBotX** | Multichain | Bot | Multi-chain trading bot platform | 🟢 Live | [dbotx.com](https://dbotx.com/?ref=81911082) |
| 🎟️ **Ave.ai (avebot)** | Solana + EVM | Bot + Web | Memecoin discovery + trading from Telegram and web | 🟢 Live | [share.ave.ai](https://share.ave.ai?code=gaurav) |

---

## 🎯 Sniper Bots & New Launch Detection

Bots focused on **catching tokens at the moment of launch** — pre-bonding-curve sniping on Pump.fun, presale entries, and anti-rug fast exits.

| Bot | Chain | Specialty | Status | Link |
| --- | --- | --- | --- | --- |
| 🎟️ **Banana Gun Sniper** | Multichain | Pre-migration sniping, anti-rug | 🟢 Live | [@BananaGunSniper_bot](https://t.me/BananaGunSniper_bot?start=ref_coinmonks) |
| 🎟️ **Maestro Sniper** | Multichain | Launch sniping, presales | 🟢 Live | [@maestro](https://t.me/maestro?start=r-gaurav_zen) |
| 🎟️ **Bloom Legendary Sniping** | Solana | Configurable presets, sub-second | 🟢 Live | [@BloomSolana_bot](https://t.me/BloomSolana_bot?start=ref_4JW9MZKN3B) |
| 🎟️ **Photon Sniper** | Solana | Pump.fun pre-migration | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| 🎟️ **Trojan Sniper** | Solana | Bonding-curve entries | 🟢 Live | [@solana_trojanbot](https://t.me/solana_trojanbot?start=r-masakitokugawa) |
| 🎟️ **MEVx Sniper** | Solana | MEV-aware, Jito-bundle | 🟢 Live | [@Mevx](https://t.me/Mevx?start=coinmonks) |
| 🎟️ **Autosnipe.ai** | Solana | Auto-sniping by ruleset | 🟢 Live | [autosnipe.ai/r/coinmonks](https://autosnipe.ai/r/coinmonks) |
| **BullX Sniper** | Multichain | New pair detection | 🟢 Live | [@BullxBetaBot](https://t.me/BullxBetaBot?start=access_ZH5O9XEG5XQ) |
| 🎟️ **Padre Sniper** | Solana | Trenches-integrated sniping | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Axiom Sniper** | Solana | Vision-integrated sniping | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| **Apexniper** | Multichain | Cross-chain sniping | 🟢 Live | [apexniper.io](https://apexniper.io) |
| **PumpFunSniper** | Solana | Pump.fun-specific sniper | 🟢 Live | [pumpfunsniper.io](https://pumpfunsniper.io) |

---

## 🪂 Trenches & Pre-Bonding-Curve Scanners

The "trenches" — that 0% to 95% bonding-curve window where most of the alpha (and most of the rugs) live. These tools are built specifically to scan, score, and alert during that window.

| Tool | Coverage | Notable Features | Status | Website |
| --- | --- | --- | --- | --- |
| 🎟️ **Padre Trenches** | Pump.fun, Four.meme | New / Almost Bonded / Recently Bonded columns, dev signals, blacklist, sound alerts | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Photon Memescope** | Pump.fun, Moonshot | Trenches-style discovery in Photon | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| **BullX Pump Vision** | Pump.fun | Real-time bonding-curve tracking | 🟢 Live | [bullx.io](https://bullx.io) |
| **PumpScope** | Pump.fun | Live token feed, whale tracking, rug detection, graduation alerts | 🟢 Live | [pumpscope.polsia.app](http://pumpscope.polsia.app/) |
| **Trench Bot** | Pump.fun, Solana | Bundle scanner, slot-level analysis | 🟢 Live | [trench.bot](https://trench.bot) |
| **Trenchy** | Pump.fun (TG) | Telegram scanner — freeze/mint, snipers, holder check | 🟢 Live | [solanabox.tools/tools/trenchy](https://solanabox.tools/tools/trenchy) |
| **TrenchScan** | Pump.fun | Visual token map, real-time | 🟢 Live | [trenchscan.lol](https://trenchscan.lol/) |
| **Pump.fun Trends** | Pump.fun | Native trending feed | 🟢 Live | [pump.fun](https://pump.fun) |
| **Vector Trenches** | Solana | Social-feed memecoin discovery | 🟢 Live | [vector.fun](https://vector.fun) |
| **GMGN Trenches** | Multichain | GMGN's pre-bonding-curve view | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Axiom Trenches** | Solana | Built into Axiom's terminal | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| **Nova Trenches** | Solana | Nova's bonding-curve view | 🟢 Live | [tradeonnova.io](https://tradeonnova.io) |

---

## 📋 Copy Trading Platforms

Mirror profitable memecoin wallets in real time. Combine smart-money discovery with one-click copy execution.

| Platform | Chains | Features | Status | Website |
| --- | --- | --- | --- | --- |
| 🎟️ **GMGN Copy Trading** | Multichain | Copy 500+ smart money wallets, configurable allocation | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Cielo Copy** | 30+ chains | Copy trading + cross-chain alerts (Pro $59/mo) | 🟢 Live | [cielo.finance](https://cielo.finance) |
| 🎟️ **BullX Copy Trading** | Multichain | Native to BullX Neo | 🟢 Live | [bullx.io](https://t.me/BullxBetaBot?start=access_ZH5O9XEG5XQ) |
| 🎟️ **Photon Copy Trading** | Solana | Photon's wallet-mirroring tool | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| 🎟️ **Axiom Copy Trading** | Solana | Vision-powered copy | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| 🎟️ **Maestro Copy Trading** | Multichain | Multi-chain copy execution | 🟢 Live | [@maestro](https://t.me/maestro?start=r-gaurav_zen) |
| 🎟️ **Bloom AFK Mode** | Solana | Automated copy / strategy trading | 🟢 Live | [@BloomSolana_bot](https://t.me/BloomSolana_bot?start=ref_4JW9MZKN3B) |
| 🎟️ **Trojan Copy Trading** | Solana | Copy 40 wallets with custom risk allocation | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |
| **Fluxbot Copy Trading** | Solana | Real-time copy trading | 🟢 Live | [fluxbot.xyz](https://fluxbot.xyz) |
| **Copin** | Multichain | 600K+ on-chain trader pool, copy across 20+ DEXs | 🟢 Live | [copin.io](https://app.copin.io?ref=IPSPYN) |
| 🎟️ **Padre Copy** | Solana | Padre's native copy trading | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **PVP Trade** | Solana | PvP-style competitive copy trading | 🟢 Live | [pvp.trade](https://pvp.trade) |

---

## 🐳 Smart Money & Wallet Trackers

Find and follow profitable wallets, KOLs, insiders, and whales across chains. Real-time alerts when smart money enters or exits.

| Tool | Chains | Specialty | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Cielo** | 30+ chains | 250-wallet free tier, EVM↔SOL bridge tracking, Whale plan = 10K wallets | 🟢 Live | [cielo.finance](https://cielo.finance) |
| ⚡ **Nansen** | Multichain | 500M+ labeled wallets, Smart Money / Fund tags ($49/mo) | 🟢 Live | [nansen.ai](https://nansen.ai) |
| 🎟️ **Arkham** | Multichain | Entity de-anonymisation, KOL tags (950+), free | 🟢 Live | [arkm.com](https://arkm.com/register?ref=03c4c435-9a97-4553-850d-c91faf29c7b8) |
| **Lookonchain** | Multichain | Real-time on-chain tracking, alerts | 🟢 Live | [lookonchain.com](https://lookonchain.com) |
| **GMGN Smart Money** | Multichain | KOL + smart money feeds, copy trade | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Birdeye Smart Money** | Solana | Wallet tracking inside Birdeye | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **Axiom Vision** | Solana | Global wallet ranking, 10K wallets monitored | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| 🎟️ **Padre Vision** | Solana | Padre's wallet ranking | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Trojan Analyzer** | Solana | Wallet ranking + performance tracking | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |
| **MadeOnSol** | Solana | KOL tracker, deployer hunter, API for KOL trades | 🟢 Live | [madeonsol.com](https://madeonsol.com) |
| **ChainEdge** | Multichain | Wallet alerts | 🟢 Live | [chainedge.io](https://chainedge.io) |
| **Wallet Whale Watcher** | Solana | Whale tx alerts | 🟢 Live | [whalewatchers.io](https://whalewatchers.io) |
| **SolanaTracker** | Solana | Wallet tracker + data API | 🟢 Live | [solanatracker.io](https://www.solanatracker.io) |
| **Pulsar Insights** | Multichain | Wallet behaviour analytics | 🟢 Live | [pulsar.fi](https://pulsar.fi) |
| **Zerion** | Multichain (EVM) | Multi-wallet portfolio + tracking | 🟢 Live | [zerion.io](https://zerion.io) |
| **DeBank** | EVM | Wallet activity feed + DeFi tracking | 🟢 Live | [debank.com](https://debank.com) |
| **Step Finance** | Solana | Solana portfolio dashboard | 🟢 Live | [step.finance](https://step.finance) |

---

## 📈 PnL Leaderboards & Wallet Performance

Discover top-performing wallets ranked by realized PnL, win rate, and ROI.

| Tool | Chains | Notable Features | Status | Website |
| --- | --- | --- | --- | --- |
| **Cielo PnL Leaderboard** | 30+ chains | Filter by PnL, ROI, win rate, volume, trade count | 🟢 Live | [docs.cielo.finance](https://docs.cielo.finance/wallet-tracking/my-wallets/pnl-leaderboard) |
| **Axiom Vision** | Solana | Global ranking with advanced filtering | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| **GMGN Top Wallets** | Multichain | Top trader leaderboard with copy | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **MadeOnSol KOL PnL** | Solana | Equity curves, drawdown, profit factor via API | 🟢 Live | [madeonsol.com](https://madeonsol.com) |
| 🎟️ **Padre Vision** | Solana | Padre's PnL ranking | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Trojan Analyzer** | Solana | Wallet ranking + filtering | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |
| **Birdeye Wallet PnL** | Solana | Built-in wallet PnL on token pages | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **Step Finance** | Solana | Self-portfolio PnL | 🟢 Live | [step.finance](https://step.finance) |
| **Solscan Account PnL** | Solana | Per-wallet PnL on Solscan | 🟢 Live | [solscan.io](https://solscan.io) |
| **Coinhall** | Multichain | Cross-chain wallet PnL | 🟢 Live | [coinhall.org](https://coinhall.org) |
| **Pulsar PnL** | Multichain | Solana wallet performance | 🟢 Live | [pulsar.fi](https://pulsar.fi) |
| **DexScreener PnL** | Multichain | Wallet PnL on token pages | 🟢 Live | [dexscreener.com](https://dexscreener.com) |

---

## 📊 Memecoin Scanners & Discovery

Scanners for finding new tokens, trending memes, liquidity events, and hot pairs across chains.

| Tool | Chains | Specialty | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **DexScreener** | Multichain | Industry standard — charts, trending, new pairs | 🟢 Live | [dexscreener.com](https://dexscreener.com) |
| ⚡ **DexTools** | Multichain | Charts, audits, hot pairs, social sentiment | 🟢 Live | [dextools.io](https://www.dextools.io) |
| ⚡ **Birdeye** | Solana + Multi | All-in-one Solana analytics, smart money | 🟢 Live | [birdeye.so](https://birdeye.so) |
| ⚡ **GeckoTerminal** | Multichain | Real-time DEX charts (CoinGecko) | 🟢 Live | [geckoterminal.com](https://www.geckoterminal.com) |
| ⚡ **GMGN.ai** | Multichain | Smart money + AI risk + memecoin discovery | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Defined.fi** | Multichain | Pro-grade charts + token screener | 🟢 Live | [defined.fi](https://www.defined.fi) |
| ⚡ **DEXrabbit** | Sol, ETH, BSC, Base, Tron, Polygon, Arbitrum, Optimism | **DexScreener alternative** — real-time DEX analytics, live token / pair / cryptocurrency feeds, market heatmaps, AI overviews, plus native Polymarket data. Powered by Bitquery API. | 🟢 Live | [dexrabbit.bitquery.io](https://dexrabbit.bitquery.io/) |
| **CoinGecko Memecoins** | Multichain | Memecoin category list + prices | 🟢 Live | [CoinGecko Memecoins](https://www.coingecko.com/en/categories/meme-token) |
| **CoinMarketCap Memecoins** | Multichain | CoinMarketCap meme category | 🟢 Live | [CMC Memecoins](https://coinmarketcap.com/view/memes/) |
| **Dexu.ai** | Solana | AI-powered memecoin discovery | 🟢 Live | [dexu.ai](https://dexu.ai) |
| **Solscan** | Solana | Block explorer + token pages | 🟢 Live | [solscan.io](https://solscan.io) |
| **Solana FM** | Solana | Block explorer (Jupiter Labs) | 🟢 Live | [solana.fm](https://solana.fm) |
| **Pump.fun Trends** | Solana | Native Pump.fun discovery | 🟢 Live | [pump.fun](https://pump.fun) |
| **Photon Memescope** | Solana | Pump.fun + Moonshot scanner | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| **Coinhall** | Multichain | Cross-chain DEX analytics | 🟢 Live | [coinhall.org](https://coinhall.org) |
| **CoinBrain** | Multichain | Token tracker + alerts | 🟢 Live | [coinbrain.com](https://coinbrain.com) |
| **DEX View** | Multichain | DexScreener alternative | 🟢 Live | [dexview.com](https://www.dexview.com) |
| **Pulsar Insights** | Multichain | Multi-chain memecoin analytics | 🟢 Live | [pulsar.fi](https://pulsar.fi) |
| **MadeOnSol** | Solana | Solana tool reviews + KOL data | 🟢 Live | [madeonsol.com](https://madeonsol.com) |
| **Apespace** | Multichain | Charts + token discovery | 🟢 Live | [apespace.io](https://apespace.io) |
| 🎟️ **Ave.ai** | Solana + Multi | Memecoin discovery + analytics + trading | 🟢 Live | [ave.ai](https://share.ave.ai?code=gaurav) |
| **Toly Stats** | Solana | Solana ecosystem stats | 🟢 Live | [tolystats.com](https://tolystats.com) |

---

## 🫧 Holder Visualization & Bubble Maps

See who actually holds the supply — detect insider clusters, sybil splits, deployer connections.

| Tool | Chains | Notable Features | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Bubblemaps** | Sol, ETH, BSC, Base, Tron | Visual holder networks, "Time Travel" view | 🟢 Live | [bubblemaps.io](https://bubblemaps.io) |
| 🎟️ **Arkham Visualizer** | Multichain | Entity-mapped graph view | 🟢 Live | [arkm.com](https://arkm.com/register?ref=03c4c435-9a97-4553-850d-c91faf29c7b8) |
| **GMGN Holder Analysis** | Multichain | Holder insider trading patterns | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Solscan Holders** | Solana | Top holders + concentration % | 🟢 Live | [solscan.io](https://solscan.io) |
| **Etherscan Holders** | EVM | Holder distribution | 🟢 Live | [etherscan.io](https://etherscan.io) |
| 🎟️ **Padre Holder Tools** | Solana | Built into Trenches | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Birdeye Holders** | Solana | Holder breakdown | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **DexCheck** | Multichain | Holder + insider analysis | 🟢 Live | [dexcheck.ai](https://dexcheck.ai) |
| **Ape.bond Holder View** | Multichain | Distribution dashboards | 🟢 Live | [ape.bond](https://ape.bond) |
| **HolderChecker** | Solana | Quick holder concentration | 🟢 Live | [holderchecker.io](https://holderchecker.io) |

---

## 💣 Bundle, Sandwich & Insider Detection

Detect coordinated buys (bundles), sandwich attacks, and insider snipes — critical for spotting orchestrated rugs and pump schemes.

| Tool | Chains | Specialty | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Trench Bot Bundle Scanner** | Solana | Slot-level bundle detection (sub-0.4s) | 🟢 Live | [trench.bot](https://trench.bot) |
| 🎟️ **Padre Bundle Detection** | Solana | Bundle/insider signals in Trenches | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **GMGN Insider Mode** | Multichain | Insider trading pattern flags | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Photon Bundle Check** | Solana | Inline bundle detection on token pages | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| **Trenchy** | Solana | Telegram-based snipe / bundle scan | 🟢 Live | [solanabox.tools/tools/trenchy](https://solanabox.tools/tools/trenchy) |
| **PumpScope Whale Tracker** | Solana | Whale + bundle alerts | 🟢 Live | [pumpscope.polsia.app](http://pumpscope.polsia.app/) |
| **Sandwich.dev** | EVM | EVM sandwich attack detection | 🟢 Live | [sandwich.dev](https://sandwich.dev) |
| **MEV Inspect** | EVM | Open-source MEV/sandwich indexer | 🟢 Live | [mev-inspect](https://github.com/flashbots/mev-inspect-py) |
| **Eigenphi** | Multichain | MEV analytics + sandwich tracking | 🟢 Live | [eigenphi.io](https://eigenphi.io) |
| **Helius MEV Insights** | Solana | Solana MEV / Jito analytics | 🟢 Live | [helius.dev](https://helius.dev) |

---

## 🛡️ Rug Detection & Token Safety

Run every token through these before you buy.

| Tool | Chains | Specialty | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **RugCheck** | Solana | The standard Solana rug check | 🟢 Live | [rugcheck.xyz](https://rugcheck.xyz) |
| **Solsniffer** | Solana | Risk score + flags | 🟢 Live | [solsniffer.com](https://solsniffer.com) |
| **GoPlus Token Security** | Multichain | Honeypot + contract risk API | 🟢 Live | [gopluslabs.io](https://gopluslabs.io) |
| **Honeypot.is** | EVM | Honeypot detection (free) | 🟢 Live | [honeypot.is](https://honeypot.is) |
| **TokenSniffer** | EVM | Contract audit summary | 🟢 Live | [tokensniffer.com](https://tokensniffer.com) |
| **De.Fi Scanner** | Multichain | Smart contract risk scanner | 🟢 Live | [de.fi/scanner](https://de.fi/scanner) |
| **Quick Intel** | Multichain | Contract audits + alerts | 🟢 Live | [quickintel.io](https://app.quickintel.io) |
| **Quill AI** | Multichain | AI-powered contract audits | 🟢 Live | [quillai.network](https://quillai.network) |
| **Bubblemaps** | Multichain | Insider cluster detection | 🟢 Live | [bubblemaps.io](https://bubblemaps.io) |
| **PumpFun Token Sniffer** | Solana | Pump.fun phishing detection (Bitquery PoC) | 🟢 Live | [Bitquery docs](https://docs.bitquery.io/docs/blockchain/Solana/Pumpfun/Pump-Fun-API/) |
| **CertiK SkyNet** | Multichain | Token & project safety scores | 🟢 Live | [skynet.certik.com](https://skynet.certik.com) |
| **HoneyShield** | EVM | Honeypot scanner | 🟢 Live | [honeyshield.io](https://honeyshield.io) |
| **Slither** | EVM | Open-source contract analyser | 🟢 Live | [Slither](https://github.com/crytic/slither) |

---

## 📈 Charting Tools for Memecoins

Real-time OHLCV, volume, and indicators for memecoin pairs.

| Tool | Chains | Specialty | Status | Website |
| --- | --- | --- | --- | --- |
| 🎟️ **TradingView** | Multichain | Pro charting via DEX integrations | 🟢 Live | [tradingview.com](https://www.tradingview.com/?offer_id=10&aff_id=24152) |
| **DexScreener Charts** | Multichain | Default charting tool | 🟢 Live | [dexscreener.com](https://dexscreener.com) |
| **GeckoTerminal** | Multichain | CoinGecko-powered DEX charts | 🟢 Live | [geckoterminal.com](https://www.geckoterminal.com) |
| **GMGN Charts** | Multichain | Charts + smart-money overlay | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Birdeye Charts** | Solana | High-resolution OHLCV | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **DexTools Charts** | Multichain | Token charts + trades | 🟢 Live | [dextools.io](https://www.dextools.io) |
| **DEXrabbit** | Sol, ETH, BSC, Base, Tron, Polygon, Arb, Optimism | DexScreener alternative — live charts, heatmaps, AI overviews, Polymarket pages | 🟢 Live | [dexrabbit.bitquery.io](https://dexrabbit.bitquery.io/) |
| **Defined.fi Charts** | Multichain | High-resolution pro charts | 🟢 Live | [defined.fi](https://www.defined.fi) |
| **Photon Charts** | Solana | Built into Photon | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| 🎟️ **Padre Charts** | Solana | Padre's chart engine | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Axiom Charts** | Solana | Built into Axiom | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| **Trojan Charts** | Solana | Trojan Web charts | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |

---

## 🤖 AI Memecoin Tools & Agents

AI-powered memecoin discovery, sentiment analysis, automated trading, and on-chain agent tokens.

| Tool | Chains | Specialty | Status | Website |
| --- | --- | --- | --- | --- |
| **GMGN AI** | Multichain | AI risk scoring + smart money | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| **Dexu AI** | Solana | AI memecoin discovery | 🟢 Live | [dexu.ai](https://dexu.ai) |
| **Kaito** | Multichain | InfoFi sentiment analytics | 🟢 Live | [kaito.ai](https://kaito.ai) |
| **ChainGPT** | Multichain | AI memecoin generator + tools | 🟢 Live | [chaingpt.org](https://chaingpt.org) |
| **Quill AI** | Multichain | AI token audits | 🟢 Live | [quillai.network](https://quillai.network) |
| **Virtuals Protocol** | Base, Solana | AI-agent token launches | 🟢 Live | [virtuals.io](https://virtuals.io) |
| **ai16z / Eliza** | Multichain | Agent framework + memecoin agents | 🟢 Live | [elizaos.ai](https://elizaos.ai) |
| **Senpi Perps** | Hyperliquid | AI-driven trading agent | 🟢 Live | [senpi.ai](https://senpi.ai) |
| **Minara AI** | Hyperliquid | AI-assisted trading | 🟢 Live | [minara.ai](https://minara.ai) |
| **Brian AI** | Multichain | Natural-language Web3 agent | 🟢 Live | [brianknows.org](https://www.brianknows.org) |
| **Wayfinder (Parallel)** | Multichain | AI agent runtime | 🟢 Live | [wayfinder.ai](https://wayfinder.ai) |
| **Fetch.ai** | Multichain | AI agent infrastructure | 🟢 Live | [fetch.ai](https://fetch.ai) |
| **AIXBT** | Multichain | AI alpha agent (token) | 🟢 Live | [aixbt.tech](https://aixbt.tech) |

---

## 📰 Memecoin News & Sentiment

| Source | Coverage | Type | Status | Website |
| --- | --- | --- | --- | --- |
| **Kaito** | Multichain | InfoFi sentiment, narrative tracking | 🟢 Live | [kaito.ai](https://kaito.ai) |
| **CoinGecko News** | Multichain | Memecoin news feed | 🟢 Live | [CoinGecko News](https://www.coingecko.com/en/news) |
| **CryptoPanic Memecoins** | Multichain | Aggregated news with filters | 🟢 Live | [cryptopanic.com](https://cryptopanic.com) |
| **Cointelegraph** | Multichain | Mainstream crypto news | 🟢 Live | [cointelegraph.com](https://cointelegraph.com) |
| **The Defiant** | Multichain | DeFi-focused news | 🟢 Live | [thedefiant.io](https://thedefiant.io) |
| **CoinDesk Markets** | Multichain | Markets news | 🟢 Live | [coindesk.com](https://www.coindesk.com) |
| **Dappier** | Multichain | Real-time crypto + finance content | 🟢 Live | [dappier.com](https://dappier.com) |
| **LunarCrush** | Multichain | Social sentiment + Galaxy Score | 🟢 Live | [lunarcrush.com](https://lunarcrush.com) |
| **Santiment** | Multichain | On-chain + social analytics | 🟢 Live | [santiment.net](https://santiment.net) |
| **Phantom News** | Solana | Phantom's curated news feed | 🟢 Live | [phantom.com/learn](https://phantom.com/learn) |
| **MadeOnSol Blog** | Solana | Deep Solana research & guides | 🟢 Live | [madeonsol.com/blog](https://madeonsol.com/blog) |

---

## 🌐 DEXs Where Memecoins Trade

The actual venues where memecoin volume happens.

| DEX | Chain | Type | Notes | Status | Website |
| --- | --- | --- | --- | --- | --- |
| ⚡ **Raydium** | Solana | AMM + CLMM + LaunchLab | Where most graduated Pump.fun tokens trade | 🟢 Live | [raydium.io](https://raydium.io) |
| ⚡ **PumpSwap** | Solana | Pump.fun-native AMM | Default migration target for Pump.fun | 🟢 Live | [swap.pump.fun](https://swap.pump.fun) |
| **Meteora** | Solana | Dynamic AMM + DLMM | Believe.app graduation target | 🟢 Live | [meteora.ag](https://meteora.ag) |
| **Jupiter** | Solana | DEX aggregator | Default routing for memecoin swaps | 🟢 Live | [jup.ag](https://jup.ag) |
| **Orca** | Solana | AMM + Whirlpools | Major Solana DEX | 🟢 Live | [orca.so](https://orca.so) |
| **Phoenix** | Solana | CLOB | Used by power-user terminals | 🟢 Live | [phoenix.trade](https://www.phoenix.trade/) |
| **PancakeSwap** | BNB Chain | AMM | Four.meme migration target | 🟢 Live | [pancakeswap.finance](https://pancakeswap.finance) |
| **Uniswap** | EVM (ETH, Base, +) | AMM | EVM memecoin venue | 🟢 Live | [uniswap.org](https://uniswap.org) |
| **Aerodrome** | Base | AMM | Base's primary AMM | 🟢 Live | [aerodrome.finance](https://aerodrome.finance) |
| **SunSwap** | Tron | AMM | SunPump migration target | 🟢 Live | [sunswap.com](https://sunswap.com) |
| **Solana Trojan Web (Trojan Trade)** | Solana | Aggregator | Trojan's swap engine | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |
| **OKX DEX** | Multichain | Aggregator | EVM + Solana aggregation | 🟢 Live | [okx.com/web3/dex](https://www.okx.com/web3/dex) |
| 🎟️ **1inch** | EVM | Aggregator | Multi-chain EVM aggregation | 🟢 Live | [1inch.io](https://app.1inch.io/#/r/0xbC9E96731FD3650538d23AD2DbFF46bF0454BA77) |
| **Matcha** (0x) | EVM | Aggregator | 0x-powered EVM aggregator | 🟢 Live | [matcha.xyz](https://matcha.xyz) |
| **CowSwap** | EVM | MEV-protected | Batch auctions, MEV protection | 🟢 Live | [cow.fi](https://cow.fi) |

---

## 📱 Mobile Apps for Memecoin Trading

The best mobile experiences for trading memecoins on the go.

| App | Platform | Chains | Notable Features | Status | Website |
| --- | --- | --- | --- | --- | --- |
| **Phantom** | iOS / Android | Sol, ETH, Base, BSC, Bitcoin | Most-used Solana wallet, in-app swap | 🟢 Live | [phantom.com](https://phantom.com) |
| **Solflare** | iOS / Android | Solana | Solana-native wallet | 🟢 Live | [solflare.com](https://solflare.com) |
| 🎟️ **Backpack Exchange** | iOS / Android | Multi-chain | Wallet + CEX combo | 🟢 Live | [backpack.exchange](https://backpack.exchange/join/a6265f58-1598-4dac-bdcc-2715c6e65ea4) |
| **Trojan Mobile** | iOS / Android | Solana | Native Trojan mobile | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |
| **GMGN Mobile** | iOS / Android | Multichain | Native GMGN app | 🟢 Live | [gmgn.ai/r/tokugawa](https://gmgn.ai/r/tokugawa) |
| 🎟️ **Padre Mobile** | iOS / Android | Multichain | Padre app | 🟢 Live | [trade.padre.gg](https://trade.padre.gg/rk/ccc) |
| **Axiom Mobile** | iOS / Android | Solana | Axiom mobile | 🟢 Live | [axiom.trade/@ny2025](https://axiom.trade/@ny2025) |
| **Photon Mobile** | iOS / Android | Solana | Photon mobile | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io/@coinmonks) |
| **DexScreener Mobile** | iOS / Android | Multichain | Mobile DexScreener | 🟢 Live | [dexscreener.com](https://dexscreener.com) |
| **Defined Mobile** | iOS / Android | Multichain | Defined.fi mobile | 🟢 Live | [defined.fi](https://www.defined.fi) |
| **Bullpen Mobile** | iOS / Android | Sol + Hyperliquid | Bullpen app | 🟢 Live | [bullpen.fi/@agile-yak](https://bullpen.fi/@agile-yak) |
| **Vector** | iOS / Android | Solana | Social-style memecoin app | 🟢 Live | [vector.fun](https://vector.fun) |
| **Moonshot Mobile** | iOS / Android | Solana | Built-in fiat onramp | 🟢 Live | [moonshot.com](https://moonshot.com) |
| **Tank** | iOS / Android | Multi-chain | Wallet + memecoin trading | 🟢 Live | [tank.bot](https://tank.bot) |

---

## 👛 Wallets for Memecoin Traders

Hot wallets, hardware wallets, and burner-friendly wallets.

| Wallet | Type | Chains | Notable Features | Status | Website |
| --- | --- | --- | --- | --- | --- |
| **Phantom** | Hot | Sol, ETH, Base, BSC, Bitcoin | Industry default | 🟢 Live | [phantom.com](https://phantom.com) |
| **Solflare** | Hot | Solana | Solana-native, Ledger support | 🟢 Live | [solflare.com](https://solflare.com) |
| 🎟️ **Backpack** | Hot | Multi | Wallet + CEX combo (xNFT runtime) | 🟢 Live | [backpack.exchange](https://backpack.exchange/join/a6265f58-1598-4dac-bdcc-2715c6e65ea4) |
| **MetaMask** | Hot | EVM + Solana (Snap) | The OG EVM wallet | 🟢 Live | [metamask.io](https://metamask.io) |
| **Rabby** | Hot | EVM | DeBank's wallet, simulation-first | 🟢 Live | [rabby.io](https://rabby.io) |
| 🎟️ **Ledger** | Hardware | Multichain | Hardware wallet, Solana support | 🟢 Live | [ledger.com](https://shop.ledger.com/?r=da6d9b98e517) |
| 🎟️ **Trezor** | Hardware | Multichain | Hardware wallet alternative | 🟢 Live | [trezor.io](https://shop.trezor.io/?offer_id=10&aff_id=5199) |
| 🎟️ **SafePal** | Hardware + Mobile | Multichain | Hardware + mobile combo | 🟢 Live | [safepal.com](https://www.safepal.com/store/s1?ref=zge5mgy) |
| **Trust Wallet** | Hot | Multi | Mobile wallet | 🟢 Live | [trustwallet.com](https://trustwallet.com) |
| **OKX Wallet** | Hot | Multichain | OKX's wallet (CEX + DeFi) | 🟢 Live | [okx.com](https://okx.com/join/8432835) |
| 🎟️ **Bitget Wallet** | Hot + Telegram | Multichain | Bitget Wallet web + Telegram bot | 🟢 Live | [partner.bitget.com](https://partner.bitget.com/bg/L94TTF) |
| **Coinbase Wallet** | Hot | Multichain | Self-custodial Coinbase wallet | 🟢 Live | [wallet.coinbase.com](https://www.coinbase.com/wallet) |
| **Glow** | Hot | Solana | Solana-native wallet | 🟢 Live | [glow.app](https://glow.app) |
| **Magic Eden Wallet** | Hot | Solana, EVM | NFT-focused but works for memes | 🟢 Live | [wallet.magiceden.io](https://wallet.magiceden.io) |
| **Trojan Wallet** | Hot | Solana | Trojan's built-in wallet | 🟢 Live | [trojan.com/@coincodecap](https://trojan.com/@coincodecap) |

---

## 🔍 Block Explorers (Solana, BSC, Base, Tron)

| Explorer | Chain | Notable Features | Status | Website |
| --- | --- | --- | --- | --- |
| **Solscan** | Solana | The standard Solana explorer | 🟢 Live | [solscan.io](https://solscan.io) |
| **Solana FM** | Solana | "True TPS" explorer (Jupiter Labs) | 🟢 Live | [solana.fm](https://solana.fm) |
| **Solana Beach** | Solana | Validator + tx explorer | 🟢 Live | [solanabeach.io](https://solanabeach.io) |
| **XRAY** | Solana | Helius-powered explorer | 🟢 Live | [xray.helius.dev](https://xray.helius.dev) |
| **BscScan** | BNB Chain | Default BSC explorer | 🟢 Live | [bscscan.com](https://bscscan.com) |
| **BaseScan** | Base | Default Base explorer | 🟢 Live | [basescan.org](https://basescan.org) |
| **Tronscan** | Tron | Default Tron explorer | 🟢 Live | [tronscan.org](https://tronscan.org) |
| **Etherscan** | Ethereum | The original | 🟢 Live | [etherscan.io](https://etherscan.io) |
| **Blockscout** | Multi-chain | Open-source EVM explorer | 🟢 Live | [blockscout.com](https://www.blockscout.com) |
| **HyperEVMScan** | Hyperliquid | Etherscan-style HL explorer | 🟢 Live | [hyperevmscan.io](https://hyperevmscan.io) |

---

## 💸 Tax Tools for Memecoin Traders

Memecoin trades break most tax software. These actually handle Solana DeFi + memecoin complexity.

| Tool | Chains | Notable Features | Status | Website |
| --- | --- | --- | --- | --- |
| 🎟️ ⚡ **Awaken Tax** | Solana + Multi | Native Solana, Phantom partner, 25K+ DeFi protocols | 🟢 Live | [awaken.tax](https://awaken.tax/?ref=coinmonks) |
| **CoinTracker** | Multichain | Solana wallet sync, NFTs, DeFi | 🟢 Live | [cointracker.io](https://www.cointracker.io) |
| 🎟️ **CoinTracking** | Multichain | One of the oldest crypto tax tools, Solana + EVM | 🟢 Live | [cointracking.info](https://cointracking.info?ref=T987862) |
| **Koinly** | Multichain | 900+ integrations, weak Solana sync | 🟢 Live | [koinly.io](https://koinly.io) |
| **CoinLedger** | Multichain | Native Jupiter + Magic Eden support | 🟢 Live | [coinledger.io](https://coinledger.io) |
| **Crypto Tax Calculator** | Multichain | Pro-grade DeFi tax | 🟢 Live | [cryptotaxcalculator.io](https://cryptotaxcalculator.io) |
| **TaxBit** | Multichain | Enterprise-friendly tax | 🟢 Live | [taxbit.com](https://taxbit.com) |
| **ZenLedger** | Multichain | Tax + accounting | 🟢 Live | [zenledger.io](https://zenledger.io) |
| **Stake.tax** | Solana | Free Solana tax export (Koinly fallback) | 🟢 Live | [stake.tax](https://stake.tax) |
| **Solana.tax** | Solana | Solana-specific tax guide hub | 🟢 Live | [solana.tax](https://solana.tax) |
| **Rotki** | Multichain | Open-source local-first tax | 🟢 Live | [rotki.com](https://rotki.com) |

---

## 🤝 MCPs for Memecoin Traders (AI Agents)

Connect AI agents (Claude, Cursor, ChatGPT, Codex) directly to memecoin data and execution. See **[Awesome Crypto MCPs](https://github.com/buddies2705/awesome-crypto-mcp)** for the full list.

| MCP | Purpose | Status | Link |
| --- | --- | --- | --- |
| ⭐ **Bitquery MCP** | Pump.fun / LetsBonk / Four.meme / SunPump trades, OHLC, market cap in plain English | 🟢 Live | [mcp.bitquery.io](https://mcp.bitquery.io/) |
| **Jupiter MCP** | Solana token swaps via Jupiter Ultra API | 🟢 Live | [GitHub](https://github.com/kukapay/jupiter-mcp) |
| **PumpFun Wallets MCP** | Analyse Pump.fun + PumpSwap wallets | 🟢 Live | [GitHub](https://github.com/kukapay/pumpfun-wallets-mcp) |
| **Memecoin Radar MCP** | Solana memecoin & Pump.fun launch radar | 🟢 Live | [GitHub](https://github.com/kukapay/memecoin-radar-mcp) |
| **Solana Launchpads MCP** | Daily activity across Solana launchpads | 🟢 Live | [GitHub](https://github.com/kukapay/solana-launchpads-mcp) |
| **Raydium LaunchLab MCP** | Launch / buy / sell tokens on LaunchLab | 🟢 Live | [GitHub](https://github.com/kukapay/raydium-launchlab-mcp) |
| **PumpSwap MCP** | Automated PumpSwap trading | 🟢 Live | [GitHub](https://github.com/kukapay/pumpswap-mcp) |
| **MCP Meme Deployer** | Deploy tradable Solana tokens via Claude chat | 🟢 Live | [GitHub](https://github.com/kirabuilds/mcp-meme-deployer) |
| **Memecoin Observatory** | Memecoin radar, social signals, whale tracking | 🟢 Live | [GitHub](https://github.com/tony-42069/solana-mcp) |
| **Solana Agent Kit MCP** | 40+ Solana actions for AI agents | 🟢 Live | [GitHub](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) |
| **Rug Check MCP** | Detect rug-pull risk in Solana memecoins | 🟢 Live | [GitHub](https://github.com/kukapay/rug-check-mcp) |
| **Honeypot Detector MCP** | Detect honeypot tokens on ETH / BSC / Base | 🟢 Live | [GitHub](https://github.com/kukapay/honeypot-detector-mcp) |
| **Whale Tracker MCP** | Track cryptocurrency whale transactions | 🟢 Live | [GitHub](https://github.com/kukapay/whale-tracker-mcp) |
| **Crypto Sentiment MCP** | Santiment-powered sentiment | 🟢 Live | [GitHub](https://github.com/kukapay/crypto-sentiment-mcp) |
| **DexScreener Trending MCP** | Real-time trending tokens | 🟢 Live | [GitHub](https://github.com/kukapay/dexscreener-trending-mcp) |
| **Crypto Indicators MCP** | 50+ TA indicators for memecoins | 🟢 Live | [GitHub](https://github.com/kukapay/crypto-indicators-mcp) |
| **Birdeye MCP** | Real-time Solana on-chain data | 🟢 Live | [Birdeye Docs](https://birdeye.so) |
| **TWZRD Agent Intel** | Verify Solana agent wallet trust before x402 payments; `score_agent`, `preflight_check` free, `get_trust_receipt` via x402 | 🟢 Live | [intel.twzrd.xyz](https://intel.twzrd.xyz) |

---

## 🏗️ Infrastructure & Developer Tools

For builders making memecoin tools, dashboards, bots, dashboards, or analytics.

| Tool | Chains | Type | Status | Website |
| --- | --- | --- | --- | --- |
| ⭐ **Bitquery** | Sol, ETH, BSC, Base, Tron, Polygon, Arbitrum, Optimism | GraphQL + WebSocket + Kafka + gRPC | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Bitquery IDE** | Multichain | GraphQL query editor | 🟢 Live | [ide.bitquery.io](https://ide.bitquery.io/) |
| **Helius** | Solana | RPC, Webhooks, Enhanced APIs, Geyser | 🟢 Live | [helius.dev](https://helius.dev) |
| **Triton One** | Solana | RPC + gRPC + Geyser (premium) | 🟢 Live | [triton.one](https://triton.one) |
| **Shyft** | Solana | RPC + APIs | 🟢 Live | [shyft.to](https://shyft.to) |
| **Jupiter API** | Solana | DEX aggregator API | 🟢 Live | [jup.ag](https://jup.ag) |
| **QuickNode** | Multichain | RPC + Streams | 🟢 Live | [quicknode.com](https://www.quicknode.com) |
| **Alchemy** | Multichain | RPC + APIs | 🟢 Live | [alchemy.com](https://www.alchemy.com) |
| **Chainstack** | Multichain | RPC + indexing | 🟢 Live | [chainstack.com](https://chainstack.com) |
| **Goldsky** | Multichain | Real-time indexing + subgraphs | 🟢 Live | [goldsky.com](https://goldsky.com) |
| **The Graph** | Multichain | Decentralised indexing | 🟢 Live | [thegraph.com](https://thegraph.com) |
| **Solana Tracker API** | Solana | Memecoin data API | 🟢 Live | [solanatracker.io](https://www.solanatracker.io) |
| **MadeOnSol API** | Solana | KOL trades + signals API | 🟢 Live | [madeonsol.com/developer](https://madeonsol.com/developer) |
| **Birdeye API** | Solana + Multi | Pricing + trade API | 🟢 Live | [docs.birdeye.so](https://docs.birdeye.so) |
| **Defined.fi API** | Multichain | Real-time pair data API | 🟢 Live | [defined.fi/api](https://www.defined.fi/api) |
| **DexScreener API** | Multichain | Free public API | 🟢 Live | [docs.dexscreener.com](https://docs.dexscreener.com) |
| **GeckoTerminal API** | Multichain | Free CoinGecko DEX API | 🟢 Live | [geckoterminal.com/api](https://www.geckoterminal.com/api) |
| **Solana Web3.js** | Solana | Solana SDK | 🟢 Live | [solana.com](https://solana.com) |
| **Anchor Framework** | Solana | Solana smart-contract framework | 🟢 Live | [anchor-lang.com](https://www.anchor-lang.com) |

---

## 🪙 Notable Memecoins to Know

The "blue chip" memecoins worth following — most have outlived their original moment and have liquid markets, derivatives, and dedicated communities.

| Token | Chain | Origin | Notable | Track Via |
| --- | --- | --- | --- | --- |
| **DOGE** | Doge / BSC / ETH | The original (2013) | $20B+ MCap, ETF speculation | [coingecko.com/en/coins/dogecoin](https://www.coingecko.com/en/coins/dogecoin) |
| **SHIB** | Ethereum | 2020 | Shibarium L2, large CT presence | [coingecko.com/en/coins/shiba-inu](https://www.coingecko.com/en/coins/shiba-inu) |
| **PEPE** | Ethereum | 2023 | Pioneered the 2023–2024 meme cycle | [coingecko.com/en/coins/pepe](https://www.coingecko.com/en/coins/pepe) |
| **BONK** | Solana | 2022 | First major Solana meme, BONK.fun launchpad | [coingecko.com/en/coins/bonk](https://www.coingecko.com/en/coins/bonk) |
| **WIF (Dogwifhat)** | Solana | 2023 | "Hat on dog", multiple 100x runs | [coingecko.com/en/coins/dogwifcoin](https://www.coingecko.com/en/coins/dogwifcoin) |
| **POPCAT** | Solana | 2024 | Long-term Solana meme | [coingecko.com/en/coins/popcat](https://www.coingecko.com/en/coins/popcat) |
| **FARTCOIN** | Solana | 2024 | Pump.fun graduate, billion-dollar meme | [coingecko.com/en/coins/fartcoin](https://www.coingecko.com/en/coins/fartcoin) |
| **TRUMP** | Solana | 2025 | Politically themed meme | [coingecko.com/en/coins/official-trump](https://www.coingecko.com/en/coins/official-trump) |
| **MELANIA** | Solana | 2025 | Counter-Trump meme | [coingecko.com/en/coins/melania-meme](https://www.coingecko.com/en/coins/melania-meme) |
| **MOG** | Ethereum | 2024 | Cultural meme, large EVM holder count | [coingecko.com/en/coins/mog-coin](https://www.coingecko.com/en/coins/mog-coin) |
| **MOTHER** (Iggy) | Solana | 2024 | Celebrity-launched Solana meme | [DexScreener](https://dexscreener.com) |
| **GOAT** | Solana | 2024 | "Goatseus Maximus", first AI-agent meme | [coingecko.com/en/coins/goatseus-maximus](https://www.coingecko.com/en/coins/goatseus-maximus) |
| **AI16Z** | Solana | 2024 | ai16z DAO meme, agent narrative | [coingecko.com/en/coins/ai16z](https://www.coingecko.com/en/coins/ai16z) |
| **FLOKI** | Multi | 2021 | Long-running Floki community | [coingecko.com/en/coins/floki](https://www.coingecko.com/en/coins/floki) |
| **BRETT** | Base | 2024 | Top Base memecoin | [coingecko.com/en/coins/based-brett](https://www.coingecko.com/en/coins/based-brett) |
| **DEGEN** | Base | 2024 | Farcaster-native memecoin | [coingecko.com/en/coins/degen-base](https://www.coingecko.com/en/coins/degen-base) |
| **MOODENG** | Solana | 2024 | Pygmy hippo meme | [coingecko.com/en/coins/moo-deng](https://www.coingecko.com/en/coins/moo-deng) |
| **PNUT (Peanut)** | Solana | 2024 | Squirrel meme, viral run | [coingecko.com/en/coins/peanut-the-squirrel](https://www.coingecko.com/en/coins/peanut-the-squirrel) |
| **PENGU (Pudgy)** | Solana | 2024 | Pudgy Penguins, NFT-to-meme bridge | [coingecko.com/en/coins/pudgy-penguins](https://www.coingecko.com/en/coins/pudgy-penguins) |
| **ME (Magic Eden)** | Multichain | 2024 | NFT marketplace token | [coingecko.com/en/coins/magic-eden](https://www.coingecko.com/en/coins/magic-eden) |

> **Note**: Inclusion is informational, not endorsement. Memecoins are extremely volatile — most go to zero. DYOR.

---

## 🐦 Crypto Twitter Accounts & KOLs to Follow

CT (Crypto Twitter) is where memecoin alpha actually breaks. Below is a starter list of accounts traders follow — verify each individually, never blindly copy trades.

### Solana memecoin specialists

- **[@aeyakovenko](https://twitter.com/aeyakovenko)** — Anatoly Yakovenko (Solana co-founder)
- **[@toly](https://twitter.com/aeyakovenko)** — Same person, different handle
- **[@GwartyGwart](https://twitter.com/GwartyGwart)** — Solana memecoin commentator
- **[@MustStopMurad](https://twitter.com/MustStopMurad)** — Long-form memecoin thesis
- **[@SmokeyTheBera](https://twitter.com/SmokeyTheBera)** — Bera + meme observer
- **[@beaniemaxi](https://twitter.com/beaniemaxi)** — NFT + meme commentator
- **[@CryptoKaduna](https://twitter.com/CryptoKaduna)** — Memecoin gem caller
- **[@xeer_eth](https://twitter.com/xeer_eth)** — Solana on-chain analytics

### General CT alpha

- **[@cobie](https://twitter.com/cobie)** — UpOnly podcast, market commentary
- **[@hsakatrades](https://twitter.com/hsakatrades)** — Trader, market structure
- **[@CryptoCred](https://twitter.com/CryptoCred)** — TA + market education
- **[@CryptoHayes](https://twitter.com/CryptoHayes)** — Arthur Hayes, BitMEX co-founder
- **[@_CryptoHustle](https://twitter.com/_CryptoHustle)** — Memecoin alpha
- **[@DefiSquared](https://twitter.com/DefiSquared)** — DeFi + memes
- **[@adamscochran](https://twitter.com/adamscochran)** — Crypto VC analyst
- **[@blknoiz06](https://twitter.com/blknoiz06)** — "Ansem", memecoin trader (Bullpen co-founder)
- **[@CL207](https://twitter.com/CL207)** — Solana trader
- **[@ottohuang_](https://twitter.com/ottohuang_)** — Memecoin commentary

### On-chain intelligence

- **[@lookonchain](https://twitter.com/lookonchain)** — Real-time whale tracking
- **[@nansen_ai](https://twitter.com/nansen_ai)** — Wallet labels and smart-money flows
- **[@arkham](https://twitter.com/arkham)** — Entity-level on-chain intel
- **[@pumpdotfun](https://twitter.com/pumpdotfun)** — Pump.fun's official account
- **[@bitquery](https://twitter.com/bitquery)** — On-chain data updates
- **[@SolanaFloor](https://twitter.com/SolanaFloor)** — Solana ecosystem news

### Founders + builders

- **[@rajgokal](https://twitter.com/rajgokal)** — Solana co-founder
- **[@aeyakovenko](https://twitter.com/aeyakovenko)** — Solana co-founder
- **[@aoxbt](https://twitter.com/aoxbt)** — AIxBT agent (auto-CT)
- **[@axiomexchange](https://twitter.com/axiomexchange)** — Axiom official
- **[@trojanonsolana](https://twitter.com/trojanonsolana)** — Trojan official

> Memecoin CT is a high-noise signal. Treat every "100x call" as marketing, not analysis.

---

## ▶️ YouTube Channels & Educational Content

| Channel | Focus | Link |
| --- | --- | --- |
| **The Solana Show** | Solana ecosystem | [YouTube](https://www.youtube.com/@theSolanaShow) |
| **Coin Bureau** | Crypto education + memecoin coverage | [YouTube](https://www.youtube.com/@CoinBureau) |
| **InvestAnswers** | Macro + memecoin | [YouTube](https://www.youtube.com/@InvestAnswers) |
| **Benjamin Cowen** | TA + on-chain | [YouTube](https://www.youtube.com/@IntoTheCryptoverse) |
| **Crypto Banter** | Daily memecoin coverage | [YouTube](https://www.youtube.com/@cryptobanter) |
| **Soltrunkz** | Solana memecoin trading | [YouTube](https://www.youtube.com/@soltrunkz) |
| **MoonCarl** | Memecoin scanner & calls | [YouTube](https://www.youtube.com/@MoonCarl) |
| **Altcoin Daily** | Daily altcoin news | [YouTube](https://www.youtube.com/@AltcoinDaily) |
| **Whiteboard Crypto** | Crypto concepts explained | [YouTube](https://www.youtube.com/@WhiteboardCrypto) |
| **Bullrank** | Bot + terminal reviews | [bullrank.io](https://bullrank.io) |
| **MadeOnSol Blog** | Solana research articles | [madeonsol.com/blog](https://madeonsol.com/blog) |
| **Hyperliquid Guide** | Hyperliquid memes + perps | [hyperliquidguide.com](https://hyperliquidguide.com) |

---

## 💬 Discord Servers & Telegram Communities

- **Pump.fun Discord** — Official Pump.fun community
- **Trojan Telegram** — Trojan bot users
- **GMGN Telegram** — GMGN community
- **r/solana** — Solana subreddit
- **r/CryptoMoonShots** — High-risk gems
- **r/CryptoCurrency** — General discussion
- **Bullrank Discord** — Bot/terminal discussion
- **MadeOnSol Discord** — Solana tool reviews
- **DexScreener Telegram** — Trending alerts
- **Photon Telegram** — Photon community
- **Bullpen Telegram** — Bullpen community

> **Safety note:** Verify all Discord/Telegram invite links from official sites only. Memecoin space is full of clones impersonating popular bots and projects.

---

## 📚 Resources & Guides

### Pump.fun & Bonding Curves

- [Bitquery — Pump.fun Token Lifecycle](https://docs.bitquery.io/docs/examples/Solana/pump-fun-to-pump-swap/) — Bonding curves → PumpSwap migration
- [Bitquery — Pump.fun API Examples](https://docs.bitquery.io/docs/blockchain/Solana/Pumpfun/Pump-Fun-API/) — Trade-level API patterns
- [Solana Guides — Best Memecoin Launchpads 2026](https://solanaguides.com/best-memecoin-launchpads-on-solana-2026-pump-fun-vs-letsbonk-vs-raydium-launchlab)
- [BlockEden — Meme Launchpad 2.0](https://blockeden.xyz/blog/2026/04/22/meme-launchpad-2-pump-fun-letsbonk-anti-sniper-bonding-curve-professionalization/)

### Trading bots & terminals

- [MadeOnSol — Best Solana Telegram Bots 2026](https://madeonsol.com/best/telegram-bots)
- [SolanaSniperBot — Best Solana Trading Bots 2026](https://solanasniperbot.net/best-solana-trading-bots/)
- [Bullrank — Telegram Trading Bots Tested & Ranked](https://bullrank.io/best/telegram-trading-bots)
- [CoinBrain — Best Web Trading Terminal 2026](https://devel.coinbrain.com/blog/which-web-trading-terminal-is-the-best)
- [Bullrank — Axiom vs Photon vs GMGN](https://bullrank.io/learn/axiom-vs-photon-vs-gmgn)
- [DexTools — Best Telegram Bots Solana 2026](https://www.dextools.io/tutorials/best-telegram-bots-for-solana-2026)

### Smart money & whale tracking

- [Cielo PnL Leaderboard Docs](https://docs.cielo.finance/wallet-tracking/my-wallets/pnl-leaderboard)
- [MadeOnSol — Best Solana Analytics Tools 2026](https://madeonsol.com/blog/best-solana-analytics-tools-track-whales)
- [Nansen — Top Memecoin Wallets to Track](https://www.nansen.ai/post/top-10-memecoin-wallets-to-track-for-2025)
- [MadeOnSol — KOL First-Touch Backtest](https://madeonsol.com/blog/scout-signal-first-kol-touch-backtest-solana)

### Trenches & pre-bonding-curve

- [Padre Docs — Trenches Guide](https://docs.padre.gg/app-guide/trenches)
- [Trench Bot — Bundle Scanner Guide](https://docs.trench.bot/bundle-tools/bundle-scanner-guide)
- [SolanaBox — Trenchy Setup](https://solanabox.tools/tools/trenchy)

### Tax / accounting

- [Awaken — Solana Tax Guide](https://awaken.tax/integrations/solana-tax-guide)
- [Solana.tax — Software Comparison](https://solana.tax/)
- [Solana Guides — Best Tax Software (UK)](https://solanaguides.com/best-crypto-tax-software-solana-defi-uk)

### Phantom / wallet education

- [Phantom — Believe.app Explainer](https://phantom.com/learn/crypto-101/believe-app-solana)
- [Phantom — Crypto 101](https://phantom.com/learn)

### Safety / rug avoidance

- [Bitquery — Pump.fun Phishing Detection](https://docs.bitquery.io/docs/blockchain/Solana/Pumpfun/Pump-Fun-API/)
- [GoPlus Token Security Docs](https://gopluslabs.io/token-security)
- [Solsniffer Methodology](https://solsniffer.com)

---

## 🔗 Related Awesome Lists

- [**Awesome Crypto MCPs**](https://github.com/buddies2705/awesome-crypto-mcp) — 100+ Crypto/Web3 MCP servers (Bitquery, Hyperliquid, Pump.fun, Solana Agent Kit, etc.) that AI agents like Claude / Cursor / ChatGPT use to trade memecoins programmatically.
- [**Awesome Perp DEXs**](https://github.com/buddies2705/awesome-perp-dex) — 200+ perpetual DEXs (Hyperliquid, dYdX, GMX, Lighter, Aster) plus terminals, analytics, and bots. Perfect companion for memecoin traders who hedge with perps.
- [**Awesome Prediction Markets**](https://github.com/buddies2705/awesome-prediction-market) — Polymarket, Kalshi, Limitless platforms, terminals, alert bots, analytics, AI agents.
- [**Awesome Crypto Tax**](https://github.com/buddies2705/awesome-crypto-tax) — 150+ crypto tax tools. Awaken Tax (the DeFi-first tax software) handles Pump.fun / LetsBonk / Bags trades natively; CoinLedger and Koinly are also strong options for memecoin volume.
- [**Awesome Blockchain & Crypto APIs**](https://github.com/buddies2705/awesome-blockchain-crypto-api) — 315+ blockchain APIs (Bitquery, Helius, Triton, Birdeye, GMGN, Bitquery Pump.fun API). The data plumbing under most memecoin trading tools in this list.

---

## 🤝 Contributing

PRs are welcome — the memecoin space ships *daily* and we'd rather over-include than miss something.

1. **Fork** this repo, create a feature branch (e.g. `feature/add-foo-bot`).
2. **Match the table format** of the section you're adding to.
3. **Quality bar:**
   - Tool must be live (or in public testnet — mark 🟡)
   - Must directly serve memecoin traders or builders
   - Must have a working website / app
   - Not a spammy clone, not abandoned, not a CEX without memecoin focus
4. **Use the legend** consistently (🟢 / 🟡 / 🔴 / ⚡ / 🆕 / 🎟️).
5. **No referral spam.** One affiliate link max per row; only mark 🎟️ if it's a verified working referral.
6. Open a PR with a one-line summary of what you added.

For corrections (broken links, dead projects, stale stats) — open an issue or a PR with a brief note.

---

## 📄 License

MIT — see [LICENSE](LICENSE).

---

**Note**: Memecoin trading is extremely high-risk. Most memecoins go to zero — often within hours. Tools and platforms change weekly. Always verify on each project's official site before depositing funds. Nothing on this list is financial advice. Some links are affiliate / referral links (marked 🎟️) — they don't change the price you pay, but they help support this list.

Made with 🐸 for the on-chain memecoin community.

---

## 🔍 Related Searches

If you arrived here looking for any of the following, you're in the right place:

`memecoin trading` · `Solana memecoins` · `Pump.fun` · `LetsBonk` · `Bags` · `best memecoin sniper bot` · `Trojan vs Photon vs GMGN` · `Axiom trading terminal` · `Pump.fun trenches` · `Solana smart money tracker` · `memecoin rug check` · `Bubblemaps` · `Cielo` · `memecoin copy trading` · `Pump.fun API` · `Bitquery memecoin` · `memecoin tax software`

---

## 📈 Popular Use Cases

- **Pump.fun trenches sniping** — Pair Padre Trenches + Bloom + RugCheck + Bitquery alerts to catch tokens at <5% bonding curve.
- **Smart-money copy trading** — GMGN + Cielo + Axiom Vision to discover wallets, then auto-mirror via Trojan / GMGN copy.
- **Multi-chain memecoin trading** — Maestro / BullX / GMGN for one bot across Solana + BSC + Base + Tron.
- **Solana memecoin discovery** — DexScreener + Birdeye + GMGN + Photon Memescope as your daily scanner stack.
- **Avoiding rugs** — Run every token through RugCheck → Solsniffer → Bubblemaps → Trench Bot before buying.
- **AI memecoin agents** — Bitquery MCP + Pump.fun Wallets MCP + Memecoin Radar MCP let Claude / Cursor / ChatGPT find and trade memes in plain English.
- **Sniping launches** — Banana Gun + Maestro + Bloom for cross-chain new-launch sniping.
- **Whale tracking** — Cielo (cross-chain) + Nansen (entity intel) + Lookonchain (real-time alerts).
- **Memecoin tax** — Awaken Tax for Solana + DeFi-native tax handling, fallback to CoinTracker for multi-chain.
- **Self-hosted memecoin bots** — Bitquery + Helius + Jupiter API + Solana Web3.js to build your own trading stack.
- **CT alpha + verification** — Follow KOL wallets via GMGN/Axiom Vision and verify against their actual on-chain trades, not just tweets.
- **Bonding-curve graduation plays** — Track Pump.fun tokens approaching 95% via PumpScope / Trench Bot / Padre Trenches and buy the migration moment.
