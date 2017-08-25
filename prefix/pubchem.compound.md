---
identifier: MIR:00000034
name: PubChem-compound
description: PubChem provides information on the biological activities of small molecules. It is a component of NIH's Molecular Libraries Roadmap Initiative. PubChem Compound archives chemical structures and records.
prefix: pubchem.compound
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100059
   accessurl: http://pubchem.ncbi.nlm.nih.gov/summary/summary.cgi?cid=${id}
   test_id: 100101
   description: NCBI PubChem Compound
   homepage: http://pubchem.ncbi.nlm.nih.gov/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
