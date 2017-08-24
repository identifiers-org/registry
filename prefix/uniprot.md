---
identifier: MIR:00000005
name: UniProt Knowledgebase
description: The UniProt Knowledgebase (UniProtKB) is a comprehensive resource for protein sequence and functional information with extensive cross-references to more than 120 external databases. Besides amino acid sequence and a description, it also provides taxonomic data and citation information.
prefix: uniprot
pattern: ^([A-N,R-Z][0-9]([A-Z][A-Z, 0-9][A-Z, 0-9][0-9]){1,2})|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9])(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100164
   accessurl: http://purl.uniprot.org/uniprot/
   description: Universal Protein Resource using Persistent URL system
   location: 
   official: true
 - identifier: MIR:00100330
   accessurl: http://www.ncbi.nlm.nih.gov/protein/
   description: UniProt through NCBI
   location: USA
   official: false
   provider_code: ncbi
---