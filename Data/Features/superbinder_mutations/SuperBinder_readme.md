## Superbinder annotations - how we curated them and their files
All files were created and hand annotated according the the fasta file in SuperBinder_Hand_Annotations. 
These were then translated onto the reference alignment of this project and those are all labled as featureName_translated.feature

### FYN Binding pocket
Taken from Kaneko, Tomonori, Haiming Huang, Xuan Cao, Xing Li, Chengjun Li, Courtney Voss, Sachdev S. Sidhu, and Shawn S. C. Li. “Superbinder SH2 Domains Act as Antagonists of Cell Signaling.” Science Signaling 5, no. 243 (September 25, 2012): ra68–ra68. These represent an independent replication of the binding pocket for FYN. We included the residue between 14 and 15 (Kaneko et al. numbering) - they did not mutate this, but it is a known interaction site to the ligand.

### Superbinder mutations
#### Kaneko et al., 2012
FYN - superbinder mutations taken from Kaneko et al. the triplet substitution that became the superbinders. We also noted the residues that appeared to be resistant to evolution, suggesting their mutations are detrimental (labled FYN_BindingPocket_NonEvolvable.feature)
* SRC -  from Kaneko et al. 2012 (aligned with FYN positions)
* GRB2 - from Kaneko et al. 2012 (from Methods A91, S96, K109)
Output file: superbinder_triplets.feature


#### Martyn et al. 2022 ACS Chemical Biology
This group went on to look at the expanded set of positions that when mutated increase affinity for ligand_contact residues.
* Added the larger set of amino acids back in that for FYN showed an increase and included Fes and other mutations that also worked. Started with supberbinder_triplets.feature to expand, so keeping the GRB2 and SRC sites.
* When adding the Fes loop, did not include the beta strand positions, which were modest substitutions (I to L) and were always coupled with the other sites
* Please note that the authors appear to have erroneously swapped the assignment of p85alpha/PIK3R1 and BRDG1/STAP-1 in Figure 6. STAP-1 sequences are EKP/RGN and p85alpha is SDP/LAQ.
