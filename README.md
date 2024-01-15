# Business Overview
Bazaar.com, a prominent online retailer in the United States, has established a significant presence in digital advertising. This includes a strong focus on display advertising as well as search engine advertising, with a particular emphasis on running paid search ads across platforms like Google and Bing. The paid advertisements by Bazaar are categorized primarily into two distinct groups based on the keywords used: branded and non-branded. Branded keywords incorporate the 'Bazaar' brand name, examples of which include 'Bazaar', 'Bazaar shoes', 'Bazaar clothes', and similar phrases. In contrast, non-branded keywords are those like 'shoes', 'dress', and other terms that do not feature the 'Bazaar' brand name. 

Bazaar.com conducted an experiment involving a paid campaign with branded keywords, specifically those containing the word 'Bazaar'. The aim was to estimate the number of customers visiting their website through both sponsored and organic advertisement links. However, during week 10 of the Google campaign, a technical glitch occurred, preventing the capture of customer traffic data through sponsored advertisements. As a result, the team used data from weeks 1 to 9 to calculate the ROI for the sponsored ads.


Regarding the traffic data from Google and Bing, Bob, a member of Bazaar's marketing analytics team, calculated a 320% Return on Investment (ROI) on the company's expenditure for sponsored ads. However, there is skepticism surrounding his result. The main concern arises from the fact that individuals searching with the term 'Bazaar' are likely already inclined to visit Bazaar.com. This casts doubt on the actual effectiveness of the branded keyword ads. 


However, Myra, one of the executives, raised concerns about potential overestimation in the ROI calculations. She posited that customers already searching for 'Bazaar' were naturally inclined to visit their website, regardless of whether they were exposed to sponsored ads or not. In her view, these customers would likely find their way to the site via organic links even in the absence of sponsored ads. This led to a decision to analyze the campaign data to assess the real impact of sponsored ads on web traffic. They planned to compare the total web traffic from both sponsored and organic advertisements before and after the week 10 glitch — essentially, up to week 9 and the subsequent period.

The primary objective now is to decipher the true causal effect of these search ads on business outcomes. To achieve a comprehensive understanding, we will conduct an in-depth analysis by addressing the following key questions:



1. What's wrong with Bob’s ROI analysis?
2. What is the treatment and control of the experiment?
3. Is the First Difference reliable to estimate the causal effect of the treatment? 
4. How should we compare with Difference-in-Difference estimation or Pre-Post estimation?  
5. Based on our new treatment effect, what should be the corrected ROI? How is it compared with Bob’s ROI?



To accurately gauge the effect of the absence of sponsored ads (due to the glitch) on the total number of advertisement clicks across various platforms, the team employed a 'difference in difference' approach. This method was chosen to more precisely estimate the actual ROI of the sponsored advertisements

The Difference in Difference (DiD) technique is a statistical method used to estimate causal relationships. It's particularly useful in observational studies where controlled experiments are not feasible. In the context of this case with Bazaar.com, here's how and why it's used, along with its assumptions:
How it's used in this case:
1.	Setup: We have two groups - one that experienced the 'treatment' (Google ads were turned off) and a control group (other search engines where ads continued). The 'before' and 'after' periods are the times before and after the Google ads were turned off.
2.	Calculation: DiD calculates the effect of the treatment by comparing the change in outcomes over time between the treatment and control groups. For Bazaar.com, it would compare the change in website traffic from Google (after ads were turned off) to the change in traffic from other search engines over the same period.
3.	Outcome: This helps isolate the effect of turning off the ads from other factors like market trends or seasonal effects, which would affect both groups similarly.
Why it's used:
•	Control for Confounders: It helps control for confounding variables that are constant over time but differ between the groups.
•	Estimate Causal Effect: DiD is useful for estimating the causal impact of the intervention (stopping ads on Google) on the outcome (web traffic).
Assumptions:
1.	Parallel Trends Assumption: The key assumption in DiD analysis is that, in the absence of treatment, the average outcomes for the treated and control groups would have followed parallel paths over time. In other words, any difference between the groups is constant over time, except for the impact of the treatment.
2.	No Interference Between Groups: The treatment of one group does not affect the control group.
3.	Consistent Treatment Effect: The effect of the treatment is consistent across individuals in the treatment group.
In this case, DiD is chosen because it can effectively isolate the impact of stopping Google ads on web traffic, considering other factors remain consistent across the groups. However, it's important to verify the parallel trends assumption with data before proceeding with this analysis.

