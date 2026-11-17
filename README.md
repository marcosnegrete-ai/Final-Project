Rough Idea：

Introduction: (Peishan)

Data: (Marcos)

Share same original dataset + same data-cleaning rule (Download official data, check variables, complete basic cleaning, and perform the statistical summary for Table 3?)
Original data
Cleaning scripts
Cleaning data
Codebook with cleaning notes

Replication:

Identification method and why: Explain Randomized Field Experiment

Assumptions classification: Explain random assignment, potential outcomes, interference, and identification conditions. (I think we both need to check identification, assumptions, balance and robustness?)

Main results:
Q: Does a White-sounding name increase the probability of receiving a callback?
Table1 - Callback Rates by Race (Peishan?)

Q: Does resume quality change the callback gap between name groups?
Table4 - Resume Quality (Marcos?)

Table2 Additional? - Employer-Level Callbacks (TBD)

Re-analysis: 

Q: Does adjusting for resume characteristics change the estimated effect of name assignment on callbacks?
Analysis1 - Covariate-adjusted ATE (Lin's Regression Adjustment) (Peishan)
- Compare the unadjusted and adjusted estimates in Table 1 of the original paper.

Q: Is the estimated average causal effect consistent across different estimators?
Analysis2 - Doubly Robust / AIPW Estimation (TBD)

Q: Is the causal effect of a White-sounding name larger among higher-quality resumes?
Analysis3 - Heterogeneous Treatment Effects (HTE) (TBD)
- Relate to Table4

Conclusion

Presentation
Planning time: 
Introduction:  2~3min (Peishan)
Data:  2~3min (Marcos)
Replication:  Total 8min (Each one explain one table ~4min)
Re-analysis:  Total 9~10min (Each 4~5min)
Conclusion:  2~3min (TBD)

Slide content: Each person prepares the slidesfor their assigned section and records their own part; then, the team reviews the presentation as a whole to ensure it flows coherently.


Paper content:
we can use Jupyter + github to work on the final report, we can each edit one
file, and then finally combine these separate parts to a complete report paper.
Ex: The main report.qmd will combine all report sections.
Planing:
Contribution: Explain how the two individuals divide their tasks.
Introduction: Research question, conclusions of the original paper, and our objectives 
Data: Data sources, cleaning process, and descriptive statistics
Replication: Experimental design, hypothesis identification, mathematical formulation, reproducibility, robustness
Re-analysis: New method, rationale for its application, calculation results, and comparison of methods
Conclusion: Key findings and research limitations
References / Appendix: Citations, R code, or links to code
