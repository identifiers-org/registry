---
identifier: MIR:00000474
name: KEGG Module
description: KEGG Modules are manually defined functional units used in the annotation and biological interpretation of sequenced genomes. Each module corresponds to a set of 'KEGG Orthology' (MIR:00000116) entries. KEGG Modules can represent pathway, structural, functional or signature modules.
prefix: kegg.module
pattern: ^([a-z]{3,5}_)?M\d{5}$
prefixed: 0
local_id: M00002
synonyms:
 - KEGG
resources:
 - identifier: MIR:00100609
   accessurl: http://www.kegg.jp/entry/${lid}
   keyword: Glycolysis
   description: KEGG Module at Kyoto University Bioinformatics Center
   homepage: http://www.kegg.jp/kegg/module.html
   institution: Department of Computational Biology, University of Tokyo, Tokyo
   location: Japan
   official: true
---
