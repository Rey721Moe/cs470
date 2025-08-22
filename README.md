# CS 470 Final Reflection — Reynaldo Ortiz

**Date:** August 2025  
**Assignment:** CS 470 Final Reflection  
**Presentation:** https://youtu.be/uib6fc2ayGc  
**PDF Artifact:** [CS470_Final_Reflection.pdf](CS470_Final_Reflection.pdf)

---

## Summary
This reflection captures what I built and learned in CS 470: a cloud‑based full‑stack application, containerized with Docker/Docker Compose and extended with AWS services. I also outline how I would plan for growth using microservices and serverless patterns, and how costs and elasticity shape those decisions.

## Experiences & Strengths
- Built and deployed a MEAN stack in containers (Angular, Node.js, MongoDB) and integrated AWS (Lambda, API Gateway, DynamoDB).  
- Strengthened troubleshooting, adaptability, and problem‑solving through hands‑on debugging of cloud and container issues.  
- Prepared for roles such as Full‑Stack Developer, Cloud Application Developer, or entry‑level DevOps Engineer.

## Planning for Growth (Scale, Reliability, Cost)
- **Architecture:** Use microservices/serverless to scale parts independently; keep core services in containers; use Lambda for bursty/event‑driven tasks.  
- **Reliability:** Monitor with CloudWatch; handle failures with retries and DLQs.  
- **Cost:** Containers = more predictable baseline; Serverless = efficient at low/variable traffic but can spike with heavy load.  
- **Elasticity & Pay‑for‑Use:** Scale with demand without over‑provisioning; align spend to actual usage.

---

> Per course guidance, only the reflection PDF (with presentation link) is shared publicly. AWS resource code/IDs are not included for security.
