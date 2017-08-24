---
identifier: MIR:00000474
name: KEGG Module
description: KEGG Modules are manually defined functional units used in the annotation and biological interpretation of sequenced genomes. Each module corresponds to a set of 'KEGG Orthology' (MIR:00000116) entries. KEGG Modules can represent pathway, structural, functional or signature modules.
prefix: kegg.module
pattern: ^([a-z]{3,5}_)?M\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100609
   accessurl: http://www.kegg.jp/entry/
   description: KEGG Module at Kyoto University Bioinformatics Center
   location: Japan
   official: true
---
