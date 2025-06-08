# Sample size calculation for bioequivalence trials
This script aims to compute the sample size for the bioequivalence trials from  multiple previous pivotal bioequivalence trials.

# Description
Once selecting the sample size for the conduction of the clinical bioequivalence trial it is mandatory to conduct the Public Assessment Reports (PAR) review. The sample size calculation is typically based on pharmakokinetic parameters such as Cmax, AUC, etc. There is a natural variation from study to study of the CV, the number of subjects etc. Typically there are multiple previous studies, and the problem is 

### What study to choose for the calculation of the sample size?  
Using this script you can include as many trials as you want, there is no limit. 

The calculation takes into account three major factors influencing the sample size:
- the design
- the coefficient of variation (CV)
- the number of subjects

# Example of the calculation
1. Create an excel sheet with the input data of a single or multiple bioequivalence pivotal trials 
![image](https://github.com/user-attachments/assets/4b8ed2d5-299f-4e1a-bcb1-7d430d587a92)




# Ackowledgments
Some parts of the sample size calculation functions are adapted from the Helmut Schutza article regarding the comparison of the sample size calculation using
different approaches: large sample approximation, central t approzimation and noncentral t approximation
Please check this article [here] (https://bebac.at/articles/Sample-Size-Estimation-for-Equivalence-Studies-in-a-Parallel-Design.phtml)

Extended by: Valery Liamtsau
