---
identifier: MIR:00000188
name: MIRIAM Registry resource
description: MIRIAM Registry is an online resource created to catalogue data types (Gene Ontology, Taxonomy or PubMed are some examples), their URIs and the corresponding resources (or physical locations), whether these are controlled vocabularies or databases.
prefix: miriam.resource
pattern: ^MIR:001\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100245
   accessurl: http://www.ebi.ac.uk/miriam/main/resources/${id}
   test_id: MIR:00100005
   description: MIRIAM Registry (resources)
   homepage: http://www.ebi.ac.uk/miriam/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
