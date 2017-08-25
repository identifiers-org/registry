---
identifier: MIR:00000056
name: Protein Modification Ontology
description: The Proteomics Standards Initiative modification ontology (PSI-MOD)  aims to define a concensus nomenclature and ontology reconciling, in a hierarchical representation, the complementary descriptions of residue modifications.
prefix: mod
pattern: ^MOD:\d{5}
prefixed: 1
resources:
 - identifier: MIR:00100084
   accessurl: http://www.ebi.ac.uk/ols/ontologies/mod/terms?obo_id=${id}
   test_id: MOD:00001
   description: Protein modifications ontology via the Ontology Lookup Service (OLS)
   homepage: http://www.ebi.ac.uk/ols/ontologies/mod
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
 - identifier: MIR:00100239
   accessurl: http://bioportal.bioontology.org/ontologies/1041?p=terms&conceptid=${id}
   test_id: MOD:00001
   description: Protein modifications ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/PSIMOD
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
