---
layout: archives
icon: fas fa-archive
order: 3
---

# How To Get Involved
If you are a researcher working with, or leading, a cohort in East or Southeast Asia (e.g., Japan, China, Taiwan, Korea, Cambodia) and you are interested in joining this Consortium, please email chloe.slaney@bristol.ac.uk. 

**NOTE: To be involved, cohorts are required to have some *ALDH2* genotype data available and relevant phenotype data for at least 1 of 3 of the key aims (listed below)**. 

## Data Required:
###AIM 1: Examine the potential *causal* effect of maternal alcohol use during pregnancy on risk of pregnancy complications and adverse offspring health using Mendelian randomization. **For the exposure, only maternal *ALDH2* genotype data is necessary, along with 1+ phenotype below.** 

```{r echo = FALSE, results = TRUE}
`Outcomes of Interest`  <- c("`Delivery Outcomes and Pregnancy Complications`","`Offspring Physical Development (0-5 years)`","`Offspring Mental Health")
Examples <- c( "Caesarean section, miscarriage, preeclampsia, placental abruption, stillbirth, preterm birth", "Weight, height, vision, hearing", "Validated measures of neurodevelopment (e.g., Ages and Stages Questionnaire, Child Behaviour Checklist) and/or neurodevelopmental conditions (Autism, ADHD) ")
Q1 <- data.frame(`Outcomes of Interest`, Examples)
knitr::kable(Q1)
```

###AIM 2: Investigate the interaction between maternal alcohol use during pregnancy and breastfeeding, and *ALDH2* genotype (maternal and child), on pregnancy and offspring outcomes. **For the exposure, maternal and/or child *ALDH2* genotype data is necessary, information on maternal alcohol use during pregnancy, along with 1+ phenotypes listed above.** 

###AIM 3: Investigate the role of *ALDH2* genotype on risk (and if available, severity) of infectious disease. **For the exposure, *ALDH2* genotype on any cohort participants with infection data are required**. For a list of infectious diseases and severity we are considering, please see below. However, we are also considering other diseases, so please do check with us if they could be included.

```{r echo = FALSE, results = TRUE}
Outcomes of Interest  <- c("`Infectious Disease Presence`","`Severity of Disease`")
Examples <- c( "Tuberculosis, Hepatitis B, Hepatitis C", "Hospitalization due to disease, death due to disease")
Q3 <- data.frame(`Outcomes of Interest`, Examples)
knitr::kable(Q3)
```

