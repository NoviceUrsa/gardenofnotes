---
{"dg-publish":true,"permalink":"/01-academics/01-lecture-notes/evidence-based-medicine/03-diagnosis-module/","tags":["IDC213,"]}
---

# Information
date:: 2022-09-27
lecturer:: Blas Mantaring

# 📦 Resources
>[!clinical]- Clinical Scenario
>- 14/F with fever for 6 days associated with headache and body malaise
>	- Younger sister has similar signs 1 week ago and recovered with Paracetamol, bed rest, and increased fluid intake
>	- Unremarkable PE
>- Outbreak of Dengue 1 month prior during which 70 patients were transferred to hospital but ==only 60% had serologically confirmed Dengue== **(pretest probability)** 
>- Tourniquet test showed **11 petechiae in 2.5 square cm area** with BP apparatus
>	- Inflated between systolic and diastolic BP for 5 minutes according to WHO guidelines

## Guide Questions
### Directness
- Direct enough answer to PEO? (Exposure is evaluation and outcome is diagnosis)
	- Patient: Children 1-15 y/o with history of fever for < 7 days with negative malaria smear and no clinical evidence of alternative diagnosis or presentation with classic DSS (*Applicable for patient*)
	- Exposure: Standard tourniquet test with BP cuff on right arm with WHO technique
	- Outcome: Diagnosis of Dengue
	- ! The study is direct enough to answer the PEO
### Validity
- Acceptable reference standard?
	- The reference standard that was used in the study was the tourniquet test, which is not acceptable as the current gold standard for Dengue diagnosis is viral isolation and molecular methods
- Definition of index test and reference standard independent?
	- The index test used in the study is the same or is a part of the reference standard
	- The tourniquet test is a part of the diagnostic criterion differentiating Dengue fever and Dengue hemorrhagic fever; moreover, the study's objective is basically to determine/justify the use of this criteria for diagnosis hence not independent of each other
- Performance of index test and reference standard independent?
	- With **prospective studies** such as this, the patients are able to undergo both the index test and the gold standard for diagnosis thus, the performance of these tests are independent of each other
	- As compared to retrospective studies, these studies recruit those who have the disease and who have underwent both the index test and the gold standard in the past which may affect proper analysis
- Interpretation of index test and reference standard independent?
### Appraisal of Results
- Likelihood ratios of test results
### Assess applicability
- Biologic issues affecting applicability (Sex, Comorbidity, Race, Age, Pathology)
- Socioeconomic issues affecting applicability of test accuracy
### Calculate patient-specific results
- How might test results affect probability of disease in your individual patient?
# 📔 Notes
## Measures of Accuracy
![Matrix of Computations.png](/img/user/assets/Matrix%20of%20Computations.png)
- Assumes that there are only two possible results
- **Sensitivity** is the probability of ==testing positive in those with disease==
- **Specificity** is the probability of ==testing negative in those without disease==
- **Positive Predictive Value** is the probability of ==having the disease with positive test result==
- **Negative Predictive Value** is the probability of ==not having the disease with negative test result==
- ! There are inherent problems with the prior 4 measures of accuracy mentioned
	- Which are clinically useful? 
		- PPV and NPV are clinically useful but ==they change with changing prevalence==
		- Specificity and Sensitivity are not clinically useful but they are stable regardless of prevalence and they are **test characteristics** that help in <mark style="background: #ABF7F7A6;">determining which test to use</mark> in the clinical setting
		- + In the clinical setting, you have to be able to tell the patient of the probability of having or not having the disorder based on the test result
	- Can only be done with a 2x2 contingency table thus, cannot be used for test with non-dichotomous results
	- Cannot tell how large the magnitude of change is between pretest and post test probability

>[!brain] Techniques to Remember
>- SpPIn: If you test positive in highly specific test, you rule in the disease
>- SnNout: If you test negative in highly sensitive test, you rule out the disease

## Likelihood Ratios
- Addresses limitations of the measures of accuracy
	- Clinical useful
	- Do not change with prevalence
	- Can use ≥2 results
	- Tell the change in pretest and posttest probabilities
- There are as many likelihood ratios as there are test results (can handle ≥2 results in a test)
### In terms of Probabilities
- LR(+) is the ratio of probability of positive test among those with disease to those without disease
	- $$LR(+)=\frac{Sensitivity}{1-Specificity}=\frac{\frac{Diseased}{Positive}}{\frac{Not\ diseased}{Positive}}$$
- LR(-) is the ratio of probability of negative test among those with disease to those without disease
	- $$LR(-)=\frac{1-Sensitivity}{Specificity}=\frac{\frac{Diseased}{Negative}}{\frac{Not\ Diseased}{Negative}}$$
### In terms of Odds
- $$LR=\frac{Posttest\ Odds}{Pretest\ Odds}$$
- $$Pretest\ Odds=\frac{Diseased}{Non-diseased}$$
	- Can be derived from pretest probability
- $$Posttest\ Odds=\frac{\frac{True+}{False+}}{\frac{False-}{True-}}$$
	- Can be converted to posttest probability
### Applying LR
#### Calculating Posttest Probability from Pretest Probability and LR
1. Calculate pretest probability based on history, PE, and initial labs
2. Convert pretest probability to pretest odds
3. Perform diagnostic test 
	- The **diagnostic threshold** is the probability of disease that is ==low enough to dismiss diagnosis==
4. Depending on test result, multiply LR by pretest odds to get posttest odds
5. Convert posttest odds to posttest probability
	- $Posttest\ Probability=\frac{Posttest\ Odds}{1+ Posttetst\ Odds}$
6. Decide to treat or not to treat
	- The **therapeutic threshold** is the probability of disease that is high enough to ==begin treatment==
# ❓ Questions
- 

# 🎯 Tasks
- 

# 📓 Summary





