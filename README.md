<p align="center"><img src="banner.svg" alt="Circuit. We don't wrap, we shield." width="100%"></p>

<p align="center">
  <a href="https://rheeunion.github.io/circuit-demo/"><b>Open the demo →</b></a>
</p>

**Circuit** is confidential DeFi on the liquidity that already exists. Deposit into a public ERC-4626 vault through one Enso route, and hold the position privately as a note in the Orbinum shielded pool.

This repository only hosts the static demo build. Source code is private.

## Try it

1. Open the demo in a browser with an EVM wallet (MetaMask, Rabby or similar).
2. **Connect wallet**, then **Sign to unlock**. No gas, no transaction.
3. **Deposit:** pick a USDC vault, enter an amount, **Preview route**, then **Shield (simulation)**.
4. **Withdraw:** send part of your note to a fresh address and watch the change note appear.

## Simulation mode

| Live | Simulated in your browser |
|---|---|
| Enso routes and quotes | Shielded pool, Merkle tree and nullifiers |
| ERC-4626 vault share prices on Base | Withdraw proofs (mock prover) and the relayer |

**No funds move.** Circuit is in development and has not been audited.

<p align="center"><sub>Powered by <b>Orbinum</b> · <b>Enso</b></sub></p>
