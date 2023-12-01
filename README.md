# Metagenomics course at FGCZ

Welcome to the Metagenomics Course!

Table of contents:
* [Schedule]()
* [Course slides](slides/)
* [Course in the Bfabric](https://fgcz-bfabric.uzh.ch/bfabric/project/show.html?id=33613&tab=details): here you can find all the communication.


For more information please see the description of each Day.

## Day 1: Introduction and 16S analysis

Today we start with an introductory lecture. This will be followed by a short set of excercises focusing on data QC.

### SUSHI instructions - How to get there

Go to [https://fgcz-course1.bfabric.org/](https://fgcz-course1.bfabric.org/)

You will end up on a page like this, not exactly like this but the same outline:
![plot](pictures/sushi_entry_page.png)

In the top right corner (window "Project") enter your project number.
Here are your project numbers:

6001 - Roos G.\
6002 - Eunhee C.\
6003 - Elizabet L.\
6004 - Gianna S.\
6005 - Mauro E.\
6006 - Luca T.\
6007 - Asa W.\
6008 - Ian Y.\
6009 - Denise Lea W.\
6010 - Vadim N.\
6011 - Michele L.\
6012 - Bright N.\
6013 - Jessie James M.\

Exercise instructions:

### FastQC

First thing to be done when you get your raw data is run quality control tests. There are many tools available out there but today we are going to run FastQC.
Please look at the following slides to run the FastQC tutorial.

* [FastQC tutorial link](instructions/FastQC.pptx)

Now that we have completed the exercises we will go on to a lecture on 16S. We will then have a guest talk from a researcher using 16S in her research. Afterwards we will do an exercises using QIIME2.

### QIIME2 analysis 

The software we will use for analysing our 16S rRNA datasets is QIIME2. For more info please see: https://docs.qiime2.org/2023.2/. We will use a dataset from the Earth Microbiome Project as discussed. 

[![Read Processing (Colab)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bokulich-lab/uzh-microbiome-tutorial/blob/main/01_read_processing.ipynb)

In this notebook, we will process the data using qiime2. Click the link to access. The notebook is created by the authors of QIIME2.

After that we will continue to the following link to learn how to visualise QIIME2 data and create figures for publications: There are some questions on the way, please answer and we will look at them together afterwards. This notebook was created by us.

[![Qiime2 Visualisation (Colab)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zajacn/QIIME2_Tutorial_FGCZ_2023/blob/main/02_16SVisualisation.ipynb)

QIIME2 creates html outputs which can also be very helpful. Have a look at these reports below (click on the links) that are created when you run the analysis with us via SUSHI:

[Static Report](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/00index.html) - this is a combined report of all analysis with fixed/non interactive graphs\
[Demux Report](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/demux_seqs.qzv.zip.folder/data/index.html) - a QIIME2 interactive report of demultiplexed sequence counts and data quality\
[Denoising Stats](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/dada2_denoising_stats.qzv.zip.folder/data/index.html) - a QIIME2 table on the filtered reads at each step\
[Feature Table](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/table.qzv.zip.folder/data/index.html) - a QIIME2 interactive report on ASV summary \
[Rep Seqs](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/dada2_rep_set.qzv.zip.folder/data/index.html) - a QIIME2 table on all features - if you click a feature it will take you to BLAST\
[Taxonomy Barplot](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/taxa-bar-plots.qzv.zip.folder/data/index.html) - a QIIME2 interactive barplot showing the taxonomy\
[Taxonomy](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/taxonomy.qzv.zip.folder/data/index.html) - a QIIME2 table of all the ASVs and their taxonomic classification\
[Shannon Diversity](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/shannon_group_significance.qzv.zip.folder/data/index.html) - a QIIME2 interactive report of alpha diversity \
[Jaccard diversity](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/jaccard_group_significance.qzv.zip.folder/data/index.html) - a QIIME2 interactive report of beta diversity (jaccard) \
[Bray Curtis Diversity](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/bray_curtis_group_significance.qzv.zip.folder/data/index.html) - a QIIME2 interactive report of beta diversity (bray curtis) \
[Jaccard Emperor Plot](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/jaccard_emperor_plot.qzv.zip.folder/data/index.html) - a QIIME2 interactive 3D PCA based on Jaccard Matrix \
[Bray Curtis Emperor Plot](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/bray_curtis_emperor_plot.qzv.zip.folder/data/index.html) - a QIIME2 interactive 3D PCA based on Bray Curtis Matrix \ 
[Alpha Rarefaction](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/alpha-rarefaction.qzv.zip.folder/data/index.html) - a QIIME2 interactive plot showing rarefaction curve \
[Differential abundance](https://fgcz-gstore.uzh.ch/projects/p26990/QIIME2App_2023-10-30--15-59-29/Results_Folder/ancom_group.qzv.zip.folder/data/index.html) - a QIIME2 interactive report on results of ANCOM

All these reports refer to the following workflow:

![QIIME2 workflow](pictures/QIIME2.workflow.png)

## Day 2: Metagenomics

You made it to Day 2 ;)! Today we are focusing on Metagenomics leaving the amplicons behind. In order to do the first part you will need to use the command line.

### How to log into the cluster - NEEDED FOR FIRST PRACTICAL

First, before you begin the practical you need to be able to log in to the cluster. Click on the instructions below where you will find an explanation on how to do that. The instructions are different whether you have a mac or a windows computer. 

* [How to log in to cluster MAC](instructions/mac_cluster.md)
* [How to log in to cluster WINDOWS](instructions/window_cluster.md)

### Metagenome Atlas Tutorial 1

If you find yourself in a place that looks like this (except with your name and perhaps a different server):

![plot](pictures/cluster_location_scshot.png)

then you are good to go! Now you have to follow the following tutorial. During the tutorial you will be creating new folders and files. Sometimes you want to see what is within your whole directory. You can do that by typing 'ls -alt *'
Otherwise if you need any help on how to navigate, here is a bash cheet sheet. Using these commands you can enter new directories, open files and exit directories:

<img src="pictures/bashcheetsheet.png" width="300">

You can find the tutorial here: https://fgcz-shiny.uzh.ch/Metagenome_Atlas_Part_1/

## Day 3: Metagenomics and Metatranscriptomics

Again busy day ahead of us. But don't worry, last day! Today we first follow the tutorial on Metagenome Atlas but the second one this time. You don't need to log into the cluster like you did before. Everything is R based.

### Metagenome Atlas Tutorial 2

You will find all information within the tutorial on how to do it. 
You can find the precise instructions and the tutorial here: https://fgcz-shiny.uzh.ch/Metagenome_Atlas_Part_2/

REMEMBER THAT IF YOU WOULD LIKE TO GO BACK TO ANY OF THE TUTORIALS YOU CAN FIND ALL OF THE INFORMATION HERE (it is a bit different than what we have done): https://github.com/metagenome-atlas/Tutorial

Now that we have explored assembly-based metagenomics, lets explore assembly-free metagenomics and metatranscriptomics. A tool that we will use for assembly-free metagenomics is Kraken2. We will look at the theory behind Kraken and do a tutorial. We will produce an html report using Krona. 
Afterwards we will turn to Metatranscriptomics (see more info below).

### Kraken2 tutorial

You will run Kraken on SUSHI. If you would like a reminder on where to go, see above. Otherwise please follow the following tutorial. 

* [Kraken Tutorial](instructions/Kraken.pptx)

Keep in mind we are looking at a dataset that we worked on during Metagenome Atlas Part 1 tutorial. We did find out which genomes we managed to assemble. Do you remember? Do you think you could have skipped it all and gone straight to taxonomy from raw reads without assembling? Lets find out and use Kraken2 for this. You are looking for 2 genomes in sample1 and 3 genomes in sample2. 

<details>
  <summary>Check for Answers here!</summary>
  
  ### Sample Content
  1. Sample1: Mesomycoplasma hyorhinis, Streptococcus thermophilus
  2. Sample2: Mesomycoplasma hyorhinis, Ureaplasma urealyticum, Streptococcus thermophilus
</details>

For the metatransciptomics part of our day, we will talk on the theory behind metatranscriptomics and we will do a tutorial where we are going to use software called Samsa2. We will also get a glimpse of other meta-omics possibilities.

### Samsa2 tutorial

Now tutorial! We will also use SUSHI and we will run a report on SAMSA2 analysis. See below for exact instructions.

* [Samsa2 Tutorial](instructions/Samsa2.pptx)

There are several questions we will discuss after you familiarize yourself with the output. Have a detailed look at what the graphs are showing.
Here are the questions:

- Is species/functional diversity (richness and evenness) higher before or after
medication and do you observe the same trends in both patient groups?
 - What species dominate the vaginal microbiome before the application of
medication and what after the application of medication? Do you observe
differences in time point 1 between patients that did and did not respond to
treatment in terms of species? Do you think any of this can explain lack of the
response
- What is log2Fold change in transcript abundance from those species before and
after medication in both patient groups?
- 16S results were different. Why do you think that is?

![16S results](pictures/Metatranscriptomics_16S.png)

- Which functions have clearly been upregulated/downregulated in the microbiome
after successful curing of BV? Do you know anything about these functions? Could
you explain what has been happening?
- What functions do you see upregulated or downregulated in the microbiome of
patients who were not successfully treated? Are there any parallels with the cured
patients? Does anything interesting strike you?

Lets discuss.

THANK YOU AND CONGRATULATIONS FOR COMPLETING THE COURSE!!!
