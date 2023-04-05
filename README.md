# Allele_Dosage_Sugarcane_APPS
In this repository you can find the script and required data to reproduce the analysis of the paper "Sequencing vs amplification for the estimation of allele dosages in sugarcane (Saccharum spp.)"

The files are:

1. KASP_Intertek.xlsx = Fluorescence intensity for the reference (Y) and alternative (X) allele, the sum of both intensities (Total), and the ratio between the reference and total intensity for each SNP and sample analyzed. The file contains a total of 185 SNP markers and 220 samples.

2. Dosage_GBS_RADSeq_179_SNP_220_Genotypes.csv = Allele dosage estimated with the baseline technique (i.e. GBS+RADSeq) for the population of 220 genotypes and for 179 SNP markers.

3. KASP_Dosis_Predicha_FitPoly_220_Genotypes_y_185_SNPs.csv = Allele dosage for each of the 220 genotypes estimated with the fitPoly package of R. More details on how to produce this dataset are found in the Script.rmd

4. Dosage_FlexSeq_81_SNPs_64_Genotypes.xlsx = Allele dosage estimated with the Flex-Seq technique for the population of 64 genotypes.

5. Correlaciones_pearson_spearman_Kendall_GBS_RADSeq_vs_KASP_FitPoly.xlsx = Pearson Correlation analysis for the allele dosage between KASP and GBS+RADSeq.

6. Correlaciones_pearson_spearman_Kendall_GBS_RADSeq_vs_FlexSeq.xlsx = Pearson Correlation analysis for the allele dosage between Flex-Seq and GBS+RADSeq.

7. Script.Rmd = R code to analyze the data and produce the files 3 to 6.

