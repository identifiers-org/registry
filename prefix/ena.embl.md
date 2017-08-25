---
identifier: MIR:00000372
name: ENA
description: The European Nucleotide Archive (ENA) captures and presents information relating to experimental workflows that are based around nucleotide sequencing. ENA is made up of a number of distinct databases that includes EMBL-Bank, the Sequence Read Archive (SRA) and the Trace Archive each with their own data formats and standards. This collection references Embl-Bank identifiers.
prefix: ena.embl
pattern: ^[A-Z]+[0-9]+(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100473
   accessurl: http://www.ebi.ac.uk/ena/data/view/${id}
   test_id: BN000065
   description: ENA at European Bioinformatics Institute
   homepage: http://www.ebi.ac.uk/ena/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
