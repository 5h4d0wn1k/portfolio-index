# ETHICS.md — Ethical Use & Responsible Disclosure

**5h4d0wn1k — Open-Source Offensive & Defensive Security Portfolio**

This document is the ethical foundation of every repository in this portfolio. It is not
legalese for its own sake — it is the answer to the question "is this responsible to build
and share?" The answer is **yes**, with the conditions below.

---

## 1. The moral test: intent, not tool

Security tools are dual-use. The same lever that cracks a password also audits one; the same
reconnaissance that maps an attack surface also maps a blast radius. Every major ethical and
faith tradition that addresses knowledge-sharing converges on the same axis: **harm and help
are judged by intent and use, not by the object itself.**

By this test, the entire portfolio is built for:
- **Education** — teaching *why* systems break, so the same knowledge defends them
- **Authorized testing** — your own systems, or systems you have written permission to assess
- **Defense** — detections, hardening, and incident response that protect people

It is *not* built to harm third parties, and nothing here works against them by default.

---

## 2. The target rule (non-negotiable)

> **Engage only systems, networks, and hardware you own — or that you hold explicit written
> authorization to test, with defined scope, duration, and limits.**

That single rule is the line between a security portfolio and a weapon catalogue. This
portfolio is the former. Unauthorized use may violate the **Computer Fraud and Abuse Act
(18 U.S.C. § 1030)**, the **Wiretap Act (18 U.S.C. § 2511)**, **EU Directive 2013/40/EU**,
and the equivalent cybercrime laws of your jurisdiction — and it is treated as such by the
author.

---

## 3. Built-in safety by default

- **Offline / simulation first.** Tools default to dry-run, deterministic, local fixtures.
- **Confirmation gates.** Actions that emit radio, touch real networks, or affect real
  systems require an explicit flag **and** membership of a lab allowlist.
- **Hard-gated suites.** Social-engineering and post-exploitation tooling is consent-locked
  with no network-send code paths.
- **No auto-pwn buttons.** Nothing here aims at a live third-party target "out of the box."

These gates are features, not friction. Removing them voids the ethical (and legal) basis of
the tool.

---

## 4. Responsible disclosure

If you discover a real vulnerability with a real owner:
1. **Report privately** to the owner/vendor first.
2. Give a **reasonable disclosure window** to fix it.
3. **Publish only after remediation** — or after the owner acknowledges and declines.

Never weaponize a finding against a third party to make a point.

---

## 5. For educators, learners, and researchers

- **Learners:** use these tools against your own lab (like a spare router, VM, or this
  portfolio's own localhost fixtures). Real skills are built in a sandbox, not on strangers'
  networks.
- **Researchers:** publish responsibly, credit your sources, and keep working code pointed
  at your own infrastructure.
- **Educators:** the authorized-use framing is part of the curriculum — teach *scope* as a
  first-class technical skill, not an afterthought.

---

## 6. AS-IS and responsibility

All software is provided "AS IS", without warranty of any kind. The author assumes no
liability for misuse. **You are solely responsible for how you use these tools.** In this
portfolio the person pointing at the target is always the accountable one — and the rules
above exist so that remains a choice every user makes freely and legally.

---

*Questions about scope, authorization, or ethical use? Open an issue or contact the author
through the portfolio site. Stay in scope, stay legal.*