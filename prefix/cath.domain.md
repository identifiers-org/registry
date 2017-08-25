---
identifier: MIR:00000210
name: CATH domain
description: The CATH database is a hierarchical domain classification of protein structures in the Protein Data Bank. Protein structures are classified using a combination of automated and manual procedures. There are four major levels in this hierarchy; Class (secondary structure classification, e.g. mostly alpha), Architecture (classification based on overall shape), Topology (fold family) and Homologous superfamily (protein domains which are thought to share a common ancestor). This colelction is concerned with CATH domains.
prefix: cath.domain
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100269
   accessurl: http://www.cathdb.info/domain/${id}
   test_id: 1cukA01
   description: CATH domain at UCL
   homepage: http://www.cathdb.info/
   institution: Institute of Structural and Molecular Biology, University College London
   location: UK
   official: false
---
