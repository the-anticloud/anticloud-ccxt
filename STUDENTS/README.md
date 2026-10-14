# Students — CCXT

**Project:** CCXT  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/ccxt/ccxt  
**Pinned commit:** `99c0c79d8a95d4cc813f74bf2cb73ecfc147766d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3fb4b06f4a1efa8b20e00c14a8148ef6b7b590045197d5e16623bff4ef7ef677`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `99c0c79d8a95d4cc813f74bf2cb73ecfc147766d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3fb4b06f4a1efa8b20e00c14a8148ef6b7b590045197d5e16623bff4ef7ef677`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
