---
identifier: MIR:00000380
name: MetaboLights
description: MetaboLights is a database for Metabolomics experiments and derived information. The database is cross-species, cross-technique and covers metabolite structures and their reference spectra as well as their biological roles, locations and concentrations, and experimental data from metabolic experiments. This collection references individual metabolomics studies.
prefix: metabolights
pattern: ^MTBLS\d+$
prefixed: 0
resources:
 - identifier: MIR:00100486
   accessurl: http://www.ebi.ac.uk/metabolights/${id}
   test_id: MTBLS1
   description: MetaboLights at EBI
   homepage: http://www.ebi.ac.uk/metabolights/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
