# Decision Lab 1: GitHub Data Audit and Decision Framing

## Purpose

Welcome to **Dr. K's Late-Night Analytics Cafe**, where the coffee is statistically significant, the brownies are overfit, and validation rules were apparently considered optional.

Your team will audit a deliberately messy business dataset and decide whether it is trustworthy enough to support decisions about location, product promotion, and service capacity. You must use an approved AI tool, but your team remains responsible for every cleaning decision, calculation, visualization, and recommendation.

This is not a contest to see which AI produces the most confident paragraph. It is an exercise in deciding what evidence deserves to be trusted.

## Schedule and submissions

### In-class first draft — 25%

**Due:** September 9 by **8:45 p.m.**

Submit the URL of your team's working repository in Harvey before leaving class. This is a graded first draft, not merely a progress check.

Dr. K will aim to provide brief feedback by the next day. Continue improving the project even if feedback is delayed; feedback is formative and may not identify every issue.

### Improved final submission — 75%

**Due:** September 15 by **11:59 p.m.**

Submit the repository URL in Harvey again after completing and verifying the final version. Every team must submit a final version. If your team concludes that its first draft already represents its best work, you may submit the same version, but include a short finalization note explaining why no changes were necessary.

## Part 1 — In-class first draft

**Available class time:** approximately 60 minutes.

### Required work

1. Create one team repository with folders for raw data, cleaned data, analysis, AI use, and the report.
2. Add the original workbook to `data/raw/`. Never overwrite the raw file.
3. Document team roles and responsibilities in the repository README.
4. Conduct a 10-minute human-first inspection before consulting AI.
5. Record at least five observations about missing values, duplicates, invalid values, inconsistent labels, outliers, or unclear fields.
6. Identify the decision-maker, decision, outcome measure, three analytical questions, and two risks created by poor-quality data.
7. Use AI to propose additional quality checks and a cleaning plan.
8. Classify material AI suggestions as **accepted**, **modified**, **rejected**, or **not testable**.
9. Complete at least three quality checks and make at least three meaningful commits.

### First-draft checkpoint

By 8:45 p.m., the repository must contain the raw data, human-first observations, decision statement, AI-assisted audit plan, three completed checks, meaningful commits, and a clear plan for the remaining work.

## Part 2 — Improved final submission

**Suggested work outside class:** approximately 3–5 hours per team.

**Report length:** approximately 4–6 pages, excluding appendices.

Revise, complete, and verify the analysis after the first-draft submission. Address instructor feedback when available, but do not treat it as a complete list of required improvements.

### Data-quality audit

Complete at least eight checks covering at least five of these categories:

- Completeness
- Uniqueness
- Validity
- Consistency
- Accuracy or reasonableness
- Timeliness
- Join or identifier integrity
- Outliers and influential observations
- Documentation and field definitions

For every material cleaning decision, document:

- the original problem;
- the records affected;
- the action taken;
- the justification;
- the possible analytical effect; and
- the verification method.

### AI red-team requirement

Identify at least two AI suggestions that were incomplete, unsupported, inappropriate, or potentially misleading. For each suggestion:

1. Show the prompt and relevant recommendation.
2. Explain why it required scrutiny.
3. Test it using the data or another reliable method.
4. Accept, modify, or reject it.
5. Explain what could have gone wrong without verification.

### Decision analysis

Answer at least three decision-focused questions and include:

- three traceable numerical findings;
- one comparison across groups, periods, or categories;
- one appropriate visualization;
- one evidence-based recommendation;
- one important limitation; and
- one conclusion the data cannot responsibly support.

## GitHub and final deliverables

Your final repository must include:

- a clear README;
- original and cleaned data stored separately;
- reproducible analysis files;
- a final report and completed AI-use log;
- at least eight meaningful commits;
- contributions from at least two team members;
- at least one branch and pull request; and
- a finalization note summarizing improvements or explaining why no changes were necessary.

Never commit passwords, API keys, private data, or unnecessary AI transcripts.

## Grading rubric — 100%

| Criterion | Weight |
|---|---:|
| In-class first draft | 25% |
| GitHub organization and reproducibility | 15% |
| Data-quality audit and cleaning | 20% |
| Decision-focused analysis | 15% |
| AI use, red-teaming, and verification | 10% |
| Recommendation and limitations | 10% |
| Report and visual communication | 5% |
| **Total** | **100%** |

The rubric uses percentages so the assignment can be mapped to any point value in Harvey without rewriting the assignment.

## Final advice

If the dataset looks perfectly clean after five minutes, your team is probably not done looking.

AI may suggest the cleaning plan, but it does not get to testify as an expert witness unless your team can reproduce the evidence.
