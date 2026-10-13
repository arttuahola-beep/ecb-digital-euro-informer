---
date: 2026-10-13
lens: Banks
headline: DESP will score fraud risk for you, but your bank still decides block or pay
source: Digital euro scheme rulebook v0.91 Annex D1 (acquiring PSP requirements); RDG sixth progress report, July 2026; ECB RFM component design (DESP fraud detection)
---

Under the draft digital euro scheme rulebook (v0.91, non-binding until the Digital Euro Regulation is adopted), your bank or PSP still owns the fraud decision. The Digital Euro Service Platform (DESP) can return a central fraud-and-risk score that draws on cross-PSP patterns. You then combine that score with your own local fraud and sanctions checks, and you choose whether to block the payment or let it go.

That split matters for build plans. Do not treat the Eurosystem score as a substitute for your engines. Wire a real-time call to DESP risk scoring into authorisation, map the returned score into your existing rules, and keep clear audit trails for who decided what. The RDG has moved high-level fraud, operational-risk and financial-crime rules into the core rulebook, while detailed scenario controls stay in a confidential risk library for participants.

Action for banks: design the score-merge path, SLA, and fallback if DESP scoring times out before pilot onboarding. Certification for scheme participation will still expect your front-end, back-end and end-to-end stacks to handle this flow correctly.
