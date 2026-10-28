# ITC Cohort Training Program
## Implementing ISO/IEC 27001:2022 in the Software Development Process
**Format:** 6 weeks · 1 in-person workshop (Week 1) · 5 weeks virtual · weekly 1:1 expert meetings per firm

---

## 1. Program Overview

| Item | Detail |
|---|---|
| Participants | 2–3 delegates per firm (recommended: a technical lead/CTO, a project/quality manager, and optionally a business owner) |
| Weekly rhythm | 1 virtual group session (≈2 h) + 1 one-to-one expert meeting per firm (≈60–90 min) + homework/deliverable (≈3–5 h) |
| Week 1 | Full-day in-person workshop (≈7 h) |
| Weeks 2–6 | Virtual group sessions + 1:1 meetings |
| Final output | Each firm leaves with a scoped ISMS starter kit for its software development process and a 6–12 month roadmap toward certification readiness |

> **Expectation setting:** Six weeks is enough to *design and start* an ISMS, not to be certified. Certification is granted only by an accredited certification body after a two-stage audit and evidence that the ISMS has been operating (typically including at least one internal audit and one management review). Many organizations take roughly 6–12 months or more to reach audit readiness — this figure is an approximation and varies widely by firm size and maturity.

### Learning objectives
By the end of the program, delegates will be able to:
1. Explain the structure of ISO/IEC 27001:2022 (Clauses 4–10 and the 93 Annex A controls in 4 themes).
2. Define an ISMS scope centered on their software development and delivery activities.
3. Run an information-security risk assessment and produce a risk treatment plan.
4. Map Annex A controls to each phase of their SDLC (requirements → design → code → test → deploy → operate).
5. Draft a Statement of Applicability (SoA) and core SDLC security policies/procedures.
6. Plan internal audit, management review, and continual improvement.

---

## 2. Six-Week Schedule

### Week 1 — In-Person Workshop: Foundations, Scope & Gap Analysis (full day)

| Time | Session | Content |
|---|---|---|
| 08:30–09:00 | Welcome & cohort introductions | Program goals, firm profiles, expectations |
| 09:00–10:15 | **Why ISO 27001 matters for software firms** | Business case, client/market demands, key messages (see Section 4) |
| 10:15–10:30 | Break | |
| 10:30–12:00 | **Anatomy of ISO/IEC 27001:2022** | Clauses 4–10 (context, leadership, planning, support, operation, performance evaluation, improvement); Annex A: 37 organizational, 8 people, 14 physical, 34 technological controls; what changed vs. 2013 (11 new controls, e.g., threat intelligence, cloud services security, configuration management, data masking, secure coding); Amendment 1:2024 (climate change consideration in Clause 4) |
| 12:00–13:00 | Lunch / networking | |
| 13:00–14:30 | **Hands-on: Context & scope** | Each firm maps interested parties, products/services, teams, locations, cloud providers, and drafts an ISMS scope statement for its development process |
| 14:30–14:45 | Break | |
| 14:45–16:00 | **Hands-on: SDLC gap-analysis self-assessment** | Guided checklist of SDLC-related controls (see Section 3); firms score current maturity |
| 16:00–16:30 | 1:1 scheduling, homework, wrap-up | Book weekly expert slots; assign Week 1 deliverables |

**Deliverables (due before Week 2 1:1):** draft ISMS scope; interested-parties list; completed gap self-assessment; named ISMS owner and top-management sponsor.
**1:1 focus (Week 1, later in the week, virtual):** validate scope boundaries, review gap results, agree on firm-specific priorities.

---

### Week 2 (Virtual) — Leadership, Policy & Risk Assessment

**Group session (≈2 h)**
- Leadership commitment and roles (Clause 5): ISMS owner, security champions in each dev team
- Information security policy and objectives (Clauses 5.2, 6.2) — measurable objectives, e.g., "% of releases passing security testing"
- Risk assessment method (Clause 6.1.2): asset/scenario identification, likelihood × impact, risk acceptance criteria
- Software-specific risk examples: leaked credentials in repositories, vulnerable open-source dependencies, unauthorized access to production, insecure APIs, client data in test environments, supplier/sub-contractor risks

**Deliverables:** information security policy (draft); risk methodology; first risk register (top 15–25 risks for the development process).
**1:1 focus:** walk through the firm's risk register; calibrate ratings; confirm risk owners.

