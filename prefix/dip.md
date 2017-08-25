---
identifier: MIR:00000044
name: Database of Interacting Proteins
description: The database of interacting protein (DIP) database stores experimentally determined interactions between proteins. It combines information from a variety of sources to create a single, consistent set of protein-protein interactions
prefix: dip
pattern: ^DIP(\:)?\-\d{1,}[ENXS]$
prefixed: 0
resources:
 - identifier: MIR:00100072
   accessurl: http://dip.doe-mbi.ucla.edu/dip/DIPview.cgi?ID=${id}
   test_id: DIP-743N
   description: Database of interacting proteins
   homepage: http://dip.doe-mbi.ucla.edu/
   institution: UCLA
   location: USA
   official: false
---
