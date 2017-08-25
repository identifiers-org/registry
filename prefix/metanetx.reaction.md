---
identifier: MIR:00000568
name: MetaNetX reaction
description: MetaNetX/MNXref integrates various information from genome-scale metabolic network reconstructions such as information on reactions, metabolites and compartments. This information undergoes a reconciliation process to minimise for discrepancies between different data sources, and makes the data accessible under a common namespace. This collection references reactions.
prefix: metanetx.reaction
pattern: ^MNXR\d+$
prefixed: 0
resources:
 - identifier: MIR:00100749
   accessurl: http://www.metanetx.org/equa_info/${id}
   test_id: MNXR101574
   description: MetaNetX reaction at SIB Swiss Institute of Bioinformatics
   homepage: http://www.metanetx.org/
   institution: Vital-IT group, SIB Swiss Institute of Bioinformatics, Lausanne
   location: Switzerland
   official: false
---
