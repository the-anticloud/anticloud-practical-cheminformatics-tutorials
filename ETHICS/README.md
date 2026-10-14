# Ethics — PRACTICAL_CHEMINFORMATICS_TUTORIALS

**Project:** PRACTICAL_CHEMINFORMATICS_TUTORIALS  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/PatWalters/practical_cheminformatics_tutorials  
**Pinned commit:** `370dc66428819e06a2c87a859fab122b77b22f5b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f503f9a113ba56ca184ae1c09e7d4a1c3531240bf00d2ac9fd7c4303399b86da`  
**Date:** October 2026

## Position

PRACTICAL_CHEMINFORMATICS_TUTORIALS is packaged for offline deployment with a verifiable audit trail. The
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
