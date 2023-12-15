# <p align="center">LOOKING INTO DNA SEQUENCE OF COVID-19 GENOME 1 & 2</p>
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
<p align="justify">The program imitates the protein synthesis of the genome. It performed transcription and translation. The process by which DNA is copied to RNA is called transcription, and that by which RNA is used to produce proteins is called translation. </p>


### III. Analysis
<p align="justify">After the data is cleaned and removed of short amino acids, they can now be analyzed through protein analysis and amino acid composition. In protein analysis, the longest amino acid chain is studied. It was analyzed using codes to reveal its Molecular Weight, Aromaticity, Isoelectric Point, and Composition. </p>

**Amino Acid Composition**
<p align="justify">The program takes a protein sequence as input and returns a dictionary representing the percentage composition of each amino acid in the given sequence.</p>

**Finding the Open Reading Frame**
<p align="justify">This generates Open Reading Frames (ORFs) from a protein sequence. ORFs are regions within a sequence that start with a start codon (usually "M" for methionine) and end with a stop codon. An ORF is a continuous sequence of nucleotides in DNA or RNA that potentially codes for a functional protein, which may be used for gene prediction, evolutionary studies, and genetic engineering.</p>

## RESULTS AND DISCUSSION
<p align="center"><img width="700" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/110b2495-2dc0-453f-831b-3e57eeee8675"></p>
<p align="justify">The nucleotide sequence of the coronavirus disease (COVID-19) genome is the specific order of nucleotide bases such as adenine (A), cytosine (C), guanine (G), and thymine  (T), that make up the genetic material of the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). 29,845 nucleotides are the total number of nucleotides used, however figure 1 only displays the initial 300 nucleotides for concise overview. Moreover, analyzing these initial sequences can provide insights about functional elements, such as coding region or regulatory sequence.</p>
<br>

<p align="center"><img width="400" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/ac8b5de0-6009-48a3-910e-4fbb49d41031"></p>
<p align="justify">The barplot offers a clear visual representation of the frequency distribution of nucleotides within the dataset. Each bar on the plot corresponds to a specific nucleotide, and the height of each bar reflects the relative abundance of that nucleotide in percentage terms. Analyzing the graph, the following composition percentages for each nucleotide are as follows: adenine (A) with 29.817%, cytosine (C) with 18.362%, guanine (G) with 19.605%, and thymine with 32.126%. These percentage values provide information about the proportional representation of each nucleotide in the analyzed dataset. Thymine, with the highest composition at 32.126%, stands out as the most prevalent nucleotide, while adenine, cytosine, and guanine contribute to the composition with their respective percentages. This breakdown not only highlights the prevalence of each nucleotide but also allows for a quick and comparative assessment of their distribution within the genomic sequence under consideration.</p>

<p align="center"><img width="300" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/7d2f71f1-8f47-4afb-ad65-cd9f706ba3ff"></p>
<p align="justify">Trimer refers to the sequence of three nucleotide bases that are consecutive along the DNA strand. The provided table offers a comprehensive overview of the dataset's trimer composition, presenting the corresponding count or number of occurrences for each unique trimer sequence. Each row in the table corresponds to a distinct trimer, while the associated count refers to the frequency with which each trimer appears in the DNA dataset.</p>
<br>

<p align="center"><img width="400" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/020cc067-234f-433b-b85b-b194b3dbd4bf"></p>
<p align="justify">Figure 4 serves as a visual complement to Figure 3, offering an alternative representation of the trimer distribution in the dataset. While Figure 3 presents the number of trimers in descending order, Figure 4 diverges by providing a barplot that showcases the distribution of trimers without a specific ordering. The barplot illustrates the distribution of the 32 unique trimer sequences found in the dataset, with each trimer associated with a distinct count of nucleotides. The longer bars signify more frequently occurring trimers, while shorter bars indicate less common ones.</p>
<br>

<p align="center"><img width="400" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/62451978-c31d-40b7-8c44-92d446989c39"></p>
<p align="justify">The table shows the length of amino acids. The count column shows the number of the amino acid sequence into the dataset. Seen in the middle column are the amino acid sequences that are being counted. The table only shows only 10 results as “nlargest” code was used for it to show the top 10 rows based on the count column. The table shows a clear representation of identifying the top 10 amino acid sequences by its length from the given data which can be useful in analysis of the dataset.</p>
<br>

<p align="center"><img width="300" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/a16e6d36-0852-4387-b3f5-7215ebec261c"></p>
<p align="justify">The table shows the protein sequence (ncov_protein), calculates the percentage composition of each amino acid using the defined function, converts the results into a DataFrame, sorts the DataFrame based on composition.</p>
<br>

