---
date: 2026-10-28
lens: Payment service providers
headline: Digital euro lets people pay each other by phone number, so build alias sign-up and lookup into your app now
source: ECB, Digital euro scheme rulebook v0.91 (draft), section 3.3.3 Alias, FUR.71–78; Annex D2, Back-end implementation specifications #2, Access management and alias lookup; Annex D1, Front-end implementation specifications #5, Common services, section 4.2
---

Every digital euro account gets a digital euro account number, the DEAN. Under the draft scheme rulebook (v0.91), users may also add an alias. Only one kind of alias is allowed: a mobile phone number. It links to exactly one DEAN. Only individual users can have one; business users cannot. Using an alias is voluntary for the user, but every scheme participant must support registering one.

This puts real work on your side. When a customer registers a number, you must validate it, for example with a one-time code, unless you have already checked that number for other purposes such as contact details. You must also let customers change the alias when their number changes and pass that change to the Eurosystem platform, DESP. When a customer pays a friend by phone number, or a shop takes payment by alias online, your back end asks DESP to resolve the alias. DESP returns the account number and the other side's PSP, so you can route the payment.

The takeaway: treat alias handling as a core build item, not an extra. Map how your app will register, validate, change and look up phone numbers. Reuse the numbers you have already verified where you can. Note these are draft rulebook rules that can still change, and the digital euro itself still needs the Regulation (COM(2023) 369) to be adopted. — Lagarde
