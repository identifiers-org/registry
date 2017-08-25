---
identifier: MIR:00000159
name: dbEST
description: The dbEST contains sequence data and other information on "single-pass" cDNA sequences, or "Expressed Sequence Tags", from a number of organisms.
prefix: dbest
pattern: ^([A-Z]+)?\d+(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100204
   accessurl: http://www.ncbi.nlm.nih.gov/nucest/${id}
   test_id: BP100000
   description: dbEST at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/nucest
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100331
   accessurl: http://www.ebi.ac.uk/ena/data/view/${id}
   test_id: BP100000.1
   description: dbEST through European Nucleotide Archive (ENA)
   homepage: http://www.ebi.ac.uk/ena
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100651
   accessurl: http://getentry.ddbj.nig.ac.jp/getentry/na/${id}
   test_id: BP100000
   description: dbEST through DNA Data Bank of Japan (DDBJ)
   homepage: http://www.ddbj.nig.ac.jp/
   institution: DNA Data Bank of Japan, Mishima, Shizuoka
   location: Japan
   official: false
---
