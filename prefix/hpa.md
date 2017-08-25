---
identifier: MIR:00000336
name: HPA
description: The Human Protein Atlas (HPA) is a publicly available database with high-resolution images showing the spatial distribution of proteins in different normal and cancer human cell lines. Primary access to this collection is through Ensembl Gene identifiers.
prefix: hpa
pattern: ^ENSG\d{11}$
prefixed: 0
resources:
 - identifier: MIR:00100431
   accessurl: http://www.proteinatlas.org/${id}
   test_id: ENSG00000026508
   description: Human Protein Atlas at AlbaNova University
   homepage: http://www.proteinatlas.org/
   institution: Department of Proteomics, School of Biotechnology, AlbaNova University Center, Stockholm
   location: Sweden
   official: false
---
