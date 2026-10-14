# Educators — POLIASTRO

**Project:** POLIASTRO  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/poliastro/poliastro  
**Pinned commit:** `21fd7719e89a7d22b4eac63141a60a7f1b01768c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `408c5baa12ef0d2639babd36d39c828ed688f6556af58c766ebaa6fb913d0b36`  
**Date:** October 2026

## Teaching with POLIASTRO

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `408c5baa12ef0d2639babd36d39c828ed688f6556af58c766ebaa6fb913d0b36` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
