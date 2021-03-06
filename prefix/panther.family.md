---
identifier: MIR:00000060
name: PANTHER Family
description: The PANTHER (Protein ANalysis THrough Evolutionary Relationships) Classification System is a resource that classifies genes by their functions, using published scientific experimental evidence and evolutionary relationships to predict function even in the absence of direct experimental evidence. This collection references groups of genes that have been organised as families.
prefix: panther.family
pattern: ^PTHR\d{5}(\:SF\d{1,3})?$
prefixed: 0
local_id: PTHR12345
resources:
 - identifier: MIR:00100088
   accessurl: http://www.pantherdb.org/panther/family.do?clsAccession=${lid}
   keyword: membrane trafficking regulatory protein
   description: PANTHER Family at USC (Los Angeles)
   homepage: http://www.pantherdb.org/
   institution: Keck School of Medicine, University of Southern California
   location: USA
   official: false
---
