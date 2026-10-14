# Students — POLIASTRO

**Project:** POLIASTRO  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/poliastro/poliastro  
**Pinned commit:** `21fd7719e89a7d22b4eac63141a60a7f1b01768c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `408c5baa12ef0d2639babd36d39c828ed688f6556af58c766ebaa6fb913d0b36`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `21fd7719e89a7d22b4eac63141a60a7f1b01768c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `408c5baa12ef0d2639babd36d39c828ed688f6556af58c766ebaa6fb913d0b36`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
