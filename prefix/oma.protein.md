---
identifier: MIR:00000342
name: OMA Protein
description: OMA (Orthologous MAtrix) is a database that identifies orthologs among publicly available, complete genome sequences. It identifies orthologous relationships which can be accessed either group-wise, where all group members are orthologous to all other group members, or on a sequence-centric basis, where for a given protein all its orthologs in all other species are displayed. This collection references individual protein records.
prefix: oma.protein
pattern: ^[A-Z0-9]{5}\d+$
prefixed: 0
resources:
 - identifier: MIR:00100437
   accessurl: http://omabrowser.org/cgi-bin/gateway.pl?f=DisplayEntry&p1=${id}
   test_id: HUMAN16963
   description: OMA Protein through OMA browser at ETH Zurich
   homepage: http://omabrowser.org/cgi-bin/gateway.pl
   institution: ETH Zurich, Computer Science, Zurich
   location: Switzerland
   official: false
---
