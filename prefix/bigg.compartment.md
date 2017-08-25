---
identifier: MIR:00000555
name: BiGG Compartment
description: BiGG is a knowledgebase of Biochemically, Genetically and Genomically structured genome-scale metabolic network reconstructions. It more published genome-scale metabolic networks into a single database with a set of stardized identifiers called BiGG IDs. Genes in the BiGG models are mapped to NCBI genome annotations, and metabolites are linked to many external databases (KEGG, PubChem, and many more). This collection references model compartments.
prefix: bigg.compartment
pattern: ^[a-z_A-Z]+$
prefixed: 0
resources:
 - identifier: MIR:00100732
   accessurl: http://bigg.ucsd.edu/compartments/${id}
   test_id: c
   description: BiGG Compartment at University of California
   homepage: http://bigg.ucsd.edu/compartments/
   institution: Systems Biology Research Group at the University of California, San Diego
   location: USA
   official: false
---
