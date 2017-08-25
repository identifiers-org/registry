---
identifier: MIR:00000028
name: Pfam
description: The Pfam database contains information about protein domains and families. For each entry a protein sequence alignment and a Hidden Markov Model is stored.
prefix: pfam
pattern: ^PF\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100685
   accessurl: http://pfam.xfam.org/family/${id}
   test_id: PF01234
   description: Pfam at EMBL-EBI
   homepage: http://pfam.xfam.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
---
