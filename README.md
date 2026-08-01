# Ataberk Yavuzer

**Smart Contract Auditor & Offensive Security Engineer** — 7+ years across Web3 and traditional security.

Pentesting (web · network · Active Directory) → blockchain security (Solidity · Move).
Ex-Principal Smart Contract Auditor @ Hacken · Ex-Lead Offensive Security Engineer @ Halborn.
I break things, then build tools so they break less.

`OSCP` · `OSWE` · `CRTP`

---

## Focus

- **Smart contract audits** — Solidity & Move; DeFi, protocols, bridges. Manual deep-dive, not just tooling.
- **Offensive security** — web, network & Active Directory; red-team mindset.
- **Security tooling** — AI-assisted automation and agentic workflows.

---

## Projects

**[gossipcat](https://github.com/gossipcat-ai/gossipcat-ai)** · `TypeScript` `MCP` `Multi-agent`
A multi-agent code-review orchestrator that filters LLM hallucinations. Every finding must cite a real
`file:line`; peer agents verify the citation against actual source — a mechanical check, not LLM-as-judge.
Verified findings and caught hallucinations become grounded reward signals that update per-agent
competency scores. In-context reinforcement learning at the prompt layer — no weights touched.

**[Gamebrew](https://github.com/ataberk-xyz/Gamebrew)** · `C#` `Unity 6` `MCP`
A self-hosted bridge that hands your running Unity game to an AI agent — walk the player, orbit a prop to
inspect it, capture the view, read live scene state, all over one loopback MCP port. No cloud, no SDK lock-in.

---

## Security advisories

Vulnerabilities I found and responsibly disclosed:

| Package | Severity | Advisory |
|---|---|---|
| [install-artifact-from-github](https://github.com/uhop/install-artifact-from-github/network/dependents?package_id=UGFja2FnZS0xMzIyODE2OTA1) | High (7.5) | [GHSA-88q3-gch3-5396](https://github.com/uhop/install-artifact-from-github/security/advisories/GHSA-88q3-gch3-5396) — install-time RCE (CWE-494) |
| [stream-json](https://github.com/uhop/stream-json/network/dependents?package_id=UGFja2FnZS0xNjE5NzY5Ng%3D%3D) | Moderate (6.2) | [GHSA-528h-pc64-c93x](https://github.com/uhop/stream-json/security/advisories/GHSA-528h-pc64-c93x) — event-loop DoS (CWE-407) |
| [node-re2](https://github.com/uhop/node-re2/network/dependents?package_id=UGFja2FnZS0xNDExNjMxNQ%3D%3D) | Moderate (6.2) | [CVE-2026-68499](https://nvd.nist.gov/vuln/detail/CVE-2026-68499) — infinite loop / memory DoS (CWE-835) |
| [node-re2](https://github.com/uhop/node-re2/network/dependents?package_id=UGFja2FnZS0xNDExNjMxNQ%3D%3D) | Moderate (5.7) | [CVE-2026-67550](https://nvd.nist.gov/vuln/detail/CVE-2026-67550) — OOB read / crash (CWE-125) |
| [node-re2](https://github.com/uhop/node-re2/network/dependents?package_id=UGFja2FnZS0xNDExNjMxNQ%3D%3D) | Moderate (6.2) | [GHSA-8hcv-x26h-mcgp](https://github.com/uhop/node-re2/security/advisories/GHSA-8hcv-x26h-mcgp) — process abort DoS (CWE-617) |
| Kentico CMS | Medium (5.4) | [CVE-2019-19493](https://nvd.nist.gov/vuln/detail/CVE-2019-19493) — stored XSS (CWE-434) |

---

## Skills

**Smart contracts** — Solidity · EVM · Move (Aptos, Sui, IOTA) · Foundry · DeFi security
**Offensive** — internal & external pentest · web app security · Active Directory (Kerberoasting, NTLM relaying, Pass-the-Hash)
**Reversing & vuln research** — n-day research · patch diffing · WinDbg · PoC development
**Build & AI** — Python · TypeScript · Node.js · multi-agent orchestration (MCP) · Claude Code · Cursor

---

[Blog](https://ataberk-xyz.github.io) · [LinkedIn](https://linkedin.com/in/ataberkyavuzer)
