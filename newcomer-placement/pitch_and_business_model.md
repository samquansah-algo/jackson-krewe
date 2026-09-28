# Part 4: 60-Second Pitch, PG/Altman Revision, and Business Model

**Working name:** *Passage*, a placeholder. Check the trademark before you use it publicly.
**Status:** draft for class. Anything in `[brackets]` or marked **(verify)** needs a real source or real data before you present it.

---

## 1. Reusable prompt: build a YC-standard elevator pitch

Paste this into Claude (or any LLM). Fill in the `{{ }}` fields.

```text
You are a Y Combinator group partner who has heard thousands of pitches. Help me write a
60-second spoken pitch (115–125 words, read aloud at ~125 words per minute).

MY VENTURE
- Problem (who hurts, how often, what it costs them): {{problem}}
- Specific person with the problem (a real or clearly labeled composite story): {{user_story}}
- Solution (what the user actually experiences, step by step): {{solution}}
- Why now (what changed: technology, policy, or behavior): {{why_now}}
- Proof so far (users, pilots, letters of intent, time saved; say "none" if none): {{traction}}
- Who pays, how much, and from which budget: {{business_model}}
- Insight competitors miss: {{insight}}
- Ask / close: {{ask}}

RULES
1. The first sentence must tell a stranger what we do and for whom. No build-up.
2. Plain words a 12-year-old understands. Banned words: platform, leverage, ecosystem,
   holistic, seamless, revolutionize, AI-powered, solution, stakeholders, empower.
3. Describe what the user experiences, not a feature list. Maximum 3 product nouns.
4. Every adjective must be replaceable with a number. If I gave you no number,
   write [NUMBER NEEDED]. Never invent statistics, partners, or traction.
5. Include exactly one concrete human moment (a named or composite person).
6. Say who pays and why it's cheaper than what they do today.
7. End on momentum (traction, the next milestone, or the ask), not a slogan.

PROCESS
Step 1: Write 3 variants: (A) story-led, (B) number-led, (C) insight-led.
Step 2: Critique each variant twice:
   - As Paul Graham: Is it clear? Is it something people want badly? Is it narrow
     enough to win? Would a smart outsider understand it on first hearing?
   - As Sam Altman: How big can this get? Why now? Is there a compounding advantage?
     Is the growth metric obvious?
Step 3: Score each variant 1–5 on: Clarity, Urgency, Specificity, Credibility,
   Business model, Memorability. Show the table.
Step 4: Merge the best parts into one final pitch. Report the word count and the
   estimated spoken time.
Step 5: List every factual claim in the final pitch that I must verify before I present,
   and the one question an investor is most likely to ask right after.
Step 6: Give me a 1-sentence version (the "what do you do?" answer, under 20 words).
```

---

## 2. The revision: Paul Graham and Sam Altman review the idea

> These are role-played critiques in the style of each person's published essays and talks. They are not their actual views.

### Paul Graham

1. **"You've described eight products."** Intake, document capture, curriculum mapping, diagnostics, recommendations, human review, family reports, cohort dashboards: that's a roadmap, not a startup. Pick the one thing someone desperately wants and do it better than anyone.
2. **"Who wants this most?"** Families have the pain but not the budget or the decision. Nonprofits have the time cost but small budgets. The **school counselor or registrar** makes the placement call, and the **district** pays. Build for the person whose "yes" changes the outcome.
3. **"Where is the pain sharpest?"** In elementary school, placement mostly follows age, so a wrong call is fixable. **High school is where it hurts.** Credits decide graduation, and a 17-year-old placed in 9th grade with zero credits may age out before finishing. Start with newcomers aged 14–21 and the credit question.
4. **"'Guidance, not placement' is honest, but it's only worth something if the school accepts it."** The product isn't a recommendation. It's a **recommendation the registrar signs**. Design the output to fit the district's own credit-evaluation form.
5. **"Do things that don't scale."** Before you write code, personally do 30–50 evaluations with one nonprofit and one district, using WhatsApp, Google Forms, and a spreadsheet. Measure credits recognized, hours saved, and how often the school accepted your recommendation. That's your pitch's proof.
6. **"This is a schlep, and that's good."** Messy documents, 40 languages, 50 state credit rules, district politics. Most founders avoid this kind of work, and that avoidance is your opening.

### Sam Altman

