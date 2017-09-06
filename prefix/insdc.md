---
identifier: MIR:00000029
name: Nucleotide Sequence Database
description: The International Nucleotide Sequence Database Collaboration (INSDC) consists of a joint effort to collect and disseminate databases containing DNA and RNA sequences.
prefix: insdc
pattern: ^([A-Z]\d{5}|[A-Z]{2}\d{6}|[A-Z]{4}\d{8}|[A-J][A-Z]{2}\d{5})(\.\d+)?$
prefixed: 0
local_id: X58356
synonyms:
 - International Nucleotide Sequence Database Collaboration
 - INSDC
 - NCBI nucleotide
 - GenBank
resources:
 - identifier: MIR:00100049
   accessurl: http://www.ncbi.nlm.nih.gov/entrez/viewer.fcgi?val=${lid}
   keyword: N.sylvestris gene for 33kd chloroplast ribonucleoprotein
   description: INSDC through GenBank
   homepage: http://www.ncbi.nlm.nih.gov/Genbank/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
 - identifier: MIR:00100066
   accessurl: http://getentry.ddbj.nig.ac.jp/getentry?database=ddbj&accession_number=${lid}
   keyword: N.sylvestris gene for 33kd chloroplast ribonucleoprotein
   description: INSDC through DDBJ
   homepage: http://www.ddbj.nig.ac.jp/
   institution: DNA Data Bank of Japan, Mishima, Shizuoka
   location: Japan
   official: false
 - identifier: MIR:00100487
   accessurl: http://www.ebi.ac.uk/ena/data/view/${lid}
   keyword: N.sylvestris gene for 33kd chloroplast ribonucleoprotein
   description: INSDC through European Nucleotide Archive (ENA)
   homepage: http://www.ebi.ac.uk/ena/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100490
   accessurl: http://www.ncbi.nlm.nih.gov/nuccore/${lid}
   keyword: N.sylvestris gene for 33kd chloroplast ribonucleoprotein
   description: INSDC through Nucleotide database at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/nuccore/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
