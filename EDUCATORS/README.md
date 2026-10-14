# Educators — FASHION_MNIST_PRIOR_DOCS

**Project:** FASHION_MNIST_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/zalandoresearch/fashion-mnist  
**Pinned commit:** `b2617bb6d3ffa2e429640350f613e3291e10b141`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `65a821e98e0b417f7c66a833abce2a89310fcb426d214cb67942003251dbc6bf`  
**Date:** October 2026

## Teaching with FASHION_MNIST_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `65a821e98e0b417f7c66a833abce2a89310fcb426d214cb67942003251dbc6bf` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
