---
identifier: MIR:00000036
name: ArrayExpress
description: ArrayExpress is a public repository for microarray data, which is aimed at storing MIAME-compliant data in accordance with Microarray Gene Expression Data (MGED) recommendations.
prefix: arrayexpress
pattern: ^[AEP]-\w{4}-\d+$
prefixed: 0
resources:
 - identifier: MIR:00100061
   accessurl: http://www.ebi.ac.uk/arrayexpress/experiments/${id}
   test_id: E-MEXP-1712
   description: ArrayExpress
   homepage: http://www.ebi.ac.uk/arrayexpress/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
