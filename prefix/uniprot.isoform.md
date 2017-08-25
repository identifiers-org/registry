---
identifier: MIR:00000388
name: UniProt Isoform
description: The UniProt Knowledgebase (UniProtKB) is a comprehensive resource for protein sequence and functional information with extensive cross-references to more than 120 external databases. This collection is a subset of UniProtKB, and provides a means to reference isoform information.
prefix: uniprot.isoform
pattern: ^([A-N,R-Z][0-9][A-Z][A-Z, 0-9][A-Z, 0-9][0-9])|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9])(\-\d+)$
prefixed: 0
resources:
 - identifier: MIR:00100502
   accessurl: http://www.uniprot.org/uniprot/${id}
   test_id: Q5BJF6-3
   description: UniProt Isoform through Universal Protein Resource
   homepage: http://www.uniprot.org/
   institution: UniProt Consortium
   location: USA, UK and Switzerland
   official: false
 - identifier: MIR:00100503
   accessurl: http://purl.uniprot.org/uniprot/${id}
   test_id: Q5BJF6-3
   description: UniProt Isoform through Universal Protein Resource using Persistent URL system
   homepage: http://purl.uniprot.org/
   institution: UniProt Consortium
   location: USA, UK and Switzerland
   official: false
 - identifier: MIR:00100504
   accessurl: http://www.uniprot.org/uniparc/?query=${id}
   test_id: Q5BJF6-3
   description: UniProt Isoform through UniParc
   homepage: http://www.uniprot.org/uniparc/
   institution: UniProt Consortium
   location: USA, UK and Switzerland
   official: false
---
