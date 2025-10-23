
# NBA Team Exploratory Data Analysis: Using 2021–22 Metrics as a Predictor of 2022–23 Success

**Goal:** Use team level advanced metrics from the 2021–22 season to understand what best explains following season's outcomes, proxied by 2022–23 win percentages.  

We combine NBA Stats API advanced metrics (offense/defense) with opponent/defensive indicators and an external age feature from Kaggle, then explore correlation structure and targeted interactions.  

**Key questions:**  
- Which 2021–22 factors (e.g., NET_RATING, OFF_RATING, EFG_PCT, DREB_PCT) are most associated with 2022–23 Win %?  
- Do these relationships differ between the East and West?  
- Do domain-motivated interactions (e.g., shooting × rebounding, pace × opponent efficiency) add signals to future performance?

Note: This notebook uses public APIs (`nba_api`) and one Kaggle dataset; we aim to annotate each step for clarity as a documention of thought process.
