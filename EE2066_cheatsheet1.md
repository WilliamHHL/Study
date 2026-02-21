<!--
EE2066 Engineers in Society — A4 DOUBLE-PAGE CHEATSHEET (2 pages)
How to print nicely:
- Use a tool that respects print CSS (e.g., VS Code “Markdown PDF”, Typora, Obsidian export, or Pandoc -> PDF).
- Print scale: 100% (then adjust font-size in CSS if needed).
-->



## 2) Why Engineering? (misconceptions → reality)
| Myth | Reality |
|---|---|
| Engineers don’t write much | Reports + documentation are crucial |
| Engineers work mostly alone | Communication/negotiation are vital |
| Engineers just follow orders | High responsibility + decision-making |
| There’s always a textbook solution | Often no “known answer”; must reason |
| Engineering = math/physics only | Also imagination, innovation, aesthetics |

### Engineer’s “many hats”
- Negotiator (balance stakeholders)
- Manager (deliver projects)
- Safety expert (protect people)
- Sustainability advocate (“tree hugger”)
- Innovator (creative solutions)
- KOL/Communicator (explain to non-experts)

### Responsibilities of an engineer (core)
- Technical analysis/design; calculations; troubleshooting
- Project + financial decisions
- Documentation/reporting
- Collaboration/communication
- **Ethical judgement**

---

## 3) Ethics basics
### Definitions (common idea)
Ethics = principles about **right/wrong**, **good/bad**, **duty/obligation**.

### Ethical thinking includes
- Moral compass (foundation)
- Decision frameworks
- Social responsibility (impact on others)
- Critical thinking (analyse moral issues)
- Professional codes
- Cultural influence (varies across time/place)

### Technology & ethics (key claim)
Availability of tech **does not** imply we **ought** to use it, or how it should be used.

### Ethical questions
- “Should we use this technology?”
- “How should we use it?”
- Focus on what we **ought** to do, not just what we **can** do.  
  **Phrase:** “Ought implies can, but can does not imply ought.”

### Evaluate tech ethically (practical)
- Tech changes society fast; **law lags** → engineers still must decide under uncertainty.
- Moral judgement often concerns **sociotechnical practices** (how tech is used in society), not the gadget alone.

---

## 4) The 4 Ethical Principles (course lens)
1. **Accuracy & Rigour**  
   Competence, evidence, uncertainty, risk.
2. **Honesty & Integrity**  
   Truthfulness, conflicts of interest, trust.
3. **Life, Law & Public Good**  
   Safety first, legality, sustainability, minimize harm.
4. **Responsible Leadership (Listening & Informing)**  
   Listen to concerns; communicate risks/benefits; speak up culture.

### Principle 1 — Accuracy & Rigour (do)
- Work within competence; keep skills updated; help others learn
- Don’t mislead; present evidence without bias
- Identify/evaluate/quantify risk where possible  
**Pipeline:** data/tests → assumptions → uncertainty → risk decision

### Principle 2 — Honesty & Integrity (do)
- Avoid deception/corruption; declare conflicts; reject bribery
- Respect others’ rights/reputation
- Be trustworthy to employer/client **without** harming public interest  
**COI types:** financial, personal, professional, cultural, political

### Principle 3 — Life, Law & Public Good (priority)
**Pyramid:** Public & environment (safety) > laws/regulations (compliance) > cost/schedule (constraints)

### Principle 4 — Responsible Leadership
- Be aware of societal issues; listen to stakeholders
- Promote public awareness of impacts/benefits
- Be objective & truthful in statements  
**Loop:** listen → explain risks/benefits → integrate views → improve design/policy

---

## 5) Why ethics matters in engineering
Engineering work is:
- **High impact** (affects many, long time)
- **Safety-critical** (failures cause major harm)
- **Technically complex** (public depends on judgement)
- **Trade-off driven** (cost/schedule/performance/sustainability/safety)

### What ethics is NOT (useful for exams)
Not feelings; not science; not religion; not cultural norms; not law.

### Common ethical dilemmas
- Safety vs cost
- Environment vs development
- Transparency vs confidentiality
- Personal ethics vs company policy

---

