# qwatt-evidence

Evidence published by the QWATT proposer host: every batch, accepted or rejected, with its hash, reasons, samples and anchoring proposal. Written only by that host's deploy key.

A public history: published files are never rewritten, except `index.json` and a pending envelope replaced for the same batch, and `.jsonl` files only grow. One directory per run: `run/` is the seven-day live run, and `rehearsal-YYYY-MM-DD/` are rehearsals.

Check it with the code at [github.com/academiaseul/QWATT](https://github.com/academiaseul/QWATT):

```
node batch/verify-cli.js <clone>/<run>
node ops/evidence-audit.js <clone>
```

Simulated input · assurance A0 · Stellar testnet. QWATT is not electricity, not an investment, not a security, not a renewable energy certificate and not a carbon credit.
