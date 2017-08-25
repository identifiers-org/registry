---
identifier: MIR:00000571
name: Human Phenotype Ontology
description: The Human Phenotype Ontology (HPO) aims to provide a standardized vocabulary of phenotypic abnormalities encountered in human disease. Each term in the HPO describes a phenotypic abnormality, such as atrial septal defect. The HPO is currently being developed using the medical literature, Orphanet, DECIPHER, and OMIM.
prefix: hp
pattern: ^HP:\d{7}$
prefixed: 1
resources:
 - identifier: MIR:00100753
   accessurl: http://compbio.charite.de/hpoweb/showterm?id=${id}
   test_id: HP:0000118
   description: Human Phenotype Ontology at Institute for Medical Genetics and Human Genetics
   homepage: http://human-phenotype-ontology.github.io/
   institution: Institute for Medical Genetics and Human Genetics, Charité-Universitätsmedizin, Berlin
   location: Germany
   official: true
 - identifier: MIR:00100754
   accessurl: http://www.ebi.ac.uk/ols/ontologies/hp/terms?obo_id=${id}
   test_id: HP:0000118
   description: Human Phenotype Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/hp
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
