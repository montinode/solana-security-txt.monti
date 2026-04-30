# John Charles Monti – Ownership / Control Verification Repository  
**metaTag:** `MONTIAI-JOHNCHARLESMONTI-VERIFICATION-BUNDLE-V1`

Welcome! This repo collects **all artefacts, logs, and proof objects** used to verify the ownership or control claims made by **John Charles Monti** across wallets, smart contracts, domains, AWS resources, and related infrastructure.

## Repository Layout

| Path / File | Purpose |
|---|---|
| `CLAIM_REGISTER.md` | Master list of every asset identifier and its verification status |
| `verification-log.md` | Step-by-step audit trail of evidence collected |
| `OWNER.md` | Formal statement of claims and rules for verification |
| `ownership.json` | Machine-readable snapshot of all claims |
| `.well-known/ownership.json` | Publicly served verification file (to be hosted at domain root) |
| `wallet-proof-log.md` | Signed wallet message collection and validation results |
| `contracts-register.json` | Source-verification + admin-role checklist for EVM contracts |
| `ownership-proof.txt` | Short plaintext notice of the verification process |
| `docs/` | Optional rendered documentation or reports |
| `.github/` | Issue templates, workflows, and security policy (see `SECURITY.md`) |

## How to Contribute Evidence

1. Fork this repo or open a Pull Request.  
2. Add artefacts (screenshots, JSON, logs) in an **evidence/** folder or reference off-chain URLs.  
3. Update the relevant tables in `CLAIM_REGISTER.md` and `verification-log.md`.  
4. Sign your commit with **PGP** or **Sigstore** if possible.  

_All contributions are publicly archived. Redact private keys or secrets before submission._

## Live Proof Endpoints

* **Well-Known URI:** `https://johncharlesmonti.com/.well-known/ownership.json` (to be deployed)  
* **DNS TXT Record:** `montiai-verification=...` (pending)  
* **Etherscan Contract Page:** `[INSERT_LINK_AFTER_VERIFICATION]`  

## Contact

For questions or responsible disclosure of security issues, please see **`SECURITY.md`**.
