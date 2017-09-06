---
identifier: MIR:00000446
name: UBERON
description: Uberon is an integrated cross-species anatomy ontology representing a variety of entities classified according to traditional anatomical criteria such as structure, function and developmental lineage. The ontology includes comprehensive relationships to taxon-specific anatomical ontologies, allowing integration of functional, phenotype and expression data.
prefix: uberon
pattern: ^UBERON\:\d+$
prefixed: 1
local_id: 0008203
synonyms:
 - Uber Anatomy Ontology
resources:
 - identifier: MIR:00100579
   accessurl: http://purl.bioontology.org/ontology/UBERON/UBERON:${lid}
   keyword: ventral body cavity
   description: UBERON through bioPortal
   homepage: http://bioportal.bioontology.org/ontologies/UBERON
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100580
   accessurl: http://www.ebi.ac.uk/ols/ontologies/uberon/terms?obo_id=UBERON:${lid}
   keyword: part of the ventral body cavity that is within the pelvis
   description: UBERON through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/uberon
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
