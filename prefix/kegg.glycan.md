---
identifier: MIR:00000026
name: KEGG Glycan
description: KEGG GLYCAN, a part of the KEGG LIGAND database, is a collection of experimentally determined glycan structures. It contains all unique structures taken from CarbBank, structures entered from recent publications, and structures present in KEGG pathways.
prefix: kegg.glycan
pattern: ^G\d+$
prefixed: 0
resources:
 - identifier: MIR:00100036
   accessurl: http://www.kegg.jp/entry/${id}
   test_id: G00123
   description: KEGG GLYCAN Database
   homepage: http://www.genome.jp/kegg/glycan/
   institution: Kyoto University Bioinformatics Center
   location: Japan
   official: true
---
