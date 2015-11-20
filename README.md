# MSc_Thesis_2015
A collection of the Python scripts self-written, and used during my MSc thesis.

Date:        	 20 November 2015

Author:      	 Stephanie J. Pitts

Title of Thesis: "An Investigation into the MicroRNA-gene Interactions involved
                 in the pathogenesis of Systemic Lupus Erythematosus"

PI:          	 Dr Nicki Tiffin

Institution: 	 South African National Bioinformatics Institute (SANBI)
University:  	 University of the Western Cape 
             	 Robert Sobukwe Road
             	 Bellville
             	 Cape Town 
--------------------------------------------------------------------------------
This MSc thesis aimed to investigate the miRNA-target interactions between genes
and miRNAs identified to be associated with the pathogenesis of Systemic Lupus
Erythematosus. 

--------------------------------------------------------------------------------

*Abbreviations used in Script titles: 

PS == Python Script (i.e. "PS1:..." is "Python Script 1:..."

** The Python scripts are listed in the order in which they were utilised during 
this study, and the script names seen here are the same in the written thesis. 

--------------------------------------------------------------------------------

List of self-written Python Scripts(PS): 

PS01.  "June_28_miRBase_1.py"

PS02.  "July_01_new_regexes.py"

PS03.  "15_July_assoc_genes_prep_&_Biomart.py"

PS04.  "16_July_DE_genes_thru_BioMart.py"

PS05.  "05_July_mirtarbase_mirecords_for_PERFECT_MATCH.py"

PS06.  "05_July_mirtarbase_mirecords_for_NOT_FOUND_IN_MIRBASE.py"

PS07.  "05_July_mirtarbase_mirecords_for_FOUND_REGEX_MATCH.py"

PS08.  "05_July_mirtarbase_mirecords_for_NOT_FOUND_REGEX_MATCH.py"

PS09.  "15_July_Genes1_thru_DBs.py"

PS10. "15_July_Genes2_thru_DBs.py"

PS11. "16_July_DE_Genes_thru_DBs.py"

PS12. "Test_miRNA_1.py"

PS13. "Test_miRNA_2.py"

PS14. "Test_miRNA_3.py"

PS15. "Test_Gene_1.py"

PS16. "Test_Gene_2.py"

PS17. "prep_genes_for_IPA.py"

PS18. "prep_miRNAs_for_IPA.py"

PS19. "ALL_mapped_IDs_prepped.py"

PS20. "Test_IPA_mapping.py"

--------------------------------------------------------------------------------

Key Components of this Study:

A. Input files:

> list of miRNAs associated with SLE (curated from literature)

> list of genes associated with SLE (curated from literature)

> list of Differentially-expressed SLE genes (used with permission of the author)


B. MiRNA-Target Interactions databases used to retrieve the interactions of 
each of the input datasets:

> miRTarBase V. 4.5 - November 01, 2013 Available at (http://mirtarbase.mbc.nctu.edu.tw/)

> miRecords  V.4    - April 27, 2013    Availabe at  (http://c1.accurascience.com/miRecords/)

C. Other software programmes/databases used:

> GeneCards Available at (http://www.genecards.org/)

> Ingenuity Pathway Analysis 

--------------------------------------------------------------------------------

Use of these Python scripts:

Each of the scripts named above were used sequentially as described in the Methods
Chapter to produce the corresponding results reported in the Results Chapter. 

Each script includes notes initiated with a "#" which served to report the findings
of the commands as each step was performed on the input data. 

Thus, the notes and instructions in each script are an extension of this README file. 
--------------------------------------------------------------------------------
