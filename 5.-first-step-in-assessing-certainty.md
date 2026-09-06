---
description: >-
  First step in assessing certainty: Calculating absolute effect based on
  baseline risk and relative effect
hidden: true
---

# First step in assessing certainty

Here we show three examples of how one can calculate a risk difference and its associated confidence interval given a relative risk (example 1), an odds ratio (example 2), or a hazard ratio (example 3) and a control group risk. Article 1 in this series provides a glossary explaining the technical terms in this Appendix including absolute risk, relative risk, hazard ratio, risk difference.

_Example 1_

The meta-analyzed relative risk (RR) of ‘disability worsening’ in patients with multiple sclerosis from two RCTs (n = 1,479) comparing teriflunomide to placebo proved to be 0.76 (95% CI 0.62 – 0.93).<sup>1</sup>

The risk in the control group (estimated as the median risk in placebo groups) is 21%. When the number of included studies (denoted here as M) is even, the following formula can be used to calculate the median risk:

<figure><img src=".gitbook/assets/Screenshot 2026-09-03 at 10.46.22 AM.png" alt=""><figcaption></figcaption></figure>

Where the studies, M, are sorted by increasing order of event rate.

In case of two control groups (M=2), the median risk is just the average of the first (here, 18.4%) and second risk (here, 23.5%) in the control groups. The median Risk = (18.4% + 23.5%)/2 = 21%.

(1)   Risk with intervention (_corresponding risk)_ = RR x Risk with control

\= 0.76 x 21%

\= 16%

(2)   Risk difference = Risk with control – Risk with intervention

\= 21% – 16%

\= 5%

We can use the same procedure to calculate the confidence interval (CI) associated with the risk difference, substituting the extremes of the CI (here, 0.62 and 0.93) for the point estimate (here, 0.76).

(3)   For the upper limit of the RR CI (0.93):

* &#x20;Risk with intervention = 0.93 x 21% = 19.5%
* &#x20;Risk difference = Risk with control – Risk with intervention = 21% – 19.5% = 1.5%

(4)   For the lower limit of the RR CI (0.62):

* &#x20;Risk with intervention = 0.62 x 21% = 13.0%
* &#x20;Risk difference = Risk with control – Risk with intervention = 21% – 13.0% = 8.0%

(5)   Risk difference is: 5% (95% CI: 1.5% to 8.0%).



_Example 2_

The odds ratio (OR) of ‘incident hypertension’ in pregnant women with overweight or obesity from four RCTs (n = 1,324) comparing exercise therapy + usual care to usual care is 0.52 (95% CI 0.28 – 0.96).<sup>2</sup>

The risk in the control group (estimated as the median risk in usual care groups) is 14%. When the number of included studies is even, the formula to calculate the median risk mentioned in example 1 can be applied. In case of four control groups (M=4), the median risk is just the average of the second (here, 9%) and third risk (here, 19.1%) in the control groups. The median risk = (9% + 19.1%)/2 = 14%.

To convert an odds ratio to a RR the next formula<sup>3</sup> can be used:

<div align="left"><figure><img src=".gitbook/assets/Screenshot 2026-09-03 at 10.49.04 AM.png" alt="" width="563"><figcaption></figcaption></figure></div>

We can use the same procedure to calculate to confidence interval (CI) associated with the odds ratio, substituting the extremes of the CI (here, 0.28 and 0.96) for the point estimate (here, 0.52).

(2)   For the upper limit of the OR CI (0.96):

<div align="left"><figure><img src=".gitbook/assets/Screenshot 2026-09-03 at 10.50.18 AM.png" alt="" width="314"><figcaption></figcaption></figure></div>

(3)   For the lower limit of the OR CI (0.28):

![](<.gitbook/assets/Screenshot 2026-09-03 at 10.49.27 AM.png>)

Now we have the RRs of the point estimate (0.58) and its associated confidence interval (0.31 – 0.97) for a risk in the control group (estimated as the median risk in placebo groups) of 14%.

(2)   Risk with intervention (_corresponding risk)_ = RR x Risk with control

\= 0.56 x 14%

\= 7.8%

(3)   Risk difference = Risk with control – Risk with intervention

\= 14% – 7.8%

\= 6.2%

We can use the same procedure to calculate the confidence interval (CI) associated with the risk difference, substituting the extremes of the CI (here, 0.31 and 0.97) for the point estimate (here, 0.56).

(4)   For the upper limit of the RR CI (0.97):

* &#x20;Risk with intervention = 0.97 x 14% = 13.6%
* &#x20;Risk difference = Risk with control – Risk with intervention = 14% – 13.6% = 0.4%

(5)   For the lower limit of the RR CI (0.31):

* Risk with intervention = 0.31 x 14% = 4.3%
* Risk difference = Risk with control – Risk with intervention = 14% – 4.3% = 9.7% Risk difference is: 6.2% (95% CI: 0.4% to 9.7%).<br>

_Example 3_

The hazard ratio (HR) of survival in patients with advanced hepatocellular carcinoma (n = 602) comparing sorafenib to placebo is 0.69 (95% CI 0.55–0.87).<sup>4</sup> Patients were followed up to about 17 months. We present two calculations. The first calculation relates to _event-free survival_. The second calculation relates to an _event_, i.e. death in this example.

The proportion of event-free patients up to about _eight_ months in the control group is 0.50 (50%).

