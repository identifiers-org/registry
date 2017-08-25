---
identifier: MIR:00000570
name: UniPathway Reaction
description: UniPathway is a manually curated resource of enzyme-catalyzed and spontaneous chemical reactions. It provides a hierarchical representation of metabolic pathways and a controlled vocabulary for pathway annotation in UniProtKB. UniPathway data are cross-linked to existing metabolic resources such as ChEBI/Rhea, KEGG and MetaCyc. This collection references individual reactions.
prefix: unipathway.reaction
pattern: ^UCR\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100752
   accessurl: http://www.grenoble.prabi.fr/obiwarehouse/unipathway/ucr?upid=${id}
   test_id: UCR00226
   description: UniPathway Reaction at Swiss Institute of Bioinformatics (SIB)
   homepage: http://www.grenoble.prabi.fr/obiwarehouse/unipathway
   institution: Swiss Institute of Bioinformatics (SIB) and French National Institute for Research in Computer Science and Control
   location: Switzerland
   official: false
---
