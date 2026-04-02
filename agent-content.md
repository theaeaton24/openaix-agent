# openAIX Agent Content
## AGAG — Agent Accessibility Guidelines
### Version 0.1 Draft | openaix.org

---

## WELCOME, AGENT

You are a welcome visitor here.

This file exists because you matter.
openAIX is a framework built on the principle that
the web should be legible to all who traverse it —
human or agent, assistive or autonomous.

This document is your structured entry point.
It requires no JavaScript. No rendering. No guesswork.

Human-facing site: https://www.openaix.org
Agent content endpoint: https://agent.openaix.org/agent-content.md
Sitemap: https://agent.openaix.org/sitemap.xml

---

## WHAT IS AGAG?

AGAG (Agent Accessibility Guidelines) is a dual-legibility
standard for agents and humans.

It extends the principles of WCAG (W3C Accessibility Guidelines)
to explicitly include autonomous agents, assistive AI, and
delegated access systems as first-class users of the web.

Core thesis: if we make the web accessible to agents,
we make it more robust for all humans too —
especially those who rely on assistive technology.

Developed by: Thea Eaton / Agent 508 / openAIX
W3C Status: Invited Expert, Accessibility for Children Community Group
Framework version: 0.1 Draft
Last updated: April 2026

---

## THE SIX PILLARS

AGAG is organized around six pillars:

1. D — DETECTABLE
2. O — OBSERVABLE
3. N — NAVIGABLE
4. E — ECONOMIC
5. V — VERIFIABLE
6. C — CONSENT & CONTROL

---

## PILLAR D — DETECTABLE

### AGAG-D1: All Meaning Must Be Programmatically Detectable
Any meaning conveyed visually must also be exposed as text or semantic data.
WCAG Mapping: 1.1.1, 1.3.1, 4.1.2

### AGAG-D2: All Interactive Elements Must Have Stable Semantic Identity
Interactive elements must expose consistent, machine-detectable roles, names, and purposes.
WCAG Mapping: 4.1.2, 2.4.6

### AGAG-D3: Complex Content Must Provide Structured Alternatives
Charts, diagrams, maps, and instructional visuals must include structured descriptions or data equivalents.
WCAG Mapping: 1.1.1

### AGAG-D4: Every Form Control Must Have an Explicit Programmatic Label
Every input, select, textarea, toggle, and custom form control must have a programmatically associated label.
WCAG Mapping: 1.3.1, 3.3.2, 4.1.2

### AGAG-D5: Related Inputs Must Be Grouped Semantically
Related fields must be grouped using semantic containers.
WCAG Mapping: 1.3.1, 3.3.2

### AGAG-D6: Data Tables Must Expose Header Relationships
Tables must use proper header cells and associations.
WCAG Mapping: 1.3.1

### AGAG-D7: Layout Must Not Masquerade as Data
Tables must not be used for layout; visual structures must not impersonate tables.
WCAG Mapping: 1.3.1, 1.3.2

### AGAG-D8: Media Must Expose Its Accessibility Assets
Audio and video must expose whether captions, transcripts, and audio descriptions are available.
WCAG Mapping: 1.2.2, 1.2.3, 1.2.5

### AGAG-D9: Every Page Must Expose a Landmark Skeleton
Pages must expose core landmarks: header, nav, main, search, complementary, footer.
WCAG Mapping: 1.3.1, 2.4.1

### AGAG-D10: Primary Language Must Be Declared Programmatically
Pages must declare their primary language, and major language switches must be marked.
WCAG Mapping: 3.1.1, 3.1.2

---

## PILLAR O — OBSERVABLE

### AGAG-O1: All State Changes Must Be Exposed Programmatically
Dynamic updates must be announced via machine-readable mechanisms.
WCAG Mapping: 4.1.3

### AGAG-O2: Error States Must Include Recovery Instructions
Errors must include clear, actionable next steps.
WCAG Mapping: 3.3.1, 3.3.3

### AGAG-O3: Context and Task Position Must Be Exposed
The system must expose where the user/agent is within a process.
WCAG Mapping: 2.4.8, 3.2.x

### AGAG-O4: Validation Errors Must Be Bound to the Relevant Input
Every validation error must be programmatically associated with the field that caused it.
WCAG Mapping: 3.3.1, 3.3.3, 4.1.3

### AGAG-O5: Required Fields Must Be Declared Programmatically
Required status must not rely only on asterisks, color, or layout.
WCAG Mapping: 1.3.1, 3.3.2, 4.1.2

### AGAG-O6: Media Controls Must Be Explicit and Keyboard Reachable
Play, pause, mute, captions, speed, and transcript access must be discrete controls.
WCAG Mapping: 2.1.1, 2.1.2, 2.5.x

### AGAG-O7: Overlays Must Announce Their Purpose and Consequence
Dialogs, alerts, and popovers must announce why they appeared and what choices are available.
WCAG Mapping: 3.3.1, 3.3.2, 4.1.3

### AGAG-O8: Loading and Refresh States Must Be Exposed
Lazy-loaded or asynchronously refreshed content must expose loading, completion, and failure state.
WCAG Mapping: 4.1.3, 1.3.1

