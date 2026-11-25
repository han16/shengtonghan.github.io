---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---




### 4. Deep-MOTIFs: an R package for a Deep learning framework for <ins>M</ins>ulti-<ins>O</ins>mics in<ins>T</ins>egrat<ins>I</ins>on <ins>F</ins>or auti<ins>S</ins>m

<p align="center">
  <a href="https://github.com/han16/Deep-MOTIFs" target="_blank">
    <img src="https://han16.github.io/shengtonghan.github.io/images/Han2026_deepmotifs.png?raw=true" 
         alt="Deep-MOTIFs workflow" style="width: 450px;">
  </a>
</p>

<span style="background-color: yellow; color: black;">Deep-MOTIFs</span>  is a deep learning framework to integrate multi-omics data for predicting risk genes not only for autism, but also for other traits and diseases as long as multi-omics data are available. Basically every gene was characterized with a high dimensional vector,  (tabular data), e.g. with the order of >1,000, consisting of continuous, discrete or whatever format, then Deep-MOTIFs learns the unique features associated with the  <span style="color: red;">known</span> risk genes and then predicts  <span style="color: green;">novel</span> risk genes genome-wide. 


**Reference paper**: Shengtong Han, Di Wang, Wenhui Sheng, Nathanael Chu, Integrating multi-omics data through deep learning with applications to autism risk gene prioritization, Briefings in Bioinformatics, Volume 27, Issue 5, September 2026, bbag588, https://doi.org/10.1093/bib/bbag588. 



### 3. MIRAGE: an R package for <ins>MI</ins>xture model based <ins>R</ins>are variant <ins>A</ins>nalysis on <ins>GE</ins>nes

<p align="center">
  <a href="https://xinhe-lab.github.io/mirage/" target="_blank">
    <img src="https://han16.github.io/shengtonghan.github.io/images/MIRAGEworkflow.png?raw=true" 
         alt="MIRAGE workflow" style="width: 450px;">
  </a>
</p>

<span style="background-color: yellow; color: black;"> MIRAGE </span> is a new Bayesian statistical method for rare variant (RV) association testing that better accounts for heterogeneity of variant effects within a gene using external functional annotations. It partitions variants into disjoint groups and variants with similar effect size are assigned into one group. MIRAGE estimates the effet size of every group and calculates the likelihood of a gene that is a risk gene by Bayes factor. Summary statistics, i.e. total number of variants in cases and controls, rather than individual level variant information  at every single genomic locus are required as input. The samples need to be matched between cases and controls.   [[read more]](https://xinhe-lab.github.io/mirage/index.html). 


[MIRAGE_v2](https://github.com/shan-team/mirageV2) is an updated version of MIRAGE that optimized the algorithm that run much faster. 

**reference paper**: Han S, Sun X, Sloofman L ...
MIRAGE: A Bayesian statistical method for gene-level rare-variant analysis incorporating functional annotations
The American Journal of Human Genetics, 2025; 113, 168-183. 





### 2. GEARS: an R package for  <ins>G</ins>aussian differ<ins>E</ins>nti<ins>A</ins>l netwo<ins>R</ins>k analysi<ins>S</ins>



<p align="center">
  <a href="https://github.com/han16/GEARS" target="_blank">
    <img src="https://han16.github.io/shengtonghan.github.io/images/gears.png?raw=true" 
         alt="MIRAGE workflow" style="width: 450px;">
  </a>
</p>





GEARS is a Bayesian approach to reconstruct Gaussian Bayesian network and compare two networks (identical or differential) with graph ordering unknown. [[read more]](https://github.com/han16/GEARS)

### 1. BBNI: an R package for <ins>B</ins>ayesian  <ins>B</ins>oolean  <ins>N</ins>etwork <ins>I</ins>nference




<p align="center">
  <a href="https://shan-team.github.io/BBNI/" target="_blank">
    <img src="https://han16.github.io/shengtonghan.github.io/images/BNdiagram.JPG?raw=true" 
         alt="MIRAGE workflow" style="width: 450px;">
  </a>
</p>



BBNI is a Bayesian approach for Boolean network reconstruction. It employs MCMC to sample the posterior distribution of both the network topology and transition functions, thus takes into account the data random noise and model uncertainty. [[read more]](https://shan-team.github.io/BBNI/)

**Reference paper**: Han S, Wong RKW, Lee TCM, Shen L, Li S-YR, Fan X (2014). A Full
  Bayesian Approach for Boolean Genetic Network Inference. PLoS ONE
  9(12): e115806. doi:10.1371/journal.pone.0115806


