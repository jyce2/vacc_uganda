### BIOS 841: Statistical Collaboration Project

#### Association between Caregiver Beliefs and Experiences and Childhood Immunizations in rural Uganda, 2021

Background:<br>
In 2016, a national health survey in Uganda revealed that about 55% of children aged 12-23 months
received all recommended vaccinations (UBOS, 2018). To explore vaccination coverage in rural areas of western Uganda, 
we analyzed a more recent vaccination survey of 12-23 month-old children, residing with a caregiver.
Data for the study were collected between January 20, 2021 and April 30, 2021 in Bugoye sub-county, Uganda.
Children of this age are recommended to receive the following vaccines and boosters:
BCG (Bacille Calmette-Guérin), polio, pentadose 1-3 (diphtheria, tetanus, pertussis, hepatitis B, and Hib disease), rotavirus 1-2, and measles (UBOS, 2018).
Our aim is to explore caregiver beliefs and experiences associated with childhood vaccination uptake.

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
Continuous variables were examined using Kendall’s Tau rank correlation, binary variables were examined using Wilcoxon Rank Sum test and Cohen’s d statistic, and multinomial variables were examined using Kruskal-Wallis test. Following Kruskal-Wallis, Dunn's test was performed for pairwise comparisons between groups that were significantly associated with belief or experience scores. All statistical tests were performed at a two-sided significance level of 0.05. The significance level in Dunn’s test was adjusted using Holm’s method. 

We used the following nonparametric analyses to evaluate caregiver and child factors associated with aggregate belief and experience scores. Continuous variables were assessed using Kendall’s Tau rank correlation, binary variables with the Wilcoxon Rank Sum test and Cohen’s d statistic, and multinomial variables using the Kruskal–Wallis test. For variables showing significant associations in the Kruskal–Wallis analysis, pairwise comparisons were conducted using Dunn’s test. All tests were two-sided with a significance threshold of 0.05. Holm’s method was applied to adjust for multiple comparisons in Dunn’s test.
Reference:<br>
Uganda Bureau of Statistics (UBOS) and ICF. (2018). *Uganda Demographic and Health Survey 2016.* Kampala, Uganda and Rockville, Maryland, USA: UBOS and ICF.


