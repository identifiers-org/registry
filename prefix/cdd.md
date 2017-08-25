---
identifier: MIR:00000119
name: Conserved Domain Database
description: The Conserved Domain Database (CDD) is a collection of multiple sequence alignments and derived database search models, which represent protein domains conserved in molecular evolution.
prefix: cdd
pattern: ^(cd)?\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100152
   accessurl: http://www.ncbi.nlm.nih.gov/Structure/cdd/cddsrv.cgi?uid=${id}
   test_id: cd00400
   description: Conserved Domain Database at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/sites/entrez?db=cdd
   institution: National Library of Medicine, National Institutes of Health, Maryland
   location: USA
   official: false
   provider_code: ncbi
---
