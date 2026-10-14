# Reproduction — PRACTICAL_CHEMINFORMATICS_TUTORIALS

1. Environment: Windows, Python 3.12.10, runner version 1.0.0
2. `cd anticloud/`
3. `python tools\run_bench.py --quiet`  (exit 0 = all 16 PASS)
4. Compare `anticloud/BENCH.json` SHA3-256: `2c0c1e6b99e5399690bdd49f5b9db14e5cc520d284aaa751d308819ff81c92ba`

The `anticloud/` overlay is a standalone copy of the anticloud_reference tree; the 16 checks run against it via `tools/run_bench.py`.
