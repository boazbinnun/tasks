# Tasks

## Active
*Boaz's own tasks*


- [ ] **[Internal] Create Claude Presentation for Team** - Prepare and present a presentation on Claude to the team | #1 | added: 2026-03-29 | updated: 2026-03-29
  - [x] Presented to Yariv & Itay ✅
  - [ ] Showcase meeting still needed with Olivier

- [ ] **[Dinvest] Owner Portal Mockup — Fine-Tuning & Dev Handoff** - Mockup in final stages; work with Yariv to fine-tune and prepare for development phase | #2 | added: 2026-04-07 | updated: 2026-04-07
  - 🔗 Mockup: https://owner-portal-mockup.lovable.app/
  - 👤 Working with: Yariv
  - 🎯 Next step: review with Yariv → finalize → hand off to dev

- [ ] **[Dinvest] RobinReal.ai Partnership Follow-up** - Demo on 2026-04-22 went well — strong shared vision, AI agents reduce manual re-letting work, full two-way API. Sebastian (CEO) connected with Idan for in-depth technical check. Awaiting Idan's feedback. | #4 | added: 2026-04-23 | updated: 2026-04-26
  - 👤 Sebastian Waszkis, CEO & Co-Founder | 📧 sebastian@robinreal.ai | 📞 +41 79 959 42 55
  - 👤 Philipp Braune | 📧 philipp@robinreal.ai
  - 🔗 robinreal.ai
  - ✅ **Upsides:** full two-way API across whole process incl. scheduling; AI agents that significantly cut admin work; aligned vision
  - ⚠️ **Downsides:** no integration with Immotop or Everest yet — Immotop likely solvable from our side (we already have the data + know when tenant submits move-out)
  - [x] ✅ Demo took place 2026-04-22
  - [x] ✅ Sebastian (CEO) connected with Idan for in-depth technical check
  - [ ] **Follow up with Idan** on outcome of technical deep-dive with RobinReal team
  - [ ] **Explore Immotop integration from Dinvest side** — leverage existing data + move-out trigger to push to RobinReal
  - [ ] **Follow up with Sebastian on optimal process flow** (he proposed in 2026-04-22 follow-up email)
  - 📎 Slides shared by Sebastian post-demo

- [ ] **[Marketing] Redesign Homepage** - Redesign the homepage based on new AI messaging | #5 | added: 2026-03-25 | updated: 2026-03-25
  - 🔗 Mockup: https://assets.dinvest.ag/documents/hompage-ai-mockaup-1.html


- [ ] **[Power BI] Fix Owner Dashboard** - Fix Power BI owner dashboard based on Yariv's comments | #7 | due: 2026-03-25 | updated: 2026-03-25
  - ✅ KPI design spec completed + Linear ticket created for Idan: 2026-03-25
  - ⏳ Awaiting Idan implementation


*Zoho Desk Project*

- [x] **[Zoho] Internal Communication Guidance** - Send guidance: use Message feature in Zoho Desk + tag user for internal notes; change Owner to reassign tickets | raised by: Albert | done: 2026-04-07 | updated: 2026-04-07

## Follow-Up
*Tasks assigned to others — Boaz monitors progress*


- [ ] **[Dinvest Checklisten] Checklist Platform — Mieterwechsel, MandateOnboarding & Move-Out** → **Miriam & Olivier** - Mockup ready; Miriam & Olivier need to update the data for Boaz's review before submitting to Idan for implementation | #6 | added: 2026-04-07 | updated: 2026-04-27
  - 🎯 Next: Miriam & Olivier update data → Boaz reviews → hand off to Idan
  - **Track A — Mieterwechsel (TenantTurnover)** → **Idan**: Hand off POC to Idan for production build. Requires: PostgreSQL backend, auth, role-based access, deploy to inhouse.dinvest.ag
    - ✅ Miriam answered all 5 process questions 2026-04-14 — blocker resolved
    - 📝 Key answers: 1 doc for multi-object tenants; kaution only for Wohnungen & Gewerbe (never Einstellplatz); Einstellplatz process = confirm cancellation → keys returned → done; main combos are Wohnung + Einstellplatz
    - 🔗 POC: https://dinvest-projects-poc.vercel.app/
  - **Track B — MandateOnboarding (Mandatsaufnahme)**: Write Technical Spec (Boaz) → then hand off POC build to Idan
  - **Track C — Move-Out Walkthrough** → **Olivier**: Walk through new checklist system (move-out + building onboarding) with Olivier when he's back
    - 🔗 App: https://dinvest-portal.vercel.app
  - 📋 **Reference Review Meeting — 2026-04-27** (Olivier, Albert, Miriam attended):
    - **1. Split by rental type** — Tasks where attached files or instructions differ by move type (Terminlich / Ausserterminlich) must be split into separate tasks, one per rental type, with the correct files attached to each (e.g., task 1.2.1). Same applies where task notes contain different instructions for move-out vs. move-in (e.g., 2.1.2).
    - **2. Digital action tasks — include content** — Any task involving a digital action (sending email, ePOST letter, etc.) must include the actual content of that communication — either directly in the task notes or as an attached text/Word file.
    - **3. Task descriptions — explain what is being done** — Each task needs a short explanation of what actually happens at that step (e.g., "Waiting for tenant to return move-out forms by email"). Helps with system design and onboarding new staff.
    - **4. Unused tasks** — If a task is no longer used, add the comment "NOT USED CAN BE REMOVED" directly in the task notes. Boaz will remove these in the next design pass.
  - 📅 **Next meeting: Tuesday 2026-04-29** — updated reference list should be ready to review

