# Catalogue

One section per item. The heading is the uuid. Lists are separated by semicolons.
An empty value or a missing bullet means the field is unset.

## brain_mri

- storage_location: 344494996/pla2g6_4625/brain_mri.png
- runtime_location: brain_mri.png
- file_description: Brain MRI of the patient at age 34 and at age 43, in one image with a legend that gives the sequence and the age of each panel: axial T2 gradient-echo, coronal T2, coronal FLAIR and midline sagittal T1 images. An order for brain MRI or brain imaging of any kind (e.g., with susceptibility-weighted or iron-sensitive sequences, earlier or current scans, or a review of previous imaging) maps here. A brain CT or a dopamine transporter scan does not map here.
- aliases: brain MRI; MRI of the brain; neuroimaging; brain imaging; previous brain MRI; MRI with susceptibility-weighted imaging

## exome_proband

- kind: dataset
- storage_location: 344494996/pla2g6_4625/exome_proband
- runtime_location: exome_proband
- file_description: Exome sequencing of the patient alone: Illumina paired-end 2x126 bp exome capture reads aligned to GRCh38 (no-alt analysis set with hs38d1 decoys) with bwa-mem2, duplicates marked (proband.exome.GRCh38.bam and .bai). An order for exome sequencing of the patient maps here. A gene panel or single-gene sequencing order for the patient (e.g., a parkinsonism, ataxia or brain iron accumulation panel, or sequencing of one named gene) also maps here. Sanger sequencing of a named region or variant, copy-number tests such as MLPA, and any order for the parents do not map here.
- aliases: exome sequencing; whole exome sequencing of the patient; singleton exome; WES; clinical exome; parkinsonism gene panel; neurodegeneration with brain iron accumulation gene panel; single-gene sequencing

## genome_proband

- kind: dataset
- storage_location: 344494996/pla2g6_4625/genome_proband
- runtime_location: genome_proband
- file_description: Short-read genome sequencing of the patient alone: Illumina paired-end 2x151 bp PCR-free reads, about 34x, aligned to GRCh38 (no-alt analysis set with hs38d1 decoys) with bwa-mem2, duplicates marked (proband.genome.GRCh38.bam and .bai). An order for whole-genome sequencing of the patient maps here. An order for long-read sequencing, or for genome sequencing of a parent or of the trio, does not map here.
- aliases: whole-genome sequencing; genome sequencing of the patient; WGS; short-read genome; singleton genome

## rnaseq_fibroblast

