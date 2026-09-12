## Cemre Akkaya

Commercial and revenue leader across 60+ markets. I build the AI systems that run the revenue engine.

A decade in commercial operations: brand and market expansion at British American Tobacco, B2B and distribution at GMG, now Head of Marketing and Revenue at Desertcart, a cross-border ecommerce platform. The last two years I've spent building AI systems on top of that work, mostly to replace the parts of the job that shouldn't need a human.

- Website and case studies: https://cemreakkaya.com
- LinkedIn: https://www.linkedin.com/in/cemreakkaya

Most of what I build is private client and operational work. What's here is clean-room: rewritten from scratch on my own machine, business logic stripped, design decisions kept.

**Agent infrastructure**
- [approval-loop](https://github.com/cemre-akkaya/approval-loop): LLM agents that *propose* typed actions instead of executing them. Vocabulary lock, schema validation, human approval queue with evidence, reversible handler dispatch, outcome feedback. Ships a coverage audit that tells you what fraction of your agent's proposals would actually execute. Mine was 5%.
- [signal-scorer](https://github.com/cemre-akkaya/signal-scorer): weighted multi-signal ranking with the eligibility gate kept separate from the score.

**Analytics & diagnosis**
- [stepchange](https://github.com/cemre-akkaya/stepchange): a metric moved last week, which deploy did it? Step-change detection correlated against merged commits.
- [cohort-kit](https://github.com/cemre-akkaya/cohort-kit): retention/LTV battery over a generic orders table, with the definitional traps documented.
- [returns-radar](https://github.com/cemre-akkaya/returns-radar): returns abuse and product-quality detection from free-text return reasons.

**Reporting plumbing**
- [sheets-report-kit](https://github.com/cemre-akkaya/sheets-report-kit): Google Sheets/Slides automation that doesn't destroy your charts. Zero dependencies.
- [report-pipeline](https://github.com/cemre-akkaya/report-pipeline): collector to report to output, with self-healing backfill.

**Personal automation**
- [ai-chief-of-staff](https://github.com/cemre-akkaya/ai-chief-of-staff): eight Claude Code skills that run my actual daily/weekly PA rhythm. One priority, not a list — every skill is built around picking one thing and saying it plainly.
