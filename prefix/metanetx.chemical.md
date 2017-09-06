---
identifier: MIR:00000567
name: MetaNetX chemical
description: MetaNetX/MNXref integrates various information from genome-scale metabolic network reconstructions such as information on reactions, metabolites and compartments. This information undergoes a reconciliation process to minimise for discrepancies between different data sources, and makes the data accessible under a common namespace. This collection references chemical or metabolic components.
prefix: metanetx.chemical
pattern: ^(MNXM\d+|BIOMASS)$
prefixed: 0
local_id: MNXM1723
resources:
 - identifier: MIR:00100748
   accessurl: http://www.metanetx.org/chem_info/${lid}
   keyword: glucose phosphate
   description: MetaNetX chemical at SIB Swiss Institute of Bioinformatics
   homepage: http://www.metanetx.org/
   institution: Vital-IT group, SIB Swiss Institute of Bioinformatics, Lausanne
   location: Switzerland
   official: false
---
