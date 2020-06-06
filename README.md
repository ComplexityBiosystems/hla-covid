# hla-covid
Codes using artificial neural networks to analyze the binding of coronavirus peptides with polymorphic human MHC class I molecules.

Copyright (C) 2020 Caterina A. M. La Porta and Stefano Zapperi, 
 Center for Complexity and Biosystems, University of Milan

These codes were used to generate results and figures for the paper:
Heterogeneity of coronavirus peptide binding across human haplotypes
by Caterina A. M. La Porta and Stefano Zapperi

paper submitted.

Codes:

Covid19-4_MHCflurry-chopped-all_alleles.ipynb: This codes runs MHCflurry to obtain predictions for SARS-CoV-2 peptides. Results are filtered with netchop and then saved for further analysis

MHCpan-flurry-covid.ipynb: This code is used to load the csv files containing the predictions for peptides binding affinities obtained with netMHCflurry and netMHCpan4.0 and then filter the results comparing the two methods. The present code is applied to SARS-CoV-2 data.

Effect-of-cutoff.ipynb:This code is used to compare the results for three virus SARS-CoV-2 obtained with a cutoff of 500nM or 1000nM for strong binding				

MHCpan-flurry-sars.ipynb: This code is used to load the csv files containing the predictions for peptides binding affinities obtained with netMHCflurry and netMHCpan4.0 and then filter the results comparing the two methods. The present code is applied to SARS-CoV data.

Haplotypes.ipynb: This code allows to compute statistics over populations by distinguishing strongly binding and weakly binding alleles			
compare-sars-covid-OC43.ipynb: This code is used to compare the results for three virus SARS-CoV-2,SARS-CoV, HCoV-OC43. It also creates various comparative plots

MHCpan-flurry-HCoV-OC43.ipynb: This code is used to load the csv files containing the predictions for peptides binding affinities obtained with netMHCflurry and netMHCpan4.0 and then filter the results comparing the two methods. The present code is applied to HCoV-OC43 data.
	
netMHCpan-load.ipynb: This code loads predictions from the netMHCpan server, applies a filter from netchop and saves data for further analysis.

 
 

