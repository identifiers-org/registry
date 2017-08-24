---
identifier: MIR:00000273
name: MassBank
description: MassBank is a federated database of reference spectra from different instruments, including high-resolution mass spectra of small metabolites (<3000 Da).
prefix: massbank
pattern: ^[A-Z]{2}[A-Z0-9][0-9]{5}$
prefixed: 0
resources:
 - identifier: MIR:00100353
   accessurl: http://www.massbank.jp/jsp/FwdRecord.jsp?id=
   description: MassBank in Japan
   location: Japan
   official: true
 - identifier: MIR:00100666
   accessurl: http://www.massbank.eu/MassBank/jsp/FwdRecord.jsp?id=
   description: MassBank in Europe
   location: Germany
   official: false
---