1. **"Why now? AI."** Until recently, translating a Dari transcript and mapping it to Massachusetts course codes needed a specialist, cost ~$100–$250, and took weeks (the range foreign credential evaluators charge; verify). Models can now read, translate, and draft that mapping in minutes for a few dollars. A human reviewer is still needed, but for 20 minutes instead of 4 hours.
2. **"What compounds?"** Every evaluation adds to an **equivalency map**: country × school system × grade × subject → local course and credit. School acceptance decisions feed back in. After 10,000 transcripts you have a dataset nobody else has, and reviewer time keeps falling. That's the moat.
3. **"The first market is small. That's fine if it leads somewhere big."** The wedge is newcomer high schoolers. The larger market is **every student whose learning doesn't transfer cleanly**: migrant, foster, military-connected, and domestic transfer students in the US, then newcomers in Canada, the UK, Germany, and Australia, then international schools. The end state is a **portable academic passport** for the world's mobile children.
4. **"Pick one growth number and report it weekly."** Suggested north star: **school-accepted recommendations per week**. Supporting numbers: credits recognized per student, turnaround time, and reviewer minutes per evaluation.
5. **"Watch the policy risk."** US refugee admissions and immigration flows can swing sharply with federal policy. Don't build on one inflow channel. Sell to districts, which enroll all newcomers regardless of how they arrived, and expand internationally early.
6. **"Trust is the product."** This population is vulnerable. Never collect immigration status. Minimize data, delete on schedule, and operate under FERPA as the district's contracted "school official." A privacy failure would end the company.

### Where they agree: the revised solution

> **Passage turns a newcomer high schooler's prior schooling (a photo of a foreign transcript, or a short interview and diagnostic when records are missing) into a counselor-ready credit and course recommendation within 48 hours, reviewed by a trained human and explained to the family in their language.**

| Original scope | Revised MVP | Later |
|---|---|---|
| All grades | **Ages 14–21 (high school credit)** | K–8 placement |
| 8 modules | **One flow:** capture → AI map → diagnostic → human review → two outputs | Full cohort analytics |
| Generic recommendation | **District-form-ready credit packet** plus a home-language family summary | Official state-recognized evaluations |
| Web app | Mobile web plus **WhatsApp intake** (how families already communicate) | Native app |
| Nonprofit dashboard | Simple case list for caseworkers | Cohort dashboards, outcome tracking |
| Diagnostics for everyone | Diagnostics **only where records are missing or thin** (students with interrupted formal education) | Adaptive diagnostics |

**What stays from the original:** multilingual, mobile-first, human review, family-ready reports, guidance rather than official placement. The difference is that it's now built to be *accepted*.

---

## 3. Business model

### Who does what

| Role | Who | What they get | Pays? |
|---|---|---|---|
| **User** | Newcomer student and family | Credit for past learning, and a plan they understand | **Never pays** |
| **Champion / distribution** | Nonprofits, resettlement and community orgs | Hours saved, better outcomes for their clients | Free tier (philanthropy-funded), then a small license |
| **Decision-maker** | Counselor, registrar, newcomer-center staff | A ready-to-sign evaluation | — |
| **Economic buyer** | District multilingual/EL director | Faster, defensible placements; less staff time; better graduation rates | **Yes** |
| **Scale buyer** (Year 2+) | State education agencies | Consistent statewide equivalency standards | **Yes** |

### Pricing (hypotheses to test)

- **Per evaluation:** **$120 per completed student evaluation** (district-paid).
- **District annual license** (includes evaluations plus the caseworker/counselor workspace):
  - Small (≤75 newcomers/yr): **$8,000**
  - Mid (≤250): **$20,000**
  - Large (250+): **$45,000+**, custom
- **Nonprofit:** free during pilots, then **~$2,400/site/yr**, with the cost offset by grants.
- **State:** licensing of the equivalency map, plus training and reporting, **$150k–$500k/yr** (Year 2+).

