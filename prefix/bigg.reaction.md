---
identifier: MIR:00000557
name: BiGG Reaction
description: BiGG is a knowledgebase of Biochemically, Genetically and Genomically structured genome-scale metabolic network reconstructions. It more published genome-scale metabolic networks into a single database with a set of stardized identifiers called BiGG IDs. Genes in the BiGG models are mapped to NCBI genome annotations, and metabolites are linked to many external databases (KEGG, PubChem, and many more). This collection references reactions.
prefix: bigg.reaction
pattern: ^[a-z_A-Z0-9]+$
prefixed: 0
local_id: 13GS
resources:
 - identifier: MIR:00100734
   accessurl: http://bigg.ucsd.edu/models/universal/reactions/${lid}
   keyword: glucan synthase
   description: BiGG Reaction at University of California
   homepage: http://bigg.ucsd.edu/universal/reactions
   institution: Systems Biology Research Group at the University of California, San Diego
   location: USA
   official: false
---
