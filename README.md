# ITS2PLANTS
The ITS2 reference dataset for subkingdom Viridiplantae

## How to cite
If you find this reference dataset useful and you are going to use it in a publication, please cite:
Banchi et al. (2019)................................................................

## Description
This reference dataset is named ITS2PLANTS, it includes 293,453 ITS2 sequences comprising 133 orders and 564 plant families within the subkingdom Viridiplantae (Cavalier-Smith, 1981). The ITS2 has already been proposed and widely used as universal barcode marker for plants. This comprehensive, updated (November 21th, 2018) and accurate reference dataset aims at providing a solid reference for ITS-based plant metabarcoding projects, which is of fundamental importance for results standardization. 
The dataset underwent manual identity checks and taxonomic assignment in order to remove misnamed sequences that impair correct taxonomic assignments. The reference dataset was validated and its reliability was tested with an ad hoc mock community and aerobiological samples. Curation and testing of the dataset are carefully described in Banchi et al. (2019) ........................................ 


## Repository content
"table_families.pdf" contains Families and orders included in the dataset and total families reported in NCBI GenBank.The sequences used to build the database were downloaded from NCBI GenBank.

"DATASET_Viridiplantae.tar.gz" contains the complete dataset (named TOTAL) and its de-replicated versions (99%, 97%, 95% and 90% identity) in .fasta format, each sequence is provided with taxonomy within the header. Sequences are identified by GeneBank accession number.  

"SEQ_Viridiplantae.tar.gz" and "TAXONOMY_Viridiplantae.tar.gz" archives contain the same datasets using QIIME2 format which requires sequences and taxonomy in two separate files. 


