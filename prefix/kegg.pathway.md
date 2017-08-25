---
identifier: MIR:00000012
name: KEGG Pathway
description: KEGG PATHWAY is a collection of manually drawn pathway maps representing our knowledge on the molecular interaction and reaction networks.
prefix: kegg.pathway
pattern: ^\w{2,4}\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100020
   accessurl: http://www.kegg.jp/entry/${id}
   test_id: hsa00620
   description: KEGG PATHWAY Database
   homepage: http://www.genome.jp/kegg/pathway.html
   institution: Kyoto University Bioinformatics Center
   location: Japan
   official: true
---
