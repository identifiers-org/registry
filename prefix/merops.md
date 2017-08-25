---
identifier: MIR:00000059
name: MEROPS
description: The MEROPS database is an information resource for peptidases (also termed proteases, proteinases and proteolytic enzymes) and the proteins that inhibit them.
prefix: merops
pattern: ^[SCTAGMNU]\d{2}\.([AB]\d{2}|\d{3})$
prefixed: 0
resources:
 - identifier: MIR:00100087
   accessurl: http://merops.sanger.ac.uk/cgi-bin/pepsum?mid=${id}
   test_id: S01.001
   description: MEROPS database at Sanger Institute
   homepage: http://merops.sanger.ac.uk/index.htm
   institution: Wellcome Trust Sanger Institute
   location: United Kingdom
   official: false
---
