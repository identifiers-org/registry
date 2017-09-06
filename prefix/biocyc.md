---
identifier: MIR:00000194
name: BioCyc
description: BioCyc is a collection of Pathway/Genome Databases (PGDBs) which provides an electronic reference source on the genomes and metabolic pathways of sequenced organisms.
prefix: biocyc
pattern: ^[A-Z-0-9]+(?<!CHEBI)(\:)?[A-Za-z0-9+_.%-]+$
prefixed: 0
local_id: ECOLI:CYT-D-UBIOX-CPLX
resources:
 - identifier: MIR:00100251
   accessurl: http://biocyc.org/getid?id=${lid}
   keyword: 3 cytochrome oxidase enzymes
   description: BioCyc at SRI International
   homepage: http://biocyc.org
   institution: Bioinformatics Research Group, SRI International, California
   location: USA
   official: false
---
