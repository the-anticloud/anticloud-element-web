# Educators — ELEMENT_WEB

**Project:** ELEMENT_WEB  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `c345bb453bf11badb4831a6a3f600c9372b3a336`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f42afdbf5f095111d07a18112a62916670af2cf728f2e465da4b927d2613085`  
**Date:** October 2026

## Teaching with ELEMENT_WEB

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `2f42afdbf5f095111d07a18112a62916670af2cf728f2e465da4b927d2613085` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
