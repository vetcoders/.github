# Security Policy

[vetcoders](https://github.com/vetcoders) ships software that runs in real codebases and real clinics. We treat security reports the way a clinic treats critical incidents — fast, quiet, structured.

---

## Reporting a vulnerability

**Please do not open a public GitHub issue for security problems.**

Send a private report to:

- **vetcoders-specific:** [hello@vetcoders.io](mailto:hello@vetcoders.io)
- **Group / mother org:** [contact@libraxis.ai](mailto:contact@libraxis.ai)

### What to include

- The repo or product affected.
- A clear description of the issue and its impact.
- Reproduction steps (or a proof-of-concept).
- Suggested mitigation, if you have one.
- Whether you would like credit and how (handle / name).

### What to expect

- **Acknowledgement within 72 hours.** Probably faster — we are awake at unusual times.
- **Triage and severity scoring within 7 days.**
- **Remediation timeline** depending on severity:
  - Critical (data exposure, auth bypass, RCE): days, with private patch first.
  - High: 1–2 weeks.
  - Medium: scheduled in next minor release.
  - Low: tracked, fixed when the area is touched.
- **Credit.** If you want it, we will list you in the affected repo's `SECURITY.md` or release notes once the fix is public.

---

## Scope

In scope:

- All public repos under [`github.com/vetcoders`](https://github.com/vetcoders) — unless explicitly archived
- `vetcoders.io` — public org site
- Production endpoints we operate (e.g. `vistavet.app`)

Sister organization [**Loctree**](https://github.com/Loctree) and mother org [**LibraxisAI**](https://github.com/LibraxisAI) have their own security policies — report to them directly for issues inside their orgs.

Out of scope:

- Third-party services we use (Cloudflare, Hugging Face, etc.) — report to them
- Social engineering of team members
- DoS / volumetric attacks — use responsible testing
- Findings already reported — we will tell you if we know

---

## Disclosure

We practise **coordinated disclosure**.

1. You report privately.
2. We acknowledge, triage, fix.
3. We coordinate the public disclosure window with you (default: 90 days from report, shorter if patched faster).
4. After patch + window, we publish: advisory in the repo, CVE if relevant, release notes credit if you wanted it.

If a fix takes longer than the disclosure window, we will tell you why. We will not silently sit on a report.

---

## What is not a security issue

- Missing security headers on a public landing page — please open an issue or PR; we triage these in batches.
- "Anyone can read public information" — that is the design.
- "I disagree with the architecture" — please open a discussion, not a security report.

---

## A note on licensing

Repos in this org use different licenses (BSL 1.1, MIT, Apache 2.0, or commercial for Vista). Licensing terms do not affect security reporting — report freely, regardless of how the code is licensed.

---

## Hall of fame

If you helped find and fix something here, your handle goes in this section by request. *(Empty for now — please be the first.)*

---

<sub>© 2024–2026 LibraxisAI · vetcoders</sub>
