# Design direction — Bank Reconciliation Dashboard

## Approach 1
**Theme Name:** Ledger Paper / Warm Audit
**Very Brief Intro:** A tactile finance workspace inspired by annotated audit folders, warm paper, graphite, and muted teal. It feels meticulous, human, and calm under scrutiny.
**Probability:** 0.07

## Approach 2
**Theme Name:** Midnight Treasury
**Very Brief Intro:** A dark institutional command center with deep ink surfaces, brass signals, and disciplined data density. It frames reconciliation as high-stakes treasury control.
**Probability:** 0.03

## Approach 3
**Theme Name:** Signal & Settlement
**Very Brief Intro:** A contemporary editorial dashboard using parchment-white surfaces, ink-blue structure, and a sharp coral exception signal. It makes the gap between bank and ledger legible at a glance.
**Probability:** 0.06

## Chosen Approach: Signal & Settlement

### Design Movement
Swiss editorial information design blended with modern financial operations tooling: high contrast, deliberate alignment, and visible hierarchy without sterile enterprise grey.

### Core Principles
1. **Exceptions are signals, not noise.** Coral is reserved for unresolved value and risk; teal indicates verified movement.
2. **Evidence stays close to the number.** Every KPI is paired with a source label, period, or action path.
3. **Editorial rhythm over dashboard sameness.** A rail, asymmetric hero, and wide evidence table create a considered reading flow.
4. **Calm density.** The page can hold detail without feeling cramped through generous line height and grouped surfaces.

### Color Philosophy
The base is a warm mineral paper (#F5F1E9) rather than cold white, creating an audit-room feel. Ink navy (#172B3A) anchors trust and legibility. Oxide coral (#D96B4A) is ownable and used only for exceptions, while settlement teal (#168C86) marks matched or reconciled movement. A pale citron (#E5D48B) supports timing-difference cautions without competing with the primary risk signal.

### Layout Paradigm
A persistent left rail establishes the workspace; the main canvas opens with an asymmetrical hero where the reconciliation status and balance equation occupy different visual weights. The lower half alternates between a compact KPI band, a balance bridge, and a wide evidence ledger rather than repeating equal cards.

### Signature Elements
- A vertical **evidence rail** with numbered review stages.
- A **balance bridge** rendered as a stepped equation with source labels.
- Coral **exception pins** and teal **verified ticks** used as small, consistent signal marks.

### Interaction Philosophy
Interactions should feel like marking evidence: filters stay visible, selected rows gain a paper-like lift, and detail drawers expose original source fields rather than hiding them behind generic modals. Actions are reversible and always state whether they change a view or a record.

### Animation
Use 180–240ms ease-out transitions for rail selection, KPI hover, table row focus, and drawer entry. On first load, stagger hero eyebrow, title, status chip, and KPI band by 50ms. Avoid looping motion. Respect reduced-motion preferences.

### Typography System
Use **IBM Plex Sans Arabic** for Arabic labels and body, paired with **Space Grotesk** for Latin numerals and English metadata. Headlines are 700 with tight tracking; body is 400/500 with comfortable line height. Financial amounts use tabular numerals and a slightly heavier weight.

### Brand Essence
A reconciliation cockpit for finance teams who need to turn bank-versus-ledger gaps into documented actions. **Precise, candid, composed.**

### Brand Voice
Headlines are direct and evidence-led; CTAs name the next review action; microcopy admits uncertainty instead of overstating confidence.

Example lines:
- “The gap is visible. The next action is documented.”
- “Review 461 bank-side exceptions before posting adjustments.”

### Wordmark & Logo
A compact mark made of two offset ledger strokes that converge into a single settlement line, paired with a custom uppercase wordmark: **SETTLE / SIGNAL**. The mark should appear as a simple geometric icon, never as a default text logo.

### Signature Brand Color
**Oxide Coral #D96B4A** — the unmistakable color of unresolved evidence in this workspace.

## Style Decisions
- Keep the dashboard light, warm, and editorial; do not switch to generic dark SaaS styling.
- Use coral only for exceptions and action-needed states.
- Preserve the distinction between “initial match” and “final match”; never visually imply that provisional matches are fully cleared.
- The desktop left rail is the review spine: all primary workspace sections carry numbered stages 01–06.
- The hero gives evidence priority to closing balance, unresolved net, and next action; decorative imagery stays subordinate.
- SETTLE / SETTLEMENT is the persistent product identity; Riyad Bank remains contextual source metadata.
- Coral is reserved for unresolved evidence and action-needed states; teal is reserved for linked or verified movement.