---

### Week 3 (Virtual) — Secure SDLC Part 1: Requirements, Design & Coding

**Group session (≈2 h)**
- 5.8 Information security in project management
- 8.25 Secure development life cycle
- 8.26 Application security requirements (security user stories, abuse cases)
- 8.27 Secure system architecture and engineering principles (threat modeling, least privilege, defense in depth)
- 8.28 Secure coding (coding standards, peer review, secret management, use of reputable libraries)
- 8.4 Access to source code; 8.9 Configuration management
- Practical: inserting security "gates" into an existing Agile/Scrum workflow (Definition of Ready / Definition of Done)

**Deliverables:** Secure Development Policy (draft); secure coding standard; code review checklist; repository access rules.
**1:1 focus:** tailor the secure SDLC to the firm's actual tools and process (e.g., its Git platform, CI/CD, ticketing tool).

---

### Week 4 (Virtual) — Secure SDLC Part 2: Testing, Environments, Change & Suppliers

**Group session (≈2 h)**
- 8.29 Security testing in development and acceptance (SAST, DAST, dependency/SCA scanning, penetration testing)
- 8.31 Separation of development, test and production environments
- 8.33 Test information; 8.11 Data masking (no real client data in test without protection)
- 8.32 Change management (release approval, rollback)
- 8.8 Management of technical vulnerabilities (patching SLAs)
- 8.30 Outsourced development; 5.19–5.22 supplier relationships & ICT supply chain
- 5.23 Information security for use of cloud services

**Deliverables:** risk treatment plan (Clause 6.1.3); change management procedure; environment separation description; supplier security requirements/clauses.
**1:1 focus:** prioritize treatments realistically given team size and budget.

---

### Week 5 (Virtual) — Operations, People & the Statement of Applicability

**Group session (≈2 h)**
- People controls: 6.3 awareness/training, 6.6 confidentiality agreements, 6.7 remote working
- 5.15–5.18 access control and identity management (MFA, joiner/mover/leaver)
- 8.13 Backup; 8.15 Logging; 8.16 Monitoring
- 5.24–5.28 Incident management (including incidents found in client-delivered software)
- 5.29–5.30 Business continuity & ICT readiness
- Building the **Statement of Applicability**: control-by-control inclusion/exclusion with justification
- Documented information & evidence (Clause 7.5): what an auditor will ask to see

**Deliverables:** SoA (draft); incident response procedure; awareness plan for the dev team.
**1:1 focus:** SoA review line by line; evidence gaps.

---

### Week 6 (Virtual) — Performance Evaluation, Improvement & Roadmap

**Group session (≈2 h)**
- Clause 9: monitoring & measurement (security KPIs), internal audit program, management review
- Clause 10: nonconformities, corrective action, continual improvement
- Certification process overview: choosing an accredited certification body, Stage 1 and Stage 2 audits, surveillance audits
- **Firm presentations (10 min each):** scope, top risks, SDLC changes made, roadmap
- Cohort retrospective and closing

**Deliverables:** 6–12 month implementation roadmap; KPI set; internal audit plan; management review agenda.
**1:1 focus:** final readiness assessment (re-score Week 1 gap analysis), next steps, and recommended follow-up support.

---

## 3. SDLC ↔ ISO/IEC 27001:2022 Annex A Control Map (quick reference)

| SDLC phase | Key Annex A controls | Example evidence |
|---|---|---|
| Planning / project | 5.8, 5.1, 5.2 | Security tasks in project plans; roles assigned |
| Requirements | 8.26, 5.34 (privacy/PII) | Security user stories; data classification of features |
| Design / architecture | 8.27, 5.23 | Threat models; architecture review records |
| Coding | 8.28, 8.4, 8.9 | Coding standard; peer-review records; branch protection |
| Testing | 8.29, 8.33, 8.11 | SAST/DAST/SCA reports; masked test data |
| Deployment / release | 8.31, 8.32 | Separate environments; change approvals |
| Operation / maintenance | 8.8, 8.15, 8.16, 8.13 | Vulnerability/patch records; logs; backup tests |
| Suppliers / outsourcing | 8.30, 5.19–5.22 | Supplier contracts with security clauses |
| People | 6.1–6.8 | Training records; NDAs |

