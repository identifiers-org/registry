---
identifier: MIR:00000112
name: PATO
description: PATO is an ontology of phenotypic qualities, intended for use in a number of applications, primarily defining composite phenotypes and phenotype  annotation.
prefix: pato
pattern: ^PATO:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100145
   accessurl: http://www.ebi.ac.uk/ols/ontologies/pato/terms?obo_id=${id}
   test_id: PATO:0001998
   description: PATO through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/pato
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100238
   accessurl: http://purl.bioontology.org/ontology/PATO/${id}
   test_id: PATO:0001998
   description: PATO through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/PATO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
