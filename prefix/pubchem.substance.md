---
identifier: MIR:00000033
name: PubChem-substance
description: PubChem provides information on the biological activities of small molecules. It is a component of NIH's Molecular Libraries Roadmap Initiative. PubChem Substance archives chemical substance records.
prefix: pubchem.substance
pattern: ^\d+$
prefixed: 0
local_id: 100101
synonyms:
 - PubChem Substance
 - PubChem SID
resources:
 - identifier: MIR:00100058
   accessurl: http://pubchem.ncbi.nlm.nih.gov/summary/summary.cgi?sid=${lid}
   keyword: 6079-78-3
   description: NCBI PubChem Substance
   homepage: http://pubchem.ncbi.nlm.nih.gov/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
