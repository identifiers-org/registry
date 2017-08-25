---
identifier: MIR:00000591
name: Environment Ontology
description: The Environment Ontology is a resource and research target for the semantically controlled description of environmental entities. The ontology's initial aim was the representation of the biomes, environmental features, and environmental materials pertinent to genomic and microbiome-related investigations.
prefix: envo
pattern: ^ENVO:\d{8}$
prefixed: 1
resources:
 - identifier: MIR:00100790
   accessurl: http://www.ebi.ac.uk/ols/ontologies/envo/terms?obo_id=${id}
   test_id: ENVO:09200010
   description: The Environment Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/envo
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100791
   accessurl: http://purl.bioontology.org/ontology/ENVO/${id}
   test_id: ENVO:09200010
   description: The Environment Ontology through BioPortal
   homepage: http://purl.bioontology.org/ontology/ENVO/
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
