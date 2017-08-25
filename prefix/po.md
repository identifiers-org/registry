---
identifier: MIR:00000307
name: Plant Ontology
description: The Plant Ontology is a structured vocabulary and database resource that links plant anatomy, morphology and growth and development to plant genomics data.
prefix: po
pattern: ^PO:\d+$
prefixed: 1
resources:
 - identifier: MIR:00100389
   accessurl: http://www.plantontology.org/amigo/go.cgi?view=details&query=${id}
   test_id: PO:0009089
   description: Plant Ontology through Amigo
   homepage: http://www.plantontology.org/
   institution: Cold Spring Harbor Laboratory, Cold Spring Harbor, New York
   location: USA
   official: false
   provider_code: amigo
 - identifier: MIR:00100390
   accessurl: http://purl.bioontology.org/ontology/PO/${id}
   test_id: PO:0009089
   description: Plant Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/PO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100676
   accessurl: http://www.ebi.ac.uk/ols/ontologies/po/terms?obo_id=${id}
   test_id: PO:0009089
   description: Plant Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/po
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
