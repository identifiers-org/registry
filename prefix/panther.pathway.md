---
identifier: MIR:00000363
name: PANTHER Pathway
description: The PANTHER (Protein ANalysis THrough Evolutionary Relationships) Classification System is a resource that classifies genes by their functions, using published scientific experimental evidence and evolutionary relationships to predict function even in the absence of direct experimental evidence. The PANTHER Pathway collection references pathway information, primarily for signaling pathways, each with subfamilies and protein sequences mapped to individual pathway components.
prefix: panther.pathway
pattern: ^P\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100461
   accessurl: http://www.pantherdb.org/pathway/pathwayDiagram.jsp?catAccession=${id}
   test_id: P00024
   description: PANTHER Pathway at USC (Los Angeles)
   homepage: http://www.pantherdb.org/
   institution: Keck School of Medicine, University of Southern California
   location: USA
   official: false
---
