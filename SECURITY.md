# Security Policy

Security is the entire point of DM NATIVE. We deeply appreciate the work of security researchers in keeping our users safe, and we are committed to working with the community through responsible disclosure.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, report them privately:

- 📧 **Email:** `security@dmnative.com`
- 🔐 Encrypt sensitive reports to our PGP key (published at [dmnative.com/security](https://dmnative.com)) where possible.

Please include, where you can:

1. A clear description of the vulnerability and its impact.
2. Steps to reproduce (proof-of-concept code, requests, or screenshots).
3. The affected component, version, or platform.
4. Any suggested remediation.

## What to Expect

| Stage | Target |
|---|---|
| **Acknowledgement** of your report | within **48 hours** |
| **Initial assessment** & severity triage | within **5 business days** |
| **Status updates** | at least every **7 days** until resolved |
| **Coordinated disclosure** | by mutual agreement, after a fix ships |

We will keep you informed throughout, credit you (with your consent) once a fix is released, and will not pursue legal action against researchers who act in good faith under this policy.

## Scope

In scope:

- The DM NATIVE mobile apps (iOS, Android) and web client.
- The DM NATIVE backend API and real-time infrastructure.
- The end-to-end encryption protocol and key-management design.

Examples of issues we especially care about:

- Breaks in end-to-end encryption, forward secrecy, or post-compromise security.
- Key-exchange / man-in-the-middle weaknesses, key extraction, or replay attacks.
- Authentication / session bypass and insecure direct object references (IDOR).
- Server-side access to plaintext or private key material.
- Metadata leakage that de-anonymizes anonymous-room participants.

## Safe Harbor

Activities conducted in a manner consistent with this policy will be considered authorized conduct, and we will not initiate legal action against you. If legal action is initiated by a third party against you for activities that complied with this policy, we will make this authorization known.

## Our Commitments

- We design for **zero-knowledge**: our servers handle ciphertext, not plaintext.
- We are commissioning an **independent third-party security audit** ahead of general availability and will publish the results.
- We will disclose material security incidents to affected users promptly and transparently.

Thank you for helping keep DM NATIVE and its users secure. 🛡️
