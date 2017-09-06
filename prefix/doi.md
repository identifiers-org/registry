---
identifier: MIR:00000019
name: DOI
description: The Digital Object Identifier System is for identifying content objects in the digital environment.
prefix: doi
pattern: ^(doi\:)?\d{2}\.\d{4}.*$
prefixed: 0
local_id: 10.1038/nbt1156
synonyms:
 - Digital Object Identifier
resources:
 - identifier: MIR:00100010
   accessurl: http://doi.org/${lid}
   keyword: Minimum information requested in the annotation of biochemical models
   description: Digital Object Identifier
   homepage: http://www.doi.org/
   institution: International DOI Foundation
   location: United Kingdom
   official: true
 - identifier: MIR:00100065
   accessurl: http://hdl.handle.net/${lid}
   keyword: Minimum information requested in the annotation of biochemical models
   description: CNRI DOI Resolver
   homepage: http://www.handle.net/index.html
   institution: Corporation for National Research Initiatives
   location: USA
   official: false
 - identifier: MIR:00100751
   accessurl: http://doai.io/${lid}
   keyword: Minimum information requested in the annotation of biochemical models (MIRIAM)
   description: DOAI (Digital Open Access Identifier) at CAPSH
   homepage: http://doai.io/
   institution: CAPSH (Committee for the Accessibility of Publications in Sciences and Humanities), Paris
   location: France
   official: false
---
