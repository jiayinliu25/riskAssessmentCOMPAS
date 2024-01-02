# Project Website 
https://sites.duke.edu/compasriskassessment/

# riskAssessmentCOMPAS
The COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) system is a decision support program used by the U.S. courts to assist judges and probation officers in assessing an individual's likelihood of reoffending. The COMPAS system incorporates predictive machine learning models to compute a risk score that forecasts an individual’s potential for general and violent recidivism. The system’s proprietary multiple risk scales use one’s detailed historical demographic data ranging from prior arrest, employment status, education, to community relations. Judges or probation officers input relevant data and incorporate the resulting risk classification during sentencing.

## Dataset 
The dataset we have provided contains variables used by the COMPAS algorithm in scoring defendants, along with the outcomes of the defendants within 2 years of the resulting decision. This dataset includes over 10,000 criminal defendants from Broward County, Florida between 2013-2014. COMPAS has only been used within legal boundaries in NY, WI, CA, FL (Broward County). We will use this algorithm to test and determine the fairness of this algorithm, identifying possible pitfalls in the form of biases.
dataset link: https://github.com/propublica/compas-analysis

## Technical Demo 

### Exploratory Data Analysis 
1. Race Break Down 
2. Age Group Break Down
3. Gender Break Down
4. Recidivism Score BreakDown
5. Violent Recidivism Score Break Down by Race
6. Violent Recidivism Score Break Down by Gender 
7. Correlation Matrix between: 'sex', 'age','juv_fel_count', 'decile_score', 
                    'juv_misd_count','juv_other_count','priors_count', 
                    'days_b_screening_arrest', 'c_days_from_compas', 'r_days_from_arrest', 'v_decile_score', 'jail_out- jail_in','score_text'
8. Interaction Table of mean ad standard deviation of: 'juv_fel_count','juv_other_count','juv_misd_count','priors_count', 'priors_count.1' Broken down by race/sex 
9. Pivot Table of count of each Decile Scores by race
10. Decile Scores by Count for Defendants By Race Bar Plot 

### Logistic Regression Model
1. Basic two feature model 
2. Five features based on recursive feature selection 

### Neural Network Model 
1. Basic two feature model
2. Five features based on recursive feature selection
   
### Recursive Feature Selection 
1. RFS on Logistic Regression Model 
2. RFS on Neural Network
   
### DataSet Bias Mitigation 
1. Resampling: Race and Gender 
-   Oversampling 
-   Undersampling
-   Combination 
