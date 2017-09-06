---
identifier: MIR:00000141
name: Protein Ontology
description: The PRotein Ontology (PRO) has been designed to describe the relationships of proteins and protein evolutionary classes, to delineate the multiple protein forms of a gene locus (ontology for protein forms), and to interconnect existing ontologies.
prefix: pr
pattern: ^PR\:\d+$
prefixed: 1
local_id: 000000024
resources:
 - identifier: MIR:00100184
   accessurl: http://pir.georgetown.edu/cgi-bin/pro/entry_pro?id=PR:${lid}
   keyword: rho-associated protein kinase
   description: Protein Ontology at Georgetown
   homepage: http://pir.georgetown.edu/pro/pro.shtml
   institution: Georgetown University Medical Center, Washington
   location: USA
   official: false
 - identifier: MIR:00100240
   accessurl: http://purl.bioontology.org/ontology/PR/PR:${lid}
   keyword: rho-associated protein kinase
   description: Protein Ontology through BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/PR
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100755
   accessurl: http://www.ebi.ac.uk/ols/ontologies/pr/terms?obo_id=PR:${lid}
   keyword: rho-associated protein kinase
   description: Protein Ontology through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/pr
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
