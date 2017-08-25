---
identifier: MIR:00000518
name: Plant Environment Ontology
description: The Plant Environment Ontology is a set of standardized controlled vocabularies to describe various types of treatments given to an individual plant / a population or a cultured tissue and/or cell type sample to evaluate the response on its exposure. It also includes the study types, where the terms can be used to identify the growth study facility. Each growth facility such as field study, growth chamber, green house etc is a environment on its own it may also involve instances of biotic and abiotic environments as supplemental treatments used in these studies.
prefix: eo
pattern: ^(P)?EO\:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100667
   accessurl: http://archive.gramene.org/db/ontology/search?query=${id}
   test_id: EO:0007404
   description: Plant Environment Ontology through Gramene
   homepage: http://archive.gramene.org/db/ontology/search_term?id=EO:0007359
   institution: Cold Spring Harbor Laboratory, New York
   location: USA
   official: false
 - identifier: MIR:00100668
   accessurl: http://purl.bioontology.org/ontology/PECO/${id}
   test_id: EO:0007404
   description: Plant Environment Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/PECO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100669
   accessurl: http://www.ebi.ac.uk/ols/ontologies/eo/terms?obo_id=${id}
   test_id: EO:0007404
   description: Plant Environment Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/eo
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
