---
identifier: MIR:00000055
name: Evidence Code Ontology
description: Evidence codes can be used to specify the type of supporting evidence for a piece of knowledge. This allows inference of a 'level of support' between an entity and an annotation made to an entity.
prefix: eco
pattern: ECO:\d{7}$
prefixed: 1
local_id: 0000006
synonyms:
 - ECO
resources:
 - identifier: MIR:00100083
   accessurl: http://www.ebi.ac.uk/ols/ontologies/eco/terms?obo_id=ECO:${lid}
   keyword: inferred from experiment
   description: Evidence Codes via the Ontology Lookup Service (OLS)
   homepage: http://www.ebi.ac.uk/ols/ontologies/eco
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100235
   accessurl: http://purl.bioontology.org/ontology/ECO/ECO:${lid}
   keyword: inferred from experiment
   description: Evidence Code Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/ECO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
