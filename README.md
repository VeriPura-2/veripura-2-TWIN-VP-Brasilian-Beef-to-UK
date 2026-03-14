VeriPura × TWIN — Brazilian Beef to UK
Interactive Compliance Model — Use Case 1
A single-page interactive model showing how VeriPura and TWIN transform the import compliance journey for frozen beef from Brazil to the UK. Built for presentation to UK government officials (APHA, DEFRA, HMRC, Border Force).

Deployment
This is a single-file GitHub Pages site. No build step, no dependencies, no server.
Push index.html to the root of this repository
In repository Settings → Pages, set source to main branch, / (root)
Site will be live at https://veripura-2.github.io/TWIN-VP-Brasilian-Beef-to-UK/

Updating Content
All content lives in the CONFIG block at the top of the <script> section inside index.html. You can edit it directly in GitHub's web editor — no local setup needed.
To update a stage (documents, VeriPura actions, TWIN notarisation, before/after text): find the relevant entry in CONFIG.stages[].
To update swimlane tasks: find the relevant entry in CONFIG.swimlanes[].
To update statistics or technology descriptions: find CONFIG.stats[] and CONFIG.technology.
Do not edit below the CONFIG block unless changing layout or design.

Sections
#
Section
Description
01
The Import Journey
10 clickable stages with document lists, VeriPura actions and TWIN notarisation
02
Party Responsibilities
Swimlane view — Signal, VeriPura, TWIN across all 10 stages
03
Dashboard
Live consignment simulation with two-act compliance drama
04
Technology
VeriPura agent architecture and TWIN/IOTA feature overview


Dashboard Demo
The dashboard simulates consignment BR-2026-0341 (18,500 kg frozen beef, Santos → Tilbury).
Run demo — auto-plays all 10 stages
Step forward / back — manual control
Pause — hold at any stage for discussion
Speed selector — Normal / Fast / Presenter
Click any stage bubble to jump directly
Act 1 (Stage 4): VeriPura catches an EHC template failure before loading. Resolved 31 hours before departure — no border impact.
Act 2 (Stage 8): A reefer temperature spike at Tilbury BCP triggers a Port Health Authority hold. TWIN's notarised cold-chain log resolves it in 47 minutes without lab sampling.

v0.3 — March 2026 — VeriPura × TWIN

