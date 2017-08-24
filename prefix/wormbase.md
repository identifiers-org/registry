---
identifier: MIR:00000027
name: WormBase
description: WormBase is an online bioinformatics database of the biology and genome of the model organism Caenorhabditis elegans and related nematodes. It is used by the C. elegans research community both as an information resource and as a mode to publish and distribute their results. This collection references genes.
prefix: wormbase
pattern: ^(WBGene\d{8}|([A-Z_a-z0-9]+(\.)?(t)?(\d+)?([a-z])?))$
prefixed: 0
resources:
 - identifier: MIR:00100038
   accessurl: http://www.wormbase.org/db/gene/gene?name=
   description: WormBase (Master)
   location: USA
   official: true
 - identifier: MIR:00100704
   accessurl: http://wormbase.bio2rdf.org/describe/?url=http://bio2rdf.org/wormbase:
   description: Bio2RDF
   location: 
   official: false
---
