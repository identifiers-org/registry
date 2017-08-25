---
identifier: MIR:00000360
name: Tissue List
description: The UniProt Tissue List is a controlled vocabulary of terms used to annotate biological tissues. It also contains cross-references to other ontologies where tissue types are specified.
prefix: tissuelist
pattern: ^TS-\d{4}$
prefixed: 0
resources:
 - identifier: MIR:00100457
   accessurl: http://www.uniprot.org/tissues/${id}
   test_id: TS-0285
   description: Tissue List at Swiss Institute of Bioinformatics
   homepage: http://www.uniprot.org/docs/tisslist.txt
   institution: Swiss Institute of Bioinformatics (SIB), Geneva
   location: Switzerland
   official: false
---
