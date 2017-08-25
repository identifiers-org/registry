---
identifier: MIR:00000392
name: HGMD
description: The Human Gene Mutation Database (HGMD) collates data on germ-line mutations in nuclear genes associated with human inherited disease. It includes information on single base-pair substitutions in coding, regulatory and splicing-relevant regions; micro-deletions and micro-insertions; indels; triplet repeat expansions as well as gross deletions; insertions; duplications; and complex rearrangements. Each mutation entry is unique, and includes cDNA reference sequences for most genes, splice junction sequences, disease-associated and functional polymorphisms, as well as links to data present in publicly available online locus-specific mutation databases.
prefix: hgmd
pattern: ^[A-Z_0-9]+$
prefixed: 0
resources:
 - identifier: MIR:00100512
   accessurl: http://www.hgmd.cf.ac.uk/ac/gene.php?gene=${id}
   test_id: CALM1
   description: HGMD at Cardiff University
   homepage: http://www.hgmd.cf.ac.uk/ac/index.php
   institution: Cardiff University, Cardiff
   location: Wales
   official: false
---
