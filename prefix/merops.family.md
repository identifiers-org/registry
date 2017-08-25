---
identifier: MIR:00000302
name: MEROPS Family
description: The MEROPS database is an information resource for peptidases (also termed proteases, proteinases and proteolytic enzymes) and the proteins that inhibit them. These are hierarchically classified and assigned to a Family on the basis of statistically significant similarities in amino acid sequence. Families thought to be homologous are grouped together in a Clan. This collection references peptidase families.
prefix: merops.family
pattern: ^[SCTAGMNU]\d+$
prefixed: 0
resources:
 - identifier: MIR:00100384
   accessurl: http://merops.sanger.ac.uk/cgi-bin/famsum?family=${id}
   test_id: S1
   description: Merops Family at Sanger Institute
   homepage: http://merops.sanger.ac.uk/index.htm
   institution: Wellcome Trust Sanger Institute, Hinxton
   location: UK
   official: false
---
