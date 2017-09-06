---
identifier: MIR:00000558
name: RRID
description: The Research Resource Identification Initiative provides RRIDs to 4 main classes of resources: Antibodies, Cell Lines, Model Organisms, and Databases / Software tools.: Antibodies, Model Organisms, and Databases / Software tools.
The initiative works with participating journals to intercept manuscripts in the publication process that use these resources, and allows publication authors to incorporate RRIDs within the methods sections. It also provides resolver services that access curated data from 10 data sources: the antibody registry (a curated catalog of antibodies), the SciCrunch registry (a curated catalog of software tools and databases), and model organism nomenclature authority databases (MGI, FlyBase, WormBase, RGD), as well as various stock centers. These RRIDs are aggregated and can be searched through SciCrunch.
prefix: rrid
pattern: ^RRID:[A-Z_a-z-0-9]+$
prefixed: 1
local_id: AB_262044
synonyms:
 - Research Resource IDentifier
resources:
 - identifier: MIR:00100735
   accessurl: https://scicrunch.org/resolver/RRID:${lid}
   keyword: Cat# F1804
   description: RRID at SciCrunch
   homepage: https://scicrunch.org/resolver
   institution: University of California, San Diego
   location: USA
   official: false
---
