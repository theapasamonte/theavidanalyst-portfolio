# Brightbooks: E-Invoice Compliance

**Client type:** SaaS accounting platform (fictional project for portfolio purposes)
**Role:** Business Analyst
**Focus:** Requirements Analysis, Process Mapping, and User Acceptance Testing for
a regulatory compliance feature.

---

## The situation

Brightbooks is a SaaS accounting platform that must comply with a new e-invoicing
regulation requiring that every Sales Invoice be validated by the Tax Authority
before it can be issued to the buyer. This changes a core part of how the product
works: an invoice can no longer be finalized on its own. It must be saved,
submitted for validation, and cleared by the Tax Authority first.

The business needed a clear specification that the development team could build
from and the QA team could test against, written in a way that non-technical
stakeholders like Compliance and Customer Support could follow as well.

---

## How the process works

The sequence for the feature:

1. The Sales Invoice is **saved** and its required fields are checked.
2. The invoice is **submitted for validation**.
3. The system sends it to the **Tax Authority**.
4. The invoice sits in **Pending** status while it waits for a response.
5. The Tax Authority responds:
   - **Validated** — a reference number is stored, and the invoice can be issued
     to the buyer.
   - **Rejected** — the invoice is returned for correction.

---

## The artifacts

Each document below is a piece of the same analysis. Read in order, they show how a
single business need travels from requirement to acceptance test without dropping
the thread.

| # | Artifact | What it shows |
|---|----------|---------------|
| 01 | [Business Requirements Document](./01-business-requirements-document.pdf) | The business need, objectives, stakeholders, and requirements. |
| 02 | [Case Study](./02-case-study.pdf) | The narrative overview of the problem, approach, and outcome. |
| 03 | [User Stories](./03-user-stories.pdf) | The requirements written from the user's point of view. |
| 04 | [User Acceptance Testing Plan](./04-uat-plan.pdf) | How the feature is tested and accepted before release. |
| 05 | Current and Proposed Process Flows | *Coming soon* |
| 06 | Functional and Non-Functional Requirements | *Coming soon* |
| 07 | Requirements Traceability Matrix | *Coming soon* |
| 08 | Data Structure | *Coming soon* |
| 09 | Issue Log | *Coming soon* |

---

## Stakeholders

The analysis was shaped around the people who own or are affected by the feature:

- **Daniel Reyes** — Product Owner
- **Sofia Mendoza** — Compliance Lead
- **Marcus Tan** — Development Lead
- **Lena Cruz** — Customer Support Lead
- **Ryan Santos** — Quality Assurance Lead
- **Isabel Navarro** — Information Security Lead
- **Brightbooks customers** — End Users

---

[← Back to portfolio home](../)
