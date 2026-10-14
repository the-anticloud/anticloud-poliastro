# Ethics — POLIASTRO

**Project:** POLIASTRO  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/poliastro/poliastro  
**Pinned commit:** `21fd7719e89a7d22b4eac63141a60a7f1b01768c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `408c5baa12ef0d2639babd36d39c828ed688f6556af58c766ebaa6fb913d0b36`  
**Date:** October 2026

## Position

POLIASTRO is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
