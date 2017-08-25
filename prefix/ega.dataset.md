---
identifier: MIR:00000512
name: European Genome-phenome Archive Dataset
description: The EGA is a service for permanent archiving and sharing of all types of personally identifiable genetic and phenotypic data resulting from biomedical research projects. The EGA contains exclusive data collected from individuals whose consent agreements authorize data release only for specific research use or to bona fide researchers. Strict protocols govern how information is managed, stored and distributed by the EGA project. This collection references 'Datasets'.
prefix: ega.dataset
pattern: ^EGAD\d{11}$
prefixed: 0
resources:
 - identifier: MIR:00100658
   accessurl: https://www.ebi.ac.uk/ega/datasets/${id}
   test_id: EGAD00000000001
   description: EGA Dataset at European Bioinformatics Institute
   homepage: https://www.ebi.ac.uk/ega/dataset
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
