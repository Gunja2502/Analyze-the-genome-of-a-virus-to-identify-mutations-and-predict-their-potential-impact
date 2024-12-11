# Analyzing the Genome of Chikungunya Virus: Mutation Impact and Functional Prediction

## **Project Overview**
This project focuses on analyzing the genome of the Chikungunya virus (CHIKV) to:
- Identify genes within the viral genome.
- Determine the functions of these genes.
- Find closely related viral genomes.
- Detect mutations in the genome.
- Predict the impact of these mutations on gene and protein functionality.

## **Objectives**
- **Gene Identification**: Locate and characterize Open Reading Frames (ORFs) in the viral genome.
- **Functional Analysis**: Assign functional roles to genes using bioinformatics tools.
- **Evolutionary Relationships**: Compare genome sequences to find related viral strains.
- **Mutation Detection**: Identify mutations in the viral genome compared to reference sequences.
- **Impact Prediction**: Predict the structural and functional consequences of the identified mutations.

## **Tools and Resources**

### **Databases**
- **NCBI ORF Finder**: Identified ORFs.
- **Swiss-Prot Database**: Functional protein analysis.
- **PDB Database**: Structural protein information.

### **Tools**
- **BLAST**: Used for sequence alignment and homolog identification.
- **Clustal Omega**: Performed multiple sequence alignments.
- **Jalview**: Visualized and analyzed alignments.
- **MUSCLE**: For advanced sequence alignments.

## **Key Findings**
- **Gene Identification**: Identified 12 significant ORFs, with notable differences in frame lengths and coding capabilities.
- **Functional Insights**: Found closely matching proteins for ORFs using the Swiss-Prot database. Some ORFs coded for structural and replicative polyproteins critical to viral replication.
- **Mutation Analysis**: Detected several mutations, including transitions and transversions, that could alter protein function and viral behavior.
- **Challenges**: Limited structural data resolution from PDB impeded detailed mutation impact analysis.

## **Methodology**

### **Genome Analysis:**
- Extracted and analyzed viral genome sequences.
- Identified coding regions using ORF Finder.

### **Functional Annotation:**
- Used BLAST and Swiss-Prot to find homologous proteins.
- Interpreted protein function based on database annotations.

### **Mutation Analysis:**
- Conducted pairwise and multiple sequence alignments.
- Highlighted and categorized mutations (e.g., substitution, transition).

### **Structural Analysis:**
- Investigated structural consequences of mutations on protein function using PDB data.

## **Future Improvements**
- Use high-resolution 3D protein structures for more precise functional prediction.
- Expand sequence alignment analysis to additional viral isolates.
- Develop computational models to predict mutation impacts with higher accuracy.

## **Installation and Usage**

### **Prerequisites**
- Python 3.x
- Bioinformatics libraries: Biopython, Jalview
- Internet access for database tools