## 6) Ethical decision-making framework (fast)
**A) Identify issue:** harm/benefit? two goods/two bads? beyond legal/efficient?  
**B) Get facts:** what’s known/unknown? stakeholders? options? consult?  
**C) Evaluate options (lenses):**
- Rights; Justice/Fairness; Utilitarian; Common good; Virtue; Care ethics  
**D) Choose + test:** public/expert reaction? implement carefully  
**E) Reflect:** outcome + lessons + follow-up

---

## 7) Reasoning traps (remember!)
- **Survivorship bias:** focus on successes; ignore failures
- **Normalization of deviance:** “worked last time so fine”
- **Groupthink:** consensus replaces analysis
- **Authority bias:** rank overrides evidence
- **Availability bias:** rare-but-severe risks ignored

### Warm-up quiz (good model answers)
1. Normalization of deviance = gradual acceptance of unsafe deviations as “normal”.
2. Spirit vs letter: meet test requirements while violating intent (e.g., defeat device; loophole compliance).
3. Often-missed stakeholders: maintenance workers/frontline operators; nearby community; future generations; vulnerable groups.
4. Worse in risk comms: **ambiguity** (bad news can be managed; unclear risk erodes trust and delays action).
5. AI harm not a bug: biased outcomes from skewed data; feedback loops; chilling effects; opacity blocking appeals.

</div>
</div>

<div class="page tiny">
<div class="cols">

# EE2066 — Cases, AI ethics, HKIE/ICAC, Professionalism

## 8) Signature case studies (map to 4 principles)
### Challenger (1986)
- Engineers warned about O-rings in cold; launch under schedule/political pressure; comms contested.
- Typical failures: weak escalation + decision-making under pressure.

### Flint Water Crisis (2014) — timeline idea
Switch source (cost) → residents complain → lead detected → researchers/pediatrician evidence → switch back → emergency.
- Ethics: transparency, due diligence, environmental justice, early escalation.

### VW “Dieselgate” (2015)
- “Defeat device” to pass tests; real-world emissions far higher.
- Ethics: integrity, spirit vs letter, corporate culture, governance.

### Cambridge Analytica / Facebook (2018)
- Large-scale data harvesting without meaningful consent; weak verification; political profiling.
- Ethics: privacy-by-design, responsibility allocation, disclosure threshold.

### Boeing 737 MAX (2018–2019)
- Safety-critical design + schedule pressure + incomplete transparency + oversight gaps.
- **Swiss-cheese model:** multiple layers fail; holes align → disaster.

### Ariane 5 Flight 501 (1996) (example for rigour)
- Reuse code not protected vs overflow; exception handling failure; self-destruct.

---

## 9) “Pressure vs Safety” checklist (what engineers do)
When pressured (cost/schedule/competition/hierarchy):
- **Document concerns** (facts, assumptions, risk)
- **Escalate appropriately** (clear ownership)
- Seek **independent review**
- **Refuse unsafe sign-off** if evidence inadequate
- Maintain traceability of decisions (who approved what, when, why)

---

## 10) Regulation: ensuring & enforcing safety
Regulators strengthen safety via:
- Standards (“safe enough” definition)
- Independent assessment (audits/certification; manage conflicts)
- Evidence requirements (testing, traceability, documentation)
- Reporting systems (incident reporting, whistleblower protection)
- Post-market monitoring (near-misses, operational data)
- Enforcement (penalties/recalls/grounding)

---

## 11) AI ethics — what’s different from “normal” software?
AI introduces:
- **Probabilistic behaviour** (errors expected)
- **Data dependence** (bias, drift, representativeness)
- **Opacity** (hard to explain)
- **Scale + automation** (small error → mass harm)
- **Feedback loops** (predictions change reality)

### AI Ethics Toolbox (use in every AI case)
**People & impacts**
- Fairness (who disadvantaged?)
- Safety (worst-case harm?)
- Transparency (explain/contest?)
- Accountability (who owns outcomes?)

**Systems & controls**
- Privacy (minimize data, consent, retention)
- Security/misuse (adversarial use, abuse)
- Monitoring (drift, incident reporting, rollback)

### AI mini-cases (what to say fast)
**A) Hiring screening**
- Evidence: selection rates by group; false negatives; audit logs.
- Tools: fairness metrics + human appeal + independent audit.
- If vendor refuses transparency: don’t deploy / require audit-rights / alternative model.

**B) Medical triage**
- “Better on average” may be unacceptable if subgroup harm is severe.
- Response: safety-first (pause/rollback), communicate uncertainty, assign accountability.

