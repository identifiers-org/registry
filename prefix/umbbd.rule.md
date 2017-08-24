---
identifier: MIR:00000328
name: UM-BBD Biotransformation Rule
description: The University of Minnesota Biocatalysis/Biodegradation Database (UM-BBD) contains information on microbial biocatalytic reactions and biodegradation pathways for primarily xenobiotic, chemical compounds. The UM-BBD Pathway Prediction System (PPS) predicts microbial catabolic reactions using substructure searching, a rule-base, and atom-to-atom mapping. The PPS recognizes organic functional groups found in a compound and predicts transformations based on biotransformation rules. These rules are based on reactions found in the UM-BBD database. This collection references those rules.
prefix: umbbd.rule
pattern: ^bt\d+$
prefixed: 0
resources:
 - identifier: MIR:00100421
   accessurl: http://www.umbbd.ethz.ch/servlets/rule.jsp?rule=
   description: Biocatalysis/Biodegradation Database Mirror (Biotransformation Rule) at ETH Zurich
   location: Switzerland
   official: false
---
