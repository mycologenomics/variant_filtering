# variant filtering
Script to filter single nucleotide polymorphisms (SNPs)

Input: vcf file
Output: vcf file with low confidence SNPs labelled as 'fail'

usage: filterGatkGenotypes.py [-h] [--min_GQ MIN_GQ] [--keep_GQ_0_refs] [--min_percent_alt_in_AD MIN_PERCENT_ALT_IN_AD] [--min_total_DP MIN_TOTAL_DP]
                              [--het_binomial_p HET_BINOMIAL_P] [--keep_all_ref]
                              infile
