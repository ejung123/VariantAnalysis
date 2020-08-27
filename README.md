# VariantAnalysis
- More details in Project 2 Notes
- Create application; input is gene variant data (vcf or 23andMe)
- Annotate gene variant data (vcf or 23andMe format) with a descriptor sentence from var_pheno_ann.tsv
- VCF data is a list of variants(rs###...) with their corresponding alternative Allele base (A, C, G, T)
- var_pheno_ann.tsv is a list of variants with a corresponding sentence.
- Sentence format example: for rs###... variant: Allele A is (not) associated with ... as compared to Allele C.
- For each variant in the vcf input file, look for that same variant in var_pheno_ann and move the corresponding sentence to the vcf input file (or create a new dataset with columns being variant, reference base, alternate base, and sentence.

1. download bcftools. https://samtools.github.io/bcftools/
