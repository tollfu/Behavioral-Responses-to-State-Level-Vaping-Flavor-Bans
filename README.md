# Behavioral-Responses-to-State-Level-Vaping-Flavor-Bans
This project evaluates the causal impact of state-level e-cigarette flavor bans on vaping and related substance use behaviors among individuals under 30, using BRFSS data from 2016 to 2023. I replicate and extend prior literature by incorporating newly available years of data, introducing mental health heterogeneity, and implementing multiple robustness checks.

Using a two-way fixed effects difference-in-differences framework with state and year fixed effects, I find that flavor bans are associated with a statistically significant reduction in current vaping. However, this effect is not uniform across individuals. Subgroup analysis reveals that reductions in vaping are largest among individuals reporting good mental health and diminish among those experiencing frequent mental distress, suggesting reduced policy responsiveness among psychologically vulnerable populations.

I further examine potential spillover effects to other substances. Results indicate statistically significant increases in combustible cigarette use and chewing tobacco use following flavor bans, consistent with behavioral substitution. No significant spillovers are detected for binge drinking or marijuana use.

To assess robustness, I implement event-study specifications to examine dynamic treatment effects and test the parallel trends assumption. While the difference-in-differences results remain stable across OLS, logit, and post-double-selection Lasso specifications, event-study estimates reveal sensitivity to limited time variation and staggered treatment timing.

Overall, the findings suggest that while flavor bans reduce vaping on average, they may induce substitution toward more harmful nicotine products and exhibit heterogeneous effects across mental health groups. These results highlight the importance of accounting for behavioral heterogeneity and unintended consequences in the design of public health regulations.
