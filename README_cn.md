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

### CNV标准流程使用教程

#### 如何使用FlowHub快速完成数据分析
+ Step1：点击流程链接，进入FLOWHUB标准流程订阅界面，点击“subscribe”，订阅flow。
  ![step1](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step1.png)
+ Step2：如果您没有FlowHub平台账号，订阅不会成功，将会进入FLOWHUB平台登录界面，已经有账号的直接账号密码登录进入平台，无账号点击“sign up”根据指引完成注册。

   <img src="https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step2.png" width="400" alt="step2" />

+ Step3：登录进入平台，再次进入FLOWHUB标准流程订阅界面，再次点击“subscribe”，进行订阅，点击“Sure”完成订阅。
  ![step3](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step3.png)

+ Step4：订阅完成后进入Community-Subscribe Manage界面，添加对应标准流程进平台项目中，根据指引，点击“Sure”创建新项目。
  ![step4](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step4.png)
+ Step5：根据指引完成新项目创建。
  ![step5](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step5.png)
+ Step6：完成新项目创建后，根据指引再次添加flow进入新创建项目中。
  ![step6](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step6.png)
+ Step7：添加成功以后，点击右上方“PROJECT”，出现项目列表，快速进入流程所在的项目。
  ![step7](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step7.png)
+ Step8：进入项目后，在Flie中上传需要处理的数据文件。进入job，点击“create job”创建任务。
  ![step8](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step8.png)
+ Step9：点击“choose flow”，根据指引选择对应流程，点击“next step”进行输入文件选择。
  ![step9](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step9.png)
+ Step10：
1. 在OutPut folder指定任务的所有输出文件的根目录；
2. 在Input Flie根据端点名称，选择输入文件；
3. 在Output Flie对需要标记的输出文件进行重命名；
   ![step10-1](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step10-1.png)
4. 查看job内使用的tool，进行个性化参数调整，CPU/GPU调整，如执行标准化流程无需更改。
   ![step10-2](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step10-2.png)
+ Step11：设置完成，根据指引完成job提交，等待计算结果。详细教程可查看[https://doc.flowhub.com.cn/en/](https://doc.flowhub.com.cn/en/)。

### Fowhub平台介绍

FlowHub 是一种创新的工作流云平台，为用户提供了全面而强大的功能。它不仅是一个可靠的数据管理平台，还是一个灵活的工具开发平台，一个高效的流程构建平台，一个智能的任务调度平台以及一个直观的数据可视化平台。

作为数据管理平台，FlowHub 提供了强大的数据存储和处理能力，用户可以安全地存储和管理各种类型的数据。通过直观的界面和易于使用的工具，用户可以轻松地对数据进行增删改查、导入导出等操作，实现对数据的全面管理。

作为工具开发平台，FlowHub 提供了丰富的开发工具和接口，使用户能够自定义和扩展平台的功能。用户可以使用自己熟悉的编程语言和技术，开发和集成各种工具、插件和扩展，以满足自己特定的需求。

流程构建是 FlowHub 的核心特性之一。它提供了直观的图形化界面，使用户能够以可视化的方式设计和构建工作流程。通过简单的拖放操作，用户可以将不同的任务和操作连接起来，形成完整的工作流程。这种图形化的方式不仅提高了工作效率，还降低了错误发生的概率。

任务调度是 FlowHub 的另一个重要功能，它能够智能地管理和调度任务的执行。用户可以设置任务的优先级、依赖关系和调度规则，FlowHub 将自动根据这些设置来合理安排任务的执行顺序和时间，以确保工作流程的顺利进行。

除此之外，FlowHub 还提供了强大的数据可视化功能。用户可以通过直观的图表、图形和报表，将复杂的数据转化为可理解和易于分析的形式。这使得用户能够更好地理解数据、发现潜在的模式和趋势，并做出基于数据的明智决策。

总之，FlowHub 是一个功能丰富、易用而强大的工作流云平台，为用户提供了全面的数据管理、工具开发、流程构建、任务调度和数据可视化能力，帮助用户更高效地处理和分析数据，提升工作效率和决策能力。

### 联系我们
email: flowhub_team@flowhub.com.cn

电话: 17399981010

微信:

<img src="https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/wechat.jpg" width="250" alt="添加微信">
