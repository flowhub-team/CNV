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

1. CNVnator：CNVnator是一种常用的基于测序深度的CNV检测工具。它基于测序数据中的序列覆盖度差异，通过计算基因组上不同区域的测序深度变异来检测CNV。可通过链接访问该项目[CNVator GitHub](https://github.com/abyzovlab/CNVnator)
2. FREEC：FREEC是一种用于检测染色体拷贝数变异的软件工具。它利用测序数据中的连续读段比对信息，计算每个基因组区域的拷贝数，并通过比较样本之间的差异来识别CNV。可通过链接访问该项目[FREEC GitHub](https://github.com/BoevaLab/FREEC)
3. CNVkit：CNVkit是一个开源工具，用于从测序数据中检测CNV。它采用目标区域的读段比对信息，根据测序深度变异来推断CNV的存在，并提供基因组上CNV的定位和拷贝数估计。可通过链接访问该项目[CNVkit GitHub](https://github.com/etal/cnvkit)
4. PennCNV：PennCNV是一种广泛应用的CNV检测算法，它利用基因芯片数据或高密度SNP阵列数据来识别CNV。它基于基因组上的连锁不平衡（linkage disequilibrium）和信号强度变异来检测CNV，并提供CNV的定位和拷贝数估计。可通过链接访问该项目[PennCNV 官方网站](http://penncnv.openbioinformatics.org/en/latest/)
5. ExomeDepth：ExomeDepth是一种专门用于外显子组测序数据的CNV检测工具。它通过比较样本与参考集的外显子覆盖度来识别CNV，并提供CNV的定位和拷贝数估计。可通过链接访问该项目[ExomeDepth 官方网站](https://www.bioconductor.org/packages/release/bioc/html/ExomeDepth.html)
6. Genome STRiP：Genome STRiP是一种基于基因组测序数据的CNV检测工具，它专注于检测较大的结构变异，包括拷贝数较高的CNV和结构重排。可通过链接访问该项目[Genome STRiP 官方网站](https://software.broadinstitute.org/software/genomestrip/)
