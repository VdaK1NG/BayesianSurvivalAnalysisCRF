# INTRODUCTION 

Hello!
This Github contains the R files corresponding to the Master's Thesis "Bayesian Survival Analysis of Acute-On-Chronic Liver Failure in Clinically Stable Outpatients with Cirrhosis", which was developed in colaboration with INCLIVA for the Master of Biostatistics of University of Valencia, Spain. If you have any doubt, do not hesitate to contact me at csebap@hotmail.com. If you would like to get the original dataset, contact the corresponding author Juan Antonio Carbonell at jacarbonell@incliva.es.

The RData corresponding to the models are not included here due to size limitations. However, they can be downloaded from the following link: https://www.mediafire.com/folder/msfgqf52yfgki/Bayesian+Survival+Anlaysis

# INSTRUCTIONS 

In this Github you can find several files:

1.- Models.Rmd contains the code used to run the different models. However, I have to warn you that these models may take up to 4 days to run (using a I7 7400K processor with 3 cores running 3 chains simultaneously and 16GB of RAM). In case you do not want to run the models yourself, you can download the RData files from the link included in the previous section.

2.- Figures.Rmd contains the code used to generate all the figures included in the Master's Thesis. Depending on the capacity of your computer, the Rmd file may be unable to compile because of the total size of objects loaded in the RStudio environment. In that case, I suggest running the figures individually in an R file using the same code.

3.- DICs.Rmd contains the code used to estimate the DIC value of the different models. Just like before, this code may take up to two days to run. If you prefer to use the RData, they are included in the DICs folder.

4.- Tables.Rmd contains the code used to generate all the tables included. Just like with the figures, the Rmd file may be unable to compile because of the total size of objects loaded in the RStudio environment. In that case, I suggest running the figures individually in an R file using the same code.

5.-JAGS Model folder contains the txt files of the Jags models used.

6.- Models RData is an empty folder where you should include the RData of the models if you want to use the same directorys that were used in the original code.

7.- DICs is a folder containing the DICs Rdata of the models used for the comparison.

This thesis was based on a previous paper by Danilo et al, which also has a github link (https://github.com/daniloalvares/Bayes-surv-BUGS) with further explanation of the code of the figures and the models if you need extra information.
