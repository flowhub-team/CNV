# CNV

[中文版](https://github.com/flowhub-team/CNV/blob/main/README_cn.md)

CNV is a form of chromosomal structural variation, which stands for Copy Number Variation. Chromosomes are the genetic material within cells that carry an individual's genetic information. Under normal circumstances, each chromosome should have two copies (a pair), one inherited from the mother and the other from the father. However, due to genetic, environmental, and random events, the copy number of chromosomes can undergo variation, which is referred to as CNV.

CNV is a common type of genetic variation that can be found widely in human and other biological populations. It may affect several genes, a whole gene, or multiple genes on a chromosome. The size of CNV can range from a few thousand base pairs to several million base pairs.

CNV can be classified into two categories: copy number gain (CNV gain) and copy number loss (CNV loss). CNV gain refers to the copy number exceeding the normal two copies in a specific region of a chromosome, while CNV loss refers to a copy number below two. These variations can be inherited or occur during an individual's developmental process.

The impact of CNV can be beneficial, neutral, or detrimental. Beneficial CNV may increase the copy number of certain genes, thereby enhancing specific functions. For example, in humans, CNV gain in immune system genes may improve disease resistance. However, detrimental CNV can lead to the loss of certain genes, resulting in genetic disorders or other diseases.

Various molecular biology and genetics techniques are used to detect CNV, including gene chips, multiplex polymerase chain reaction (PCR), and genome sequencing. Through these techniques, researchers can identify the presence of CNV, locate its position, and determine the accurate copy number.

CNV plays an important role in genetic research, individual genomics, and disease studies. They can serve as genetic risk factors for diseases and be used to study inter-individual genetic variations. By studying the association between CNV and specific diseases, we can gain a better understanding of the mechanisms underlying diseases and provide guidance for their diagnosis and treatment.

In conclusion, CNV is a form of chromosomal structural variation that involves an increase or decrease in the copy number of genes on chromosomes. The presence of CNV has significant implications for an individual's genetic traits and disease risk, and it holds broad applicability in genetic research and disease studies.

### 以下是一些常用的CNV分析工具和算法

1. CNVnator: CNVnator is a commonly used sequencing-based CNV detection tool. It detects CNVs by calculating the variation in sequencing depth across different regions of the genome, based on differences in sequence coverage in the sequencing data. You can access the project through this [CNVator GitHub](https://github.com/abyzovlab/CNVnator)
2. FREEC: FREEC is a software tool used for detecting chromosomal copy number variations. It utilizes the information from paired-end sequencing data to calculate the copy number in each genomic region and identifies CNVs by comparing differences between samples. You can access the project through this [FREEC GitHub](https://github.com/BoevaLab/FREEC)
3. CNVkit: CNVkit is an open-source tool for CNV detection from sequencing data. It uses read depth information from targeted regions to infer the presence of CNVs based on variations in sequencing depth and provides the genomic localization and copy number estimation of CNVs. You can access the project through this [CNVkit GitHub](https://github.com/etal/cnvkit)
4. PennCNV: PennCNV is a widely used CNV detection algorithm that utilizes gene chip data or high-density SNP array data. It detects CNVs based on linkage disequilibrium and signal intensity variations across the genome, providing CNV localization and copy number estimation. You can access the project through the official [PennCNV website](http://penncnv.openbioinformatics.org/en/latest/)
5. ExomeDepth: ExomeDepth is a CNV detection tool specifically designed for exome sequencing data. It identifies CNVs by comparing the coverage of exons in the sample to a reference set and provides CNV localization and copy number estimation. You can access the project through the official [ExomeDepth website](https://www.bioconductor.org/packages/release/bioc/html/ExomeDepth.html)
6. Genome STRiP: Genome STRiP is a CNV detection tool based on whole-genome sequencing data, focusing on detecting larger structural variations, including high-copy CNVs and structural rearrangements. You can access the project through the official [Genome STRiP website](https://software.broadinstitute.org/software/genomestrip/)
