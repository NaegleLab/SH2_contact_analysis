# Steps for contact mapping
1. For InterPro SH2 superfamily (IPRxxx), we retrieved all uniprot IDs for the human species (default) (UniprotIDs = CoDAC.helper.Interpro(IPR))
2. We produced a human reference SH2 CSV file CoDAC.helper.UniProt.makeReferenceFile(outpufile to be udpated) 
3. We produced a human reference SH2 Fasta file (TO be written)
4. We produced a structure reference file (CoDAC.helper.PDB(SH2_human_reference.csv)) for all PDB IDs for the uniprot IDs from our reference (using CoDAC.helper.PDB_IDs(Uniprot_ID)), then annotated that structure reference file with UniprotRefFile in order to get inclusive domains.
5. We filtered to relevant PDBS that spanned SH2 domains within them, then got relevant CIF-based PDB Files (TBD) and converted these to adjacency lists using Arpeggio (TBD), then annotated the structurereferenceFile to account for CIF-based residue number differences. 


