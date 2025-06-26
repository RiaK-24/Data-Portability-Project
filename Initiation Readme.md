# 01 – Initiation and Discovery

## Objective
- To define the scope, align stakeholders, and interpret Quebec Law 25 requirements

## What I Did
- Led the project kickoff with Legal, Cybersecurity, Business, and Architecture teams
- Created the stakeholder matrix and clarified roles using a RACI model
- Collaborated with Legal to break down compliance requirements into actionable deliverables
- Set up project tracking tools (Jira, Confluence) and initiated RAID log

## Key Deliverables
- Project Charter
- Stakeholder Map & RACI
- Initial Risk Register
- Compliance Interpretation Summary

## Approach and Methodology 

We followed a Hybrid Agile model:

- Sprint-based delivery for feature development and testing
- Waterfall checkpoints for legal reviews, architecture sign-offs, and change control

## Key steps

1. Conducted workshops with Legal, Privacy, and App Owners to scope PI data

2. Mapped 78+ systems to identify if PI resided in common databases or was fragmented

3. Used data classification matrix to prioritize which PI elements were critical

4. Facilitated architecture working groups to design:
  - A common database ingestion model (when feasible)
  - Orchestrated on-demand data pull via secured APIs (when data was decentralized)
  - Implemented encryption standards (AES-256) and routing through secure API gateways
  - Delivered testable JSON outputs to simulate real customer/employee requests
