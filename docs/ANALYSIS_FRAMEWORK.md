# Country-Based App Opportunity Analysis Framework

## Purpose

Turn a country (and, where needed, a city or region) plus founder constraints into an evidence-led shortlist of business opportunity domains and app concepts worth validating. The framework helps select what to investigate; it does not guarantee profitability or replace interviews, legal advice, or market-specific expertise.

## Principles

- Start from a country and a customer problem, not a preselected app category.
- Treat desk research as hypotheses. A statistic about a market is not proof that a particular buyer wants a product.
- Separate facts, customer statements, observed behavior, estimates, and assumptions.
- Cite every material market claim with a source, publication date, geography, and access date.
- Consider direct competitors, indirect alternatives, and the status quo, including manual work and doing nothing.
- Score the evidence and the opportunity separately. Unknowns must not look like negative evidence or false precision.
- End with a test that can change the recommendation.

## Inputs

Required:

- Country and analysis date.

Useful constraints (record as unknown when not provided):

- City/region, target language(s), B2B/B2C preference, founder skills and relevant access, budget, time to first test, preferred revenue model, and excluded industries or regulated activities.

Do not silently fill missing founder constraints with assumptions. Produce a general market scan where they are unknown and flag concepts whose feasibility depends on them.

## Analysis stages

### 1. Establish the country context

Build a compact country profile relevant to software businesses: population and urbanization where useful, connectivity and device access, language, common payment methods, business formality, logistics, purchasing power proxies, relevant regulation, and regional differences. Select only indicators that could affect a customer workflow, willingness to pay, delivery, or market access. Record the reference period; do not mix years without saying so.

Use a PESTLE-style scan (political, economic, social, technological, legal, environmental) as a checklist for external conditions, not as a substitute for customer research. Mark each factor as relevant or not relevant to candidate domains.

### 2. Identify customer segments and jobs

Map concrete customer groups and workflows. For each, specify:

- User, buyer, budget owner, and decision process (they may differ).
- The job the customer is trying to complete, in what situation, and how often.
- Recent pain: urgency, frequency, time/money lost, errors, risk, or missed revenue.
- Current alternatives: named products where discoverable, staff, spreadsheets, messaging, paper, cash, informal networks, or inaction.
- How to reach a first group of ten plausible interviewees.

Use Jobs to Be Done language to describe the customer's progress and Value Proposition Canvas categories (jobs, pains, gains) to keep the problem and proposed value connected. Do not infer a job solely from demographic labels.

### 3. Build an evidence ledger

For each claim, record its exact claim, evidence type, source title and URL, publisher, publication date, data period, geography, access date, and notes on limitations. Evidence types:

1. **Primary/official data:** statistics agencies, central banks, regulators, official datasets, laws, company filings, and direct observation.
2. **Credible secondary research:** transparent methods and identifiable sample/geography.
3. **Market signals:** search interest, app listings/reviews, job postings, procurement, directories, prices, and competitor messaging. Signals suggest activity; they rarely establish demand by themselves.
4. **Customer discovery:** interview statements, observed workflows, artifacts, and behavior-based commitments. State sample size and recruitment method.
5. **Estimate or assumption:** explicit method, inputs, range, and what would invalidate it.

Prefer local and primary sources for country-specific claims. Cross-check important claims when independent sources exist. Keep evidence at the claim level, including contrary evidence. Use a consistent freshness note: explain why older data remains relevant or seek a newer source.

### 4. Find and describe opportunity domains

Cluster recurring pains into domains such as a customer group plus workflow, not generic sectors such as “tourism” or “AI.” A domain should have a defined population, problem pattern, likely buyer, and plausible entry point. For each domain, summarize supporting evidence, counterevidence, substitutes, country fit, regulatory/dependency risks, and the key unknown.

Estimate market size only to the precision supported by data. Prefer a transparent bottom-up range (reachable number of buyers × plausible annual spend) and state assumptions. TAM/SAM/SOM may be used as labels for total, serviceable, and initially obtainable markets; do not use global TAM as a proxy for local demand or invent precise market shares.

### 5. Generate app concepts

Generate a small number of concepts for the best-supported domains. Each concept must name:

- Target user and paying buyer.
- Triggering situation and job.
- Current workaround and its measurable cost.
- Proposed software-enabled outcome and why it may be better.
- Core workflow (what the user actually does in the app).
- Revenue hypothesis, pricing basis, acquisition channel, and delivery/support costs.
- Local requirements: language, connectivity/offline use, payment, data handling, regulation, and integrations as relevant.
- Alternatives and a specific differentiation hypothesis.
- Riskiest assumption and the cheapest useful test.

Use Value Proposition Canvas to check problem-solution fit and Business Model Canvas to check how the offer could create, deliver, and capture value. These canvases are hypotheses to test, not validation badges.

