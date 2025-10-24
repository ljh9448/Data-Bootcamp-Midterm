
# NBA Team Exploratory Data Analysis: Using Historical Metrics as a Predictor of Next Season's Success

## Team Members 
1. Solomon Roy:  sr7018@nyu.edu
2. Emiliano Eguez:  ee2488@nyu.edu
3. Lucas Huang:  ljh9448@nyu.edu

## Project Overview
**Goal:** Use team level advanced stats to understand what best explains following season's outcomes. 

We combine NBA Stats API advanced metrics (offense/defense) with opponent/defensive indicators and an external age feature from Kaggle, to explore correlation structures and targeted interactions.  

**Key questions:**  
- Which factors (e.g., NET_RATING, OFF_RATING, EFG_PCT, DREB_PCT) are most associated with future Win %?  
- Do these relationships differ between the East and West?  
- Do domain-motivated interactions (e.g., shooting × rebounding, pace × opponent efficiency) add signals to future performance?

Note: This notebook uses public APIs (`nba_api`) and one Kaggle dataset; we aim to annotate each step for clarity as a documention of thought process.


## Table of Contents
1. Project Overview & Research Question
2. Environment & Imports
3. Team Reference Lists & Display Options
4. NBA Advanced Team Stats (2021–22, Per 100 Possessions)
5. Opponent (Defensive) Team Stats (2021–22)
6. Next Season Outcome Target (2022–23 Win%)
7. External Dataset: Kaggle Player Data → Team Average Age (2021–22)
8. Master Merge: 2021–22 Features + 2022–23 Target
9. Correlation Matrix: Baseline Metrics vs 2023 Win%
10. Key Bivariate Relationships (2022 metrics → 2023 Win%)
11. Engineered Interaction Features (Domain-Motivated)
12. Correlation Matrix: Interaction Terms vs 2023 Win%
13. Conference Split (East vs West): Correlations & Visuals
14. Conference Split: Interaction Terms vs 2023 Win%
15. Outlier/Influential Checks on Selected Interactions
16. Takeaways, Limitations, and Next Steps (Markdown)
