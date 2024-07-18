# Steps for contact mapping
1. See the [Setup](/SH2_domain_setup.ipynb) file, this:
  * We produced a human reference SH2 CSV file CoDAC.helper.UniProt.makeReferenceFile. We hand annotated/identified differences (as noted in the notebook)
  * We produced a human reference SH2 Fasta file
  * We used promals3d to align
  * We produced a structure reference file (CoDAC.helper.PDB(SH2_human_reference.csv)) for all PDB IDs for the uniprot IDs from our reference (using CoDAC.helper.PDB_IDs(Uniprot_ID)), then annotated that structure reference file with UniprotRefFile in order to get inclusive domains.
  * We filtered to relevant PDBS that spanned SH2 domains within them, then got relevant CIF-based PDB Files (TBD) and converted these to adjacency lists using Arpeggio (TBD), then annotated the structurereferenceFile to account for CIF-based residue number differences.
2. 


