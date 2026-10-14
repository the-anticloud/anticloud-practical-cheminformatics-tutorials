# Students — PRACTICAL_CHEMINFORMATICS_TUTORIALS

**Project:** PRACTICAL_CHEMINFORMATICS_TUTORIALS  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/PatWalters/practical_cheminformatics_tutorials  
**Pinned commit:** `370dc66428819e06a2c87a859fab122b77b22f5b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f503f9a113ba56ca184ae1c09e7d4a1c3531240bf00d2ac9fd7c4303399b86da`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `370dc66428819e06a2c87a859fab122b77b22f5b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f503f9a113ba56ca184ae1c09e7d4a1c3531240bf00d2ac9fd7c4303399b86da`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
