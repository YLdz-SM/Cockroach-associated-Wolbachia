# Cockroach-associated _Wolbachia
Urban entomology heavily relies on the use of conventional insecticides for cockroach management. Yet the symbiotic relationship between cockroaches and their endosymbionts such as Wolbachia holds apposite insights that could be exploited for control.  To better understand the cladogenetic lineage and  host relationship of cockroach-associated Wolbachia we provide here a set of analysis conducted on  MLST data, Biotin synthesis genes from Wolbachia as well as the host Phylogeny.


# All input and output files used in the present study are as follow:

# Cophylogeny and event-based analysis

> Mafft_on_BiotinC-H: MSA of the concatenated Biotin C and H genes from cockroach and Cimicidae-associated Wolbachia
> Biotin-C&H.nwk: Parasimony tree from Mafft_on_BiotinC-H

> Mafft_on_HcpA.fas: MSA of the HcpA gene from cockroach and Cimicidae-associated Wolbachia
> hcpA.nwk: Parasimony tree from Mafft_on_HcpA.fas

> Mafft_on_COI.fas: MSA of the cox1 gene from Wolbachia hosts used in this analysis
> COI.nwk: Parasimony tree from Mafft_on_COI.fas

# Phylogenitic Model
                 
> RefMSA.fas: Multiloci Sequnce alignement of the concatenated CoxA, HcpA, GatB, Vird4 and Wsp genes of Wolbachia, used for the following Phylogenetic analysis ==> 

> RefMSA.fas.iqtree: Iqtree analysis under 1000 UFb.

> CLFml.labelled_tree.newick: branche correction regarding to the recombination events. This analysis was conducted on the Iqtree phylogeny using ClonalFrameML.

> Query.fas: All GenBank entries of the quested Wolbachia genes (CoxA, HcpA, GatB, Vird4 and Wsp).

> MLST_Wol_IQ_ML_CF.jplace: The final phylogenetic tree after Branche lenghth correction using FastTree and phylogenetic placement using the Apples software. This tree is the final version (https://itol.embl.de/tree/9116312116620381644353101) used in our article.

                             
# Annotation files

> Labels.txt: Tree label for RefMSA.fas.iqtree, CLFml.labelled_tree.newick and MLST_Wol_IQ_ML_CF.jplace tree files.

> Species delimitation.txt: Color coeds used to show the results of the Limes analyses on ASAP, AGBD, bPTP, PTP and GYMC delimitation algorythms

> highlighting our sequences.txt: color code and style to make species from our study more visible

> Position.txt: Position of the recombination events throughout the alignement.

> CLFml.em.txt: Detailed result of the ClonalFrameML analysis

# Script and flags
to be added

# Citation
It you use the data abouve, please cite the following paper:

Seun Oladipupo, Younes Laidoudi, John Beckmann, Xing Ping Hu, and Arthur Appel. Symbiotic heritage: The co-speciation in cockroach-associated Wolbachia intimate the pattern in their bedbug host-prey (Under review. DOI: coming...)