<p align="center"><img width="400" alt="image" src="https://github.com/BioE-3101-Group1/LOOKING-INTO-DNA-SEQUENCE-OF-COVID-19-GENOME-1-2/assets/150891754/6d264d81-f15a-480a-86d6-2abada767fdc"></p>
<p align="justify">The figure is a visualization of the composition of amino acids in the table above using a bar chart with a purple color gradient. The visualization provides a quick and intuitive overview of the amino acid composition in the given protein sequence.</p>

## APPLICATION
<p align="justify">The application of the developed software has significant practical implications in real-world medical situations and is critical to the advancement of the healthcare industry. This technology enables healthcare institutions and pharmaceutical companies to develop treatments for serious illnesses more quickly and efficiently. This tool's predictive capability assists healthcare practitioners in categorizing risks and developing personalized treatment plans for individuals suspected of having cardiovascular issues. The program provides insight into the likelihood of various heart diseases by examining several predetermined factors. As a result, clinicians can make better decisions about diagnostic tests, interventions, and long-term management strategies.</p>
<p align="justify">Some useful applications of the software include Protein-DNA Interaction Modeling. Understanding how proteins interact with DNA is essential for understanding gene regulation and other cellular processes. These interactions are simulated and analyzed using molecular dynamics simulations and other modeling techniques. Another would be Drug Design and Discovery. DNA sequences are important drug targets. To aid in the discovery of potential therapeutic agents, computational methods can be used to predict the binding affinity of small molecules to specific DNA sequences. Last example is Structural Bioinformatics. Understanding the functions of biomolecules, including DNA, requires modeling their three-dimensional structures. DNA sequences are used by various software tools to predict and visualize the structure of DNA and its interactions with other molecules.</p>
<p align="justify">These advancements in healthcare help to streamline decision-making, improve overall quality, and address the changing medical landscape. They prioritize precision, efficiency, and patient-centric care, resulting in a more tailored and effective approach. As technology continues to shape the industry, these advancements position healthcare to meet current and future challenges.</p>

## CONCLUSION
<p align="justify">In conclusion, this python project stands as an indispensable asset in the analysis of COVID-19 datasets within the realm of bioinformatics. Its broad features allow for a thorough evaluation of genetic data, aiding viral genome decoding, identification of significant genetic markers, and a better understanding of the evolutionary patterns of a virus. It is a strong tool for sequence assembly, comparative genomics, and the understanding of viral genomic architecture due to capabilities such as determining nucleotide compositions, estimating GC-content, and examining Tri-mers. This not only aids in the dissection of individual COVID genomes, but also allows for comparison analysis across various strains, providing crucial insights into genetic variances, evolutionary links, and aiding in the discovery of potentially harmful mutations or variants.</p>
<p align="justify">Moreover, the project’s focus on protein synthesis, structural analysis, and property determination plays a pivotal role in comprehending the functional aspects of viral genes and proteins. This knowledge is critical in understanding the virus' intricacies, establishing focused therapeutic interventions, and producing medicines. It provides researchers with insights into the stability, functioning, and various features of proteins encoded by the virus by clarifying critical protein properties such as amino acid lengths, aromaticity, isoelectric points, and compositions. In essence, this versatile tool empowers bioinformaticians and researchers alike, offering a robust platform to decode genetic information, explore genomic intricacies, and uncover the underlying mechanisms governing biological systems.</p>

## DISCLAIMER
The instructions and code used in the project are based on the provided guidelines. The program and dataset used for this gathered from the work of SRESHTA PUTCHALA, retrieved from [https://www.kaggle.com/code/litaldavar/heart-disease-classification/notebook?fbclid=IwAR2cdwNNp4vxBi9uz7WbOQonzs0qwT-eMuV4JVDBU4kgN8FGGptylk7p93k](https://www.kaggle.com/code/sreshta140/looking-into-a-dna-sequence?fbclid=IwAR0BgQc_Wuhqgd_g0FaFJXspQ1sJEoq_22RBju4DqMHFJTivVM20HHDVlUI)https://www.kaggle.com/code/sreshta140/looking-into-a-dna-sequence?fbclid=IwAR0BgQc_Wuhqgd_g0FaFJXspQ1sJEoq_22RBju4DqMHFJTivVM20HHDVlUI and https://www.kaggle.com/code/sreshta140/looking-into-dna-sequence-2/notebook?fbclid=IwAR1xayAgDqs4uAOPYyB_Gp6P1YkB2jRgWLrHRNGKJL46c01W_3shKupi5lo


