# Sean O’Donnell’s AI workflow for consulting

_Course working guidance. Synvitta examples below; method is engagement-agnostic._

## Core principle

AI is weakest where consulting adds the most value.

Use AI to expand thinking, supply specialist capacity, execute analysis, and improve the form of
communication. Keep human ownership over prioritization and synthesis: deciding what matters,
exercising judgment, integrating conflicting evidence, and choosing the recommendation.

## Where AI is best in the process

1. **Define — AI as thought partner.** Challenge the problem statement, distinguish symptoms from
   causes, expose assumptions, generate alternative framings. The consultant owns the final definition.
2. **Disaggregate — AI as thought partner.** Propose issue-tree branches, hypotheses, missing
   questions, MECE tests. The consultant checks fit to the client’s situation.
3. **Prioritize — you.** Decide which branches matter and what the team will not pursue.
4. **Work-plan — AI as virtual expert.** Translate prioritized questions into analyses, data needs,
   owners, sequencing, milestones, quality checks. *(Only after prepare gate / explicit ask.)*
5. **Analyze — AI as virtual expert.** Specific professional role + verifiable deliverable. Verify
   sources, formulas, units, definitions, assumptions.
6. **Synthesize — you.** Integrate findings, resolve contradictions, choose the recommendation.
7. **Communicate — AI as virtual expert.** Turn synthesis into exhibits, memos, slide language, Q&A.

## Six prompt controls, then iterate

A strong prompt is a controlled work order, not a topic.

1. **Role** — thought partner, RUO diagnostics GTM expert, skeptical reviewer, etc.
2. **Context** — audience, decision, governing files, time horizon, outs
3. **Task** — a deliverable, not a topic
4. **Constraints** — length, exclusions, confidence flags (for Synvitta: RUO only; no FDA / forecast / national sizing)
5. **Format** — table, memo, issue tree, canvas, 90-day plan, etc.
6. **Examples** — show the shape you want

Then iterate: inspect, tighten the weakest control, rerun. Do not merely ask to “make it better.”

## Applied to Synvitta (prepare)

### Thought-partner prompt (define)

> You are a skeptical strategy-consulting thought partner. Synvitta needs a first foothold for RUO
> thyroid and syphilis assays. Using only `Synvitta-Case-Background.md` and
> `PrimarySources/CORE-INFORMATION.md`, propose three materially different definitions of the
> underlying market-entry problem. For each: implied issue-tree branches, evidence that would
> falsify it, and what recommendation space it opens or closes. Do not pick the opportunity or
> customer. Do not write a 90-day plan. No FDA, forecast, or national TAM. Return a draft table:
> framing / assumptions / what we would measure — and one question for the client.

### Virtual-expert prompt (evidence gather)

> You are a research-use diagnostics commercial expert. Build an account-level evidence pack for
> possible first customers of Synvitta’s RUO thyroid and syphilis assays. Use only sources in
> `PrimarySources/` plus clearly tagged public retrieves. Output: updates to CORE-INFORMATION and
> rows for `Research/customer-longlist.md`. Tag every line RETRIEVED or ESTIMATED. Do not rank a
> winner. No national market sizing.

### Plan/solve prompt (only after prepare gate)

> You are a market-entry consultant. Using Framing + Research + PrimarySources, recommend exactly
> one opportunity and one customer for Synvitta’s RUO thyroid/syphilis assays, explain how they
> enter, and produce a 90-day plan with kill criteria. Appendix: killed alternatives. No FDA filing
> strategy, no financial forecast, no national TAM.

### Human-controlled synthesis questions

- Which finding changes the recommendation?
- What evidence is strong enough to put in front of Synvitta?
- What trade-off are we choosing (assay focus, account type, access path)?
- What must be true for the 90-day plan to work?
- What are we unwilling to claim?

AI can help answer and challenge these. The team owns the answers.