To convert a hazard ratio (HR) to a proportion of event-free patients in the intervention group the next formula<sup>5</sup> can be used:

(1)   Proportion with intervention = 𝑒ln (𝑐𝑜𝑛𝑡𝑟𝑜𝑙 𝑔𝑟𝑜𝑢𝑝 𝑒𝑣𝑒𝑛𝑡−𝑓𝑟𝑒𝑒 𝑝𝑟𝑜𝑝𝑜𝑟𝑡𝑖𝑜𝑛) ×𝐻𝑅

\= 𝑒ln(0.50) ×0.69

\= 𝑒−0.6931 ×0.69

\= 𝑒ln(−0.4783)

\= 0.6199 (i.e. 62.0% when rounded)

(2)   Event-free survival difference = proportion event-free patients with intervention – proportion event-free patients with control

\= 62% – 50% = 12.0% up to about eight months

We can use the same procedure to calculate the confidence interval (CI) associated with the hazard ratio, substituting the extremes of the CI (here, 0.55 and 0.87) for the point estimate (here, 0.69).

(3)   For the upper limit of the CI (0.87):

* &#x20;Proportion with intervention = 𝑒<sup>ln(0.50)</sup> <sup>×0.87</sup> = 0.5471 (i.e. 54.7% rounded)
* Event-free survival difference = proportion event-free patients with intervention – proportion event-free patients with control

&#x20;     \= 54.7% – 50% = 4.7%

(4)   For the lower limit of the CI (0.55):

* &#x20;Proportion with intervention = 𝑒<sup>ln(0.50)</sup> <sup>×0.55</sup> = 0.6830 (i.e. 68.3% rounded)
* &#x20;Event-free survival difference = proportion event-free patients with intervention – proportion  event-free patients with control

&#x20;      \= 68.3% – 50% = 18.3%

(5)   Event-free survival difference up to about eight months is: 12.0% (95% CI: 4.7% to 18.3%).

The next section addresses calculating the occurrence of an event, i.e. death in this scenario.

As mentioned earlier, the second calculation relates to the occurrence of an event, i.e. death in this example; we use the same data as used for event-free survival. The proportion of patients with event in the control group \[i.e. control group risk] up to about _ten_ months is 0.625 (62.5%).

To convert a hazard ratio (HR) to an absolute risk in the intervention group the next formula <sup>5</sup> can be used:

(1)   Risk with intervention = 1 − 𝑒ln(1−𝑐𝑜𝑛𝑡𝑟𝑜𝑙 𝑔𝑟𝑜𝑢𝑝 𝑝𝑟𝑜𝑝𝑜𝑟𝑡𝑖𝑜𝑛 𝑒𝑣𝑒𝑛𝑡𝑠) × 𝐻𝑅

\= 1 − 𝑒ln(1−0.625) × 0.69

\= 1 − 0.5083 = 0.4917 (i.e. 49.2% when rounded)

(2)   Risk difference = Risk with control – Risk with intervention

\= 62.5% – 49.2%

\= 13.3% up to about ten months

We can use the same procedure to calculate the confidence interval (CI) associated with the hazard ratio, substituting the extremes of the CI (here, 0.55 and 0.87) for the point estimate (here, 0.69).

(3)   For the upper limit of the CI (0.87):

* &#x20;Risk with intervention = 1 − 𝑒<sup>ln(1−0.625)</sup> <sup>×</sup> <sup>0.87</sup> = 0.5740 (i.e. 57.4% rounded)
* &#x20;Risk difference = Risk with control – Risk with intervention = 62.5% – 57.4% = 5.1%

(4)   For the lower limit of the CI (0.55):

* &#x20;Risk with intervention = 1 − 𝑒<sup>ln(1−0.625)</sup> <sup>×</sup> <sup>0.55</sup> = 0.4169 (i.e. 41.7% rounded)
* &#x20;Risk difference = Risk with control – Risk with intervention = 62.5% – 41.7% = 20.8%

(5)   Risk difference up to about ten months is: 13.3% (95% CI: 5.1% to 20.8%).

#### References

1\.  Montalban X, Gold R, Thompson AJ, et al. ECTRIMS/EAN Guideline on the pharmacological treatment of people with multiple sclerosis. _Mult Scler_ 2018;24(2):96-120. doi: 10.1177/1352458517751049 \[published Online First: 20180120]

2\.  Behnam S, Timmesfeld N, Arabin B. Lifestyle Interventions to Improve Pregnancy Outcomes: a Systematic Review and Specified Meta-Analyses. _Geburtshilfe Frauenheilkd_ 2022;82(11):1249-64. doi: 10.1055/a-1926-6636 \[published Online First: 20221103]

3\. Prasad K, Jaeschke R, Wyer P, et al. Tips for teachers of evidence-based medicine: understanding odds ratios and their relationship to risk ratios. _J Gen Intern Med_ 2008;23(5):635-40. doi: 10.1007/s11606-007-0453-4 \[published Online First: 20080105]

4\.  Llovet JM, Ricci S, Mazzaferro V, et al. Sorafenib in advanced hepatocellular carcinoma. _N Engl J Med_ 2008;359(4):378-90. doi: 10.1056/NEJMoa0708857

5\. Tierney JF, Stewart LA, Ghersi D, et al. Practical methods for incorporating summary time-to-event data into meta-analysis. _Trials_ 2007;8:16. doi: 10.1186/1745-6215-8-16 \[published Online First: 20070607]
