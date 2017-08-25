---
identifier: MIR:00000024
name: Systems Biology Ontology
description: The goal of the Systems Biology Ontology is to develop controlled vocabularies and ontologies tailored specifically for the kinds of problems being faced in Systems Biology, especially in the context of computational modeling. SBO is a project of the BioModels.net effort.
prefix: sbo
pattern: ^SBO:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100034
   accessurl: http://www.ebi.ac.uk/sbo/main/${id}
   test_id: SBO:0000262
   description: SBO
   homepage: http://www.ebi.ac.uk/sbo/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100176
   accessurl: http://www.ebi.ac.uk/ols/ontologies/sbo/terms?obo_id=${id}
   test_id: SBO:0000262
   description: SBO through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/sbo
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100242
   accessurl: http://purl.bioontology.org/ontology/SBO/${id}
   test_id: SBO:0000262
   description: SBO through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/SBO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
