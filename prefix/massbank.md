---
identifier: MIR:00000273
name: MassBank
description: MassBank is a federated database of reference spectra from different instruments, including high-resolution mass spectra of small metabolites (<3000 Da).
prefix: massbank
pattern: ^[A-Z]{2}[A-Z0-9][0-9]{5}$
prefixed: 0
resources:
 - identifier: MIR:00100353
   accessurl: http://www.massbank.jp/jsp/FwdRecord.jsp?id=${id}
   test_id: PB000166
   description: MassBank in Japan
   homepage: http://www.massbank.jp
   institution: The MassBank Consortium
   location: Japan
   official: true
 - identifier: MIR:00100666
   accessurl: http://www.massbank.eu/MassBank/jsp/FwdRecord.jsp?id=${id}
   test_id: PB000166
   description: MassBank in Europe
   homepage: http://www.massbank.eu/
   institution: NORMAN Network and The MassBank Consortium
   location: Germany
   official: false
---
