# Tasks

## Active
*Boaz's own tasks*


- [x] **[Internal] Create Claude Presentation for Team** - Prepare and present a presentation on Claude to the team | done: 2026-03-29

- [ ] **[Marketing] Redesign Homepage** - Redesign the homepage based on new AI messaging | added: 2026-03-25

- [ ] **[Dinvest] Reporting Walkthrough with Ruslan & David** - Demo meeting on Thursday 2026-04-09. Walk through Power BI + WW Portal live (screen share). | introduced by: Yariv | added: 2026-03-31
  - 📧 Ruslan Marakhovskii (David's accountant, scheduling contact)
  - 👤 David Gast (portfolio owner, based in NY)
  - 🎯 Demo current reports (1 month of data) + present upcoming developments & mockups
  - ⚠️ **Pre-meeting checklist (before Thursday):**
    - [ ] Verify David Gast has login access to Power BI
    - [ ] Verify Ruslan has login access to Power BI
    - [ ] Verify David Gast has login access to WW Portal
    - [ ] Verify Ruslan has login access to WW Portal
    - [ ] Test screen share setup before the call

- [x] **[Dinvest] Design Mockup for Tenant App (imofix replacement)** - Working mockup + full product documentation built. Replaces Zoho checklists for move-outs and building onboarding. Live at: https://dinvest-portal.vercel.app | done: 2026-04-06

- [x] **[Dinvest] Open Linear Ticket for Idan — Tenant App** - Linear ticket opened with PRDs, Excel task lists, and all supporting files for the new checklist system (move-out + building onboarding) | done: 2026-04-06

- [ ] **[Dinvest] Open Linear Ticket for Idan — Migrate Owners Data from Zoho to Inhouse Hub** - Create Linear ticket for Idan to migrate all owner data from Zoho into the inhouse hub | added: 2026-04-06

- [ ] **[Dinvest Checklisten] Write Technical Spec — MandateOnboarding (Mandatsaufnahme)** - Design docs complete; write Technical Spec so Idan can start building the POC checklist tool for onboarding new property mandates | added: 2026-04-07

- [ ] **[Power BI] Fix Owner Dashboard** - Fix Power BI owner dashboard based on Yariv's comments | due: 2026-03-25
  - ✅ KPI design spec completed + Linear ticket created for Idan: 2026-03-25
  - ⏳ Awaiting Idan implementation


*Zoho Desk Project*

- [x] **[Zoho] Internal Communication Guidance** - Send guidance: use Message feature in Zoho Desk + tag user for internal notes; change Owner to reassign tickets | raised by: Albert | done: 2026-04-07

## Follow-Up
*Tasks assigned to others — Boaz monitors progress*

- [ ] **[Onboarding App] New Employee Onboarding** → **Onboarding App** - Monitor onboarding setup for new employees in the new onboarding app
  - 👤 **Ryan Gauci-Maistre** — Start: 2026-04-16
  - 👤 **Dominik Inguanta** — Start: 2026-05-01

- [x] **[Onboarding App] Include Direct Manager in Office 365 Admin Request** → **Onboarding App / Admir (IT)** - When the onboarding app sends a new Office 365 user request to Admir, also include the new employee's direct manager | done: 2026-03-29

- [x] **[Onboarding App] Job Title → Security Template Mapping** → **Onboarding App / Admir (IT)** - Add feature to map each job title to a Microsoft security template; when Admir receives a new employee request, the correct security template is shown automatically | done: 2026-03-29

- [x] **[Zoho] Holiday/Vacation Coverage** → **Idan** - Triage Agent & Call-to-Ticket vacation warning integration | done: 2026-03-29
- [x] **[Zoho] Phone Number Format** → **Idan** - Display phone numbers in Swiss format (+41 76 541 03 45) instead of raw format | raised by: Philipp | Linear ticket created: 2026-03-25 | done: 2026-03-30
- [x] **[Zoho] Ticket Creator Visibility** → **Idan** - Show actual ticket creator (Ali, Tobias, Triage Agent) instead of Idan; consider adding a new field | raised by: Olivier | Linear ticket created: 2026-03-25 | done: 2026-03-29
  - ✅ Deployed in Portal Release 2026-03-29: tickets now created on behalf of the original sender
- [ ] **[Power BI] Owner Dashboard KPI Fields** → **Idan** - Add 6 new Netto-based KPI fields + rename 2 existing ones + retire 6 old Brutto/Akonto cards | Linear ticket created: 2026-03-25
  - 🆕 New: Ist-Ertrag Netto /Monat & /Jahr, Leerstand Netto /Monat & /Jahr, Leerstandsquote %, Anzahl Leerstände
  - ✏️ Rename: current Netto/Monat → Potenzial Netto/Monat; Netto/Jahr → Potenzial Netto/Jahr
  - 🗑️ Remove: Akonto & Brutto cards (×3 monthly + ×3 yearly)
- [x] **[Zoho] Email Reply Thread** → **Idan** - Development task already planned; implement fix in email threading | raised by: Albert | done: 2026-03-30
- [ ] **[Dinvest] Move-Out Checklist Process** → **Olivier** - Walk through new checklist system (move-out + building onboarding) with Olivier when he's back. App is live at https://dinvest-portal.vercel.app | added: 2026-04-05

- [ ] **[Dinvest Checklisten] Build Mieterwechsel — Production** → **Idan** - Hand off TenantTurnover (Mieterwechsel) POC to Idan for production build. Requires: PostgreSQL backend, auth, role-based access, deploy to inhouse.dinvest.ag | POC: https://mieterwechsel-poc.vercel.app | added: 2026-04-07
  - ⚠️ Blocked until Miriam answers 5 open process questions (Phase 3 / Kaution scope) — email sent 2026-04-06

- [ ] **[Dinvest Checklisten] Build MandateOnboarding POC** → **Idan** - Hand off MandateOnboarding (Mandatsaufnahme) to Idan once Technical Spec is written | added: 2026-04-07
  - ⚠️ Blocked until Technical Spec is complete (Boaz's task)

- [ ] **[Zoho] Ticket Routing Rules** → **Philipp → Olivier → Idan** - Philipp sends current routing rules to Olivier; Olivier reviews and forwards to Idan; Idan implements | raised by: Philipp
- [x] **[Zoho] Phone Ticket Data Quality** → **Olivier** - Already addressed via Phone AI Processing training (same action) | raised by: Miriam | done: 2026-03-29
  - ✅ Training completed earlier; Call-to-Ticket category field mapping also fixed in Portal Release 2026-03-29

## Waiting On

- [ ] **[Dinvest Checklisten] Miriam — Open Process Questions (Mieterwechsel Phase 3 / Kaution)** - Waiting for Miriam (operations) to answer 5 open questions about Phase 3 / Kaution scope before Mieterwechsel task list can be fully finalized | email sent: 2026-04-06
  - ⏳ Unblock: Idan's production handoff for Mieterwechsel depends on this

- [ ] **[Dinvest] Facility Management Software Research** - Evaluating FM software solutions for a joint venture in Swiss real estate. | since: 2026-03-25
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

- [x] **[Zoho] Support Email Architecture (Reply-To Fix)** - Dedicated support@dinvest.ag mailbox connected to Zoho Desk, replacing info@dinvest.ag Reply-To that caused duplicate tickets via Triage Tool | raised by: Albert | done: 2026-03-30
  - ✅ Diagnosed root cause: replies going to info@dinvest.ag → Triage Tool creating duplicates instead of threading
  - ✅ Rejected per-agent email approach (would worsen the problem)
  - ✅ Idan approved dedicated support@dinvest.ag solution
  - ✅ Coordinated with Admir (BelCore IT / Shkumbin Zeqiri) — converted to shared mailbox with IMAP/SMTP after external forwarding & redirect were blocked by M365 policy
  - ✅ Zoho Desk configured: support@dinvest.ag connected as verified From Address via Microsoft Outlook OAuth
  - ✅ Forwarding tested & working — emails to support@dinvest.ag arrive as tickets in Zoho Desk

- [ ] **[Dinvest / nvc.ch] Insurance Integration** - Thomas forwarded to François Eisele (group project manager, coordinates with BAYO). Thomas on holiday until 2026-04-20. Next Advisory Board meeting (14 broker CEOs) end of April. Follow up with François or wait for consolidated response. | since: 2026-03-24 | Project: Dinvest - nvc.ch insurance integration
  - 📧 thomas.keller@nvc.ch | **New contact: François Eisele** (project manager, coordinating with BAYO)
  - 📞 +41 61 227 95 84 (Thomas, direct)
  - 🔑 BAYO = their system provider (API/integration docs requested)
  - ⏳ Thomas OOO until 2026-04-20 | Advisory Board end of April

## Someday

## Done

- [x] ~~**[Zoho] Phone AI Processing (Swiss German)**~~ - Both Ali and Tobias confirmed guidance received and understood | done: 2026-03-25
- [x] **[Linear] Write Ticket to Idan** - Linear ticket created for Zoho Desk UI fixes (phone format + ticket creator visibility) | done: 2026-03-25
- [x] **[Zoho] Team View for Philipp** - Created filtered view in Zoho Desk for Philipp's team | raised by: Philipp | done: 2026-03-25
  - 🔗 https://desk.zoho.com/agent/dinvestbewirtschaftung/support/tickets/list/stweg-offen?view=table
  - 📧 Email sent to Philipp
- [x] **[Zoho] Client Notifications** - Disable ALL automated emails to customers until system is stabilized | raised by: Albert | done: 2026-03-25
- [x] **[Zoho] Add Philipp Huber & Daniela Seitz to Zoho Project** - Implemented both users in Zoho | done: 2026-03-25
- [x] **[Zoho] Email Signature** - Configure signatures in Zoho Desk and send setup instructions to the team | raised by: Albert | done: 2026-03-25
- [x] **[Zoho] STWEG Owner Portal Welcome Template** - Update welcome letter template in Zoho with revised bullet point about document upload timing | requested by: Philipp | done: 2026-03-25
