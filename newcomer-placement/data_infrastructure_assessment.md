# Is There a Data Infrastructure Opportunity? (Newcomer Placement)

**Role:** a state education data strategist who has run a research–practice partnership, the kind of person who builds state longitudinal data systems and then watches whether anyone uses them.
**Question:** Should the venture be a centralized data system, or a "Statista for newcomer education"?

---

## 1. Short answer

**Yes, there is a real data infrastructure problem. But it is not the one a centralized database or a Statista would solve.**

- **System-level data already exists.** Massachusetts's state data system is good enough that Brown's Annenberg Institute, working with the state education department (DESE), could track newcomers statewide and show that **older newcomers in Springfield are 38 percentage points more likely to be placed in 9th grade than similar newcomers in Boston**.
- **What's missing is data on what a student knew on day one.** No standard record exists of a newcomer's prior schooling, home-language literacy, or math starting point at enrollment. So the research can show that placement *varies*. It cannot show which placements were *right*, because "similar newcomers" can only be matched on age, English level, and demographics, not academic readiness.
- **The missing variable is the academic starting point.** That's exactly what your team's problem statement is about. The infrastructure opportunity is to **capture it at intake in a standard way**, so it flows into systems that already exist.

---

## 2. Three options, judged

| Option | Verdict | Why |
|---|---|---|
| **A. "Statista for newcomer education"** (aggregated statistics, reports, charts) | **Reject as the business** (fine as a marketing asset) | The data is already free: the Migration Policy Institute's state profiles and data hub, NCES, the federal English-learner clearinghouse (NCELA), state report cards. Few buyers will pay, since it serves researchers, journalists, and nonprofits. It doesn't change a single placement decision. Statista works because it covers thousands of topics; one vertical can't sustain it. |
| **B. Centralized student-level database** (one national or multi-state store of newcomer records) | **Reject** | (1) **States already own this layer** through their longitudinal data systems, and won't hand it to a startup. (2) **History is against it.** The federal Migrant Student Record Transfer System was shut down as **costly and underused**. It drifted into a reporting tool instead of a record exchange. (3) **Safety.** A central database of immigrant children is a target in the current enforcement climate. Research finds immigration raids increase student absences; families avoid systems they fear. |
| **C. Intake-to-outcome data layer** (a standard way to capture day-one starting points inside the enrollment workflow, kept in district and state systems, and aggregated for system insight) | **Recommend** | It fills the variable that research and districts are missing. It rides on existing standards and systems instead of replacing them. Data is created *as a byproduct of a task staff already must do*, which is the lesson from data-use research (§3). |

---

## 3. Why option C (the research basis)

| Evidence | What it tells you |
|---|---|
| **Placement varies sharply by district:** a 38-point gap in 9th-grade placement between Springfield and Boston (Annenberg/DESE, *Land of Opportunity?*, 2026) | The problem is system-level and measurable. Without starting-point data, nobody can say which district is getting it right. |
| **No federal definition or data collection for SLIFE** (WIDA); state criteria vary. Massachusetts does have a SLIFE indicator in its state student data system. | Identification is inconsistent across states, so a common intake protocol has real value. MA is a good first state because a data field already exists to feed. |
| **"Date first enrolled in a US school"** already exists as a standard data element in state systems | Don't reinvent. Extend existing standards (CEDS, Ed-Fi) with the few elements that are missing. |
| **MPI recommends common definitions for newcomers** and better English-learner data systems; state policies are a "patchy landscape" | The field is asking for standardization, which gives you a policy tailwind. |
| **Coburn & Turner (2011):** data use is an interpretive, organizational, power-laden process; data alone doesn't change practice | Build the **routine** first (the enrollment check), and let the data come from it. A dashboard nobody's workflow depends on dies. |
| **The migrant records system (MSRTS) was shut down** as costly and underused | Central record exchanges fail when they aren't embedded in a daily task. |
| **More than half of MA high school newcomers arrive after September; about half are 16 or older** (Annenberg/DESE) | Intake happens all year, one student at a time. The data layer must work at a single enrollment desk, not only in a fall testing window. |
| **MA newcomer enrollment dropped about 20%** (reported July 2026) | Flows swing with policy. Aim for durable infrastructure, not volume-dependent revenue. |

---

## 4. What the system would look like

```
STUDENT (at enrollment)        DISTRICT                      STATE / RESEARCH
─────────────────────────      ─────────────────────────     ──────────────────────────
Starting-Point Check     ──►   Profile saved in district's   De-identified, aggregated
• schooling history            existing systems (student     flows to the state data system
• home-language literacy       information system, EL        via existing standards
• math screener                platform)                     ──► research partnership
• English screener (already    ──► placement + first-month      analyzes: which placements
  required: reuse the result)      instruction plan              lead to credits, English
                               ──► district dashboard            growth, graduation
                                                             ──► state guidance and funding
```

**The minimum intake dataset (about 10 elements):**
1. Date first enrolled in a US school (an existing standard element)
2. Age at arrival
3. Years of formal schooling completed
4. Years or months of interruption
5. Type of last school: public/private, rural/urban, country (optional, coarse)
6. Home-language literacy level (a scale, not a score)
7. Math starting point (grade-band estimate)
8. English screener result (reused, not re-tested)
9. Placement decision and date
10. Placement change within 90 days, with a reason

