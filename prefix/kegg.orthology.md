---
identifier: MIR:00000116
name: KEGG Orthology
description: KEGG Orthology (KO) consists of manually defined, generalised ortholog groups that correspond to KEGG pathway nodes and BRITE hierarchy nodes in all organisms.
prefix: kegg.orthology
pattern: ^K\d+$
prefixed: 0
resources:
 - identifier: MIR:00100149
   accessurl: http://www.kegg.jp/entry/${id}
   test_id: K00001
   description: KEGG Orthology Database
   homepage: http://www.genome.jp/kegg/ko.html
   institution: Department of Computational Biology, University of Tokyo, Tokyo
   location: Japan
   official: true
---
