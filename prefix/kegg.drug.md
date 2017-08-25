---
identifier: MIR:00000025
name: KEGG Drug
description: KEGG DRUG contains chemical structures of drugs and additional information such as therapeutic categories and target molecules.
prefix: kegg.drug
pattern: ^D\d+$
prefixed: 0
resources:
 - identifier: MIR:00100035
   accessurl: http://www.kegg.jp/entry/${id}
   test_id: D00123
   description: KEGG DRUG Database
   homepage: http://www.genome.jp/kegg/drug/
   institution: Kyoto University Bioinformatics Center
   location: Japan
   official: true
---