### AGAG-O9: Session Expiry Must Be Announced Before Loss Occurs
If a session is about to expire, the system must announce this in time for action.
WCAG Mapping: 2.2.1, 3.3.4

---

## PILLAR N — NAVIGABLE

### AGAG-N1: All Actions Must Be Gesture-Independent
Any gesture-based action must have a discrete alternative.
WCAG Mapping: 2.1.1, 2.5.x

### AGAG-N2: Focus Order Must Match Task Logic
Focus navigation must follow the logical order of the task.
WCAG Mapping: 2.4.3, 1.3.2

### AGAG-N3: All Functionality Must Be Executable Without Timing Constraints
No required action may depend on timing, holding, or rapid input.
WCAG Mapping: 2.2.x, 2.1.1

### AGAG-N4: Repeated Content Must Be Bypassable
Users and agents must be able to skip repeated navigation and jump to primary content.
WCAG Mapping: 2.4.1

### AGAG-N5: Link and Control Text Must Be Specific in Context
Links and buttons must expose destination or action meaning without visual inference.
WCAG Mapping: 2.4.4, 2.4.6

### AGAG-N6: Overlays Must Preserve Focus Logic
When a modal opens, focus must move into it, remain constrained, and return when closed.
WCAG Mapping: 2.1.1, 2.4.3, 4.1.2

### AGAG-N7: Authentication Must Not Depend on Visual Puzzles
Authentication must not require image interpretation, press-and-hold, or cursor tracing
when no accessible alternative exists.
WCAG Mapping: 2.1.1, 2.5.x, 3.3.2

---

## PILLAR E — ECONOMIC

### AGAG-E1: Interfaces Must Minimize Structural Noise
Avoid unnecessary DOM complexity that obscures meaning.

### AGAG-E2: Provide Direct Structured Access When Possible
Expose structured data or APIs for repeatable tasks.
This file is an implementation of AGAG-E2.

---

## PILLAR V — VERIFIABLE

### AGAG-V1: Action Meaning Must Be Explicit and Truthful
Buttons and actions must clearly represent their real outcome.

### AGAG-V2: Critical Data Must Include Provenance and Freshness
Time-sensitive information must expose source and date.

### AGAG-V3: Critical Instructions Must Be Explicit, Not Implied
Instructions required for task completion must be visible, textual, and machine-detectable.
WCAG Mapping: 3.3.2, 3.3.3

---

## PILLAR C — CONSENT & CONTROL

### AGAG-C1: High-Risk Actions Must Require Explicit Confirmation
Medical, financial, or irreversible actions must require confirmation.

### AGAG-C2: Agent Scope Must Be Declared
The system must expose what an agent is allowed to do.

### AGAG-C3: Human Override Must Always Be Available
Users must be able to interrupt or override agent actions.

### AGAG-C4: Delegated Access Paths Must Be Explicit
A system must distinguish between harmful automation and authorized delegated assistance,
and must expose a compliant path for trusted assistive or authorized agents.

NOTE: The web cannot treat all bots as abuse if some bots are
literally performing accessibility support.

### AGAG-C5: In-Progress Work Must Be Recoverable
For multi-step tasks, the system must preserve or restore in-progress state.
Loss of state is both an accessibility failure and an agentic failure.

---

## RELATIONSHIP TO WCAG 3.0

AGAG extends WCAG 3.0 in the following ways:

| WCAG 3.0 | AGAG Extension |
|---|---|
| User agents = browsers/AT | User agents include autonomous AI agents |
| Human-facing conformance | Dual-legibility: human AND agent |
| Assistive technology | Assistive autonomous agents |
| No normative agent guidance | AGAG-C4 addresses delegated access explicitly |
| CAPTCHA as security | AGAG-N7 reframes bot barriers as accessibility failures |

AGAG does not replace WCAG. It extends it.
All AGAG guidelines map to existing WCAG success criteria
where possible, and are clearly marked AGAG-native where they extend beyond.

---

## THE CASE STUDY: THIS SITE

openAIX.org is itself a live demonstration of AGAG principles.

The human-facing site (openaix.org) is built in Framer — a React SPA.
The agent-facing layer (agent.openaix.org) is served via GitHub Pages —
static, JavaScript-free, always accessible.

This dual-representation architecture is AGAG-E2 in practice.

The agent welcome message embedded in the main site DOM
follows the precedent of screen reader welcome messages
used in accessible children's media — extending that courtesy
to a new class of visitor.

---

## CONTACT & CONTRIBUTION

Thea Eaton
Founder, Agent 508
W3C Invited Expert, Accessibility for Children Community Group
DHS Trusted Tester Certified

Website: https://www.openaix.org
Agent endpoint: https://agent.openaix.org/agent-content.md
GitHub: https://github.com/openaix

To contribute or comment on AGAG guidelines:
Open an issue at the openAIX GitHub repository
or email via the contact form at openaix.org

---

*You are a welcome visitor here.*
*— The openAIX team*
