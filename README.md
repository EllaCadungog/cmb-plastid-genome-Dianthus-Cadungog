# cmb-plastid-genome-Dianthus-Cadungog

Analysis and characterization of the complete chloroplast genome of *Dianthus caryophyllus* using NCBI, Galaxy, and GitHub.

# Characterization of the Plastid Genome of *Dianthus caryophyllus*

## Student Information

**Student Name:** Ella Pearl V. Cadungog  
**Program:** BS Biology  
**Subject:** Cell and Molecular Biology  

## Chosen Genus and Species

* **Genus:** *Dianthus*
* **Species:** *Dianthus caryophyllus*

## NCBI Accession and Source Links

* **NCBI RefSeq Accession:** NC_039650.1
* **NCBI Nucleotide Record:** https://www.ncbi.nlm.nih.gov/nuccore/NC_039650.1
* **NCBI GenBank Record:** https://www.ncbi.nlm.nih.gov/nuccore/NC_039650.1?report=genbank

## Date Retrieved

**Date Retrieved:** October 8, 2026

## Genome Size and Plastome Summary

The chloroplast genome of *Dianthus caryophyllus* is a complete circular plastome with the typical quadripartite organization commonly found in angiosperm chloroplast genomes. It consists of a Large Single-Copy (LSC) region, a Small Single-Copy (SSC) region, and two Inverted Repeat (IR) regions.

The main structural regions of the plastome are:

* **Large Single-Copy (LSC) region:** 84,775 bp
* **Small Single-Copy (SSC) region:** 17,102 bp
* **Inverted Repeat A (IRa):** 22,863 bp
* **Inverted Repeat B (IRb):** 22,863 bp

The plastome contains protein-coding genes, transfer RNA (tRNA) genes, and ribosomal RNA (rRNA) genes that contribute to photosynthesis, transcription, translation, and other essential plastid functions.

## Genome Download and Galaxy Upload Procedure

The complete chloroplast genome of *Dianthus caryophyllus* (NC_039650.1) was obtained from the NCBI RefSeq database.

The FASTA sequence was downloaded from the NCBI Nucleotide record using the FASTA display option. The annotated genome record was obtained from the GenBank format page.

The FASTA file was uploaded to Galaxy:

https://usegalaxy.org

Galaxy recognized the uploaded dataset as a FASTA file. The dataset was renamed using the species name and accession number to make the analysis easier to identify and reproduce.

## Galaxy History and Tools Used

### Galaxy History Name

**Plastid_Dianthus_Cadungog**

### Tools Used

**FASTA Statistics / gfastats (Sequence Statistics):** Used through Galaxy to determine the basic characteristics of the chloroplast genome, including genome length, sequence count, and GC content.

**GeSeq (v2.03):** Used for automated annotation of the chloroplast genome to identify gene boundaries, protein-coding genes, tRNA genes, rRNA genes, introns, and other plastid genome features.

## Results

| Parameter | Value |
|---|---|
| Genome Length | 147,604 bp |
| Number of Sequences | 1 |
| GC Content | 36.30 % |

## Gene Content and Important Observations

### Gene Content Summary

| Category | Count |
|---|---:|
| Total Unique Genes | 123 |
| Protein-Coding Genes | 83 |
| tRNA Genes | 34 |
| rRNA Genes | 6 |

### Important Observations

The plastome of *Dianthus caryophyllus* displays the typical LSC-SSC-IR quadripartite organization observed in many flowering plants.

Genes located within the inverted repeat regions are duplicated because the two IR regions contain corresponding copies of the same DNA sequences.

The chloroplast genome contains genes involved in photosynthesis, transcription, translation, and other important plastid functions.

The **rps12** gene is associated with trans-splicing, with different portions of the gene located in separate regions of the chloroplast genome.

Several genes contain introns, including:

* **rps16**
* **atpF**
* **rpoC1**
* **petB**
* **petD**
* **rpl16**
* **ndhB**
* **ndhA**
* **ycf1**
* **ycf3**
* **clpP**

Among these genes, **rps16, atpF, rpoC1, petB, petD, rpl16, ndhB, ndhA, and ycf1** contain one intron, while **ycf3 and clpP** contain two introns.

The plastome of *Dianthus caryophyllus* belongs to the family **Caryophyllaceae**. Therefore, its plastid genome characteristics are interpreted in the context of Caryophyllaceae rather than the grass-specific plastome features found in *Oryza sativa*.

## Data Sources and References

### Databases

**NCBI RefSeq Nucleotide Database**

https://www.ncbi.nlm.nih.gov/nuccore/NC_039650.1

**NCBI GenBank Record**

https://www.ncbi.nlm.nih.gov/nuccore/NC_039650.1?report=genbank

### Software and Annotation References

**GeSeq Annotation Tool:**

Tillich, M., Lehwark, P., Pellizzer, T., Ulbricht-Jones, E. S., Fischer, A., Bock, R., & Greiner, S. (2017). GeSeq – versatile and accurate annotation of organelle genomes. *Nucleic Acids Research*, 45(W1), W6–W11.

https://doi.org/10.1093/nar/gkx391

## Primary Reference

Yang, G., et al. (2018). Structural characteristic and phylogenetic analysis of the complete chloroplast genome of *Dianthus caryophyllus*. *Mitochondrial DNA Part B: Resources*, 3(2), 1004–1005.

## Reproducibility Statement

Another student can reproduce this analysis by:

1. Accessing the NCBI RefSeq record **NC_039650.1** for *Dianthus caryophyllus*.
2. Downloading the complete chloroplast genome FASTA sequence.
3. Uploading the FASTA sequence to Galaxy.
4. Running the **FASTA Statistics / gfastats** tool to obtain the total genome length, sequence count, and GC content.
5. Submitting the FASTA sequence to the **GeSeq organellar genome annotation web server (v2.03)**.
6. Using chloroplast reference sets to identify and annotate protein-coding genes, tRNAs, rRNAs, introns, and gene boundaries.
7. Reviewing and comparing the GeSeq annotation with the NCBI GenBank annotation.
8. Recording the genome size, GC content, gene composition, and major plastome features.
9. Examining the LSC, SSC, and IR regions and identifying genes duplicated within the IR regions.
10. Comparing the obtained results with the published information for *Dianthus caryophyllus*.
