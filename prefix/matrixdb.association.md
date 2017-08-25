---
identifier: MIR:00000068
name: MatrixDB
description: MatrixDB stores experimentally determined interactions involving at least one extracellular biomolecule. It includes mostly protein-protein and protein-glycosaminoglycan interactions, as well as interactions with lipids and cations.
prefix: matrixdb.association
pattern: ^([A-N,R-Z][0-9][A-Z][A-Z, 0-9][A-Z, 0-9][0-9])_.*|([O,P,Q][0-9][A-Z, 0-9][A-Z, 0-9][A-Z, 0-9][0-9]_.*)|(GAG_.*)|(MULT_.*)|(PFRAG_.*)|(LIP_.*)|(CAT_.*)$
prefixed: 0
resources:
 - identifier: MIR:00100098
   accessurl: http://matrixdb.univ-lyon1.fr//cgi-bin/current/newPort?type=association&value=${id}&class=Association
   test_id: P00747__P07355
   description: MatrixDB Association
   homepage: http://matrixdb.univ-lyon1.fr/
   institution: Institut de Biologie et Chimie des Protéines, Lyon University
   location: France
   official: true
---
