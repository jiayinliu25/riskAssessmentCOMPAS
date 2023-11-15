# riskAssessmentCOMPAS

### TO DO
1. Exploratory Data Analysis 

TODO: implement the filtering explained above

- Hint: you should end up with 6172

TODO: find the Pearson correlation between length of stay (jail_out - jail_in) and COMPAS decile


After filtering we have the following demographic breakdown:


TODO: find counts for each age group - dpone

TODO: find counts and percentages for each race group- done 

TODO: find counts of each score_text group - done 


TODO: create interaction table of counts between race/sex interactions - done

TODO: find counts and percentages for each gender group - done 

TODO: How many defendants had two-year recidivism in last two years? What percentage of all defendants? - what does mean 


Judges are often presented with two sets of scores from the Compas system -- one that classifies people into High, Medium and Low risk, and a corresponding decile score. There is a clear downward trend in the decile scores as those scores increase for white defendants.


TODO: plot decile scores by count for African-America defendantsv- done 

TODO: plot decile scores by count for Caucasian defendants - done 

TODO: Create a pivot table between decile_score and race - done 


After filtering out bad rows, our first question is whether there is a significant difference in Compas scores between races. To do so we need to change some variables into factors, and run a logistic regression, comparing low scores to high scores.


TODO: create columns for all options for charge_degree, age, race, sex, and 

TODO: Run these input features to predict whether score_text is Low or Med/High using a Logistic Regression

TODO: What is the correlation coefficient for African_American? What is the odds ratio?


Ref: https://github.com/irenetrampoline/compas-python/blob/master/COMPAS_Python.ipynb


