# Ethics — FASHION_MNIST_PRIOR_DOCS

**Project:** FASHION_MNIST_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/zalandoresearch/fashion-mnist  
**Pinned commit:** `b2617bb6d3ffa2e429640350f613e3291e10b141`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `65a821e98e0b417f7c66a833abce2a89310fcb426d214cb67942003251dbc6bf`  
**Date:** October 2026

## Position

FASHION_MNIST_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
