---
identifier: MIR:00000388
name: UniProt Isoform
description: The UniProt Knowledgebase (UniProtKB) is a comprehensive resource for protein sequence and functional information with extensive cross-references to more than 120 external databases. This collection is a subset of UniProtKB, and provides a means to reference isoform information.
prefix: uniprot.isoform
pattern: ^([A-N,R-Z][0-9][A-Z][A-Z, 0-9][A-Z, 0-9][0-9])|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9])(\-\d+)$
prefixed: 0
resources:
 - identifier: MIR:00100502
   accessurl: http://www.uniprot.org/uniprot/
   description: UniProt Isoform through Universal Protein Resource
   location: USA, UK and Switzerland
   official: false
 - identifier: MIR:00100503
   accessurl: http://purl.uniprot.org/uniprot/
   description: UniProt Isoform through Universal Protein Resource using Persistent URL system
   location: USA, UK and Switzerland
   official: false
 - identifier: MIR:00100504
   accessurl: http://www.uniprot.org/uniparc/?query=
   description: UniProt Isoform through UniParc
   location: USA, UK and Switzerland
   official: false
---
