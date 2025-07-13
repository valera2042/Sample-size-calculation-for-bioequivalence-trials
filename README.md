# Sample size calculation for bioequivalence trials
This script aims to compute the sample size for the bioequivalence trials from  multiple previous pivotal bioequivalence trials.

# Description
Once selecting the sample size for the conduction of the clinical bioequivalence trial it is mandatory to conduct the Public Assessment Reports (PAR) review. The sample size calculation is typically based on pharmakokinetic parameters such as Cmax, AUC, etc. There is a natural variation from study to study of the CV, the number of subjects etc. The general approach is based on the calculation of the sample size using the data (intra subject variability (ISCV) and the study design) of only one study found either in the literature (Public Assessment Report / scientific research article) or having experimental data from the previous pilot study. This script allows to employ MULTIPLE bioequivalence studies having different designs and various ISCV.

### What study to choose for the calculation of the sample size?  
Using this script you can include in the calculation as many trials as you want, there is no limit. 

The calculation takes into account three major factors influencing the sample size:
- the design
- the coefficient of variation (CV)
- the number of subjects

# Example of the calculation
The script takes the dataframe (excel sheet) and computes the sample size, power and pooledCV for the desired study
based on Cmax parameter (usually Cmax has the highest variability than AUCt).
Here is the diagram of how the calculation is going on:

1. Create an excel sheet with the input data of a single or multiple bioequivalence pivotal trials.

<img width="1280" height="720" alt="Presentation2" src="https://github.com/user-attachments/assets/19080d9a-3778-4246-b7bd-0c978535a61e" />

2. Run the script.
   
<img width="1280" height="720" alt="Presentation1" src="https://github.com/user-attachments/assets/9cf86d18-e531-4210-917c-10ababe68626" />

# Installation instructions
Please go to file named sample size pooled.R and click in the upper right corner the icon copy to copy the code, insert it, for example, into R studio,
specify the path for your excel file and run it.

# Found a bag?
If you found a bag or have an idea of how to improve this project, please contact me on [here](https://www.linkedin.com/in/vlia/) 

# What was learned from this project?
Sample size can be calculated by the central and the non central t approximation. 
The calculation based on the large sample approximation should be avoided because this underpowers the study.

# Ackowledgments
Some parts of the sample size calculation functions are adapted from the Helmut Schutz article regarding the comparison of the sample size calculation using
different approaches: large sample approximation, central t approzimation and noncentral t approximation
Please check this article [here] (https://bebac.at/articles/Sample-Size-Estimation-for-Equivalence-Studies-in-a-Parallel-Design.phtml)

Extended by: Valery Liamtsau
