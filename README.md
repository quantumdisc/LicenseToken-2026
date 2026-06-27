# LicenseToken-2026

**A native Solana primitive for selling the right to execute a program.**

Subscriptions, tiers, lifetime licenses, and an atomic resale market with creator
royalties, all enforced on-chain by the Solana runtime rather than a server. The
protocol charges no fee: 100% of every payment goes to the creator. When a creator
burns their program's upgrade authority, the licensing terms become permanent and
verifiable by anyone.

It proposes a fourth native asset type. Not spendable value, not fungible ownership,
not unique ownership, but the **right to execute**.

### Read the whitepaper

**[WHITEPAPER.pdf](https://quantumdisc.github.io/LicenseToken-2026/WHITEPAPER.pdf)**

### The idea in one minute

A blockchain has produced three native asset types: spendable value, fungible
ownership, and unique ownership. None of them records a statement about *using*. Yet
the largest businesses in software are built on the recurring right to use, granted
for a time and under terms.

LicenseToken-2026 makes that right an on-chain asset. A license is an account proving
one wallet may run one program until one moment in time. The program performs the
check inside its own instruction as a mandatory step in its execution path, and once
the creator burns the upgrade authority, that check can never be removed. There is no
server to bypass. Payment, renewal, gift, sale, and revocation are ordinary program
instructions that settle without an intermediary, and a creator can make the terms
permanent in a way a buyer can verify rather than trust.

### Contact

Quantum Discoveries · quantumdiscoveries@proton.me

<sub><sub>The terms described in this document are subject to change.</sub></sub>
