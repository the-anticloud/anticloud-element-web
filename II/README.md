# Independent Insurance — ELEMENT_WEB

**Project:** ELEMENT_WEB  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `c345bb453bf11badb4831a6a3f600c9372b3a336`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f42afdbf5f095111d07a18112a62916670af2cf728f2e465da4b927d2613085`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | ELEMENT_WEB with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `2f42afdbf5f095111d07a18112a62916670af2cf728f2e465da4b927d2613085`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
