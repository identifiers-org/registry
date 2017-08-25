---
identifier: MIR:00000417
name: Bgee family
description: Bgee is a database of gene expression patterns within particular anatomical structures within a species, and between different animal species. This collection refers to expression across species.
prefix: bgee.family
pattern: ^(ENSFM|ENSGTV:)\d+$
prefixed: 0
resources:
 - identifier: MIR:00100540
   accessurl: http://bgee.unil.ch/bgee/bgee?page=gene_family&action=family_details&gene_family_id=${id}
   test_id: ENSFM00500000270089
   description: Bgee at Lausanne
   homepage: http://bgee.unil.ch/bgee/bgee
   institution: Swiss Institute of Bioinformatics, Lausanne
   location: Switzerland
   official: false
---
