---
identifier: MIR:00000340
name: TarBase
description: TarBase stores microRNA (miRNA) information for miRNA–gene interactions, as well as miRNA- and gene-related facts to information specific to the interaction and the experimental validation methodologies used.
prefix: tarbase
pattern: ^[a-z]{3}\-(mir|let|lin)\-\w+(\-\w+\-\w+)?
prefixed: 0
resources:
 - identifier: MIR:00100713
   accessurl: http://diana.imis.athena-innovation.gr/DianaTools/index.php?r=tarbase/index&mirnas=${id}
   test_id: hsa-let-7a-2-3p
   description: TarBase v7 at University of Thessaly
   homepage: http://diana.imis.athena-innovation.gr/DianaTools/index.php?r=tarbase/index
   institution: DIANA-Lab, Department of Electrical & Computer Engineering, University of Thessaly
   location: Greece
   official: false
---
