---
identifier: MIR:00000100
name: CTD Gene
description: The Comparative Toxicogenomics Database (CTD) presents scientifically reviewed and curated information on chemicals, relevant genes and proteins, and their interactions in vertebrates and invertebrates. It integrates sequence, reference, species, microarray, and general toxicology information to provide a unique centralized resource for toxicogenomic research. The database also provides visualization capabilities that enable cross-species comparisons of gene and protein sequences.
prefix: ctd.gene
pattern: ^\d+$
prefixed: 0
local_id: 101
resources:
 - identifier: MIR:00100131
   accessurl: http://ctdbase.org/detail.go?type=gene&acc=${lid}
   keyword: ADAM metallopeptidase domain
   description: Comparative Toxicogenomics Database (Gene)
   homepage: http://ctdbase.org/
   institution: The Mount Desert Island Biological Laboratory
   location: USA
   official: false
---
