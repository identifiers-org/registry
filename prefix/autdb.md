---
identifier: MIR:00000415
name: AutDB
description: AutDB is a curated database for autism research. It is built on information extracted from the studies on molecular genetics and biology of Autism Spectrum Disorders (ASD). The four modules of AutDB include information on Human Genes, Animal models, Protein Interactions (PIN) and Copy Number Variants (CNV) respectively. It provides an annotated list of ASD candidate genes in the form of reference dataset for interrogating molecular mechanisms underlying the disorder.
prefix: autdb
pattern: ^[A-Z]+[A-Z-0-9]{2,}$
prefixed: 0
resources:
 - identifier: MIR:00100538
   accessurl: http://autism.mindspec.org/GeneDetail/${id}
   test_id: ADA
   description: AutDB at MindSpec
   homepage: http://autism.mindspec.org/autdb/
   institution: MindSpec Inc., Fairfax, Virginia
   location: USA
   official: false
---
