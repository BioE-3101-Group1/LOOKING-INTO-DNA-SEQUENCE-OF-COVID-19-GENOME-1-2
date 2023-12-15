# <p align="center">LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2</P>
## INTRODUCTION
<p align="justify">The year 2019 saw the emergence of a new coronavirus known as SARS-CoV-2, which rapidly caused a global health disaster known as COVID-19. When an infected person coughs, sneezes, or speaks, respiratory droplets are the main way that the virus spreads from person to person. The convergence of data analysis and sophisticated algorithms in the modern healthcare environment has greatly increased the significance of illness prediction and management, with a focus on the COVID-19 worldwide pandemic. In order to support early diagnosis and treatment, it is now important to develop precise and fast predictive analysis  as the number of infected patients increases. Given the prevalence of the disease and the variety of its symptoms, advanced instruments that are capable of identifying complex patterns and risk factors. Consequently, this enables medical personnel to make better-informed conclusions, which may result in initial treatments and better patient outcomes.</p>
<p align="justify">In the pursuit of advancing our understanding and management of the COVID-19 pandemic, this study embarked on an important objective. The main goal of this study was to analyze the data of  COVID 19 disease by using the data set of genome sequence for analysis and information. The dataset includes a diverse set of genome sequences  allowing for a detailed examination of its genetic variations. The objective is to use the information obtained from the dataset analysis to support prevention healthcare initiatives.</p>

## OBJECTIVES
* <p align="justify">To analyze the Covid 19 disease based on the given dataset.</p>
* <p align="justify">Visualize the data using relevant graphs and charts in order to understand the correlations between various characteristics.</p>
* <p align="justify">Conduct a thorough statistical analysis of the SARS-CoV-2 dataset for a better understanding of the variable distribution and features.
* <p align="justify">Explore the developed program's practical applications in various healthcare environments.

## METHODOLOGY
<p align="justify">The Biopython Project is an international association of developers of freely available Python tools for computational molecular biology. Python is an object oriented, interpreted, flexible language that is becoming increasingly popular for scientific computing. </p>
<p align="justify">In this project, COVID genome will be analyzed by using the Python language. The sequence used can be downloaded from http://www.ncbi.nlm.nih.gov/. NCBI is now a leading source for public biomedical databases, software tools for analyzing molecular and genomic data, and research in computational biology.</p>
<p align="justify">Various modules are needed to run the program which includes the following:</p>
* <p align="justify">numpy - adds powerful data structures to Python that guarantee efficient calculations with arrays and matrices and it supplies an enormous library of high-level mathematical functions.</p>
* <p align="justify">pandas - for analyzing, cleaning, exploring, and manipulating data.</p>
* <p align="justify">Bio - built for helping in performing genomic data analysis.</p>
* <p align="justify">nglview - allows interactive viewing of molecular structures as well as trajectories from molecular dynamics simulations.</p>
* <p align="justify">matplot - a comprehensive library for creating static, animated, and interactive visualizations in Python.</p>
* <p align="justify">seaborn - build on top of the matplotlib data visualization library and can perform exploratory analysis.</p>
<p align="justify">The following processes are utilized to analyze the COVID genome sequence:</p>

### I. Data Columns Description 
<p align="justify">The program used various codes, syntax, tools, and modules to generate the analysis capability of the system. The system used a genome sequence as data to be analyzed; the sequence consists of 29845 nucleotides to be analyzed. To further understand, the user must be familiarized with the data description below which are extracted from the genome sequence and will be used for the analysis.</p>

**FASTA File**
<p align="justify">A FASTA format is a text-based format for representing either nucleotide sequences or peptide sequences, in which base pairs or amino acids are represented using single-letter codes.</p>

**Nucleotide Composition**
<p align="justify">This displays the composition of each nucleotide present in the sequence; displaying the total number of bases. Each nucleotide contains a sugar and a phosphate molecule, which make up the 'backbone' of DNA, and one of four organic bases. The bases are adenine (A), guanine (G), cytosine (C) and thymine (T).</p>

**GC-content of Each Nucleotide**
<p align="justify">This section provides the number of Guanine-Cytosine bases that may represent the stability of the DNA, because GC-content level indicates higher melting temperature.</p>

**Tri-nucleotide Compositions (Trimer)**
<p align="justify">The trinucleotide composition of the genome is presented which can be used in the context of computational genomics and sequence analysis.</p>

### II. Preprocessing Data
<p align="justify">The data acquired from the previous section are processed to be used for molecular analysis. This includes performing protein synthesis, acquiring the amino acids from the synthesized proteins, and cleaning the list of proteins by removing chains smaller than 20 amino acids long.</p>

**Imitating Protein Synthesis**
The program imitates the protein synthesis of the genome. It performed transcription and translation. The process by which DNA is copied to RNA is called transcription, and that by which RNA is used to produce proteins is called translation. 

### III. Analysis
<p align="justify">After the data is cleaned and removed of short amino acids, they can now be analyzed through protein analysis and amino acid composition. In protein analysis, the longest amino acid chain is studied. It was analyzed using codes to reveal its Molecular Weight, Aromaticity, Isoelectric Point, and Composition. </p>

**Amino Acid Composition**
<p align="justify">The program takes a protein sequence as input and returns a dictionary representing the percentage composition of each amino acid in the given sequence.</p>

**Finding the Open Reading Frame**
<p align="justify">This generates Open Reading Frames (ORFs) from a protein sequence. ORFs are regions within a sequence that start with a start codon (usually "M" for methionine) and end with a stop codon. An ORF is a continuous sequence of nucleotides in DNA or RNA that potentially codes for a functional protein, which may be used for gene prediction, evolutionary studies, and genetic engineering.</p>
