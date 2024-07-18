# Steps for contact mapping
1. See the [Setup](/SH2_domain_setup.ipynb) file, this:
  * We produced a human reference SH2 CSV file. We hand annotated/identified differences (as noted in the notebook)
  * We produced a human reference SH2 Fasta file
  * We used promals3d to align
  * We produced a structure reference file for all PDB IDs for the uniprot IDs from our reference, then annotated that structure reference file with UniprotRefFile in order to get inclusive domains.
  * We filtered to relevant PDBs that spanned SH2 domains within them. 
2. AlphaFold
3. CIF file fetch
4. Adjacency 


