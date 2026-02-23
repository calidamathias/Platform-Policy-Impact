# Policy Evaluation (RD + DiD + Fixed Effects)

## Business Question
Did a policy/intervention causally change outcomes, and how can we estimate impact without randomization?

## Data
Panel-style and cutoff-based datasets suitable for quasi-experimental designs (Quarto/R workflow).

## Methods (What I did)
- **Regression Discontinuity (RD):** causal effect at a threshold/cutoff
- **Fixed Effects (FE):** control for time-invariant unit differences
- **Difference-in-Differences (DiD):** compare treated vs control trends over time
- **Diagnostics:** RD continuity checks + DiD parallel trends logic

## Deliverable
- `report.qmd`: full Quarto report with results + assumption checks

## Reproduce
Open `report.qmd` in RStudio → click **Render**  
or run: `quarto render`

## Keywords
RD, DiD, Fixed Effects, quasi-experiments, causal inference