> Control numbers follow ISO/IEC 27001:2022 Annex A (aligned with ISO/IEC 27002:2022). Please confirm wording against your licensed copy of the standard before distributing to participants.

---

## 4. Key Messages: How ISO 27001 Improves the Business

Use these messages in invitations, the opening session, and communications to firm leadership.

### 4.1 Core messages
1. **"Security becomes a selling point, not a cost."** A certified ISMS gives clients independent evidence that their data and software are handled responsibly — this can shorten due-diligence and security questionnaires in sales processes.
2. **"Open doors to international and enterprise markets."** Many large clients, public-sector buyers, and regulated industries (finance, health) ask suppliers for ISO 27001 or equivalent assurance in tenders and contracts.
3. **"Build it secure once, instead of fixing it many times."** Defects and vulnerabilities found early in the SDLC are generally much cheaper to fix than those found in production or by a client.
4. **"Fewer surprises, faster recovery."** Defined incident, backup, and continuity processes reduce downtime and the chaos of responding to a breach.
5. **"A management system, not a pile of documents."** ISO 27001 is built on the Plan-Do-Check-Act cycle: it drives decisions by risk and makes improvement routine.

### 4.2 Benefits to business processes
- Clear, repeatable development workflow with defined security checkpoints
- Better change and release discipline → more predictable deliveries
- Defined roles and responsibilities (who approves, who owns which risk)
- Measurable objectives and KPIs that leadership can track
- Improved documentation that also helps onboarding of new developers
- Risk-based prioritization of investment (spend on what matters most)

### 4.3 Benefits to relationships
- **Clients:** increased trust; a common language for security requirements; smoother contract negotiations
- **Suppliers & sub-contractors:** clear security expectations in contracts; better control of outsourced development
- **Partners & investors:** evidence of operational maturity, which may support due diligence
- **Employees:** a security-aware culture; clarity about what is expected of them
- **Regulators:** supports (but does not by itself guarantee) compliance with data-protection and sector regulations

### 4.4 Other benefits
- Protection of the firm's own intellectual property (source code, designs)
- Stronger resilience against ransomware and credential theft
- A foundation for related frameworks (e.g., ISO/IEC 27701 for privacy, SOC 2, cloud-security standards)
- Possible positive influence on cyber-insurance discussions (varies by insurer — firms should verify)
- Competitive differentiation for the cohort as a group of trusted national software suppliers

### 4.5 Short messages for communications
- *"Your clients trust you with their data. ISO 27001 lets you prove it."*
- *"Secure by design, certified by evidence."*
- *"Six weeks to build the foundation; one standard recognized worldwide."*
- *"Security in every sprint — not just before the audit."*
- *"From good intentions to a managed system."*

---

## 5. Roles & Logistics

| Role | Responsibility |
|---|---|
| Program coordinator (ITC) | Logistics, venue, virtual platform, attendance, communication |
| ISO 27001 expert | Workshop delivery, group sessions, weekly 1:1s, deliverable review |
| Firm delegates | Attend all sessions, complete deliverables, bring real process data |
| Firm sponsor (senior manager) | Approve scope/policy, allocate time, attend Week 1 opening and Week 6 presentations |

**Suggested templates to provide:** scope statement, interested-parties register, gap self-assessment checklist, risk register, risk treatment plan, SoA, secure development policy, secure coding checklist, incident response procedure, KPI dashboard, roadmap.

**Weekly time commitment per firm (approx.):** 2 h group + 1–1.5 h 1:1 + 3–5 h internal work.

### Success indicators for the program
- % of firms completing all six deliverable sets
- Average improvement in gap-assessment score (Week 1 vs. Week 6)
- Number of firms with a sponsor-approved policy and SoA
- Number of firms that start the certification process within 6–12 months
- Participant satisfaction (post-program survey)

---

## 6. Notes & Caveats
- ISO/IEC 27001:2022 is a copyrighted standard; participants should use licensed copies. Templates should paraphrase rather than reproduce the standard text.
- The 2013 → 2022 transition period for certified organizations ended on 31 October 2025; new certifications are issued against the 2022 version (please verify with your chosen certification body).
- Benefits described in Section 4 are commonly reported qualitative outcomes; no specific statistics are claimed here. If figures are needed for promotional material, cite them from primary sources (e.g., ISO's annual certification survey).
