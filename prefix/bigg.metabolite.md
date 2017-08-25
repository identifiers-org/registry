---
identifier: MIR:00000556
name: BiGG Metabolite
description: BiGG is a knowledgebase of Biochemically, Genetically and Genomically structured genome-scale metabolic network reconstructions. It more published genome-scale metabolic networks into a single database with a set of stardized identifiers called BiGG IDs. Genes in the BiGG models are mapped to NCBI genome annotations, and metabolites are linked to many external databases (KEGG, PubChem, and many more). This collection references individual metabolotes.
prefix: bigg.metabolite
pattern: ^[a-z_A-Z0-9]+$
prefixed: 0
resources:
 - identifier: MIR:00100733
   accessurl: http://bigg.ucsd.edu/models/universal/metabolites/${id}
   test_id: 12dgr161
   description: BiGG Metabolite at University of Cakifornia
   homepage: http://bigg.ucsd.edu/universal/metabolites
   institution: Systems Biology Research Group at the University of California, San Diego
   location: USA
   official: false
---