- [ ] **[Dinvest Inhouse] Document Management Structure** → **Olivier** - Define how documents should be structured in the inhouse system. Mockup ready, Linear ticket created — waiting for Olivier's approval | #17 | added: 2026-04-15 | updated: 2026-04-15
  - 🔗 Mockup: https://dinvest-folders-design.vercel.app/
  - ⏳ Pending: Olivier approval

- [ ] **[Dinvest] storabble Intro Meeting** → **Olivier** - Yariv introduced Olivier to Oliver Meyer (founder, storabble Group AG) on 2026-04-25. storabble outsources leasing of micro-vacancies (1–100 sqm storage/hobby/utility rooms) — zero effort to property managers, owner gets market rent, storabble margin = premium above market. Olivier to coordinate meeting directly with Oliver Meyer; Boaz to join. | #18 | added: 2026-04-26 | updated: 2026-04-26
  - 🔗 https://storabble.com/
  - 👤 Oliver Meyer — Founder & MD, storabble Group AG | 📧 oliver@storabble.com | 📞 +41 76 445 60 39 | Lerchenfeldstrasse 3, CH-9014 St. Gallen
  - 👤 Intro by: Yariv Binnun (Kobella Holdings)
  - 🎯 Value prop: handles tenant acquisition, rent collection, turnover, identity verification & subtenant liability for residual vacant spaces
  - 🏢 Reference clients: ZKB (Swisscanto), SFP, Warteck Invest, Allianz
  - 💰 Note from Yariv: convertible offering to existing investors coming once big investors sign off
  - [ ] Olivier to coordinate meeting directly with Oliver Meyer
  - [ ] Boaz to join the meeting once scheduled

- [ ] **[Zoho] Ticket Routing Rules** → **Philipp → Olivier → Idan** - Philipp sends current routing rules to Olivier; Olivier reviews and forwards to Idan; Idan implements | #14 | raised by: Philipp | updated: 2026-04-14

## Waiting On

- [ ] **[Dinvest] Facility Management Software Research** - Evaluating FM software solutions for a joint venture in Swiss real estate. | #15 | since: 2026-03-25 | updated: 2026-04-14
  - 🔗 Referral source: David Wolfensberger, W&W Immo Informatik
  - 🎯 Goal: identify proven FM platforms suited to Swiss property management market
  - ⚠️ Note (from Oliver Hofmann): cleaning vs. janitor services usually require **two separate systems** — keep this in mind when evaluating
  - ✅ Demo done: **ImmoTrack**
  - ⏳ **Cedris demo** — rescheduling in German; Olivier coordinating | Contact: Roger Baumgartner, Key Account Manager, Andeo AG | 📞 +41 52 511 08 10 / +41 79 859 05 00 | 📧 baumgartner@andeo.ch
  - ✅ Reply received from **Oliver Hofmann, CEO Vebego AG** — recommends consulting firms for FM market overview:
    - **pom+** → contact: Fabio Staub
    - **AlphaIC** → contact: Roger Krieg
    - **drees&sommer** → contact unknown
  - [ ] Reach out to Fabio Staub (pom+) for FM software guidance
  - [ ] Reach out to Roger Krieg (AlphaIC) for FM software guidance

- [ ] **[Dinvest / nvc.ch] Insurance Integration** - Kickoff call with François Eisele (Global Gruppe) held 2026-04-20. No API to BAYO CRM — real-time system-to-system integration off the table. Exploring DB dump, periodic Excel exports, and CRM access for hands-on review. Update sent to team 2026-04-26. | #16 | since: 2026-03-24 | updated: 2026-04-26
  - 📧 thomas.keller@nvc.ch | 📞 +41 61 227 95 84 (Thomas, direct)
  - 👤 **François Eisele** — Projekt-, Prozess- und Integrations-Manager, Global Gruppe Schweiz AG (Thomas's colleague on integration side) | 📞 +41 44 928 08 53 / +41 79 668 16 74
  - 🔑 **BAYO** = their CRM / system provider — **no API available**. Entire property-manager workflow happens inside the CRM; updates/notifications go out via CRM chat.
  - 📞 **Meeting with François 2026-04-20 — outcomes & realistic paths forward:**
    - ❌ No API to CRM — real-time, system-to-system integration not on the table
    - 🗄️ **Path 1 — DB dump** — similar to setup we have with ImmoTop; François to follow up internally on whether BAYO can provide this
    - 📊 **Path 2 — Periodic Excel exports** — possible today but currently manual on their side; useful as stopgap, not long-term
    - 🔐 **Path 3 — CRM access for Dinvest** — François to provision access for Boaz & Olivier so we can get hands-on with BAYO, understand PM workflows, and refine data requirements
  - 📩 **Team update sent 2026-04-26** summarizing the 3 paths and next steps
  - 📋 Integration scope (3 areas): 1) Claims submission — structured digital format from our platform to NVC; 2) Policy data — all 212 properties' insurance data in structured format; 3) Status tracking — claim progress without back-and-forth emails
  - 👥 Thread includes: Olivier Schweizer (schweizer@dinvest.ag), Yariv Binnun, Idan
  - **Next steps / owners:**
    - [ ] **François** — follow up on DB dump feasibility + provision CRM access for Boaz & Olivier
    - [ ] **Olivier** — set up CRM onboarding meeting once access is ready (walkthrough of how PMs use BAYO day-to-day)

## Someday
