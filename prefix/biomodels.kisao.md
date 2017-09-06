---
identifier: MIR:00000108
name: KiSAO
description: The Kinetic Simulation Algorithm Ontology (KiSAO) is an ontology that describes simulation algorithms and methods used for biological kinetic models, and the relationships between them. This provides a means to unambiguously refer to simulation algorithms when describing a simulation experiment.
prefix: biomodels.kisao
pattern: ^KISAO_\d+$
prefixed: 0
local_id: KISAO_0000057
synonyms:
 - Kinetic Simulation Algorithm Ontology
resources:
 - identifier: MIR:00100141
   accessurl: http://purl.bioontology.org/ontology/KISAO/kisao:${lid}
   keyword: In the Brownian diffusion Smoluchowski method, 
   description: KiSAO via NCBO's Bioportal
   homepage: http://bioportal.bioontology.org/ontologies/KISAO
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100757
   accessurl: http://www.ebi.ac.uk/ols/ontologies/kisao/terms?short_form=${lid}
   keyword: In the Brownian diffusion Smoluchowski method,
   description: KiSAO through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/kisao
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
