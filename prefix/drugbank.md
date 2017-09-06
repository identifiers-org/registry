---
identifier: MIR:00000102
name: DrugBank
description: The DrugBank database is a bioinformatics and chemoinformatics resource that combines detailed drug (i.e. chemical, pharmacological and pharmaceutical) data with comprehensive drug target (i.e. sequence, structure, and pathway) information. This collection references drug information.
prefix: drugbank
pattern: ^DB\d{5}$
prefixed: 0
local_id: DB00001
resources:
 - identifier: MIR:00100133
   accessurl: http://www.drugbank.ca/drugs/${lid}
   keyword: Lepirudin
   description: DrugBank drug information
   homepage: http://www.drugbank.ca/
   institution: Departments of Computing Science & Biological Sciences,  University of Alberta
   location: Canada
   official: true
 - identifier: MIR:00100691
   accessurl: http://drugbank.bio2rdf.org/describe/?url=http://bio2rdf.org/drugbank:${lid}
   keyword: Lepirudin
   description: Bio2RDF
   homepage: http://drugbank.bio2rdf.org/fct/
   institution: Bio2RDF.org
   location: 
   official: false
---