**C) Facial recognition**
- Harms even if accurate: chilling effects, misuses, surveillance creep, unequal burden.
- Red lines: no consent/no oversight/no audit/no appeal; high false positive risk.

**D) Deepfakes**
- Duty: communicate quickly **and** carefully; pre-plan spokesperson + verification protocol.
- Decide actions with staged response (verify → temporary mitigation → confirm → communicate).

**E) GenAI in safety-critical reporting**
- Negligence when: unverified assumptions/citations; reliance replaces engineering judgement.
- Minimum checks: verify features exist; verify clauses/standards; peer review; traceability.
- Record: prompts/outputs, what verified, who approved, final responsibility.
- Policy idea: AI allowed for formatting/summarising internal notes; not allowed to “invent” compliance claims or cite unverifiable standards.

---

## 12) HKIE Rules of Conduct (exam-friendly)
1. **To profession:** uphold dignity/standing/reputation.
2. **To colleagues:** don’t maliciously damage reputation; foster advancement.
3. **To employers/clients:** integrity + high business ethics.
4. **To public:** overriding public interest—environment, welfare, health, safety.

---

## 13) ICAC / POBO essentials (high-level memory)
**POBO (Prevention of Bribery Ordinance)**
- Private sector focus: **Section 9**
  - 9(1): agent **solicits/accepts** an advantage without principal’s approval in relation to principal’s business
  - 9(2): **offer** of advantage (offeror also guilty)
  - 9(3): use **false/erroneous/defective documents** to deceive principal
- “Advantage” includes gifts/loans/fees/commissions, employment/contract, release of liability, services/favours, exercise of rights/power **(entertainment excluded)**.
- Entertainment = food/drink consumed on the occasion + connected entertainment (but lavish/frequent can be a trap).
- Obtain principal approval: follow code of conduct; permission **beforehand** or ASAP afterwards.
- “Customs of the trade” is **not a defence**.

**Conflict of interest (COI)**
- When personal interest competes with company interest.
- Manage: **Avoid → Declare → Remove from decision / reassign / record**.

---

## 14) Week 4 ICAC-related case summaries
1. **Dummy agents commission fraud**: fake policies → HK$52M commission; laundering; control failures in incentive systems.
2. **Property manager COI**: concealed ownership of contractors; self-dealing; policy breach; jail.
3. **Tender secrets leakage**: bribes for confidential bid info; long-term subversion of fair competition.

---

## 15) Professional development & registration (HKIE/IET themes)
### IET / CEng (UK-SPEC-style) competence buckets
1. Knowledge & understanding
2. Design/development/problem-solving
3. Responsibility/management/leadership
4. Communication & interpersonal skills
5. Professional commitment (ethics, sustainability, CPD)

### HKIE “road to MHKIE” (conceptual)
- Multiple routes (formal training / general experience / RRA / non-degree, etc.)
- Competence standards typically cover:
  - Apply engineering knowledge
  - Develop solutions to complex problems
  - Manage engineering work + risk
  - Professional acumen (ethics, impacts, communication)

---

## 16) Engineering in practice: delivery, innovation, digital
### MTR new stations (safer/faster/cheaper) — keywords
- Reality: cost/time/interfaces/community + concurrent projects
- PMO focus: cost, programme, risk/opportunity, reporting, change/baseline
- Early Contractor Involvement (constructability, stakeholder engagement)
- Digital backbone: digital engineering + construction + project management
- Performance specifications: functional outcomes, flexibility, lifecycle optimisation

### Innovation via “reapplication” (AI/robotics/IoT)
- Predictive maintenance; energy optimisation; document automation
- Robotics/drones/exoskeletons for safety + productivity
- Skills: data literacy, AI fluency, cross-disciplinary communication

### Arup digitalisation / structured data (pizza analogy)
- Problem: “everything smashed together” → hard handovers, rework
- Goal: **uniform data exchange + structured storage** → automation
- Once data exists, scripting/automation becomes easy (Rhino/Grasshopper/Python)

---

## 17) Synthesis: patterns across cases (memorise)
- Incentives misaligned with safety/public good
- Weak escalation pathways
- Poor transparency + risk communication
- Lack of monitoring + independent auditing
- Vulnerable groups bear disproportionate risk

</div>
</div>
