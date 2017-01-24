# NIPA
Pathway and Gene Ontology enrichment

User needs to adjsut settings at top of code (line 20-60).

******************** N.B Check KEGG terms if commercial user. ****************************


Code to determine enriched Gene Ontology and Pathways using KEGG and Reactome using hypergeometric tests.
Input: list of ids of type specified in code.
Outputs:
Gene Ontology (Enrichment using GOstats) Tables GO enriched terms GO.BP.table, GO.CC.table, GO.MF.table for "Biological Process", "Cellular Component" and "Molecular Function" respectively Figures of enriched terms for upto 10 most significant groups. x axis = -log10 pvalue, number of IDs in term shown by size and colour of circle.

Reactome (using ReactomePA) Table of significnat terms Plots of enriched terms and interacting proteins.

KEGG (using gage and pathview) enriched pathways table (KEGG.enrichment.analysis.results.table) pathview output e.g mmu03010.pathview.png: red shows entities in user input list which are present in enriched pathway mmu03010.png: all entities present in test species shown in green mmu03010.xml: xml file to generate above

NIPA.report.txt: Any errors will appear here.

