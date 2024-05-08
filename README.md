# Woof-Repo
Project Overview:

This project focuses on leveraging bioinformatics techniques to explore genetic variations between different dog breeds, particularly Labrador Retrievers and Bulldogs. By analyzing genomic data, I aim to uncover insights into breed-specific traits, genetic predispositions, and evolutionary relationships.

Objectives:

- Compare the genetic profiles of Labrador Retrievers and Bulldogs to identify breed-specific variations.
- Investigate the molecular basis of phenotypic differences and disease susceptibilities between the two breeds.
- Contribute to the understanding of canine genetics and inform breeding programs and veterinary research.

Data Sources:

- Reference Genome of Labrador Retriever: This dataset provides the complete genome sequence of the Labrador Retriever, serving as a reference for comparative genomic analysis. See this link https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_014441545.1/
- Partial Sequence of Bulldog: The partial sequencing data from the Bulldog represents a subset of its genome, offering valuable insights into breed-specific genetic variations. See this link https://www.ncbi.nlm.nih.gov/sra/ERX10692180%5Baccn%5D

Data Collection:

I obtained genomic data from publicly available repositories, including the National Center for Biotechnology Information (NCBI). The reference genome of the Labrador Retriever was retrieved in FASTA format from the NCBI Genome database. Similarly, the partial sequence data of the Bulldog was accessed from the Sequence Read Archive (SRA) database in FASTQ format.

Data Format:

- Reference Genome (Labrador Retriever): The genome is provided in FASTA format, containing nucleotide sequences of chromosomes and associated metadata.

- Partial Sequence (Bulldog): The partial sequencing data is available in FASTQ format, comprising short nucleotide reads generated from high-throughput sequencing technology.

Preprocessing:

No preprocessing steps were performed on the reference genome of the Labrador Retriever. However, the partial sequence data of the Bulldog was processed using the prefetch and fasterq-dump tools to download and extract FASTQ files from the SRA database.

Tools Used:

The analysis pipeline involves the utilization of several bioinformatics tools to handle data retrieval, processing, and analysis.

- prefetch: A tool from the SRA Toolkit used to download data from the Sequence Read Archive (SRA) database efficiently.
- fasterq-dump: Another tool from the SRA Toolkit, used to extract FASTQ files from SRA data for downstream analysis.
- GATK (Genome Analysis Toolkit): A powerful software package for variant discovery and genotyping in high-throughput sequencing data. GATK will be employed to compare genetic variants between Labrador Retrievers and Bulldogs, enabling the identification of breed-specific differences.

These tools collectively facilitate the acquisition, preprocessing, and analysis of genomic data, enabling comprehensive investigation into the genetic landscapes of Labrador Retrievers and Bulldogs.
