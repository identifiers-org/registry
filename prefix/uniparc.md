---
identifier: MIR:00000041
name: UniParc
description: The UniProt Archive (UniParc) is a  database containing non-redundant protein sequence information from many sources. Each unique sequence is given a stable and unique identifier (UPI) making it possible to identify the same protein from different source databases.
prefix: uniparc
pattern: ^UPI[A-F0-9]{10}$
prefixed: 0
resources:
 - identifier: MIR:00100069
   accessurl: http://www.ebi.ac.uk/cgi-bin/dbfetch?db=uniparc&id=${id}
   test_id: UPI000000000A
   description: UniProt Archive (UniParc)
   homepage: http://www.ebi.ac.uk/uniparc/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100476
   accessurl: http://www.uniprot.org/uniparc/${id}
   test_id: UPI000000000A
   description: UniParc through UniProt
   homepage: http://www.uniprot.org/uniparc/
   institution: UniProt Consortium
   location: USA, UK and Switzerland
   official: false
---
