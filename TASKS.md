# Tasks

## Active
*Boaz's own tasks*


- [x] **[Internal] Create Claude Presentation for Team** - Prepare and present a presentation on Claude to the team | done: 2026-03-29

- [ ] **[Marketing] Redesign Homepage** - Redesign the homepage based on new AI messaging | added: 2026-03-25

- [ ] **[Dinvest] Design Mockup for Tenant App (imofix replacement)** - Design a mockup for the Tenant App to replace imofix | Project: Dinvest Tenant App design (imofix alternative)

- [ ] **[Power BI] Fix Owner Dashboard** - Fix Power BI owner dashboard based on Yariv's comments | due: 2026-03-25
  - ✅ KPI design spec completed + Linear ticket created for Idan: 2026-03-25
  - ⏳ Awaiting Idan implementation


*Zoho Desk Project*

- [ ] **[Zoho] Internal Communication Guidance** - Send guidance: use Message feature in Zoho Desk + tag user for internal notes; change Owner to reassign tickets | raised by: Albert

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
- [ ] **[Zoho] Ticket Routing Rules** → **Philipp → Olivier → Idan** - Philipp sends current routing rules to Olivier; Olivier reviews and forwards to Idan; Idan implements | raised by: Philipp
- [x] **[Zoho] Phone Ticket Data Quality** → **Olivier** - Already addressed via Phone AI Processing training (same action) | raised by: Miriam | done: 2026-03-29
  - ✅ Training completed earlier; Call-to-Ticket category field mapping also fixed in Portal Release 2026-03-29

## Waiting On

- [ ] **[Dinvest] Facility Management Software Research** - Evaluating FM software solutions for a joint venture in Swiss real estate. Reached out to Mr. Hoffmann at Vebego for recommendations — referred by David Wolfensberger (W&W Immo Informatik). | since: 2026-03-25
  - 📧 Outreach email sent to Vebego contact (Mr. Hoffmann) — awaiting reply
  - 🔗 Referral: David Wolfensberger, W&W Immo Informatik
  - 🎯 Goal: identify proven FM platforms suited to Swiss property management market
  - ✅ Demo done: **ImmoTrack**
  - ⏳ Awaiting demo: **Cedris** (Andeo AG)

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
