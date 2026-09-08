# MobiKash Cybersecurity Assessment Portfolio

A comprehensive security assessment of **MobiKash Technologies Ltd.**, a FinTech startup providing mobile wallet, USSD banking, and micro-lending services across West Africa. This portfolio documents my work as **Threat Modeler** in a 10-person team over an 8-week internship with **Thrive Africa Cybersecurity**.

---

## 📋 Project Overview

**Company:** MobiKash Technologies Ltd. (Accra, Ghana)  
**Services:** Mobile wallet, USSD banking, micro-lending (QuickKredit)  
**Target Market:** Unbanked communities across West Africa  
**Assessment Duration:** 8 weeks (August–November 2026)  
**Team:** Group 18 (10 roles)

### Why This Matters
MobiKash handles sensitive financial data and transactions for vulnerable populations. The assessment identifies threats to confidentiality, integrity, and availability across their infrastructure—from mobile apps to cloud backends to agent networks.

---

## 🎯 My Role: Threat Modeler

**Responsibilities:**
- Identify and map all attack surfaces and entry points
- Develop STRIDE-based threat models for each component
- Document threats, impacts, and mitigations
- Support the team with threat context for vulnerability testing and remediation

## 🏢 Company Snapshot

MobiKash Technologies Ltd. is a Series A FinTech startup based in Accra, Ghana, running three core products: **Smart Wallet** (mobile app), **Offline USSD Banking** (*844#), and **QuickKredit** (automated micro-lending). Platform is hosted entirely on AWS (Africa, Cape Town Region) with a PostgreSQL database on Amazon RDS. See `docs/company_overview.md` for full details, leadership, and the 15-asset inventory.

---

## 📂 Weekly Deliverables

### Week 1: Threat Modeling Foundations ✅

| Deliverable | Status | Notes |
|---|---|---|
| **Threat Model Document** | Complete | STRIDE analysis across 6 attack surfaces |
| **Network Topology Diagram** | Complete | Device-level & zone-based views |
| **Entry Points & Attack Surface Map** | Complete | Comprehensive attack surface inventory |
| **GitHub Portfolio Setup** | Complete | Repo initialized with docs |

#### Week 1 Key Artifacts:
- `docs/Week1_ThreatModel.md` — Full STRIDE analysis, entry points, priority mitigations
- `docs/company_overview.md` — Company background, leadership, asset inventory
- `diagrams/network_diagram.jpeg` — High-level AWS network architecture

### Weeks 2–8: Coming Soon
- Week 2: Vulnerability assessment & scanning
- Week 3: Security testing & exploitation
- Week 4: API & authentication review
- Week 5: Infrastructure & cloud security audit
- Week 6: Data protection & compliance analysis
- Week 7: Remediation planning & reports
- Week 8: Final recommendations & portfolio wrap-up

---

## 🛠️ Tools & Skills

**Threat Modeling & Security:**
- STRIDE methodology
- Attack surface analysis
- Threat mapping & risk assessment
- Security architecture review

**Documentation & Diagrams:**
- Network topology modeling
- Data flow diagrams (DFDs)
- Threat model documentation
- Architecture visualization

**Technologies (MobiKash Stack):**
- Mobile: Android/iOS (Smart Wallet)
- Backend: Node.js/Python APIs
- Database: PostgreSQL (RDS)
- Caching: Redis
- Cloud: AWS (EC2, S3, VPC, IAM)
- Telecom: USSD gateway integration
- Payments: Mobile money, bank APIs

---

## 📖 How to Use This Portfolio

1. **Start with** `README.md` (you're here)
2. **Read** `docs/Week1_ThreatModel.md` for the full threat analysis
3. **Review** `diagrams/network_topology.png` for system architecture
4. **Check** `docs/attack_surfaces.md` for entry point details
5. **Follow along** as new weeks are added

Each week includes:
- Threat/vulnerability findings
- Technical artifacts (diagrams, configs, reports)
- Methodology & approach
- Lessons learned

---

## 🔗 Key Files

```
MobiKash-Cybersecurity-Portfolio/
├── README.md                          # You are here
├── docs/
│   ├── Week1_ThreatModel.md          # STRIDE analysis, entry points, mitigations
│   └── company_overview.md            # Company background & asset inventory
└── diagrams/
    └── network_diagram.jpeg           # High-level AWS network architecture
```

---

## 🚀 Getting Started (Local Setup)

Clone this repo and explore:

```bash
git clone https://github.com/YOUR_USERNAME/MobiKash-Cybersecurity-Portfolio.git
cd MobiKash-Cybersecurity-Portfolio
```

Each week's artifacts are in dated folders for easy tracking.

---

## 📊 Assessment Scope

**Attack Surfaces Covered:**
1. **Smart Wallet Mobile App** — Client-side threats, app security
2. **USSD Gateway** — Telecom integration, man-in-the-middle risks
3. **APIs & Microservices** — Authentication, authorization, injection
4. **AWS Infrastructure** — Cloud misconfiguration, access control
5. **PostgreSQL Database** — SQL injection, privilege escalation
6. **Agent Network & QuickKredit** — Human factors, social engineering

**Threat Categories:**
- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

---

## 📝 Methodology

- **STRIDE** for threat identification
- **Attack Trees** for exploitation paths
- **Likelihood × Impact** for risk scoring
- **Defense-in-Depth** for mitigation strategy
- **CWE/OWASP Top 10** for context

---

## 🤝 Team Context

**Group 18 Roles:**
- Chief Executive Officer – Alexander Nyarko. 
- Marketing manager – Isaac Oppong. 
- Data Analyst – Hannah Dankwah. 
- Accountant – Dogbo Lawrencia Adzo Fafali. 
- Certified Finance Officer – Asmah Paul.    
- Operations manager – Oheneba Joshua Gyan. 
- Security and fraud detector manager – Agyapong Stephen.  
- Compliance specialist – Faustina Awuah.

Each role feeds into the final security assessment report.

---

## 📧 Questions?

This portfolio is a living document. Each week adds new findings, diagrams, and threat analysis. Feedback welcome!

---

**Last Updated:** Week 1 (August 2026)  
**Next Update:** Week 2 (September 2026)

---

*Part of the Thrive Africa Cybersecurity Internship Program*
