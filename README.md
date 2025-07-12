# Sample size calculation for bioequivalence trials
This script aims to compute the sample size for the bioequivalence trials from  multiple previous pivotal bioequivalence trials.

# Description
Once selecting the sample size for the conduction of the clinical bioequivalence trial it is mandatory to conduct the Public Assessment Reports (PAR) review. The sample size calculation is typically based on pharmakokinetic parameters such as Cmax, AUC, etc. There is a natural variation from study to study of the CV, the number of subjects etc. The general approach is based on the calculation of the sample size using the data (intra subject variability (ISCV) and the study design) of only one study found either in the literature (Public Assessment Report / scientific research article) or having experimental data from the previous pilot study. This script allows to employ MULTIPLE bioequivalence studies having different designs and various ISCV.

### What study to choose for the calculation of the sample size?  
Using this script you can include as many trials as you want, there is no limit. 

The calculation takes into account three major factors influencing the sample size:
- the design
- the coefficient of variation (CV)
- the number of subjects

# Example of the calculation

The script takes the dataframe (excel sheet) and computes the sample size, power and pooledCV for the desired study
Here is the diagram of how the calculation is going on:

1. Create an excel sheet with the input data of a single or multiple bioequivalence pivotal trials.
![image](https://github.com/user-attachments/assets/cf173960-8964-4804-9c37-994644284ab5)


<img width="1280" height="720" alt="trial picture" src="https://github.com/user-attachments/assets/867445e2-1a46-4a9c-91e0-2d2c03be5a00" />

3. Run the script. 



# Installation instructions

clone the repository and download it, to load the file pls specify the excel sheet file path to load the dataset


# Known issues
stuf that did not work well in theis project

# Found a bag?
If you found a bag or have an idea of how to improve this project, please contact me on [here](https://www.linkedin.com/in/vlia/) 

# What was learned from this project?
xxxx



# Ackowledgments
Some parts of the sample size calculation functions are adapted from the Helmut Schutza article regarding the comparison of the sample size calculation using
different approaches: large sample approximation, central t approzimation and noncentral t approximation
Please check this article [here] (https://bebac.at/articles/Sample-Size-Estimation-for-Equivalence-Studies-in-a-Parallel-Design.phtml)

Extended by: Valery Liamtsau
