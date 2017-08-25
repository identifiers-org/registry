---
identifier: MIR:00000027
name: WormBase
description: WormBase is an online bioinformatics database of the biology and genome of the model organism Caenorhabditis elegans and related nematodes. It is used by the C. elegans research community both as an information resource and as a mode to publish and distribute their results. This collection references genes.
prefix: wormbase
pattern: ^(WBGene\d{8}|([A-Z_a-z0-9]+(\.)?(t)?(\d+)?([a-z])?))$
prefixed: 0
resources:
 - identifier: MIR:00100038
   accessurl: http://www.wormbase.org/db/gene/gene?name=${id};class=Gene
   test_id: WBGene00000001
   description: WormBase (Master)
   homepage: http://www.wormbase.org/
   institution: Cold Spring Harbor Laboratory
   location: USA
   official: true
 - identifier: MIR:00100704
   accessurl: http://wormbase.bio2rdf.org/describe/?url=http://bio2rdf.org/wormbase:${id}
   test_id: WBGene00000001
   description: Bio2RDF
   homepage: http://wormbase.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---
