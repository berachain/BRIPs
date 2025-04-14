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
~~- **Standard** – Ecosystem standards (e.g., wallet formats, smart contract interfaces)~~
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
