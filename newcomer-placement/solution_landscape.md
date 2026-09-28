# Solution Landscape: Newcomer Placement & Academic Starting Points

**Role:** the same state education data strategist and research–practice partnership lead as in the data assessment, now mapping every credible path, not just the ones already discussed.
**Problem (team's definition):** middle and high school newcomers, especially SLIFE (students with limited or interrupted formal education), arrive with widely varying starting points, and schools lack a consistent way to identify them and act on it.

**Evidence ratings used below:**
- **Strong** = randomized trials or meta-analyses
- **Moderate** = quasi-experimental or cohort studies
- **Emerging** = practice-based, descriptive, or self-reported
- **Analogy** = research on a related population, applied here by inference

---

## 1. The full map (18 options in 6 families)

### A. Identify: know the starting point
| # | Solution | Evidence | Notes |
|---|---|---|---|
| 1 | **Enrollment Starting-Point Check**: an in-school, adult-run check of math, home-language literacy, and schooling history | Emerging | The core idea so far. It fills the gap left by the English screener (WIDA), i-Ready, and Lexia. |
| 2 | **Language-light math diagnostic only**: visual and audio, many languages | Emerging | The narrowest possible product; math was the gap the teacher saw most. Easy to pilot. |
| 3 | **Transcript and credit translation** ("Passage"), ages 14–21 | Emerging | Only helps students *with* records; SLIFE often have none. |
| 4 | **Placement copilot for counselors**: AI drafts the intake summary, placement options under state rules, and required paperwork | Emerging | Targets the paperwork burden the teacher described. Human decides. |

### B. Place: make better placement decisions
| # | Solution | Evidence | Notes |
|---|---|---|---|
| 5 | **"Place by age, support by need" protocol**: default to age-appropriate grade plus intensive support, instead of placing students down | Analogy (strong) | Grade-retention research: across 17 studies, retention was associated with dropout (Jimerson, 2001). This is retention research, not newcomer research; placing a 17-year-old in 9th grade is an analogy. |
| 6 | **State placement guidance and benchmarking**: a common protocol plus district comparisons | Moderate (need) | Springfield vs. Boston: a 38-point gap in 9th-grade placement for similar older newcomers (Annenberg/DESE, 2026). Mainly a policy or nonprofit play. |
| 7 | **30-day placement review**: an automatic re-check after the first month | Emerging | Cheap. It fixes wrong first guesses, and roughly half of newcomers arrive mid-year. |

### C. Accelerate: help students progress once placed
| # | Solution | Evidence | Notes |
|---|---|---|---|
| 8 | **High-dosage tutoring, bilingual, during school** | **Strong** | Meta-analysis: pooled effect 0.29–0.37 SD. Largest when held **during school**, ≥3 days/week, with teachers or paraprofessionals (Nickow, Oreopoulos & Quan, 2020/2024). This matches the teacher's point that self-paced use outside school fails. |
| 9 | **Bilingual educator marketplace**: remote, vetted Haitian Creole, Portuguese, Arabic, Dari (etc.) assessors and tutors, booked by the hour | Strong (tutoring) + Emerging (model) | Solves the bilingual staffing shortage. It's the most venture-like option here. |
| 10 | **Home-language credit by proficiency exam**: earn world-language credits by testing in the home language | Emerging | A quick win for students aged 16+. MA requires 2 world-language credits for MassCore; heritage speakers can earn proficiency credits by testing in some districts. Also opens a path to the **MA Seal of Biliteracy**. |
| 11 | **SLIFE foundational curriculum**, e.g., CUNY's *Bridges to Academic Success* | Emerging | Content exists; implementation support is the gap. |
| 12 | **Newcomer program or school model**, e.g., the **Internationals Network** | Moderate | Cohort study: 63.4% four-year graduation vs. 30.3% for English learners in traditional NYC schools (Fine et al.; not randomized, so selection is possible). |
| 13 | **Career-technical and work-based pathways for older newcomers** | Emerging | Newcomers are underrepresented in career-technical education; **Waltham High** is a bright spot (~25% participating). Many students aged 16+ work. |

### D. Engage families
| # | Solution | Evidence | Notes |
|---|---|---|---|
| 14 | **Automated home-language text alerts to parents**: grades, absences, missed work | **Strong** | Randomized trial: **27% fewer course failures, 12% higher attendance**; stronger for high schoolers (Bergman & Chan, 2021). Cost: $63 for 32,000 texts. |
| 15 | **Weekly one-sentence teacher-to-parent messages** | **Strong** | Randomized trial: students failing to earn credit fell from **15.8% to 9.3% (41%)** (Kraft & Rogers, 2015). |
| 16 | **Two-generation family learning**: parents learn English *at school* while their children attend | Emerging | Tests the teacher's parent insight without building a self-paced app. |

### E. Remove barriers outside the classroom
| # | Solution | Evidence | Notes |
|---|---|---|---|
| 17 | **Flexible scheduling, evening sessions, and case management for working or unaccompanied older newcomers** | Moderate (community-schools research) | About half of MA high school newcomers arrive at 16+, many without parents. Scheduling may matter more than curriculum. |

### F. Infrastructure
| # | Solution | Evidence | Notes |
|---|---|---|---|
| 18 | **Standard intake data layer**: about 10 elements, federated, no immigration status | Moderate (need) | See `data_infrastructure_assessment.md`. Built as a byproduct of #1. |

---

## 2. Scoring (1 = weak, 5 = strong)

| Solution | Evidence | Fits team's problem | Venture viability | Feasible for a student team | **Total** |
|---|---|---|---|---|---|
| #1 Starting-Point Check | 2 | 5 | 4 | 3 | **14** |
| #9 Bilingual educator marketplace | 4 | 4 | 5 | 2 | **15** |
| #14/15 Home-language parent alerts | 5 | 3 | 3 | 4 | **15** |
| #10 Home-language credit by exam | 2 | 4 | 3 | 5 | **14** |
| #8 In-school bilingual tutoring (as a service) | 5 | 3 | 3 | 3 | **14** |
| #2 Math-only diagnostic | 2 | 4 | 3 | 5 | **14** |
| #5/6/7 Placement protocol and review | 3 | 5 | 2 | 3 | **13** |
| #12 Internationals-style model | 3 | 3 | 1 | 1 | **8** |
| Parent English app (from the interview) | 1 | 2 | 1 | 3 | **7** |

---

## 3. Recommendation: a "stack," not a single product

The research points one way: **measure at intake, act during school, and loop in families with short, automated messages in their home language.** No single competitor connects the three.

```
DAY 1            WEEK 1–4                  ONGOING
Starting-Point → Placement + 30-day   →   In-school bilingual tutoring (marketplace)
Check (#1/#2)    review (#7)               Home-language credit by exam (#10)
                                           Parent alerts in home language (#14/15)
      └──────────── intake data layer (#18) feeds all of the above ────────────┘
```

**How to start (the team can do this in one semester):**
1. **Pilot the math-only diagnostic (#2)** with 10–20 newcomers at one school, run by an adult during the school day.
2. **Use each result to trigger two actions:** a placement suggestion, and a home-language text to the parent (#14) explaining it.
3. **Check eligibility for credit by exam (#10)** for every student aged 16+, since it may be the fastest credit win available.
4. **Measure:** placement changes within 30 days, parent reply rate, and credits earned.

**Business path:**
- **Start:** district-paid diagnostic plus parent messaging, funded from English-learner funds.
- **Scale:** the bilingual educator marketplace (#9). Recurring revenue, a strong evidence base, and it solves the staffing gap every district names.
- **Long term:** the data layer (#18) and state benchmarking (#6).

**Drop or park:** the parent English app (low evidence, no payer) and a full newcomer school model (excellent, but it's a school network, not a startup).

---

## Sources

- Nickow, Oreopoulos & Quan, [*The Promise of Tutoring for PreK–12 Learning*, AERJ 2024](https://journals.sagepub.com/doi/abs/10.3102/00028312231208687) · [NBER 2020 version](https://www.nber.org/papers/w27476)
- Bergman & Chan, [*Leveraging Parents through Low-Cost Technology*, J. Human Resources 2021](https://jhr.uwpress.org/content/56/1/125)
- Kraft & Rogers, [*The Underutilized Potential of Teacher-to-Parent Communication*, Econ. of Ed. Review 2015](https://www.sciencedirect.com/science/article/abs/pii/S0272775715000497)
- Jimerson, [*Meta-analysis of Grade Retention Research* (2001)](https://www.researchgate.net/publication/279888141_Meta-analysis_of_Grade_Retention_Research_Implications_for_Practice_in_the_21st_Century) · [NASP summary](https://www.wrightslaw.com/info/fape.grade.retention.nasp.pdf)
- Fine et al., [*The Internationals Network for Public Schools: cohort analysis*](https://web.stanford.edu/~hakuta/Courses/Ed205X%20Website/Resources/The%20Internationals%20Network%20-%20Michelle%20Fine.pdf) · [LPI case study](https://learningpolicyinstitute.org/product/deeper-learning-networks-cs-internationals-network-report) · [Newcomer graduation policy brief](https://files.eric.ed.gov/fulltext/ED605499.pdf)
- [Boston Public Schools, Heritage Language Learning](https://www.bostonpublicschools.org/students-families/world-languages/heritage-language-learning) · [MA DESE World Languages](https://www.doe.mass.edu/worldlanguages/) · [Highline (WA) credit by proficiency example](https://www.highlineschools.org/departments/language-learning/credit-by-proficiency)
- Annenberg/DESE, [*Land of Opportunity?* (2026)](https://annenberg.brown.edu/edopportunity/land-of-opportunity) · [Education Week coverage](https://www.edweek.org/teaching-learning/immigrant-students-face-big-barriers-to-success-in-high-school/2026/08)
