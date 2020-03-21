---
layout: page
title: Schedule
menu: true
order: 2
---


All course delivery for Spring 2020 will be online via this public facing website.  Clicking on the class topics below will take you to corresponding video lectures, pre-class video screen-casts, required reading material and homework assignments.

<br>

| \# | Week         | Topics for Spring 2020                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| :-: | :-----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1  | 03/30/20 | [**Getting Oriented**](#1) <br> Course introduction, Learning goals & expectations, Meet the instructional team. Setup your computer with required software.                                                                                                                                               |
| 2  | 04/06/20 | [**Welcome to Bioinformatics**](#2) <br> Biology is an information science, History of Bioinformatics, Types of data, Application areas and introduction to upcoming course segments, Hands on with major Bioinformatics databases and key online NCBI and EBI resources                                                                                                                                               |
| 3  | 04/13/20 | [**Sequence alignment fundamentals, algorithms and applications**](#3) <br> Homology, Sequence similarity, Local and global alignment, classic Needleman-Wunsch, Smith-Waterman and BLAST heuristic approaches, Hands on with dot plots, Needleman-Wunsch and BLAST algorithms highlighting their utility and limitations                                                                                                                                                 |
| *  | 04/20/20  | **Project:** [**Find a gene project assignment**](#11) <br> (Part 1) Principles of database searching, due in 3 weeks. (Part 2) Sequence analysis, structure analysis and general data analysis with R due at the end of the quarter.                                                                                                                                                                                                 |
| 4  | 04/20/20  | [**Bioinformatics data analysis with R**](#4) <br> Why do we use R for bioinformatics? R language basics and the RStudio IDE, Major R data structures and functions, Using R interactively from the RStudio console                                                                                                                                                                                                                                          |
| 5  | 04/27/20  | [**Data exploration and visualization in R**](#5) <br> The exploratory data analysis mindset, Data visualization best practices, Simple base graphics (including scatterplots, histograms, bar graphs, dot chats, boxplots and heatmaps), Building more complex charts with ggplot.                                                                                                                                                                                                                                                       |
| 6  | 05/04/20 | [**Why, when and how of writing your own R functions**](#6) <br> The basics of writing your own functions that promote code robustness, reduce duplication and facilitate code re-use. <br> Plus: [**Bioinformatics R packages from CRAN and BioConductor**](#6) <br> Extending functionality and utility with R packages, Obtaining R packages from CRAN and BioConductor, Working with Bio3D for molecular data                                                                                                                                                                                                                                                                                      |
| 7  | 05/11/20  | [**Machine learning for Bioinformatics**](#7) <br> Unsupervised learning, K-means clustering, Hierarchical clustering, Heatmap representations. Dimensionality reduction, Principal Component Analysis (PCA)                                                                                                                                                                                                                                                            |
| 8  | 05/18/20  | [**Genome informatics and high throughput sequencing**](#8) <br> Searching genes and gene functions, Genome databases, Variation in the Genome, High-throughput sequencing technologies, biological applications, bioinformatics analysis methods; The Galaxy platform along with resources from the EBI & UCSC                                                                                                                                                                                                                                                            |
| 9  | 05/25/20  | [**Transcriptomics, RNA-Seq analysis, and the interpretation of gene lists**](#9) <br> RNA-Seq aligners, Differential expression tests, RNA-Seq statistics, Counts and FPKMs and avoiding P-value misuse, Hands-on analysis of RNA-Seq data with R. Gene function annotation, Functional databases KEGG, InterPro, GO ontologies and functional enrichment analysis.                                                                                                                                                                                                                                            |
| 10  | 06/01/20  | [**Course summary**](#10) <br> Summary of learning goals, Student course evaluation time; **Find a gene assignment due\!**                                                                                                                                                                                                              |



# Class material

---



<a name="1"></a>
## Week 1: Getting oriented

**Topics:**  
Course introduction, Learning goals & expectations, Meet the instructional team. Setup your computer with required software.   

**Goals:**
- Understand course scope, expectations, logistics and ethics code.  
- Complete the pre-course questionnaire.  
- Setup your computer for this course.  


**Videos:**
- 1.1 - [Course introduction and overview (intro to course)]()  
- 1.2 - [Meet the team (Barry, Alena & Hanqing)]() 
- 1.3 - [Meet the toolset (Website, Piazza, Zoom, R, RStudio, GitBash, Galaxy)]()  
- 1.4 - [A note about COVID-19 and this most unusual of quarters]() 

**Supporting material:**  
- Handout: [Class Syllabus]({{ site.baseurl }}/class-material/BIMM143_S20_syllabus.pdf){:.no-push-state}{:target="_blank"},  
- Pre-course [Questionnaire](https://forms.gle/9iP4PsU6UJ6MPfuo7){:target="_blank"},   
- Computer [Setup Instructions]({{ site.baseurl }}/setup/).  



---

<a name="2"></a>
## Week 2: Welcome to Bioinformatics

**Topics:**
Biology is an information science, History of Bioinformatics, Types of data, Application areas and introduction to upcoming course segments, Introduction to NCBI & EBI resources for the molecular domain of bioinformatics, Hands-on session using NCBI-BLAST, Entrez, GENE, UniProt, Muscle and PDB bioinformatics tools and databases.

**Goals:**
- Understand the increasing necessity for computation in modern life sciences research.  
- Get introduced to how bioinformatics is practiced. 
- Be able to query, search, compare and contrast the data contained in major bioinformatics databases (GenBank, GENE, UniProt, PFAM, OMIM, PDB) and describe how these databases intersect. 
- The goals of the hands-on session is to introduce a range of core bioinformatics databases and associated online services whilst actively investigating the molecular basis of several common human disease.  


**Videos:**
- 2.1 - [Introduction to bioinformatics (what, where and why of bioinformatics)]()  
- 2.2 - [Major bioinformatics resource providers (NCBI and EBI)]()  
- 2.3 - [A quick tour of major NCBI and EBI resources (GENE, UniProt, GO, OMIM, PDB, PFAM)]()  


**Supporting Material**:  
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture1-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture1-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},      
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/lab-1-bimm143.pdf){:target="_blank"}{:.no-push-state}  
- Feedback: [Muddy Point Assessment](https://forms.gle/fHMc1C5gd7hh5eog7){:.no-push-state}{:target="_blank"},    


**Homework**:  
- [Questions](https://forms.gle/dtaBRcPb1ydGJceUA){:.no-push-state}{:target="_blank"},  
- Readings: 
  - PDF1: [What is bioinformatics? An introduction and overview]({{ site.baseurl }}/class-material/bioinformatics_review.pdf){:.no-push-state},  
  - PDF2: [Advancements and Challenges in Computational Biology]({{ site.baseurl }}/class-material/bioinformatics_challenges_2015.pdf){:.no-push-state}.  
  

---

<a name="3"></a>
## Week 3: Sequence alignment fundamentals, algorithms and applications

**Topics:**
Sequence Alignment and Database Searching: Homology, Sequence similarity, Local and global alignment, Heuristic approaches, Database searching with BLAST, E-values and evaluating alignment scores and statistics.

**Goals:**
- Be able to describe how dynamic programming works for pairwise sequence alignment.  
- Appreciate the differences between global and local alignment along with their major application areas.  
- Understand how aligning novel sequences with previously characterized genes or proteins provides important insights into their common attributes and evolutionary origins.  
- The goals of the hands-on session are to explore the principles underlying the computational tools that can be used to compute and evaluate sequence alignments.  


**Videos:**  
- 3.1 - [Alignment fundamentals]()  
- 3.2 - [Dot plots]()  
- 3.3 - [Dynamic programing, global alignment]()  
- 3.4 - [Dynamic programing, local alignment]()  
- 3.5 - [BLAST basics and search statistics]()   

**Supporting Material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture2-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture2-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},    
- [Handout: Major Bioinformatics Databases]({{ site.baseurl }}/class-material/Major_Databases_BIMM143.pdf){:.no-push-state}{:target="_blank"}  
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/lecture2-BIMM143-lab.pdf){:.no-push-state}{:target="_blank"}  
- Feedback: [Muddy Point Assessment](https://forms.gle/T1LnVTjLWp8ZJCJh9){:.no-push-state}{:target="_blank"}.   
     


**Homework**:   
- [Questions](https://forms.gle/hx4mLpUouH6XmCk9A){:.no-push-state}{:target="_blank"},  
- [Alignment Problem]({{ site.baseurl }}/class-material/lecture2-BIMM134_homework.pdf){:.no-push-state}{:target="_blank"},  


**Readings**:    
- Readings: PDF1: [What is dynamic programming?]({{ site.baseurl }}/class-material/Dynamic_programming_primer.pdf){:.no-push-state},  
- Readings: PDF2 [Fundamentals of database searching]({{ site.baseurl }}/class-material/Fundamentals.pdf){:.no-push-state}.   


 
---
<a name="11"></a>
<br>


## Week 4: (**Project:**) Find a Gene Assignment Part 1        
The [**find-a-gene project**]({{ site.baseurl }}/class-material/Find_A_Gene_Project.pdf){:.no-push-state} is a required assignment for BIMM-143. The objective with this assignment is for you to demonstrate your grasp of database searching, sequence analysis, structure analysis and the R environment that we have covered to date in class.

You may wish to consult the scoring rubric at the end of the above linked project description and the [**example report**]({{ site.baseurl }}/class-material/Find_A_Gene_Project_Example.pdf){:.no-push-state} for format and content guidance.  
 
Your responses to questions Q1-Q4 are due **Friday May 15th** (05/15/20) at 12pm San Diego time.   

The complete assignment, including responses to all questions, is **Friday June 5th** (06/05/20) at 12pm San Diego time.  

Late responses will not be accepted under any circumstances.  


---
<a name="4"></a>
## Week 4: Bioinformatics data analysis with R


**Topics:**
Why do we use R for bioinformatics? R language basics and the RStudio IDE, Major R data structures and functions, Using R interactively from the RStudio console.

**Goal:**
- Understand why we use R for bioinformatics
- Familiarity with R’s basic syntax,
- Be able to use R to read and parse comma-separated (.csv) formatted files ready for subsequent analysis,
- Familiarity with major R data structures (vectors, matrices and data.frames),
- Understand the basics of using functions (arguments, vectorizion and re-cycling).


**Videos:**
- 4.1 [Why R]()  
- 4.2 [Using RStudio]()  
- 4.3 [Major R data structures, data types, and using functions]()
- 4.4 [Using DataCamp (intro to R and intermediate R)]()

**Supporting Material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture4-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture4-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on section 1]({{ site.baseurl }}/class-material/04_rintro/){:.no-push-state},  
- Feedback: [Muddy point assessment](https://goo.gl/forms/d23JGkVJyr0EcpTg2){:.no-push-state}{:target="_blank"},  
  


**Homework**:   
- Due today: [DataCamp, Into to R!](https://www.datacamp.com/){:.no-push-state}{:target="_blank"}.  
- Due next week: [DataCamp,  Intermediate R!](https://www.datacamp.com/){:.no-push-state}{:target="_blank"}.    



---
<a name="5"></a>
## Week 5: Data exploration and visualization in R

**Topics:** 
The exploratory data analysis mindset, Data visualization best practices, Simple base graphics (including scatterplots, histograms, bar graphs, dot chats, boxplots and heatmaps), Building more complex charts with ggplot.


**Goal:**
- Appreciate the major elements of exploratory data analysis and why it is important to visualize data.  
- Be conversant with data visualization best practices and understand how good visualizations optimize for the human visual system.  
- Be able to generate informative graphical displays including scatterplots, histograms, bar graphs, boxplots, dendrograms and heatmaps and thereby gain exposure to the extensive graphical capabilities of R.  
- Appreciate that you can build even more complex charts with ggplot and additional R packages such as rgl. !!To update!!


**Videos:**
- 5.1 - [Using base plot]() 
- 5.2 - [Introduction to ggplot]()
- 5.3 - [Data visualization best practices]()
- 5.4 - [Going further with ggplot course on DataCamp]()

**Supporting Material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture5-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture5-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- Rmarkdown documents for [plot session 1]({{ site.baseurl }}/class-material/05_draw_circle_points/){:.no-push-state}{:target="_blank"}, and [more advanced plots]({{ site.baseurl }}/class-material/05_draw_lecture_plots2/){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on worksheet]({{ site.baseurl }}/class-material/lecture5_lab_web.html){:.no-push-state}{:target="_blank"},
- Lab: [Supplement: Plotting with color in R]({{ site.baseurl }}/class-material/Rcolor.html){:.no-push-state}{:target="_blank"}, 
- Lab: [PDF supplement]({{ site.baseurl }}/class-material/lecture5-BIMM143_lab.pdf){:.no-push-state}{:target="_blank"}, 
- Example data for hands-on sections [bimm143_05_rstats.zip]({{ site.baseurl }}/class-material/bimm143_05_rstats.zip){:.no-push-state},  
- Feedback: [Muddy point assessment](https://forms.gle/FJHD9Bnrmgj32Tk69){:.no-push-state}{:target="_blank"},  
 
 
**Homework**:   
- This units homework is all [via **DataCamp** (Intro to R, Intermideate R)](https://www.datacamp.com/){:.no-push-state}{:target="_blank"}.   
 

---
<a name="6"></a>
## Week 6: The why, when and how of writing your own R functions

**Topics:** 
Using R scripts and Rmarkdown files, Import data in various formats both local and from online sources, The basics of writing your own functions that promote code robustness, reduce duplication and facilitate code re-use.

**Goals:**
- Be able to import data in various flat file formats from both local and online sources.
- Understand the structure and syntax of R functions and how to view the code of any R function.
- Understand when you should be writing functions.
- Be able to follow a step by step process of going from a working code snippet to a more robust function.

**Videos:**  
- 6.1 - [Project introduction  (your find a gene assignment begins)]()
- 6.2 - [Writing your own functions (why and when)]()
- 6.3 - [Example function writing (how)]()
- 6.4 - [Another function example]()

**Supporting material:**
 Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture6-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture6-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},
- Flat files for importing with read.table: [test1.txt]({{ site.baseurl }}/class-material/test1.txt){:.no-push-state}, [test2.txt]({{ site.baseurl }}/class-material/test2.txt){:.no-push-state}, [test3.txt]({{ site.baseurl }}/class-material/test3.txt){:.no-push-state}.  
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/lecture6-BIMM143_W19.pdf){:.no-push-state}{:target="_blank"},  
- Feedback: [Muddy point assessment](https://forms.gle/8EaXUypQFPKucYME8){:.no-push-state}{:target="_blank"},  


**Homework**:   
- Project  ADD DETAILS HERE!  
- See **Q6** of the [hands-on lab sheet above]({{ site.baseurl }}/class-material/lecture6-BIMM143_W19.pdf){:.no-push-state}{:target="_blank"}. This entails turning a supplied code snippet into a more robust and re-usable function that will take any of the three listed input proteins and plot the effect of drug binding. Note assessment rubric and submission instructions within document. (Submission deadline: 9:30am next **Th, 01/30/20**).    
- The remainder of this units homework is all [via **DataCamp**](https://www.datacamp.com/){:.no-push-state}.   
 


---
<a name="12"></a>
## Week 6: Bioinformatics R packages from CRAN and BioConductor

**Topics:** 
More on how to write R functions with worked examples. Further extending functionality and utility with R packages, Obtaining R packages from CRAN and Bioconductor, Working with Bio3D for molecular data, Managing genome-scale data with bioconductor.

**Goals:**
- Be able to find and install R packages from CRAN and bioconductor,  
- Understand how to find and use package vignettes, demos, documentation, tutorials and source code repository where available.  
- Be able to write and (re)use basic R scripts to aid with reproducibility.  

**Videos:**  
- 6.5 - [Introduction to CRAN]()
- 6.6 - [Introduction to BioConductor]()  
- 6.7 - [How to best explore packages (using vignettes, GitHub, community forums and online tutorials)]()  

**Supporting material:**  
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture07-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture07-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- [Collaborative Google Doc based notes on selected R packages](https://docs.google.com/document/d/1dEYypb4mUNJFUhER9a9p7slQPmCsFt2XqGLla8K6fG8/edit?usp=sharing){:.no-push-state}{:target="_blank"},    
- [Introductory tutorial on R packages](https://www.datacamp.com/community/tutorials/r-packages-guide){:.no-push-state}{:target="_blank"},  
- Feedback: [Muddy point assessment](https://forms.gle/eUNPU9xAV2WLabu28){:.no-push-state}.      
- SideNote: [Convincing with graphics](https://xkcd.com/833/){:.no-push-state}.   
 
 
**Homework**:   
 See **Q6** from the last days [hands-on lab sheet above]({{ site.baseurl }}/class-material/lecture6-BIMM143_W19.pdf){:.no-push-state}. This entails turning a supplied code snippet into a more robust and re-usable function that will take any of the three listed input proteins and plot the effect of drug binding. Note assessment rubric and submission instructions within document. (Submission deadline: 9am **next class**).    
- The remainder of this units homework is all [via **DataCamp**](https://www.datacamp.com/){:.no-push-state}.   
 



---
<a name="7"></a>
## Week 7: Introduction to machine learning for Bioinformatics

**Topics:** 
The find-a-gene project is a required assignment for BIMM-143. The objective with this assignment is for you to demonstrate your grasp of database searching, sequence analysis, structure analysis and the R environment that we have covered to date in class.

Unsupervised learning, supervised learning and reinforcement learning; Focus on unsupervised learning, K-means clustering, Hierarchical clustering, Heatmap representations. Dimensionality reduction, visualization and analysis, Principal Component Analysis (PCA) Practical considerations and best practices for the analysis of high dimensional datasets.


**Goal:**  
- Understand the major differences between unsupervised and supervised learning.  
- Be able to create k-means and hierarchical cluster models in R  
- Be able to describe how the k-means and bottom-up hierarchical cluster algorithms work.  
- Know how to visualize and integrate clustering results and select good cluster models.  
- Be able to describe in general terms how PCA works and its major objectives.  
- Be able to apply PCA to high dimensional datasets and visualize and integrate PCA results (e.g identify outliers, find structure in features and aid in complex dataset visualization).

Unsupervised Learning Mini-Project
Topics: Longer hands-on session with unsupervised learning analysis of cancer cells, Practical considerations and best practices for the analysis and visualization of high dimensional datasets.

**Videos:**
- 7.1 - [Introduction to unsupervised learning]()   
- 7.2 - [Clustering: kmeans]()  
- 7.3 - [Clustering: hclust]()  
- 7.4 - [Principal component analysis (PCA and related methods)]()   
- 7.4 - [Combining methods (using clustering and PCA together)]()  

**Supporting material:**  
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture08-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture08-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- WebApp: [Introduction to PCA]({{ site.baseurl }}/class-material/pca/){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on section worksheet for PCA]({{ site.baseurl }}/class-material/lab-8-bimm143.html){:.no-push-state}{:target="_blank"},  
- Data files: [UK_foods.csv]({{ site.baseurl }}/class-material/UK_foods.csv){:.no-push-state},   
- Feedback: [Muddy point assessment](https://docs.google.com/forms/d/e/1FAIpQLSdiQn7n6XvvRGq5AfQWaRa7G22-twFCN4bYNANCWSK09DBYZg/viewform){:.no-push-state}.  

 

**Other Material**:  
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture09-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture09-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on section worksheet for PCA]({{ site.baseurl }}/class-material/lab-9-bimm143.html){:.no-push-state}{:target="_blank"},  
- Data file: [WisconsinCancer.csv]({{ site.baseurl }}/class-material/WisconsinCancer.csv){:.no-push-state}, [new_samples.csv]({{ site.baseurl }}/class-material/new_samples.csv){:.no-push-state}.     

- Bonus: [Kevin’s StackExchange Link on PCA](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa){:.no-push-state}{:target="_blank"}.   



---
<a name="8"></a>
## Week 8: Genome informatics

**Topics:** 
Genome sequencing technologies past, present and future (Sanger, Shotgun, PacBio, Illumina, toward the $500 human genome), Biological applications of sequencing, Variation in the genome, RNA-Sequencing for gene expression analysis; Major genomic databases, tools and visualization resources from the EBI & UCSC, The Galaxy platform for quality control and analysis; Sample Galaxy RNA-Seq workflow with FastQC and Bowtie2

**Goals:**
- Appreciate and describe in general terms the rapid advances in sequencing technologies and the new areas of investigation that these advances have made accessible.  
- Understand the process by which genomes are currently sequenced and the bioinformatics processing and analysis required for their interpretation.  
- For a genomic region of interest (e.g. the neighborhood of a particular SNP), use a genome browser to view nearby genes, transcription factor binding regions, epigenetic information, etc.  
- Be able to use the Galaxy platform for basic RNA-Seq analysis from raw reads to expression value determination.  
- Understand the FASTQ file format and the information it holds.  
- Understand the SAM/BAM file format and the information it holds.  

**Videos:**  
- 8.1 - [Introduction to genomics]()  
- 8.2 - [HTS Sequencing methods]()  
- 8.3 - [Using Galaxy for HTS analysis]()  
- 8.4 - [Overview of major analysis steps]()  

**Supporting material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture13_BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture13_BIMM143-small.pdf){:.no-push-state}{:target="_blank"},
- [Hands-on section worksheet]({{ site.baseurl }}/class-material/lecture13-BIMM143-lab.pdf){:.no-push-state}{:target="_blank"},
- RNA-Seq data files: [HG00109_1.fastq]({{ site.baseurl }}/class-material/HG00109_1.fastq){:.no-push-state}, [HG00109_2.fastq]({{ site.baseurl }}/class-material/HG00109_2.fastq){:.no-push-state}, [genes.chr17.gtf]({{ site.baseurl }}/class-material/genes.chr17.gtf){:.no-push-state}, [Expression genotype results]({{ site.baseurl }}/class-material/rs8067378_ENSG00000172057.6.txt){:.no-push-state}, [Example R script]({{ site.baseurl }}/class-material/lecture13_plot.r){:.no-push-state}, [Example Rmd](https://github.com/bioboot/test_github/blob/master/lecture13_plot.md){:.no-push-state}.
- [SAM/BAM file format description]({{ site.baseurl }}//class-material/sam_format/){:.no-push-state}{:target="_blank"}.  
- Feedback: [Muddy point assessment](https://forms.gle/Qx4UTSc4zkpafRvq9){:.no-push-state}{:target="_blank"}.  

## IPs     
- nt1  IP: http://3.212.78.120/galaxy  
- nt2  IP: http://3.231.195.172/galaxy  


---
<a name="9"></a>
## Week 9: Transcriptomics and the analysis of RNA-Seq data

**Topics:** 
Analysis of RNA-Seq data with R, Differential expression tests, RNA-Seq statistics, Counts and FPKMs, Normalizing for sequencing depth, DESeq2 analysis. Gene finding and functional annotation from high throughput sequencing data, Functional databases KEGG, InterPro, GO ontologies and functional enrichment.  


**Goals:**  
- Given an RNA-Seq dataset, find the set of significantly differentially expressed genes and their annotations.  
- Gain competency with data import, processing and analysis with DESeq2 and other bioconductor packages.  
- Understand the structure of count data and metadata required for running analysis.  
- Be able to extract, explore, visualize and export results.  
- Perform a GO analysis to identify the pathways relevant to a set of genes (e.g. identified by transcriptomic study or a proteomic experiment). Use both Bioconductor packages and online tools to interpret gene lists and annotate potential gene functions.

**Videos:**
- 9.1 - [Analysis of RNA-Seq data]()  
- 9.2 - [Differential expression tests: DESeq2]()  
- 9.3 - [Genome annotation and the interpretation of gene lists]()  
- 9.4 - [Pathway analysis]()  

**Supporting material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture14_BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture14_BIMM143-small.pdf){:.no-push-state}{:target="_blank"}.
- Detailed [Bioconductor setup]({{ site.baseurl }}//class-material/bioconductor_setup/){:.no-push-state}{:target="_blank"} instructions.
- [Hands-on section worksheet]({{ site.baseurl }}/class-material/lab-14-bimm143.html){:.no-push-state}{:target="_blank"},
- Data files: [airway_scaledcounts.csv]({{ site.baseurl }}/class-material/airway_scaledcounts.csv){:.no-push-state}, [airway_metadata.csv]({{ site.baseurl }}/class-material/airway_metadata.csv){:.no-push-state}, [annotables_grch38.csv]({{ site.baseurl }}/class-material/annotables_grch38.csv){:.no-push-state}.
- [Muddy point assessment](https://goo.gl/forms/CjzYyzBT0VsuOvBt2){:.no-push-state}.  


**Readings**:
 - Excellent review article: [Conesa et al. A survey of best practices for RNA-seq data analysis. _Genome Biology_ 17:13 (2016)](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8){:.no-push-state}.
 - An oldey but a goodie: [Soneson et al. "Differential analyses for RNA-seq: transcript-level estimates improve gene-level inferences." _F1000Research_ 4 (2015)](https://f1000research.com/articles/4-1521/v2).
 - Abstract and introduction sections of: [Himes et al. "RNA-Seq transcriptome profiling identifies CRISPLD2 as a glucocorticoid responsive gene that modulates cytokine function in airway smooth muscle cells." _PLoS ONE_ 9.6 (2014): e99625](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0099625){:.no-push-state}.




**More?**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture15_BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture15_BIMM143-small.pdf){:.no-push-state}.  
- [Hands-on section worksheet]({{ site.baseurl }}/class-material/lab-15-bimm143.html){:.no-push-state}{:target="_blank"},  
- Data files: [GSE37704_featurecounts.csv]({{ site.baseurl }}/class-material/GSE37704_featurecounts.csv){:.no-push-state}, [GSE37704_metadata.csv]({{ site.baseurl }}/class-material/GSE37704_metadata.csv){:.no-push-state}.   
- Muddy point assessment
 

**R Knowledge Check**:
[**Quiz Assessment**](https://forms.gle/qnVdsaGCPii4z3DD6){:.no-push-state}{:target="_blank"}. 


**Readings**:    
 - Good review article: Trapnell C, Hendrickson DG, Sauvageau M, Goff L et al. "*Differential analysis of gene regulation at transcript resolution with RNA-seq*". Nat Biotechnol 2013 Jan;31(1):46-53. [PMID: 23222703](https://www.ncbi.nlm.nih.gov/pubmed/23222703){:.no-push-state}.  


---
<a name="10"></a>
## Week 10: Course wrap up, project completion

**Topics:** 
Summary of learning goals, Student course evaluation time; Find a gene assignment due. Open study. Student topic of choice from those below:


- Biological network analysis
- Cancer genomics
- Unix for Bioinformatics
- Structural Bioinformatics and computational drug design


---



  
**Screen Casts**:  

<br/>

<iframe width="560" height="315" src="https://www.youtube.com/embed/P2oSO7YPyfU?rel=0" frameborder="0" allowfullscreen></iframe>
**1 Welcome to BIMM-143:**
Course introduction and logistics.
{:.message}  

<br/>

<iframe width="560" height="315" src="https://www.youtube.com/embed/gJNXQfpErLY?rel=0" frameborder="0" allowfullscreen></iframe>
**2 What is Bioinformatics?**
Bioinformatics can mean different things to different people. What will we actually learn in this class?
{:.message}  

<br/>

<iframe width="560" height="315" src="https://www.youtube.com/embed/cCim7LrQZLY?rel=0" frameborder="0" allowfullscreen></iframe>
**3 How do we do Bioinformatics?**
Some basic bioinformatics can be done online or with downloaded tools. However, most often we will need a specialized computational setup.
{:.message}  