**Possible funding sources for districts (verify with each district's federal-programs office):** Title III, including the immigrant children & youth subgrant under ESSA §3114(d); Title I; and local general funds. Title III's definition of "immigrant children and youth" (ages 3–21, not born in the US, fewer than 3 full academic years in US schools) matches this customer almost exactly.

### Why the price is easy to justify (value anchor)

| Today's cost (per student) | Estimate |
|---|---|
| Counselor/registrar time to reconstruct records | 3–6 hrs × ~$60 loaded = **$180–$360** (verify locally) |
| One unnecessarily repeated semester | ~½ of per-pupil spending ≈ **$7,000–$9,000** of public money (US average per-pupil spending ≈ $15–18k; verify for your state) |
| Private foreign-credential evaluation (built for college, not K-12) | **~$100–$250**, weeks of turnaround (verify) |

**Pitch line:** we cost less than the staff time we replace, and much less than the semester we prevent.

### Unit economics (per evaluation, illustrative)

| Line | Year 1 | Year 3 (as the map matures) |
|---|---|---|
| AI extraction, translation, mapping | $3 | $1 |
| Human reviewer (45 → 15 min at $35/hr) | $26 | $9 |
| Diagnostic, hosting, secure storage | $2 | $1 |
| Support and QA | $6 | $3 |
| **Cost of goods sold (COGS)** | **~$37** | **~$14** |
| Price | $120 | $120 |
| **Gross margin** | **~69%** | **~88%** |

### Market size (build it bottom-up; don't quote a top-down TAM)

- **Wedge (US, newcomers aged 14–21):** `[N newcomers aged 14–21 entering US public schools per year]` × $120. Get N from state Title III immigrant-student counts (verify). This market is small, probably tens of millions of dollars.
- **US expansion:** add migrant, foster, military-connected, and cross-state transfer students. Credit loss on transfer is a known problem for all of them. That's millions of mobile students a year (verify).
- **Global:** newcomer systems in Canada, the UK, Germany, Australia, and the Nordics, plus international schools and relocating families (who can pay directly).
- **Venture framing:** the $120 evaluation is the wedge. The asset is the **equivalency map plus acceptance data**, which becomes the credit-transfer infrastructure for mobile students.

### Go-to-market sequence

1. **Months 0–3 (don't scale):** 1 nonprofit and 1 district. 30–50 evaluations done largely by hand. Record acceptance rate, credits recognized, and hours saved. Free.
2. **Months 3–9:** 3 paid district pilots (~$8k each), timed to spring budget planning for July 1 fiscal years. 300–500 students.
3. **Year 2:** 15–25 districts across 2–3 states, and the first state-agency conversation. Nonprofit network as the referral engine.
4. **Year 3+:** adjacent mobile-student populations; first international market.

**Capital strategy:** blended. Philanthropy funds the family-free and nonprofit tiers, and district revenue proves demand. Consider a **Public Benefit Corporation** so the mission is protected and venture investment is still possible. PG's warning: grants are not customers, so don't let grant-writing replace selling.

### Metrics

- **North star:** school-accepted recommendations per week
- Credits recognized per student vs. the district's historical baseline
- Turnaround time (target ≤48 hrs)
- Reviewer minutes per evaluation (should fall every quarter)
- Family comprehension (teach-back check in home language)
- 12-month outcome: student on track to graduate

### Top risks

| Risk | Mitigation |
|---|---|
| Schools ignore recommendations | Co-design output with registrars; match district forms; track acceptance rate from day one |
| Wrong recommendation (AI error, bias by country) | Human sign-off on every case; confidence flags; per-country accuracy audits |
| Privacy breach / fear of immigration exposure | Never collect status; FERPA "school official" contracts; state student-privacy compliance; data minimization and deletion |
| Slow district sales cycles | Enter via nonprofits; small pilots under procurement thresholds; sell in budget season |
| Policy swings in immigration flows | Sell to districts (all arrival routes); diversify to other mobile students and other countries |
| No records at all | Structured interview plus diagnostic, aligned with state credit-by-exam / competency-based credit rules |

---

## 4. The 60-second pitch

### Version B: PG/Altman-sharpened (recommended), 121 words

> A sixteen-year-old arrives from Guatemala with nine years of school. She leaves the registrar's office as a ninth grader with no credit, because her transcript is in Spanish and nobody has time to decode it. Students like her repeat classes they've passed, and many age out before graduating.
>
> Passage turns a phone photo of a foreign transcript into a counselor-ready credit recommendation in 48 hours. AI reads and maps the record to state course requirements, a short diagnostic fills the gaps, and a trained reviewer signs off. Families get the result in their own language.
>
> Districts pay per student, less than the staff hours it replaces. We're piloting with [partner] and [district] this fall, and every transcript makes our map smarter.

### Version A: faithful to the assignment's full solution, 125 words

> When newly arrived students enroll in a new school, their past education rarely comes with them. Records are in another language or missing, so schools guess. Students land below or above their readiness, repeat what they have mastered, and families can't follow the decision. Nonprofit staff spend hours rebuilding histories by hand.
>
> Passage is a multilingual, mobile-first platform that translates a child's prior schooling into a clear academic starting point. Families complete guided intake and snap photos of records and coursework. We map them to local grades, courses, and credits, add a short diagnostic, and a trained reviewer checks every recommendation. Families get a report in their language; nonprofits get a cohort dashboard.
>
> We don't replace the school's decision. We make it an informed one.

### One-liner (for "So what do you do?")

> **We help newcomer high schoolers get credit for the school they've already done.**

### Before you deliver it

- The Guatemala student is a **composite**. Replace her with a real story (with permission, details anonymized) or say "imagine."
- Fill in `[partner]` and `[district]` only with real commitments. If you have none yet, close with: *"We're doing our first 30 evaluations by hand with a local nonprofit this month."*
- Rehearse at ~125 words per minute and time it. Stop at 60 seconds.
- Expect this question: *"Why would a district trust your recommendation?"* Answer: human reviewer sign-off, the output matches their form, and we track the acceptance rate.
