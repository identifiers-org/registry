---
identifier: MIR:00000343
name: OMA Group
description: OMA (Orthologous MAtrix) is a database that identifies orthologs among publicly available, complete genome sequences. It identifies orthologous relationships which can be accessed either group-wise, where all group members are orthologous to all other group members, or on a sequence-centric basis, where for a given protein all its orthologs in all other species are displayed. This collection references groupings of orthologs.
prefix: oma.grp
pattern: ^[A-Z]+$
prefixed: 0
local_id: LCSCCPN
resources:
 - identifier: MIR:00100438
   accessurl: http://omabrowser.org/cgi-bin/gateway.pl?f=DisplayGroup&p1=${lid}
   keyword: SARHA02316
   description: OMA Group through OMA browser at ETH Zurich
   homepage: http://omabrowser.org/cgi-bin/gateway.pl
   institution: ETH Zurich, Computer Science, Zurich
   location: Switzerland
   official: false
---