**Never collected:** immigration status, visa type, how or when the student crossed the border, parents' status. The system has **no field** for them.

---

## 5. What system-level insight enables

| Level | Insight | Action it drives |
|---|---|---|
| **Classroom** | "6 of your 14 newcomers are at a grade 3–4 math starting point" | Group students; assign foundational math |
| **School** | "Median time to a stable placement: 47 days" | Fix the intake process; add a 30-day review |
| **District** | "Our SLIFE identification rate is 2× or 0.5× similar districts" | Check for over- or under-identification |
| **District** | "Mid-year arrivals wait 3 weeks for assessment" | Keep rolling intake capacity |
| **State** | "Placement for comparable starting points varies 38 points across districts" (the research already shows this for age; you'd show it for readiness) | Statewide placement guidance and funding |
| **State / research** | "Students placed at their starting point earn X more credits in year 1" | Evidence for which placement policies work |

---

## 6. Business model implications

| Layer | Who pays | What they pay for |
|---|---|---|
| **Workflow** (the Starting-Point Check) | District (English-learner funds) | Faster, defensible placement; less paperwork. **This is the wedge.** |
| **District insights** | District | Benchmarks against similar districts; the time-to-placement dashboard |
| **State insights and standards** | State education agency, philanthropy | A common intake protocol, statewide benchmarking, and implementation support |
| **Research access** | No one. Provided through a formal research partnership. | Evidence builds legitimacy; it's not a revenue line. |

**Rules:** never sell student data. The district owns its data; the state receives aggregates under its existing agreements.

**Legal structure:** the data-trust question pushes toward a **nonprofit or public benefit corporation** with a data governance board that includes families and advocates. If a state is the main payer, a nonprofit (or an open-source protocol the state adopts) is the more natural fit.

---

## 7. How to test this (next 30 days)

1. **Talk to the people who built the research** (the Educational Opportunity in Massachusetts partnership at Brown/Annenberg) and **DESE's Office of Language Acquisition**. Ask: *"When you compared similar newcomers across districts, what variable did you wish you had?"* If they say "prior schooling or academic starting point," the thesis holds.
2. **Ask 3 district English-learner directors:** *"Walk me through what gets recorded when a newcomer enrolls. Where does it live? Who looks at it after week one?"*
3. **Ask a Harvard contact** whether the Strategic Data Project at Harvard's Center for Education Policy Research (CEPR) has alumni in MA districts or at DESE (verify). They are natural early users.
4. **Kill test:** if the state says *"we already capture that,"* or districts say *"we'd never enter more fields,"* then the data layer isn't the opportunity. Fall back to the workflow tool alone.

---

## Sources

- Annenberg Institute at Brown, [*Land of Opportunity?* (2026)](https://annenberg.brown.edu/edopportunity/land-of-opportunity) · [Education Week coverage, Aug 2026](https://www.edweek.org/teaching-learning/immigrant-students-face-big-barriers-to-success-in-high-school/2026/08) · [Brown news release](https://www.brown.edu/news/2026-07-28/report-immigrant-newcomers-massachusetts-high-schools) · [Boston Globe on the enrollment drop](https://www.bostonglobe.com/2026/07/28/metro/massachusetts-high-school-immigrant-student-enrollment-drop/)
- Annenberg/DESE, [*Rising Numbers, Unmet Needs* (2023)](https://annenberg.brown.edu/sites/default/files/Rising%20Numbers%20Unmet%20Needs.pdf)
- MA DESE, [SLIFE guidance](https://www.doe.mass.edu/ele/slife/guidance.pdf) · [SIMS Data Handbook (SLIFE element)](https://oese.ed.gov/files/2020/10/ma_datahandbook_p.29_ra_el_p.51_slife.pdf)
- WIDA, [SLIFE resources (no federal definition or data collection)](https://wida.wisc.edu/resources/students-limited-or-interrupted-formal-education-slife)
- Colorado Dept. of Education, ["Date First Enrolled in US" data element](https://www.cde.state.co.us/datapipeline/student-interchange_datefirstenrolledus) · [CEDS](https://ceds.ed.gov/)
- Migration Policy Institute, [*Refining State Accountability Systems for English Learner Success*](https://www.migrationpolicy.org/publication/refining-state-accountability-systems-english-learner-success) · [*The Patchy Landscape of State EL Policies under ESSA*](https://www.migrationpolicy.org/publication/patchy-landscape-state-english-learner-policies-under-essa)
- Federal Register (2016), [Migrant Education Program rule, background on MSRTS termination](https://www.federalregister.gov/documents/2016/05/10/2016-10658/title-i-improving-the-academic-achievement-of-the-disadvantaged-migrant-education-program) · [MSIX overview](https://www2.ed.gov/admins/lead/account/recordstransfer.html)
- Coburn, C. E., & Turner, E. O. (2011). [Research on Data Use: A Framework and Analysis](https://eric.ed.gov/?id=EJ953127). *Measurement*, 9(4).
- [Recent immigration raids increased student absences](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12625821/) (PMC)
