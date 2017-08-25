---
identifier: MIR:00000136
name: Unit Ontology
description: Ontology of standardized units
prefix: uo
pattern: ^UO:\d{7}?
prefixed: 1
resources:
 - identifier: MIR:00100178
   accessurl: http://www.ebi.ac.uk/ols/ontologies/uo/terms?obo_id=${id}
   test_id: UO:0000080
   description: Unit Ontology via Ontology Lookup Service
   homepage: http://www.ebi.ac.uk/ols/ontologies/uo
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100243
   accessurl: http://purl.bioontology.org/ontology/UO/${id}
   test_id: UO:0000080
   description: Unit Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/UO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
