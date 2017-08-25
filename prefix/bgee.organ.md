---
identifier: MIR:00000420
name: Bgee organ
description: Bgee is a database of gene expression patterns within particular anatomical structures within a species, and between different animal species. This collection refers to anatomical structures.
prefix: bgee.organ
pattern: ^(XAO|ZFA|EHDAA|EMAPA|EV|MA)\:\d+$
prefixed: 0
resources:
 - identifier: MIR:00100543
   accessurl: http://bgee.unil.ch/bgee/bgee?page=anatomy&action=organ_details&organ_id=${id}&organ_children=on
   test_id: EHDAA:2185
   description: Bgee at Lausanne
   homepage: http://bgee.unil.ch/bgee/bgee
   institution: Swiss Institute of Bioinformatics, Lausanne
   location: Switzerland
   official: false
---
