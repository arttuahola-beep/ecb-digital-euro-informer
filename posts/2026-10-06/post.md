---
date: 2026-10-06
lens: Payment service providers
headline: Offline digital euro puts AML checks and device funding in your back end, so plan that build now
source: ECB, Digital euro scheme rulebook v0.91 (draft, non-binding, published July 2026); ECB presentation "Offline digital euro" (April 2026); ECB FAQs on the digital euro pilot
---

Offline digital euro payments go straight from one device to another, with no PSP in the middle. That doesn't mean PSPs are out of the loop. The ECB's design puts an "offline distribution component" in each intermediary's own back end. It funds and defunds users' devices from their accounts and manages each device's link to its PSP. It also applies the limits and policies. Anti-money laundering checks happen at funding and defunding, much like a cash withdrawal or deposit today, because PSPs won't see the offline payments themselves.

The draft rulebook (v0.91) also sets front-end rules. Users must be able to pick online or offline as their default mode. Before authentication, the app must show which mode a payment uses and, where relevant, let the payer switch. In the pilot, PSPs that build offline payments into their own app must use an ECB SDK, which handles the phone's secure element.

Takeaway: treat offline as a back-end and compliance project, not just a wallet feature. Map how funding moves money out of customer accounts, where your AML monitoring will sit, and how you'll handle lost or replaced devices. Keep in mind that these are draft rules, not adopted law. The rulebook says a participation model specific to offline will come in a later version, and the final text depends on the Digital Euro Regulation. The pilot, set to start in the second half of 2027, will test offline person-to-person payments over NFC.
