---
identifier: MIR:00000294
name: ArrayExpress Platform
description: ArrayExpress is a public repository for microarray data, which is aimed at storing MIAME-compliant data in accordance with Microarray Gene Expression Data (MGED) recommendations.This collection references the specific platforms used in the generation of experimental results.
prefix: arrayexpress.platform
pattern: ^[AEP]-\w{4}-\d+$
prefixed: 0
local_id: A-GEOD-50
resources:
 - identifier: MIR:00100376
   accessurl: http://www.ebi.ac.uk/arrayexpress/arrays/${lid}
   keyword: spotted DNA/cDNA
   description: ArrayExpress Platform at EBI
   homepage: http://www.ebi.ac.uk/arrayexpress/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
