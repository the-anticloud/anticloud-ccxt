# Ethics — CCXT

**Project:** CCXT  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/ccxt/ccxt  
**Pinned commit:** `99c0c79d8a95d4cc813f74bf2cb73ecfc147766d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3fb4b06f4a1efa8b20e00c14a8148ef6b7b590045197d5e16623bff4ef7ef677`  
**Date:** October 2026

## Position

CCXT is packaged for offline deployment with a verifiable audit trail. The
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
