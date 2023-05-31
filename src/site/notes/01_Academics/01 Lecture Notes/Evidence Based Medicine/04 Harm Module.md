---
{"dg-publish":true,"permalink":"/01-academics/01-lecture-notes/evidence-based-medicine/04-harm-module/","tags":["IDC213,"]}
---

# Information
date:: 2022-09-28
lecturer:: Blas Mantaring

# 📦 Resources
![Odds Ratio Summary.png](/img/user/assets/Odds%20Ratio%20Summary.png)

# 📔 Notes
- Calculations use a **2x2** contingency table with the ==outcomes of interest as the columns== and the ==exposure occupies the rows== 
## Odds Ratios
$$OR=\frac{Odds\ Outcome\ was\ Exposed}{Odds\ Outcome\ was\ not\ Exposed}=\frac{\frac{Outcome\ with\ Exposure}{Outcome\ without\ Exposure}}{\frac{No\ Outcome\ with\ Exposure}{No\ Outcome\ and\ No\ Exposure}}$$

$$Post-exposure\ Odds= Pre-exposure\ Odds\times OR$$
- Able to create an **association** between the exposure and the outcome
	- **Non-directional** output
- Used in <mark style="background: #ABF7F7A6;">cross-sectional data collection or using a case control study design</mark> **(retrospective)**
	- *Vertical* recruitment such that you recruit ==starting from the outcome of interest== and from that pool, you determine who was exposed
	- Because of the nature of these studies, data derived are **not true incidences** such that the <mark style="background: #FFB8EBA6;">prevalence is an artificial prevalence</mark>
		- In case-control studies, the **investigator** decides how many cases and controls will be included in the study
		- Study design cannot be used to determine if the exposure preceded the outcome of interest or the outcome preceded the exposure
	- **Exposures and outcomes** are collected ==at the same time period or point== 
## Relative Risk
$$RR=\frac{\frac{Exposed\ with\ Outcome}{Total\ Exposed}}{\frac{Unexposed\ with\ Outcome}{Total\ Unexposed}}=\frac{True\ Incidence\ among\ Exposed}{True\ Incidence\ among\ Unexposed}$$
- Risk of developing the **outcome of interest** among those *exposed* compared to the outcome of interest compared to those unexposed
- Studies that are **prospective** like clinical trials and cohort studies, the recruitment is *horizontal* such that the exposure comes first then the patients are followed-up to determine the outcome
	- During the start of the study, ==none of the patients should have the outcome of interest==
## Individualizing Results
1. Take the **pre-exposure probability** of the outcome from literature or expert opinions
2. Convert pre-exposure probability to **pre-exposure odds** (if small, probability = odds)
3. Multiple pre-exposure odds with **odds ratio** to get the <mark style="background: #FFB8EBA6;">post-exposure odds</mark> of the outcome
4. Convert post-exposure odds to **post-exposure probability**
5. Make a decision if the exposure should be stopped

# ❓ Questions
>[!clinical] Clinical Scenario
> - Household helper **6 months pregnant**
> - Recently took vacation to care for **sick father living in small hut in rice fields**
> 	- **Pest outbreak** necessitated daily spraying with pesticide **Maltox** and the helper claims ==she got dizzy from the smell of pesiticide==
> - ! Does exposure of fetus to pesticides including malathion cause ASD?

>[!info] Study Details
>Prenatal and infant exposure to **ambient pesticides** and ASD in children: Population-based **case-control study**
>- Examine **association** between early developmental exposure to ambient pesticides and ASD
>- *Setting:* California **agricultural region** (Central Valley)
>- *Exposure:* Prenatal and infant exposure to high-pesticides (within 2000 m of maternal residence)
>- *Outcome:* OR and 95% CI to check for association between pesticide exposure and ASD in offspring
## Directness
**Direct** enough because the P, E, and O are consistent with each other albeit the E for our clinical scenario specifically identifies malathion
- Malathion is one of the 25 pesticide substances explicitly identified by the study
## Validity
### Exposure precedes undesirable outcome?
- **Yes,** while the study design involves identifying those with outcomes then identifying their exposure, the study specifically defines that there should be *pre-natal* exposure with *post-natal* outcome
### Were important prognostic factors balanced at time of exposure?
- **No,** the study mentions that most individuals with ASD were male, with older mothers, and mothers that had completed more years of education; thus at the time of exposure, these prognostic factors were unequal
#### If not, were statistical adjustments made of these factors
- **Yes,** the study mentions adjustment for the imbalance in prognostic factors. The statistical analysis section of the study mentions that all models were adjusted for matching variables: se, year of birth, and selected potential confounders based on available information
### Were unbiased criteria used to determine exposure in all patients
**Yes,** pesticide exposure was determined using data from geocoding of residential birth addresses and crossmatching it with California's state mandated Pesticide Use Reporting data on location, date, and mount of active ingredient applied
- CA-PUR reports were combined with land use survey information from California Department of Water Resources on locations of specific crops
### Were unbiased criteria used to determine outcome in all patients
- **Yes,** the diagnosis of ASD in involved patients were based on the Diagnostic and Statistical Manual of Mental Disorders
### Were follow-up rates adequate
- **Yes,** for all case-control studies, ==follow-up rate is always adequate== as the outcome and exposure are already accounted for and recorded, and there is no risk of losing patients to follow-up
## Results
### Odds Ratio
|              | Outcome (+) | Outcome(-) |
| ------------ |:-----------:|:----------:|
| Exposure (+) |     642     |    7277    |
| Exposure (-) |    2,319    |   28,093   |
| Total        |    2961     |   35370    | 

$$OR=\frac{642}{7277}\div \frac{2319}{28093}=1.07$$
### Are there biologic issues that may affect applicability of estimates of a harmful effect?
- **No explicit discussion** is found in the article
### Are there socioeconomic issues that may affect applicability of estimates of a harmful effect
- **No explicit discussion** only that it may have been considered in analysis
## Individualizing Results
### What is the likely effect of the exposure on the risk of your individual patient?
No effect since **OR is close to 1**
# 🎯 Tasks
- 

# 📓 Summary





