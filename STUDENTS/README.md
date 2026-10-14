# Students — ELEMENT_WEB

**Project:** ELEMENT_WEB  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `c345bb453bf11badb4831a6a3f600c9372b3a336`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f42afdbf5f095111d07a18112a62916670af2cf728f2e465da4b927d2613085`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `c345bb453bf11badb4831a6a3f600c9372b3a336`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `2f42afdbf5f095111d07a18112a62916670af2cf728f2e465da4b927d2613085`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
