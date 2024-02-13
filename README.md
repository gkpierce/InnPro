# InnPro
Research Relating to U.S. Exonerations and Wrongful Incarcerations

All research conducted by Gavin Pierce, in support of efforts by Nayak Polissar and The Mountain-Whisper-Light consulting firm. 

Data from The National Registry of Exonerations at the University of Michigan is used for research. This data requires agreeing to conditions set forth by the NRE prior to viewing.
This agreement can be found here: 
https://www.law.umich.edu/special/exoneration/Pages/Spread-Sheet-Request-Form.aspx.

Additionally, data from the Bureau of Justice Statsitics has been used for conducting this research. Data from this source spans multiple years and has been employed in a variety of fashions. Specifically, we are using the "Prisoners" data set to track incarcerations by state across years. As an example, the data from 2021 can be found here:
https://bjs.ojp.gov/library/publications/prisoners-2021-statistical-tables

# Research: Exoneration Rate Comparison

Our primary focus here is to develop a method for comparing exoneration rates for U.S. states, with the end goal of identifying the number wrongfully incarcerated individuals who, under ideal conditions, would have been exonerated. To do so, we combined the above data sets to identify the number of exonerations per 100,000 individuals incarcerated. 

# Research: Fitting Models

My attempts to fit collected data to well-established parametric models. Data presents as "count" data and primary goal is comparing rates, so I began with the intuitive step of attempting to fit a Poisson regression model. Subsequent steps involved evaluating this Poisson model against a negative binomial model, as well as zero-inflated versions of Poisson and negative binonmial. Tradtional methods for evaluating model fits such as AIC / BIC and assessing Pearson residuals were employed in conjunction with machine learning techniques, such as DHARMa residuals, permuting on predictor of interest, and bootsrapping confidence intervals. Findings are preliminary and research is ongoing.

# Research: Spatiotemporal Modeling


The research is ongoing and a work in progress. Any and all mistakes found in this research can be attributed to Gavin Pierce. 

Please inquire with any questions.

