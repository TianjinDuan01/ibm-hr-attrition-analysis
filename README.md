# ibm-hr-attrition-analysis
IBM HR Attrition Analysis — Who Is Leaving &amp; Why

# IBM HR Attrition Analysis — Who Is Leaving & Why

🔗 [View Interactive Dashboard](https://tianjinduan01.github.io/ibm-hr-attrition-analysis/) · [Tableau Public](https://public.tableau.com/app/profile/tianjin.duan/viz/IBMHRAttritionAnalysisWhoIsLeavingWhy/Dashboard1) · [Full Slide Deck (PDF)](./IBM_HR_Attrition_Analysis.pdf)

---

## Overview

An end-to-end analysis of the IBM HR Employee Attrition dataset (1,470 employees, 3 departments, 35 variables), built to answer four questions: **who is leaving, why, what it costs, and what to do about it.**

| Metric | Value |
|---|---|
| Overall attrition rate | 16.1% (237 of 1,470 employees) |
| Estimated annual replacement cost | $13.6M (conservative, 100% salary replacement) |
| Highest-risk segment | Sales × Job Level 1 — 42.1% attrition |

## Who Is Leaving?

- **Sales × Level 1 = 42.1%** attrition — 2.6× the company average, and the single highest-risk intersection in the dataset. Roughly every 2nd–3rd entry-level Sales hire leaves.
- **HR Level 3 = 33.3%**, though on a small team (n<5) so interpret with caution.
- **R&D Level 4 = 1.5%** — the safest zone company-wide.
- By role: **Sales Representative** has the highest attrition rate (39.8%) but only 33 departures, while **Lab Technicians** are more stable (23.9%) yet contributed the most total departures (62) of any role. **Research Director** is the most retained role at 2.5%, suggesting seniority and specialization are protective.
- By age: **18–24** loses nearly 2 in 5 employees (39.2%); attrition falls below 11% after 35 (mid-career stability), then ticks back up to 15.9% at 55+. The **25–34** group is the largest cohort (n=495) at 20.2% attrition — improving retention here would prevent the most departures in absolute terms.

## Why Are They Leaving?

- **Income gap**: employees who left earned ~30% less on average ($4,787 vs. $6,833 for those who stayed).
- **Overtime**: employees working overtime leave at 30.5% vs. 10.4% for those who don't — 3× higher. Single employees on overtime hit 49.6% attrition, nearly 1 in 2.
- **Low income + low job satisfaction** together account for 61% of all departures despite representing only 31% of headcount.
- **Equity matters**: moving employees from Stock Option Level 0 (none) to Level 1 (low) cuts attrition from 24.4% to 9.4% — a 61% reduction, and the highest-ROI retention lever in the dataset. Level 2 is the lowest-risk tier overall (7.6%, n=158).
- **Job satisfaction by role**: Sales Executive has both the most dissatisfied (123) and most satisfied (203) employees — a polarized team and a retention risk. Human Resources shows an even 26/26 split, suggesting structural issues within the team responsible for everyone else's wellbeing.

## What Does It Cost?

Estimated annual attrition replacement cost, assuming 100% of annual salary per leaver (industry-conservative):

| Department | Estimated Cost |
|---|---|
| R&D | $6.6M (133 leavers, above-average salaries) |
| Sales | $6.5M (92 leavers) |
| HR | $0.5M |
| **Total** | **$13.6M** |

At 150% salary replacement (a more realistic figure for specialized roles), the cost rises to $20.4M.

## Recommendations

1. **Intervene at Sales × Level 1 first** — structured mentorship, a clear promotion path, and a compensation review for entry-level Sales staff. Intervention costs far less than repeated replacement.
2. **Audit and reduce overtime for at-risk groups** — identify employees with sustained overtime and low satisfaction, prioritizing single employees on overtime (49.6% attrition). Est. impact: ~65 exits/year avoided, ~$2M saved.
3. **Expand stock option access beyond Level 0** — even minimal equity grants show a measurable, outsized retention effect at low cost.
4. **Invest in early-career retention programs** — structured onboarding with 90-day check-ins, peer mentorship, and visible promotion timelines for employees under 30. The 25–34 group generates the most absolute departures, so gains here have the largest headcount impact.

## Methodology

Built in Tableau Public. The dashboard includes:
- Attrition heatmap by department × job level
- Departure breakdowns by job role (rate vs. absolute headcount)
- Age-group attrition trends
- Income/satisfaction scatter and box plots segmented by attrition status
- Job satisfaction distribution by role
- Stock option level vs. attrition rate trend
- Department-level cost modeling with adjustable salary-replacement assumptions

## Files

- `docs/index.html` — GitHub Pages embed of the interactive dashboard
- `IBM_HR_Attrition_Analysis.pdf` — full slide deck with narrative and findings
