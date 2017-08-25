---
identifier: MIR:00000088
name: Anatomical Therapeutic Chemical
description: The Anatomical Therapeutic Chemical (ATC) classification system, divides active substances into different groups according to the organ or system on which they act and their therapeutic, pharmacological and chemical properties. Drugs are classified in groups at five different levels;  Drugs are divided into fourteen main groups (1st level), with pharmacological/therapeutic subgroups (2nd level).  The 3rd and 4th levels are chemical/pharmacological/therapeutic subgroups and the 5th level is the chemical substance. The Anatomical Therapeutic Chemical (ATC) classification system and the Defined Daily Dose (DDD) is a tool for exchanging and comparing data on drug use at international, national or local levels.
prefix: atc
pattern: ^[A-Z](\d+([A-Z]{1,2}(\d+)?)?)?$
prefixed: 0
resources:
 - identifier: MIR:00100119
   accessurl: http://www.whocc.no/atc_ddd_index/?code=${id}
   test_id: A10BA02
   description: Anatomical Therapeutic Chemical Index at WHO
   homepage: http://www.whocc.no/atc_ddd_index/
   institution: World Health Organisation
   location: Switzerland
   official: false
---
