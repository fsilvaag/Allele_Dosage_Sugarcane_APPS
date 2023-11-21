# Allele_Dosage_Sugarcane_APPS
In this repository, you can find the script and required data to reproduce the analysis of the paper "Sequencing vs amplification for the estimation of allele dosages in sugarcane (Saccharum spp.)". 

The raw data for GBS and RADSeq sequencing data can be found at https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1040257 under accession number PRJNA1040257. The filtering process and steps can be found in the main text and in the paper Saavedra et al. under revision in BMC Plant Breeding.

The files are:

1. KASP_Intertek_FluorescenceRatios_185_SNPs_485_Sugarcane_Varieties.xlsx = Fluorescence intensity for the reference (Y) and alternative (X) allele, the sum of both intensities (Total), and the ratio between the reference and total intensity for each SNP and sample analyzed. The file contains a total of 185 SNP markers and 483 samples.

2. GBS_RADSeq_Allele_Dosage_76_SNPs_in_53_sugarcane_varieties_in_Cenicana.csv = Allele dosage estimated with the baseline technique (i.e. GBS+RADSeq) for the population of 53 genotypes and for 76 SNP markers.

3. Prediction_Fitpoly_KASP_117_de_185_Markers_KASP_483_Individuos.xlsx = Allele dosage for each of the 483 genotypes estimated with the fitPoly package of R. More details on how to produce this dataset are found in the Script.rmd

4. Flex_Seq_Allele_dosage_76_SNPs_53_Genotypes.csv = Allele dosage estimated with the Flex-Seq technique for the population of 53 genotypes and 76 SNPs.

5. Allele_Dosage_76_SNPs_in_53_sugarcane_varieties_GBS_RADSeq_FlexSeq_and_KASP.xlsx = Allele dosage estimated with the baseline technique (i.e. GBS+RADSeq), Flex-Seq, and KASP for the population of 53 genotypes and for 76 SNP markers. Empty cells correspond to markers not converted to KASP.

6. Script.Rmd = R code to analyze the data and produce the files 3 to 6.

