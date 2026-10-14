# Educators — CCXT

**Project:** CCXT  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/ccxt/ccxt  
**Pinned commit:** `99c0c79d8a95d4cc813f74bf2cb73ecfc147766d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3fb4b06f4a1efa8b20e00c14a8148ef6b7b590045197d5e16623bff4ef7ef677`  
**Date:** October 2026

## Teaching with CCXT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3fb4b06f4a1efa8b20e00c14a8148ef6b7b590045197d5e16623bff4ef7ef677` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
