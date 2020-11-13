# 16S mini project
The 16S rRNA is a ribosomal RNA necessary for the synthesis of all prokaryotic proteins. 
It is a component of the 30S small subunit of a prokaryotic ribosome binds to the Shine-Dalgarno sequence. The genes coding for it are referred to as the 16S rRNA gene and are used in reconstructing phylogenies due to the slow rates of evolution of this gene region. 

The internal structure of 16S rRNA gene is composed of variable regions and conserved regions. All the bacteria share the conserved area, and the variable regions have different degrees of difference among the different bacteria, with the specificity of the genus or species. The variable regions and the conservative areas are interlaced. Therefore, the universal primers of various bacteria can be designed according to the conservative area, and specific primers or probes of specific bacteria can be designed according to the variable area. 
The interspecific differences of the information contained in the variable regions of 16S rRNA make the detection specific [[1]](https://www.cd-genomics.com/blog/16s-rrna-one-of-the-most-important-rrnas/).

The basic principle of the 16S rRNA sequence analysis technique is to obtain the 16S rRNA sequence information from the 16S rRNA gene fragment in the 
microorganism sample by cloning, sequencing, or enzyme cutting and probe hybridization, and then comparing with the sequence data or other data in the 16S rRNA database to determine its position in the evolutionary tree, thus identifying the possible microbes species that exist in a given sample or microorganism.

H3ABionet has developed a [pipeline](https://h3abionet.github.io/H3ABionet-SOPs/16s-rRNA) for analyzing 16s RNA data with setout SOPs.

## H3ABioNet pipeline
The pipeline has the following main steps;
  - Quality check
  - Trimming and filtering reads
  - Chimera detection
  - OTU picking
  - ASV prediction
  - Classification and alignment
  - Phylogenetic analysis
  - Measurement of diversity
    - *Alpha diversity*
    - *Beta diversity* 
    
The H3ABionet also recommends different tools that can be used at each step.


## Project tasks

1. Create a road map for your mini project
2. Create an analysis pipeline for 16s RNA data from the Illumina sequencing platform
3. The pipeline should be based on the Qiime metagenomics analysis tool on the applicable steps
4. Compare the different tools that can be utilized at each step and write a short critique summary on performance, pros, and cons
5. Document your scripts and work on GitHub ensuring it is reproducible
    
Throughout the project, demonstrate project organization, documentation, collaborative working, and report writing.
