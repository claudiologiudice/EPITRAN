# EPITRAN course 24/06/21
<p align="justify"> Epitranscriptome refers to all biochemical RNA modifications affecting cellular RNAs. 
To date, >150 different RNA modifications have been discovered, and, among them, RNA editing represents the most prominent post-transcriptional mechanism.<br> 
In mammals, it involves the deamination of cytosine to uridine or, more commonly, the conversion of adenosine to inosine (A-to-I) and, concurrently with alternative splicing, increases the diversity of the eukaryotic transcriptome and proteome.<br>
Nowadays, RNAseq is the de facto standard approach to discover RNA editing candidates in whole eukaryotic genomes.
Although the identification of editing sites is, in principle, quite simple, it represents a computational challenge because true RNA editing events have to be discriminated from genome-encoded SNPs and technical artefacts caused by sequencing or read-mapping errors.<br>
The use of genomic reads from whole genome sequencing (WGS) or whole exome sequencing (WXS) experiments in single individuals, annotations in dbSNP
and several stringent filters can minimize the detection of false RNA editing candidates
To promote and facilitate the investigation of RNA editing at genomic scale, we developed and released the first software package devoted to this purpose, named <b>REDItools</b>. <br>
It comprises a suite of python scripts has been conceived to handle massive transcriptome sequencing data through a variety of filters to provide accurate RNA editing calls.<br>
Reditools have been applied in thousands of human RNAseq experiments, leading to the discovery of >16 million events in several human body sites, collected in our specialized <b>REDIportal</b> database.<br>
REDItools and REDIportal represent two relevant and efficient computational resources to investigate RNA editing in a variety of organisms and in different physiological and pathological conditions.<br> 
Today, we are going to reproduce step-by-step a bioinformatics pipeline aimed to study A-to-I editing in human samples, combininig both Reditools and Rediportal information.
</p>
