---
identifier: MIR:00000580
name: Mammalian Phenotype Ontology
description: The Mammalian Phenotype Ontology (MP) classifies and organises phenotypic information related to the mouse and other mammalian species. This ontology has been applied to mouse phenotype descriptions in various databases allowing comparisons of data from diverse mammalian sources. It can facilitate in the identification of appropriate experimental disease models, and aid in the discovery of candidate disease genes and molecular signaling pathways.
prefix: mp
pattern: ^MP:\d{7}$
prefixed: 1
local_id: 0005452
resources:
 - identifier: MIR:00100774
   accessurl: http://www.informatics.jax.org/searches/Phat.cgi?id=MP:${lid}
   keyword: total amount of connective
   description: Mammalian Phenotype Ontology at The Jackson Lab
   homepage: http://www.informatics.jax.org/
   institution: The Jackson Laboratory, Bar Harbor, Maine
   location: USA
   official: false
 - identifier: MIR:00100775
   accessurl: http://www.ebi.ac.uk/ols/ontologies/mp/terms?obo_id=MP:${lid}
   keyword: total amount of connective
   description: Mammalian Phenotype Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/mp/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100776
   accessurl: https://bioportal.bioontology.org/ontologies/MP/MP:${lid}
   keyword: total amount of connective
   description: Mammalian Phenotype Ontology through BioPortal
   homepage: https://bioportal.bioontology.org/ontologies/MP
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
