---
date: 2026-10-12
lens: Credit institutions
headline: Digital euro settles in a new central bank account, so plan liquidity for a 24/7 DESP cash account now
source: ECB, FAQs on the digital euro pilot; T2-CG item 5.4 (11 June 2026); T2 change request T2-0150 "T2 adaptations due to digital euro"; T2-CG item 5.3 DESP DCA messaging and connectivity (18 Feb 2026)
---

Digital euro payments will not settle in your normal TARGET account. Each PSP will use a dedicated cash account in central bank money, called a DESP DCA, inside the Eurosystem's new Digital Euro Service Platform. Your treasury team will move liquidity between T2 and that account, and the account must cover payments around the clock, every day of the year.

The plumbing is already being built. The ECB has scheduled the T2 changes for the June 2027 release, in time for a pilot that it says starts in September 2027. The draft message set uses ISO 20022 over a REST interface, close to what TIPS uses today, with status queries available 24/7 and floor and ceiling alerts if you subscribe. But during the pilot, funding and defunding the DESP DCA will be manual. No automatic top-ups are planned yet. Banks that act as co-managers for smaller PSPs have already told the ECB the setup does not meet their liquidity needs, and better credit-limit tools are only requested for after the pilot.

The takeaway: treat the digital euro as a new 24/7 liquidity position, not just a new product. Map who funds the account at night and at weekends, set your own buffers and alert thresholds, and check your ISO 20022 tooling against the TIPS-style messages. If you plan to settle for other PSPs, raise your co-management needs through your national central bank now. These are pilot and project specifications, not final rules, and the digital euro still depends on the EU regulation being adopted.
