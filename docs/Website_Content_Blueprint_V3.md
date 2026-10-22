# BioVault Saudi — Website V3 (October 22, 2026)

## Scope of this revision
This revision responds to two owner corrections: (1) EndlessJob is **completed**, not under development, according to the company owner; this fact is owner-confirmed and not an independent external audit. (2) The former repeated SAR-500 value-split slider has been replaced with a four-event value-state story showing BalanceChain as an **additional layer beside the authoritative bank ledger**.

## BalanceChain visitor journey: source composition vs bank balances

The financial case uses **only synthetic data**, not a live bank, actual integration, regulatory clearance, or independently certified product function.

| Event | Bank ledger state | Represented value-source composition (requires event and explicit selection evidence) |
|---|---|---|
| 01 Two inbound funds | Business A receives SAR 3,000 + 2,000 = SAR 5,000 | Enrollment anchors for contract revenue SAR 3,000 and program funding SAR 2,000 |
| 02 Payment A → B | SAR 2,500 transferred; A=2,500, B=2,500 | Example recorded selection: B holds SAR 500 revenue + SAR 2,000 funding; A retains SAR 2,500 revenue |
| 03 Payment B → C | SAR 1,000 transferred; A=2,500, B=1,500, C=1,000 | Example recorded selection: C holds SAR 200 revenue + SAR 800 funding; B holds SAR 300 revenue + SAR 1,200 funding |
| 04 C → nonparticipant | SAR 600 leaves monitored perimeter; A=2,500, B=1,500, C=400 | Last observed exit SAR 100 revenue + SAR 500 funding; C retains SAR 100 revenue + SAR 300 funding; no claims beyond perimeter |

Conservation: SAR 5,000 = current participating accounts SAR 4,400 + recorded exit SAR 600. 

### Evidentiary distinction
- Monetary postings and settlement remain authoritative in existing systems. BalanceChain models additional value-state and lineage **within participating/observed systems**.
- Source selection is explicitly fictional in this educational case. If selection is not recorded in reality, a declared shadow rule (FIFO/pro-rata/etc.) produces **modeled attribution**, not discovered historical facts.
- Lineage anchors reflect first supported observation, not necessarily original issuance or source of all money.
- Crossing an unconnected institutional boundary ends visibility. Retain last-known exit state; never imply downstream tracking.
- Product design is not evidence of production readiness, audited performance, regulatory approval or customer deployment.

## EndlessJob
All 'in development' labels removed from the site's English and Arabic public-facing copy; now shown as 'Completed project' / 'مشروع مكتمل'. Individual workflow descriptions remain explanatory, not claimed independently verified.

## Bilingual and visual behavior
- Introductory corporate site remains same visual identity: approved emerald/silver logo crop, dark navy, Riyadh artwork, network/motif language.
- Four journey step selectors, ledger-vs-value overlay switch, per-account source-composition bars, step-wise evidence inspector, boundary alert, conservation equation, previous/next controls.
- RTL/LTR support, accessible native buttons, responsive layout, no network calls or data tracking.

## Approval and publishing gates
- Replace temporary logo image crop with approved transparent/vector original when source bytes accessible.
- Confirm EndlessJob final demo and feature list independently before detailing individual flows; do not revert overall completion status without owner instruction.
- Verify product technical assertions and allowed case studies; confirm Saudi legal identity and marketing approvals before public publishing.
- Domain, hosting and GitHub intentionally unchanged/deferred.

## Testing
Headless Chromium tested desktop 1440 px + mobile 390 px, English + Arabic toggling, transition steps, balance conservation, compare overlay visibility, and no JS runtime errors at the time of revision.