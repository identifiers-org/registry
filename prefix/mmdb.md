---
identifier: MIR:00000121
name: Molecular Modeling Database
description: The Molecular Modeling Database (MMDB) is a database of experimentally determined structures obtained from the Protein Data Bank (PDB). Since structures are known for a large fraction of all protein families, structure homologs may facilitate inference of biological function, or the identification of binding or catalytic sites.
prefix: mmdb
pattern: ^\d{1,5}$
prefixed: 0
local_id: 50885
synonyms:
 - MMDB
 - Entrez Structure
resources:
 - identifier: MIR:00100154
   accessurl: http://www.ncbi.nlm.nih.gov/Structure/mmdb/mmdbsrv.cgi?uid=${lid}
   keyword: Structural Basis of Aspirin
   description: MMDB at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/sites/entrez?db=structure
   institution: National Library of Medicine, National Institutes of Health, Maryland
   location: USA
   official: false
---
