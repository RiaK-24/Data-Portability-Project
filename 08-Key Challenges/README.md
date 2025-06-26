# Key Challenges and Resolutions

This section highlights five key challenges encountered during the Data Portability Compliance Project, along with the solutions implemented and the program management techniques used to overcome them.

| Challenge Faced | Solution Implemented | Program Management Technique |
|-------------------|-------------------------|-------------------------------|
| 1. Unclear scope of PI data across multiple systems | Conducted system mapping workshops with app owners and data governance to identify where PI was stored and in what format | Scope Definition, Stakeholder Workshops, RACI Modeling |
| 2. Legal interpretation of Quebec Law 25 was ambiguous at early stages | Engaged Privacy and Legal SMEs early, documented interpretations as formal compliance use cases for the delivery team | Stakeholder Alignment, Risk Register, Change Control |
| 3. Conflicting opinions between Architecture and Cybersecurity teams on API design | Facilitated decision-making sessions with both teams, documented trade-offs, and aligned on secure API gateway + encryption standards | Decision Logs, Architecture Working Group, Conflict Resolution |
| 4. Fragmented PI data across legacy and modern apps made centralized access difficult | Designed a hybrid solution: centralized database for available apps, federated API access for the rest | Hybrid Solution Architecture, Risk-Based Prioritization |
| 5. Legal and Security validation created bottlenecks before Go-live | Scheduled legal and security reviews as fixed Waterfall checkpoints between Agile sprints, reducing last-minute surprises | Hybrid Agile Planning, Stage Gates, Dependency Tracking |

---

## Summary

These challenges reflect the complexity of managing cross-functional compliance projects that intersect legal, tech, and user experience. By blending Agile delivery with structured governance, we were able to deliver the project on time and with minimal rework.

