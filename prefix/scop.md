---
identifier: MIR:00000371
name: SCOP
description: The SCOP (Structural Classification of Protein) database is a comprehensive ordering of all proteins of known structure according to their evolutionary, functional and structural relationships. The basic classification unit is the protein domain. Domains are hierarchically classified into species, proteins, families, superfamilies, folds, and classes.
prefix: scop
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100470
   accessurl: http://scop.mrc-lmb.cam.ac.uk/scop/search.cgi?sunid=${id}
   test_id: 47419
   description: SCOP at MRC
   homepage: http://scop.mrc-lmb.cam.ac.uk/scop/
   institution: MRC Laboratory of Molecular Biology, Centre for Protein Engineering, Hills Road, Cambridge
   location: UK
   official: false
 - identifier: MIR:00100471
   accessurl: http://scop.berkeley.edu/sunid=${id}
   test_id: 47419
   description: SCOP at Berkeley
   homepage: http://scop.berkeley.edu/
   institution: University of California, Berkeley
   location: USA
   official: false
---
