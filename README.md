### BIOS 841: Statistical Collaboration Project

Background:<br>
In 2016, a national health survey in Uganda revealed that only 55% of children aged 12-23 months
received all recommended vaccinations (UBOS, 2018). The target population consists of households with
12-23 month old children, who reside with a caregiver in Bugoye sub-county, a small rural town in
western Uganda. Children of this age are recommended to receive the following vaccines and boosters:
BCG (Bacille Calmette-Guérin), polio, pentadose 1-3 (diphtheria, tetanus, pertussis, hepatitis B, and Hib disease), rotavirus 1-2, and measles (UBOS, 2018).
This study aims to explore caregiver beliefs and experiences associated with childhood vaccination uptake.
Data for the study were collected between January 20, 2021 and April 30, 2021.

![alt text](uganda_vacc.png "(UBOS 2018)")
Image credits (UBOS, 2018).


Data Description:<br>
The Phase 3 dataset is a cross-sectional survey of 1,689 children aged 12–23
months in Bugoye sub-county, capturing vaccination uptake from vaccination cards or self-reports when cards were
unavailable. It includes covariates, covering child characteristics, caregiver
beliefs, and caregiver experiences, potential confounders such as caregiver education, marital status, and household demographics, 
and response rates to vaccination uptake.  We created an additional response variable, indicating full vaccination status based on the eight vaccines
already in the dataset.

Methods (Factors Associated with Belief and Experience Scores):<br>
To assess caregiver and child factors associated with aggregate belief and experience scores, we used various nonparametric tests. 
Associations between continuous factors and aggregate scores were examined using Kendall’s Tau rank correlation, 
binary factors and aggregate scores were examined using Wilcoxon Rank Sum test and Cohen’s d statistic, and multinomial factors and aggregate scores were examined using Kruskal-Wallis test. Based on the Kruskal-Wallis results, Dunn's test was performed to conduct pairwise comparisons between levels from factors that were significantly associated with belief or experience scores. All statistical tests were performed at a two-sided significance level of 0.05. The significance level in Dunn’s test was adjusted using Holm’s method. 

References:<br>
Uganda Bureau of Statistics (UBOS) and ICF. (2018). *Uganda Demographic and Health Survey 2016.* Kampala, Uganda and Rockville, Maryland, USA: UBOS and ICF.


