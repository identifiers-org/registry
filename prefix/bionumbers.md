---
identifier: MIR:00000101
name: BioNumbers
description: BioNumbers is a database of key numberical information that may be used in molecular biology. Along with the numbers, it contains references to the original literature, useful comments, and related numeric data. 

prefix: bionumbers
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100132
   accessurl: http://www.bionumbers.hms.harvard.edu/bionumber.aspx?s=y&id=${id}&ver=1
   test_id: 104674
   description: BioNumbers database
   homepage: http://www.bionumbers.hms.harvard.edu/search.aspx
   institution: Weizmann Institute
   location: Israel
   official: false
---
