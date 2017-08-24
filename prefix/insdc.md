---
identifier: MIR:00000029
name: Nucleotide Sequence Database
description: The International Nucleotide Sequence Database Collaboration (INSDC) consists of a joint effort to collect and disseminate databases containing DNA and RNA sequences.
prefix: insdc
pattern: ^([A-Z]\d{5}|[A-Z]{2}\d{6}|[A-Z]{4}\d{8}|[A-J][A-Z]{2}\d{5})(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100049
   accessurl: http://www.ncbi.nlm.nih.gov/entrez/viewer.fcgi?val=
   description: INSDC through GenBank
   location: USA
   official: false
 - identifier: MIR:00100066
   accessurl: http://getentry.ddbj.nig.ac.jp/getentry?database=ddbj&accession_number=
   description: INSDC through DDBJ
   location: Japan
   official: false
 - identifier: MIR:00100487
   accessurl: http://www.ebi.ac.uk/ena/data/view/
   description: INSDC through European Nucleotide Archive (ENA)
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100490
   accessurl: http://www.ncbi.nlm.nih.gov/nuccore/
   description: INSDC through Nucleotide database at NCBI
   location: USA
   official: false
   provider_code: ncbi
---
