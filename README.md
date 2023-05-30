# CPRD_Aurum_ethnicity_childhood_vaccination
Ethnicity and routine childhood vaccinations in England (CPRD Aurum)

This repository contains the code lists and R code used to derive ethnicity and routine childhood vaccinations in England using the Clinical Practice Research Datalink (CPRD) Aurum database. 

Ethnicity files include:
- Code list categorising ethnicity using the 2001 (16 categories), 2011 (18 categories) and 2021 Census England & Wales (19 categories) classification systems
- R code for assigning each individual a single most plausible ethnic category using CPRD Aurum linked to HES Admitted Patient Care data 
- Ethnic categories by order of frequency in the general population of women aged 15-49 years at the time of the 2011 Census England & Wales (used in the R script as part of the algorithm)

Routine childhood vaccination files include:
- Medical codes and product codes for the following vaccines: MMR, 6/5/4-in-1, MenC & HibMenC, MenB, rotavirus, pneumococcal
- R code for identifying vaccinations in the CPRD Aurum Observations and Drug Issue data tables, and deriving variables indicating whether the primary course and full course (primary + booster dose) had been completed by the expected birthday (first, second and fifth birthdays, as per the UKHSA/NHS Digital annual statistical reports)
- Cumulative number of doses expected by each birthday according to England's national schedule (correct for the financial years between 2006-07 and 2020-2021)

The algorithms corresponding to these code lists and R code have been published in the supplemental appendix of XXX. Validation of these algorithms (completeness and representativeness) are also detailed within this paper. 
