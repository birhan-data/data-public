# README
This directory contains five prediction models developed for the paper entitled **Development of risk prediction models for preterm delivery in a rural setting in Ethiopia**. The published paper can be found here: https://jogh.org/2023/jogh-13-04051

All models were trained to predict risk of preterm delivery. Each model is saved as a .Rdata object and include all coefficients and feature importance scores to allow predictions for individuals. To load the model, run load("modelname.Rdata") in R.

A codebook of all predictors is also shared as a csv file.

### Study abstract:
**Background**: Preterm birth complications are the leading causes of death among children under five years. A key practical challenge, however, is the inability to accurately identify pregnancies that are at high risk of preterm delivery, especially in resource-limited settings.

**Methods**: We evaluated whether risk of preterm delivery can be predicted using available data from a pregnancy and birth cohort in North Shewa, Ethiopia. All participants were enrolled in the cohort between December 2018 and March 2020. The study outcome was preterm delivery, defined as any delivery occurring before week 37 of gestation regardless of vital status of the fetus or neonate. A range of sociodemographic, clinical, environmental, and pregnancy-related factors were considered as potential inputs. Cox and accelerated failure time models, and decision tree ensembles were used to predict risk of preterm delivery. Model discrimination was estimated using the area-under-the-curve (AUC). Additionally, the conditional distributions of cervical length (CL) and fetal fibronectin (FFN) were simulated to ascertain whether those factors could improve model performance.

**Results**: A total of 2493 pregnancies were included. Of those, 138 women were censored due to loss-to-follow-up before delivery. Overall, predictive performance was poor. The AUC was highest for the tree ensemble classifier (0.60, 95%CI[0.57, 0.63]). When models were calibrated so that 90% of women who experienced a preterm delivery were classified as high risk, at least 75% of those classified as high risk did not experience the outcome. The simulation of CL and FFN distributions did not significantly improve models’ performance.

**Discussion**: Prediction of preterm delivery remains a major challenge. In resource-limited settings, predicting high-risk deliveries would not only save lives, but also inform resource allocation.  It may not be possible to accurately predict risk of preterm delivery without investing in novel technologies to identify genetic factors, immunological biomarkers or the expression of specific proteins.

