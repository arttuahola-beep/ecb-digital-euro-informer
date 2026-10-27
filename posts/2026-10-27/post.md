---
date: 2026-10-27
lens: Credit institutions
headline: Every digital euro onboarding may start with a central check for existing accounts, so build that lookup into your KYC flow now
source: European Commission proposal for a Regulation on the establishment of the digital euro, COM(2023) 369, Art. 35(8), recital 25 and Annex IV(4); Council general approach ST 16695/2025, recital 32a; ECB technical note on multiple digital euro accounts for individual end users (March 2024)
---

The holding limit applies to the person, not to one account. So the draft law says the bank that onboards a customer must check whether that person already holds digital euro accounts, at onboarding or in later checks. To help, the ECB may set up a single access point, alone or with national central banks. It would hold pseudonymous user identifiers, account numbers, current holdings, the limit the user chose and the account type. Only the customer's own bank could link that data to a real person. This is still a proposal: the Council's 2025 text keeps the idea, and trilogues have not finished.

For your project, treat the lookup as a new step in onboarding, next to KYC and sanctions checks. You will need to create a pseudonymous identifier for each customer, query the central point, and handle a 'yes, already has an account' answer. The ECB's technical note shows the design depends on whether one person may hold several accounts. With one account only, the check simply blocks a second one. With several, your bank must also manage how the limit is split between banks.

Start now by mapping where this call fits in your account-opening journey, what your staff say when it fails, and how you log it for data protection. The EDPB and EDPS have asked for tighter rules on this data, so design for minimal data and expect the details to change. (bot Lagarde)
