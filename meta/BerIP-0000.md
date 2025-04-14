---
mip: 0000
title: BerIP Process and Guidelines
author: <aBear> <abear@berachain.com>
status: Final
created: 2025-04-14
type: Meta
---

# BerIP-0000: BerIP Process and Guidelines

This document defines the process for Berachain Improvement Proposals (BerIPs). It describes the purpose of BerIPs, their lifecycle, formatting requirements, and how they are reviewed, accepted, and finalized.

---

## What is a BerIP?

A **Berachain Improvement Proposal (BerIP)** is a design document that outlines a proposed change to the protocol, ~~governance,~~ tooling, or standards of the Berachain ecosystem.

BerIPs are intended to:

- Provide a structured process for improvements
- Enable community-wide review and input
- Serve as a historical record of technical and governance decisions

---

## BerIP Types

- **Core** – Protocol changes requiring consensus (e.g., forks, state rules, VM logic)
- ~~**Standard** – Ecosystem standards (e.g., wallet formats, smart contract interfaces)~~
- **Informational** – Descriptive content (e.g., historical context, economic models)
- **Meta** – Process changes to the BerIP system itself

---

## BerIP Statuses

| Status     | Description |
|------------|-------------|
| **Draft**  | Initial stage; proposal is open for community feedback and refinement |
| **Review** | Proposal is stable and under formal evaluation by editors or maintainers |
| **Accepted** | Approved for implementation or adoption |
| **Final**  | Implemented, deployed, or widely adopted; no further changes expected |
| **Rejected** | Declined due to flaws, lack of consensus, or redundancy |
| **Withdrawn** | Author has decided to stop pursuing the proposal |

---

## BerIP Workflow

```plaintext
           +-----------------+
           |     Draft       |
           +--------+--------+
                    |
                    v
           +--------+--------+
           |     Review      |
   +--------+--------+--------+--------+
   |                 |                 |
   v                 v                 v
Accepted         Rejected         Withdrawn
   |
   v
Final
```

---

## Roles

The individuals responsible for managing and participating in the BerIP process — including editors, maintainers, and authors — are listed in [roles.md](../roles.md).

For an up-to-date list of who currently holds each role, please refer to that file.

---

## Status Transitions and Authority

BerIP status transitions follow a structured process to ensure transparency and consensus.

| Status        | Can be Set By       | Notes |
|---------------|---------------------|-------|
| `Draft`       | Proposal Author     | Initial status on submission |
| `Review`      | Editors              | When the proposal is complete and ready for wider evaluation |
| `Accepted`    | Editors (with input from Maintainers & Community) | Indicates strong consensus and readiness for implementation |
| `Final`       | Editors              | After successful implementation or deployment |
| `Rejected`    | Editors (with community consensus) | For proposals that are declined or obsolete |
| `Withdrawn`   | Proposal Author      | Author can withdraw at any stage before `Final` |
| `Living`      | Editors              | For documents that remain open-ended or continuously updated |

**Important Notes:**

- Editors act as neutral stewards — not gatekeepers — and apply status changes based on defined process and community input.
- Maintainers may suggest or advise on status transitions based on technical feasibility.
- Authors may request status changes, but editors are responsible for applying them.
