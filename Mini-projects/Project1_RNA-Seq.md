# RNA-Seq mini project

RNA-seq (RNA-sequencing) is a technique that can examine the quantity and sequences of RNA in a sample using next-generation sequencing (NGS). 
Over the past few years, RNA sequencing (RNA-seq) has become an indispensable tool for transcriptome-wide analysis of differential gene expression and differential splicing of mRNAs [[1]](https://www.nature.com/articles/s41576-019-0150-2). It is is rapidly replacing gene expression microarrays in many labs as it lets you quantify, discover, and profile RNAs.

Several tools and pipelines exist for RNA-Seq data analysis. Different consortiums and institutions use different sets of guidelines and standards for their
data analysis. The H3ABioNet has developed a standard SOP and guidelines for RNA-Seq data analysis with some recommendations for gene expression analysis in human.


## H3ABioNet pipeline
The standard data analysis guidelines and quality checks have been documented in this [document](https://h3abionet.github.io/H3ABionet-SOPs/RNA-Seq). 
The main pipeline analysis steps are;
  - Quality check of the raw reads
  - Adapter removal and quality trimming 
  - Quality recheck
  - Alignment
  - Trascripts/gene counts
  - Collect and tabulate statistics
  - Statistical analysis
      - *QC check*
      - *Outlier removal and normalization*
      - *Differential expression*
        
The pipeline also provides recommendations of different tools that can be utilized on each of the above steps.

## Project tasks
1. Create a road map for your mini project
2. Create a pipeline for RNA-seq pre-processing and gene expression analysis using the best-selected tool by H3ABionet SOP
3. For each step, test different tools which can be utilized and write a short report on the challenges, performance, and pros
4. Document your scripts and work on GitHub ensuring it is reproducible

Throughout the project, demonstrate project organization, documentation, collaborative working, and report writing.

