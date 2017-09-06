---
identifier: MIR:00000238
name: KEGG Genome
description: KEGG Genome is a collection of organisms whose genomes have been completely sequenced.
prefix: kegg.genome
pattern: ^(T0\d+|\w{3,5})$
prefixed: 0
local_id: eco
synonyms:
 - KEGG Organism
 - KEGG
resources:
 - identifier: MIR:00100303
   accessurl: http://www.kegg.jp/entry/${lid}
   keyword: MG1655
   description: KEGG Genome Database
   homepage: http://www.genome.jp/kegg/catalog/org_list.html
   institution: Kyoto University Bioinformatics Center, Kyoto
   location: Japan
   official: true
---
