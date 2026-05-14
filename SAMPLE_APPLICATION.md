# SPP3 Sample Application

> This is a realistic, minimally viable submission for reference. It demonstrates clear structure, verifiable deliverables, and direct rationale. Not a template; use it to understand what a fundable application looks like.

## Example: ENS Indexer and Analytics Infrastructure

---

**Team:** Blockscout Labs  
**ENS handle:** blockscout.eth  
**Contact:** grants@blockscout.com  
**Requested amount:** $320,000  
**Category:** ENS Infrastructure

---

## Prior Work

Blockscout has maintained open-source EVM block explorer infrastructure since 2018. During SPP2 we received $280,000 to build and maintain an ENS-native indexer supporting reverse resolution across mainnet and three L2s. All four milestones delivered on schedule. Quarterly reports posted to the forum (with links to verifiable deliverables in each). One milestone was rescoped in Q2 (Base L2 support delayed by an upstream contract change); disclosed in the Q2 report and delivered in Q3.

---

## Problem

ENS resolution data is fragmented across chains. Developers building on ENS today query multiple RPC endpoints to resolve names across L2s, producing inconsistent results and slowing integration. There is no single open, maintained source of truth for ENS state across mainnet and major L2s.

## Approach

We will extend our existing ENS indexer to cover Optimism, Arbitrum, Base, and Linea, with unified query endpoints and a public dashboard tracking resolution volume, registration trends, and integration health by chain. All infrastructure is open source and self-hostable.

## Success Definition

By May 2027: unified indexer live across all four L2s, query endpoints publicly documented and available, and at least 10 third-party integrations (wallets, dApps, or developer tools) using the endpoints in production, verifiable by on-chain lookup or public documentation.

---

## Milestones

| # | Deliverable | Verification | Date |
|---|-------------|--------------|------|
| 1 | Optimism and Arbitrum indexing live | Public endpoint + dashboard link | Aug 31, 2026 |
| 2 | Base and Linea indexing live | Public endpoint + dashboard link | Nov 30, 2026 |
| 3 | 5 third-party integrations documented | Public list with links | Nov 30, 2026 |
| 4 | 10 third-party integrations documented | Public list with links | Feb 28, 2027 |
| 5 | End-of-cycle retrospective | Forum post | May 31, 2027 |

---

## Budget

| Item | Amount |
|------|--------|
| Engineering (2 FTE, 12 months) | $260,000 |
| Infrastructure and hosting | $40,000 |
| Documentation and developer relations | $20,000 |
| **Total** | **$320,000** |

---

## Why SPP3

L2 ENS resolution is currently a gap that suppresses integrations. Developers skip ENS support when resolution is unreliable across chains. This infrastructure closes that gap and is maintainable beyond the cycle; we have run the mainnet indexer for two years without interruption. Without SPP3 funding, this work does not happen on this timeline.

---

## About This Sample

This is a realistic, minimally viable submission in text form. Real applications typically include substantial supporting material:
- **Links** to prior work, repos, deployed contracts, live products
- **Data & analytics** showing adoption, usage, or impact metrics
- **Videos or demos** of infrastructure or products
- **Supporting documents** (whitepapers, technical specs, audits)
- **Letters of support** or partnership agreements
- **Forum posts or public records** of prior delivery

**You are free to structure your application differently.** This sample shows one format, but you have creative freedom in how you present your work—as long as you include all minimum criteria:
- Prior delivery history (verifiable evidence)
- Clear problem and approach
- Specific, measurable success definition
- Milestone structure with verification methods
- Itemized budget
- Direct rationale for why SPP3 funds this work

Make your case with the evidence and artifacts that best support it. Use this as a reference for clarity and structure, not as a rigid template.
