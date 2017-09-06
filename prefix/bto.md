---
identifier: MIR:00000111
name: Brenda Tissue Ontology
description: The Brenda tissue ontology is a structured controlled vocabulary eastablished to identify the source of an enzyme cited in the Brenda enzyme database. It comprises terms of tissues, cell lines, cell types and cell cultures from uni- and multicellular organisms.
prefix: bto
pattern: ^BTO:\d{7}$
prefixed: 1
local_id: 0000146
synonyms:
 - BTO
resources:
 - identifier: MIR:00100144
   accessurl: http://www.ebi.ac.uk/ols/ontologies/bto/terms?obo_id=BTO:${lid}
   keyword: part of the brain
   description: Brenda Tissue Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/bto
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100233
   accessurl: http://purl.bioontology.org/ontology/BTO/BTO:${lid}
   keyword: part of the brain
   description: Brenda Tissue Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/BTO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
