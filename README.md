# The first T2T assembly for Giraffe (Giraffa tippelskirchi)
This project aims to produce the first telomere-to-telomere, high-quality (QV73.6) genome assembly for the giraffe—the long-necked, charming, yet giant mammal. It is also part of the [Ruminant T2T Consortium](https://bmurdoch42.wixsite.com/ruminant-t2t). In this GitHub repository, you will find the complete assembly, an analysis set for mapping-based methods, gene annotation files, and the raw sequencing data.

## Latest assembly release
### T2T-Giraffe v1.2 (mGirTip1.pri.cur.MT.20251124)
* [mGirTip1.pri.cur.MT.20251124.fasta.gz](https://genomeark.s3.amazonaws.com/species/Giraffa_tippelskirchi/mGirTip1/assembly_curated/mGirTip1.pri.cur.MT.20251124.fasta.gz) : Primary assembly of the Masai giraffe (Giraffa tippelskirchi). This represents the gapless, high-quality haplotype of the diploid T2T-mGirTip1 assembly that includes both X and Y sex chromosomes. Chromosomal haplotypes were assigned using parental information and are provided in the original FASTA file available on genomeark.org.

* Previous assemblies and the README.md containing the release log can be found [here](https://genomeark.s3.amazonaws.com/index.html?prefix=species/Giraffa_tippelskirchi/mGirTip1/assembly_curated/)

## Samples (by individuals and tissues)
|BioSample|ID|Tissue|Name of individual|Relationship|
|-|-|-|-|-|
|SAMN51204129|mGirTip1|leukocytes from whole blood|Fennessey|Child|
|SAMN51283588|mGirTip1_testes|testes|Fennessey|Child|
|SAMN51204130|mGirTip2|tail hair root cells|Tessa|Maternal|
|SAMN51204131|mGirTip3|skin dermal fibroblasts|Kimba|Paternal|
|SAMN53299408|mGirTip4|cardiac muscle tissue|Calf of Nasha|Fenn’s Nephew|

## Downloads
### Sequencing data
* DNA and transcriptome sequencing data, including HiFi, ONT, Hi-C, and long reads ISO sequencing data.
  * From [NCBI (PRJNA1322564)](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1322564) and [NCBI (PRJNA1367195)](https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA1367195).
  * From [Genomark (Giraffa_tippelskirchi)](https://genomeark.s3.amazonaws.com/index.html?prefix=species/Giraffa_tippelskirchi/)

### Analysis set 
Analysis set for using T2T-Giraffe v1.2 (mGirTip1.pri.cur.MT.20251124) as a reference for mapping based research will be available soon!
* PAR masked curated genome (to be uploaded) : The primary haplotype reference with the PAR on chrY masked.
  
### Gene annotation (to be uploaded)
* [mGirTip1v1.2.pri.cur.20251124.eviann.gff.gz](https://github.com/jjuhyunkim/giraffeT2T/blob/main/annotation_data/mGirTip1v1.2.pri.cur.20251124.eviann.gff.gz) : Gene annotation of the T2T-Giraffe v1.2 primary assembly using [EviAnn](https://github.com/alekseyzimin/EviAnn_release?tab=readme-ov-file) with long-read RNA-seq and protein-similarity evidence.

* [mGirTip1v1.2.alt.cur.20250806.eviann.gff.gz](https://github.com/jjuhyunkim/giraffeT2T/blob/main/annotation_data/mGirTip1v1.2.alt.cur.20250806.eviann.gff.gz) : Gene annotation of the T2T-Giraffe v1.2 alternative assembly using [EviAnn](https://github.com/alekseyzimin/EviAnn_release?tab=readme-ov-file) with long-read RNA-seq and protein-similarity evidence.

### Other annotation
* [mGirTip1v1.2.gap.bed](https://github.com/jjuhyunkim/giraffeT2T/blob/main/annotation_data/mGirTip1v1.2.gap.bed) :Gap regions in BED format.
* [mGirTip1v1.2.telomere.bed](https://github.com/jjuhyunkim/giraffeT2T/blob/main/annotation_data/mGirTip1v1.2.telomere.bed)  : The regions containing telomere motifs in BED format.
* [mGirTip1v1.2.par.bed](https://github.com/jjuhyunkim/giraffeT2T/blob/main/annotation_data/mGirTip1v1.2.par.bed) : The pseudo-autosomal region between chromosomes X and Y in BED format.
* Non-syntenic_region.bed (to be uploaded) : Non-syntenic regions between T2T-Giraffe v1.2 (mGirTip1.pri.cur.MT.20251124) and the previous giraffe assembly ([ASM1828223v1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_018282235.1/)) are provided in BED format. These regions represent novel, newly resolved genomic sequences, including centromeres, telomeres, and short arms of acrocentric chromosomes.

## Contact
Please raise issues on this Github repository concerning this dataset. 

## Data reuse and license
Kim, J., Rosen, B. D., Fumagalli, S. E., Kuhn, K. L., Long, A., Schoenebeck, J. J., ... & Rhie, A. (2025). [Finishing a complete giraffe genome from telomere to telomere with Verkko-Fillet.](https://www.biorxiv.org/content/10.1101/2025.10.01.679366v1) bioRxiv, 2025-10.
