# Notes

Scratchpad for random dev notes.

## Solana

- jito bundles need a tip; no tip, no landing.
- fetch the blockhash right before signing, not earlier.
## EVM

- resync nonce and retry on a flaky RPC; a landed-but-unacked tx bumps it.
- simulate before every send.
