---
identifier: MIR:00000067
name: FMA
description: The Foundational Model of Anatomy Ontology (FMA) is a biomedical informatics ontology. It is concerned with the representation of classes or types and relationships necessary for the symbolic representation of the phenotypic structure of the human body.  Specifically, the FMA is a domain ontology that represents a coherent body of explicit declarative knowledge about human anatomy.
prefix: fma
pattern: ^FMA:\d+$
prefixed: 1
resources:
 - identifier: MIR:00100097
   accessurl: http://www.ebi.ac.uk/ols/ontologies/fma/terms?obo_id=${id}
   test_id: FMA:67112
   description: Foundational Model of Anatomy via Ontology Lookup Service (OLS)
   homepage: http://www.ebi.ac.uk/ols/ontologies/fma/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100236
   accessurl: http://purl.bioontology.org/ontology/FMA_subset/${id}
   test_id: FMA:67112
   description: Foundational Model of Anatomy through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/FMA
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
