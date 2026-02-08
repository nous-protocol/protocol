# NOUS Protocol

**NOUS** is a sovereign decentralized inference network on Avalanche: a protocol for coordinating, verifying, and paying for machine-learning inference across independent operators.

This repository is the canonical home for the **whitepaper**, **protocol specs**, and (eventually) **reference implementations**.

> Train anywhere. Serve on NOUS.

---

## What NOUS is

- **Inference-first**: models are trained off-network and deployed to NOUS for serving.
- **Verification-aware**: a layered **Proof-of-Inference (PoI)** design targets economic fraud-proofing (not absolute correctness claims).
- **Service economics**: fees flow into a **protocol treasury** to pay node operators for active work and fund deployer maintenance grants (not passive revenue rights).

---

## Repository layout

- `whitepaper/` — Latest whitepapers (FULL + spec)
- `spec/` — Normative protocol specs (drafts become binding over time)
- `docs/` — Investor memo, design notes, and supporting documents
- `src/` — Reference implementations (placeholder for now)

---

## Current status

This repo is **documentation-first** while the protocol is being finalized.

**Near-term outputs:**
1) Finalize v3.3 whitepaper wording and terminology
2) Convert key sections into normative specs (PoI, routing/tiers, treasury flows)
3) Publish a benchmark harness plan + testnet acceptance criteria

---

## Read first

- **Whitepaper (FULL):** `whitepaper/NOUS_Whitepaper_v3.3_FULL.md`
- **Whitepaper (SPEC / diligence):** `whitepaper/NOUS_Whitepaper_v3.3_SPEC.md`
- **Investor memo:** `docs/NOUS_Investor_Memo_v3.3.md`

---

## Contributing

We welcome issues and PRs, but we want to keep changes reviewable and threat-model grounded.

**Before a PR:**
- Open a **[proposal]** issue describing motivation, design, and threat model.
- If you add performance claims, include a benchmark harness plan.
- If you add slashing/verification logic, include adversary assumptions and failure recovery.

See: `CONTRIBUTING.md`

---

## Security

Please report vulnerabilities privately.  
See: `SECURITY.md`

---

## License

MIT — see `LICENSE`.

---

## Disclaimer

This repository is for research and development purposes. It does not constitute an offer to sell or a solicitation to buy any tokens or securities. Regulatory classification may vary by jurisdiction.
