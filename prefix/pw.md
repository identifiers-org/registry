---
identifier: MIR:00000242
name: Pathway Ontology
description: The Pathway Ontology captures information on biological networks, the relationships between netweorks and the alterations or malfunctioning of such networks within a hierarchical structure. The five main branches of the ontology are: classic metabolic pathways, regulatory, signaling, drug, and disease pathwaysfor complex human conditions.
prefix: pw
pattern: ^PW:\d{7}$
prefixed: 1
local_id: 0000208
resources:
 - identifier: MIR:00100309
   accessurl: http://rgd.mcw.edu/rgdweb/ontology/annot.html?acc_id=PW:${lid}
   keyword: Diabetes mellitus
   description: Pathway Ontology at Rat Genome Database
   homepage: http://rgd.mcw.edu/rgdweb/ontology/search.html
   institution: Medical College of Wisconsin, Wisconsin
   location: USA
   official: false
 - identifier: MIR:00100310
   accessurl: http://www.ebi.ac.uk/ols/ontologies/pw/terms?obo_id=PW:${lid}
   keyword: Diabetes mellitus
   description: Pathway Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/pw
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100311
   accessurl: http://purl.bioontology.org/ontology/PW/PW:${lid}
   keyword: Diabetes mellitus
   description: Pathway Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/PW
   institution: National Center for Biomedical Ontology, Stanford, California
   location: USA
   official: false
   provider_code: bptl
---
