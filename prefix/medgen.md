---
identifier: MIR:00000594
name: MedGen
description: MedGen is a portal for information about conditions and phenotypes related to Medical Genetics. Terms from multiple sources are aggregated into concepts, each of which is assigned a unique identifier and a preferred name and symbol. The core content of the record may include names, identifiers used by other databases, mode of inheritance, clinical features, and map location of the loci affecting the disorder.
prefix: medgen
pattern: ^[CN]*\d{4,7}$
prefixed: 0
local_id: 760050
resources:
 - identifier: MIR:00100794
   accessurl: https://www.ncbi.nlm.nih.gov/medgen/${lid}
   keyword: Caffeine
   description: MedGen at NCBI
   homepage: https://www.ncbi.nlm.nih.gov/medgen/
   institution: National Center for Biotechnology Information (NCBI), NIH, Maryland
   location: USA
   official: false
   provider_code: ncbi
---
