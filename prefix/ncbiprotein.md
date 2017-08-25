---
identifier: MIR:00000344
name: NCBI Protein
description: The Protein database is a collection of sequences from several sources, including translations from annotated coding regions in GenBank, RefSeq and TPA, as well as records from SwissProt, PIR, PRF, and PDB.
prefix: ncbiprotein
pattern: ^(\w+\d+(\.\d+)?)|(NP_\d+)$
prefixed: 0
resources:
 - identifier: MIR:00100439
   accessurl: http://www.ncbi.nlm.nih.gov/protein/${id}
   test_id: CAA71118.1
   description: NCBI Protein at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/protein
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
