---
identifier: MIR:00000196
name: GOA
description: The GOA (Gene Ontology Annotation) project provides high-quality Gene Ontology (GO) annotations to proteins in the UniProt Knowledgebase (UniProtKB) and International Protein Index (IPI). This involves electronic annotation and the integration of high-quality manual GO annotation from all GO Consortium model organism groups and specialist groups.
prefix: goa
pattern: ^(([A-N,R-Z][0-9][A-Z][A-Z, 0-9][A-Z, 0-9][0-9])|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9]))|(URS[0-9A-F]{10}(_[0-9]+){0,1})|(EBI-[0-9]+)$
prefixed: 0
local_id: P12345
synonyms:
 - Gene Ontology Annotation
 - UniProtKB-GOA
resources:
 - identifier: MIR:00100253
   accessurl: http://www.ebi.ac.uk/QuickGO/GProtein?ac=${lid}
   keyword: Oryctolagus cuniculus
   description: GOA through QuickGO
   homepage: http://www.ebi.ac.uk/GOA/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: quickgo
---
