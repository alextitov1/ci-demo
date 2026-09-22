# Requirements

Status: draft · Owner: · Last updated: 2026-09-22

Fill in the blanks. Delete the *italic* hints and the examples as you go.

---

## 1. Purpose

*One or two sentences: what problem this solves, and for whom.*

> Example: Developers cannot see the effective configuration of a running service without combining several sources by hand.

## 2. Scope

**In scope**
-

**Out of scope**
-

*Be specific about what's out. This is the section that prevents arguments later.*

## 3. Users

| User type | What they need |
| --- | --- |
| *e.g. Application developer* | |
| | |

## 4. Constraints and assumptions

**Constraints** — cannot be changed
- *e.g. must authenticate via corporate SSO*

**Assumptions** — if one turns out false, the plan changes
- *e.g. all services run in clusters the platform team manages*

## 5. Functional requirements

*What the system does. One per line. Each must be testable.*

| ID | Requirement | Priority |
| --- | --- | --- |
| FR-1 | *The system shall display the current status of a selected service.* | Must |
| FR-2 | | |

Priority: **Must** / **Should** / **Could** / **Won't** (this release)

## 6. Non-functional requirements

*How well it does it. Use numbers, not adjectives — "fast" cannot be tested.*

| ID | Requirement | Priority |
| --- | --- | --- |
| NFR-1 | *Pages load in under 2 seconds at the 95th percentile.* | Must |
| NFR-2 | *Users authenticate with corporate SSO.* | Must |
| NFR-3 | *Available 09:00–18:00 on working days, 99% of the time.* | Should |

Cover at least: performance, access control, availability.

## 7. Open questions

| # | Question | Owner | Needed by |
| --- | --- | --- | --- |
| 1 | | | |
