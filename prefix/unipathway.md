---
identifier: MIR:00000083
name: Unipathway
description: UniPathway is a manually curated resource of metabolic pathways for the UniProtKB/Swiss-Prot knowledgebase. It provides a structured controlled vocabulary to describe the role of a protein in a metabolic pathway.
prefix: unipathway
pattern: ^UPA\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100114
   accessurl: http://www.grenoble.prabi.fr/obiwarehouse/unipathway/upa?upid=${id}
   test_id: UPA00206
   description: UniPathway
   homepage: http://www.grenoble.prabi.fr/obiwarehouse/unipathway
   institution: Swiss Institute of Bioinformatics (SIB) and French National Institute for Research in Computer Science and Control
   location: Switzerland
   official: false
---