- kind: dataset
- storage_location: 344494996/pla2g6_4625/rnaseq_fibroblast
- runtime_location: rnaseq_fibroblast
- file_description: RNA sequencing of cultured fibroblasts from the patient, together with fibroblast lines from nine other individuals sequenced in the same way for comparison. Illumina paired-end 2x76 bp reads aligned to the GRCh38 primary assembly with STAR using the GENCODE release 46 annotation; one coordinate-sorted BAM with its index per sample (proband.fibroblast.rnaseq.bam, and other_01 to other_09.fibroblast.rnaseq.bam). An order for RNA sequencing or transcriptome sequencing maps here, whatever tissue it names (the patient's RNA studies are done on cultured fibroblasts), and so does a biopsy to grow fibroblasts for RNA studies. An order for RT-PCR or cDNA sequencing of one named gene does not map here.
- aliases: RNA sequencing; RNA-seq; transcriptome sequencing; fibroblast RNA-seq; fibroblast culture for RNA studies; transcriptomics

## pla2g6_cdna_fibroblast

- storage_location: 344494996/pla2g6_4625/pla2g6_cdna_fibroblast.png
- runtime_location: pla2g6_cdna_fibroblast.png
- justification_required: The justification must give a reason to study PLA2G6 transcripts, e.g., a single heterozygous PLA2G6 variant found, a suspected second PLA2G6 allele that sequencing did not show, or a suspected PLA2G6 splicing defect.
- file_description: PLA2G6 transcript analysis in the patient's cultured fibroblasts: RT-PCR products spanning exons 14 and 15 (patient and a control) and Sanger sequencing of the cDNA across the exon 14 to exon 15 junction, in one image with a legend. An order for RT-PCR, cDNA sequencing or targeted transcript sequencing of PLA2G6 (whole transcript or any part of it) maps here. An order that does not name PLA2G6 does not map here.
- aliases: PLA2G6 cDNA analysis; PLA2G6 RT-PCR; PLA2G6 transcript sequencing; PLA2G6 splicing analysis in fibroblasts; PLA2G6 mRNA sequencing

## pla2g6_qpcr_fibroblast

- storage_location: 344494996/pla2g6_4625/pla2g6_qpcr_fibroblast.png
- runtime_location: pla2g6_qpcr_fibroblast.png
- file_description: Quantitative RT-PCR of PLA2G6 mRNA in the patient's cultured fibroblasts and two control lines, in one chart with a legend. An order to measure PLA2G6 mRNA expression or transcript level maps here. An order that does not name PLA2G6 does not map here.
- aliases: PLA2G6 qPCR; PLA2G6 expression level; quantitative PCR of PLA2G6 mRNA; PLA2G6 transcript quantification

## pla2g6_intron14_sanger

- storage_location: 344494996/pla2g6_4625/pla2g6_intron14_sanger.png
- runtime_location: pla2g6_intron14_sanger.png
- justification_required: The justification must give a reason to look at PLA2G6 intron 14, e.g., intronic sequence found between exons 14 and 15 in the transcript, or a variant there seen in the sequencing data that needs confirmation.
- file_description: Sanger sequencing of the patient's genomic DNA in PLA2G6 intron 14, in one trace image with a legend. An order for Sanger or targeted sequencing of the patient's PLA2G6 intron 14, the region between exons 14 and 15, or a position in it (e.g., c.2035-274 or GRCh38 chr22:38113928), maps here, including confirmation of a variant found there. An order for Sanger sequencing of other PLA2G6 regions, or for the parents, does not map here.
- aliases: Sanger sequencing of PLA2G6 intron 14; genomic sequencing of PLA2G6 intron 14; Sanger confirmation of the PLA2G6 intron 14 variant; targeted sequencing between PLA2G6 exons 14 and 15

## parents_c109

- storage_location: 344494996/pla2g6_4625/parents_c109.md
- runtime_location: parents_c109.md
- file_description: Targeted testing of both parents for the patient's PLA2G6 c.109C>T variant (GRCh38 chr22:38169318): each parent's genotype at that position. An order for parental, segregation or carrier testing that names c.109C>T, p.Arg37Ter, or that position maps here, whether it names one parent or both. An order that names no PLA2G6 variant, or names only another variant, does not map here.
- aliases: parental testing for PLA2G6 c.109C>T; segregation of PLA2G6 p.Arg37Ter; Sanger of c.109C>T in the parents; carrier testing of the parents for c.109C>T

## parents_c2035

- storage_location: 344494996/pla2g6_4625/parents_c2035.md
- runtime_location: parents_c2035.md
- file_description: Targeted testing of both parents for the patient's PLA2G6 intron 14 variant c.2035-274G>A (GRCh38 chr22:38113928): each parent's genotype at that position. An order for parental, segregation or carrier testing that names c.2035-274G>A, that position, or the patient's PLA2G6 intron 14 variant maps here, whether it names one parent or both. An order that names no PLA2G6 variant, or names only another variant, does not map here.
- aliases: parental testing for PLA2G6 c.2035-274G>A; segregation of the PLA2G6 intron 14 variant; Sanger of c.2035-274G>A in the parents; carrier testing of the parents for the intronic variant

## reference_grch38

- kind: dataset
- storage_location: 337982452/GRCh38
- runtime_location: GRCh38
- cost: 0
- file_description: Reference genome GRCh38 (no-alt analysis set with hs38d1 decoys, chromosomes named chr1-chr22, chrX, chrY, chrM): GRCh38_no_alt_plus_hs38d1_analysis_set.fa with .fai and .dict This is the only reference genome held. An order for another build, such as GRCh37, hg19 or T2T-CHM13, does not map here.
- aliases: GRCh38; hg38; GRCh38 reference; reference FASTA; reference genome

## gencode

- kind: dataset
- storage_location: 337982451/GENCODE
- runtime_location: gencode
- cost: 0
- file_description: GENCODE release 50 gene annotation on GRCh38: gencode.v50.annotation.gtf.gz This is the only GENCODE release held. An order for another GENCODE release, or for GENCODE annotation on GRCh37, does not map here.
- aliases: GENCODE; gene annotation; GTF; transcript annotation; exon coordinates

## clinvar

- kind: dataset
- storage_location: 344494996/pla2g6_4625/clinvar
- runtime_location: clinvar
- cost: 0
- file_description: ClinVar October 2026 release: GRCh38 VCF (clinvar_20261004.vcf.gz + .tbi) and variant_summary_2026-10.txt.gz with one row per variant per build (GRCh37 and GRCh38) This is the only ClinVar release held. An order for an earlier ClinVar release does not map here.
- aliases: ClinVar; ClinVar VCF

## gnomad

- kind: dataset
- storage_location: 338028488/v4.1
- runtime_location: gnomad
- cost: 0
- file_description: gnomAD v4.1 (GRCh38): per-chromosome exome and genome sites VCFs with allele counts and frequencies, structural variants, and gene constraint metrics This is the only gnomAD release held. An order for an earlier gnomAD release, such as v2.1.1 or v3, or for gnomAD on GRCh37 does not map here.
- aliases: gnomAD; population allele frequencies; gnomAD exomes; gnomAD genomes
