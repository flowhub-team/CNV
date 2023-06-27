# CNV
[English](https://github.com/flowhub-team/CNV/blob/main/README.md)

CNV是染色体结构变异的一种形式，全称为染色体拷贝数变异（Copy Number Variation）。染色体是细胞内的遗传物质，它们携带了个体的遗传信息。正常情况下，每个染色体应该有两个拷贝（一对）存在，其中一个来自母亲，另一个来自父亲。然而，由于遗传、环境和随机事件的影响，染色体的拷贝数可能发生变异，这就是CNV。

CNV是一种常见的遗传变异类型，它可以在人类和其他生物种群中广泛存在。它可能影响染色体上的几个基因、一整个基因或者多个基因。CNV的大小可以从数千个碱基对到数百万个碱基对不等。

CNV可以分为两类：拷贝数增加（CNV增加）和拷贝数减少（CNV减少）。拷贝数增加指的是染色体上特定区域的拷贝数超过正常的两个，而拷贝数减少指的是拷贝数少于两个。这些变异可能是遗传的，也可能是在个体的发育过程中发生的。

CNV的影响可能是有益的、中性的或者有害的。有益的CNV可能增加某些基因的拷贝数，从而增强某种特定的功能。例如，在人类中，CNV增加在免疫系统基因的拷贝数可能提高抵抗疾病的能力。然而，有害的CNV可能导致某些基因的丧失，从而引发遗传性疾病或其他疾病。

CNV的检测方法包括多种分子生物学和遗传学技术，例如基因芯片、串联PCR（Polymerase Chain Reaction）和基因组测序。通过这些技术，研究人员可以识别CNV的存在、定位和准确的拷贝数。

CNV在遗传学研究、个体基因组学和疾病研究中扮演着重要的角色。它们可以作为疾病的遗传风险因素，也可以用作个体间的遗传变异研究。通过研究CNV与特定疾病之间的关联，我们可以更好地理解疾病的发生机制，并为疾病的诊断和治疗提供指导。

总之，CNV是染色体结构变异的一种形式，它涉及染色体上基因的拷贝数增加或减少。CNV的存在对个体的遗传特征和疾病风险有着重要的影响，它在遗传学研究和疾病研究中具有广泛的应用价值。

### 以下是一些常用的CNV分析工具和算法

1. CNVnator：CNVnator是一种常用的基于测序深度的CNV检测工具。它基于测序数据中的序列覆盖度差异，通过计算基因组上不同区域的测序深度变异来检测CNV。可通过链接访问该项目[CNVator GitHub](https://github.com/abyzovlab/CNVnator)
2. FREEC：FREEC是一种用于检测染色体拷贝数变异的软件工具。它利用测序数据中的连续读段比对信息，计算每个基因组区域的拷贝数，并通过比较样本之间的差异来识别CNV。可通过链接访问该项目[FREEC GitHub](https://github.com/BoevaLab/FREEC)
3. CNVkit：CNVkit是一个开源工具，用于从测序数据中检测CNV。它采用目标区域的读段比对信息，根据测序深度变异来推断CNV的存在，并提供基因组上CNV的定位和拷贝数估计。可通过链接访问该项目[CNVkit GitHub](https://github.com/etal/cnvkit)
4. PennCNV：PennCNV是一种广泛应用的CNV检测算法，它利用基因芯片数据或高密度SNP阵列数据来识别CNV。它基于基因组上的连锁不平衡（linkage disequilibrium）和信号强度变异来检测CNV，并提供CNV的定位和拷贝数估计。可通过链接访问该项目[PennCNV 官方网站](http://penncnv.openbioinformatics.org/en/latest/)
5. ExomeDepth：ExomeDepth是一种专门用于外显子组测序数据的CNV检测工具。它通过比较样本与参考集的外显子覆盖度来识别CNV，并提供CNV的定位和拷贝数估计。可通过链接访问该项目[ExomeDepth 官方网站](https://www.bioconductor.org/packages/release/bioc/html/ExomeDepth.html)
6. Genome STRiP：Genome STRiP是一种基于基因组测序数据的CNV检测工具，它专注于检测较大的结构变异，包括拷贝数较高的CNV和结构重排。可通过链接访问该项目[Genome STRiP 官方网站](https://software.broadinstitute.org/software/genomestrip/)
