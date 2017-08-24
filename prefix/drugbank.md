---
identifier: MIR:00000102
name: DrugBank
description: The DrugBank database is a bioinformatics and chemoinformatics resource that combines detailed drug (i.e. chemical, pharmacological and pharmaceutical) data with comprehensive drug target (i.e. sequence, structure, and pathway) information. This collection references drug information.
prefix: drugbank
pattern: ^DB\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100133
   accessurl: http://www.drugbank.ca/drugs/
   description: DrugBank drug information
   location: Canada
   official: true
 - identifier: MIR:00100691
   accessurl: http://drugbank.bio2rdf.org/describe/?url=http://bio2rdf.org/drugbank:
   description: Bio2RDF
   location: 
   official: false
---
