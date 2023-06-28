# CNV

[中文版](https://github.com/flowhub-team/CNV/blob/main/README_cn.md)

CNV is a form of chromosomal structural variation, which stands for Copy Number Variation. Chromosomes are the genetic material within cells that carry an individual's genetic information. Under normal circumstances, each chromosome should have two copies (a pair), one inherited from the mother and the other from the father. However, due to genetic, environmental, and random events, the copy number of chromosomes can undergo variation, which is referred to as CNV.

CNV is a common type of genetic variation that can be found widely in human and other biological populations. It may affect several genes, a whole gene, or multiple genes on a chromosome. The size of CNV can range from a few thousand base pairs to several million base pairs.

CNV can be classified into two categories: copy number gain (CNV gain) and copy number loss (CNV loss). CNV gain refers to the copy number exceeding the normal two copies in a specific region of a chromosome, while CNV loss refers to a copy number below two. These variations can be inherited or occur during an individual's developmental process.

The impact of CNV can be beneficial, neutral, or detrimental. Beneficial CNV may increase the copy number of certain genes, thereby enhancing specific functions. For example, in humans, CNV gain in immune system genes may improve disease resistance. However, detrimental CNV can lead to the loss of certain genes, resulting in genetic disorders or other diseases.

Various molecular biology and genetics techniques are used to detect CNV, including gene chips, multiplex polymerase chain reaction (PCR), and genome sequencing. Through these techniques, researchers can identify the presence of CNV, locate its position, and determine the accurate copy number.

CNV plays an important role in genetic research, individual genomics, and disease studies. They can serve as genetic risk factors for diseases and be used to study inter-individual genetic variations. By studying the association between CNV and specific diseases, we can gain a better understanding of the mechanisms underlying diseases and provide guidance for their diagnosis and treatment.

In conclusion, CNV is a form of chromosomal structural variation that involves an increase or decrease in the copy number of genes on chromosomes. The presence of CNV has significant implications for an individual's genetic traits and disease risk, and it holds broad applicability in genetic research and disease studies.

### Here are some commonly used CNV analysis tools and algorithms:

1. CNVnator: CNVnator is a commonly used sequencing-based CNV detection tool. It detects CNVs by calculating the variation in sequencing depth across different regions of the genome, based on differences in sequence coverage in the sequencing data. You can access the project through this [CNVator GitHub](https://github.com/abyzovlab/CNVnator)
2. FREEC: FREEC is a software tool used for detecting chromosomal copy number variations. It utilizes the information from paired-end sequencing data to calculate the copy number in each genomic region and identifies CNVs by comparing differences between samples. You can access the project through this [FREEC GitHub](https://github.com/BoevaLab/FREEC)
3. CNVkit: CNVkit is an open-source tool for CNV detection from sequencing data. It uses read depth information from targeted regions to infer the presence of CNVs based on variations in sequencing depth and provides the genomic localization and copy number estimation of CNVs. You can access the project through this [CNVkit GitHub](https://github.com/etal/cnvkit)
4. PennCNV: PennCNV is a widely used CNV detection algorithm that utilizes gene chip data or high-density SNP array data. It detects CNVs based on linkage disequilibrium and signal intensity variations across the genome, providing CNV localization and copy number estimation. You can access the project through the official [PennCNV website](http://penncnv.openbioinformatics.org/en/latest/)
5. ExomeDepth: ExomeDepth is a CNV detection tool specifically designed for exome sequencing data. It identifies CNVs by comparing the coverage of exons in the sample to a reference set and provides CNV localization and copy number estimation. You can access the project through the official [ExomeDepth website](https://www.bioconductor.org/packages/release/bioc/html/ExomeDepth.html)
6. Genome STRiP: Genome STRiP is a CNV detection tool based on whole-genome sequencing data, focusing on detecting larger structural variations, including high-copy CNVs and structural rearrangements. You can access the project through the official [Genome STRiP website](https://software.broadinstitute.org/software/genomestrip/)

### CNV Standard Workflow Tutorial

#### How to use FlowHub to quickly complete data analysis
+ Step1：Click flow link，Enter FLOWHUB standard subscribe page，click "subscribe" to subscribe to the flow.
  ![step1](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step1.png)
+ Step2：If you do not log in to the platform in advance, the subscription will not be successful, and you will enter the login interface of the FLOWHUB platform. If you already have an account, you can log in to the platform directly with the account password. If you do not have an account, click "sign up" to complete the registration according to the instructions.

   <img src="https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step2.png" width="400" alt="step2" />

+ Step3：Login to the platform, enter the FLOWHUB standard pipeline subscription interface again, click "subscribe" once more, proceed with the subscription, and click "Sure" to complete the subscription.
  ![step3](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step3.png)

+ Step4：After completing the subscription, enter the Community-Subscribe Manage interface, add the corresponding standard process to the platform project, follow the instructions, and click "Sure" to create a new project.
  ![step4](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step4.png)
+ Step5：Complete the new project creation according to the instructions.
  ![step5](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step5.png)
+ Step6：After completing the creation of the new project, follow the instructions to add a flow again and enter the newly created project.
  ![step6](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step6.png)
+ Step7：After successful addition, click on "PROJECT" in the upper right corner to display the project list and quickly access the project where the flow is located.
  ![step7](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step7.png)
+ Step8：Upon entering the project, upload the data file that needs to be processed in the "Files" section. Then, navigate to the job and click on "Create Job" to create a task.
  ![step8](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step8.png)
+ Step9：Click on "Choose Flow" and follow the instructions to select the flow. Then, click on "Next Step" to proceed with the selection of input files.
  ![step9](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step9.png)
+ Step10：
1. Specify the root directory for all output files of the task in the "Output folder" field.
2. In the "Input File" section, select the input file based on the endpoint name.
3. In the "Output File" section, rename the output file that needs to be labeled.
   ![step10-1](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step10-1.png)
4. Check the tools used within the job and make personalized parameter adjustments, such as CPU/GPU settings. If executing the standardization process, no changes are needed.
   ![step10-2](https://github.com/flowhub-team/CNV/blob/main/asset/tutoral-step10-2.png)
+ Step11：Once the settings are completed, follow the instructions to submit the job and wait for the computation results. For detailed instructions, please refer to the tutorial.``[https://doc.flowhub.com.cn/en/](https://doc.flowhub.com.cn/en/)。

### Introduction to Fowhub Platform

FlowHub is an innovative cloud-based workflow platform that offers users comprehensive and powerful functionalities. It serves not only as a reliable data management platform but also as a flexible tool development platform, efficient workflow construction platform, intelligent task scheduling platform, and intuitive data visualization platform.

As a data management platform, FlowHub provides robust data storage and processing capabilities, allowing users to securely store and manage various types of data. Through an intuitive interface and user-friendly tools, users can easily perform operations such as data manipulation, import/export, and comprehensive data management.

As a tool development platform, FlowHub offers a rich set of development tools and interfaces, enabling users to customize and extend the platform's functionalities. Users can utilize their preferred programming languages and technologies to develop and integrate various tools, plugins, and extensions to meet their specific needs.

Workflow construction is one of the core features of FlowHub. It provides a visual and intuitive graphical interface that allows users to design and build workflows in a visual manner. Through simple drag-and-drop operations, users can connect different tasks and operations to create complete workflows. This graphical approach not only enhances work efficiency but also reduces the probability of errors.

Task scheduling is another important feature of FlowHub, as it intelligently manages and schedules task execution. Users can set task priorities, dependencies, and scheduling rules, and FlowHub will automatically arrange task execution order and timing based on these settings to ensure the smooth progression of the workflow.

In addition, FlowHub provides powerful data visualization capabilities. Users can transform complex data into understandable and analyzable forms through intuitive charts, graphs, and reports. This enables users to better understand the data, discover potential patterns and trends, and make informed decisions based on the data.

In summary, FlowHub is a feature-rich, user-friendly, and powerful workflow cloud platform that provides comprehensive data management, tool development, workflow construction, task scheduling, and data visualization capabilities. It helps users efficiently handle and analyze data, enhance work efficiency, and improve decision-making abilities.

### To contact us, please use the following contact information:

email: flowhub_team@flowhub.com.cn

Phone: (+86)17399981010

Wechat:

<img src="https://github.com/flowhub-team/CNV/blob/main/asset/wechat.jpg" width="250" alt="add my wechat">
