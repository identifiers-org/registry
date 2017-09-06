---
identifier: MIR:00000110
name: Cell Type Ontology
description: The Cell Ontology is designed as a structured controlled vocabulary for cell types. The ontology was constructed for use by the model organism and other bioinformatics databases, incorporating cell types from prokaryotes to mammals, and includes plants and fungi.
prefix: cl
pattern: ^CL:\d{7}$
prefixed: 1
local_id: 0000232
synonyms:
 - Cell Ontology
 - CL
resources:
 - identifier: MIR:00100143
   accessurl: http://www.ebi.ac.uk/ols/ontologies/cl/terms?obo_id=CL:${lid}
   keyword: mature erythrocytes
   description: Cell Type Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/cl
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100234
   accessurl: http://purl.bioontology.org/ontology/CL/CL:${lid}
   keyword: mature erythrocytes
   description: Cell Type Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/CL
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
