---
identifier: MIR:00000237
name: CAS
description: CAS (Chemical Abstracts Service) is a division of the American Chemical Society and is the producer of comprehensive databases of chemical information.
prefix: cas
pattern: ^\d{1,7}\-\d{2}\-\d$
prefixed: 0
local_id: 50-00-0
synonyms:
 - Chemical Abstracts Service
 - CAS Registry Number
 - CAS Number
 - CASRN
resources:
 - identifier: MIR:00100301
   accessurl: https://commonchemistry.cas.org/detail?cas_rn=${lid}
   keyword: Formaldehyde
   description: CAS Common Chemistry
   homepage: http://commonchemistry.cas.org/
   institution: American Chemistry Society, Washington, DC
   location: USA
   official: false
---
