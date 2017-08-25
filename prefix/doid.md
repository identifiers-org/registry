---
identifier: MIR:00000233
name: Human Disease Ontology
description: The Disease Ontology has been developed as a standardized ontology for human disease with the purpose of providing the biomedical community with consistent, reusable and sustainable descriptions of human disease terms, phenotype characteristics and related medical vocabulary disease concepts.
prefix: doid
pattern: ^DOID\:\d+$
prefixed: 1
resources:
 - identifier: MIR:00100292
   accessurl: http://purl.bioontology.org/ontology/DOID/${id}
   test_id: DOID:11337
   description: Human Disease Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/DOID
   institution: National Center for Biomedical Ontology, Stanford University
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100293
   accessurl: http://www.ebi.ac.uk/ols/ontologies/doid/terms?obo_id=${id}
   test_id: DOID:11337
   description: Human Disease Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/doid
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100297
   accessurl: http://disease-ontology.org/term/${id}
   test_id: DOID:11337
   description: Human Disease Ontology at Northwestern University
   homepage: http://disease-ontology.org/
   institution: University of Maryland (Maryland) and Northwestern University (Illinois)
   location: USA
   official: false
---