### 6. Apply gates before comparing

First check reachability, problem significance, the sufficiency of free/current alternatives, required access and trust, proportional delivery economics, and legal/platform/privacy/security/ethical risks. A failed fatal gate blocks the current framing; an unresolved fatal unknown keeps the build boundary closed. Do not let high scores compensate for a fatal problem.

Then define the decision objective (for example, first customer quickly, specialist B2B entry, or low-maintenance income) and select criteria and weights that fit it. Use anchored scores, normally 0–4, with evidence IDs and a support confidence for each rating. Use ranges when evidence is uncertain and `Unknown` when evidence is absent. Do not import fixed universal weights.

For exact ratings, calculate `sum(weight × score) / sum(weights)`. Keep evidence support separate; never multiply the opportunity score by confidence and present the result as a success probability. Test whether reasonable changes in weights or unknown ranges change the winner. Report a robust winner, fragile winner, tie, or insufficient evidence to rank. See the [scoring reference](../framework/references/scoring-model.md) and use its deterministic helper when useful.

Keep confidence tied to evidence quality and applicability, not optimism. Evidence coverage does not turn a hypothesis into a fact.

Decision gates after screening:

- **Research candidate:** plausible pain and a reachable customer group; enough evidence to write a testable hypothesis.
- **Interview:** conduct problem interviews before pitching a solution; ask about the last occurrence, steps, frequency, cost, workaround, prior spend, and decision maker.
- **Pilot candidate:** interviews confirm a recurring costly problem and behavior-based tests show a credible willingness to act/pay. Define thresholds before running a test.
- **Build consideration:** repeatable evidence supports a valuable workflow, buyer, delivery path, and viable economics. The app is a delivery choice, not the goal.

No score alone advances an idea. A high score with low evidence coverage is a research priority, not a build recommendation.

### 7. Recommend experiments and a decision

For each leading idea, state the riskiest assumption, experiment, target participant count, method, time/cost, success threshold, failure threshold, and next action for each result. Prefer tests of current behavior and concrete commitment over “Would you use this?” surveys. Examples include workflow observation, concierge/manual service, landing-page signups with qualified prospects, price/offer tests, or a paid pilot offer.

Finish with a ranked shortlist, explicit “why now/why here” evidence, top risks, unresolved questions, and one next action. Keep desk-research conclusions labeled unvalidated until customer evidence changes their status.

## Output contract

Every report follows [the analysis template](ANALYSIS_TEMPLATE.md). Include an “as of” date and a source list. The first page should make clear:

1. What country/region and founder constraints were analyzed.
2. Which domains rank highest and why.
3. Which app concepts merit customer discovery (not automatic development).
4. What evidence would change the ranking.

## Business standards and references

- **Market and competitor research:** U.S. Small Business Administration, [Market research and competitive analysis](https://www.sba.gov/business-guide/plan-your-business/market-research-competitive-analysis). Its categories (customers, competition, market trends, barriers) are useful as a checklist; country-specific research must use relevant local sources.
- **Business model:** Strategyzer, [Business Model Canvas](https://www.strategyzer.com/library/the-business-model-canvas), a structured view of customers, value proposition, delivery, partners, costs, and revenue.
- **Customer/problem fit:** Strategyzer, [Value Proposition Canvas](https://www.strategyzer.com/library/the-value-proposition-canvas), which connects customer jobs, pains, and gains to an offer.
- **Experiment design:** Strategyzer, [How to design a strong experiment](https://www.strategyzer.com/library/design-experiment-that-connects-to-your-value-proposition-canvas) and [start with critical hypotheses](https://www.strategyzer.com/library/how-to-test-your-idea-start-with-the-most-critical-hypotheses).
- **Initial evidence discipline and country example:** the [World Bank Enterprise Survey](https://www.enterprisesurveys.org/), [INS Tunisia statistics](https://www.ins.tn/), AfricanNenda [SIIPS research](https://www.africanenda.org/), and [UNECA](https://www.uneca.org/). These are source families/examples, not automatic endorsements of any app concept.

These methods provide structure, not universally binding certification standards. Adapt the evidence sources and legal review to the selected country and industry.

## Existing framework adapted

The operational workflow and helper tools in [`framework/`](../framework/SKILL.md) are adapted from [highstat/product-opportunity](https://github.com/highstat/product-opportunity), an MIT-licensed Codex skill for evidence-led software opportunity discovery and validation. Its claim/evidence ledger, fatal gates, first-customer route, confidence-aware scoring, and experiment learning are the core decision system here. This repository adds the country-first market scan and a domain-to-app discovery layer. Copyright and license notice are retained in [`framework/LICENSE`](../framework/LICENSE).
