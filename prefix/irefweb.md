---
identifier: MIR:00000123
name: iRefWeb
description: iRefWeb is an interface to a relational database containing the latest build of the interaction Reference Index (iRefIndex) which integrates protein interaction data from ten different interaction databases: BioGRID, BIND, CORUM, DIP, HPRD, INTACT, MINT, MPPI, MPACT and OPHID. In addition, iRefWeb associates interactions with the PubMed record from which they are derived.
prefix: irefweb
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100156
   accessurl: http://wodaklab.org/iRefWeb/interaction/show/${id}
   test_id: 617102
   description: iRefWeb Protein Interaction Reference Index
   homepage: http://wodaklab.org/iRefWeb/
   institution: Wodak Lab, Hospital for Sick Children, Toronto
   location: Canada
   official: false
---
