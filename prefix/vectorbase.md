---
identifier: MIR:00000232
name: VectorBase
description: VectorBase is an NIAID-funded Bioinformatic Resource Center focused on invertebrate vectors of human pathogens. VectorBase annotates and curates vector genomes providing a web accessible integrated resource for the research community. Currently, VectorBase contains genome information for three mosquito species: Aedes aegypti, Anopheles gambiae and Culex quinquefasciatus, a body louse Pediculus humanus and a tick species Ixodes scapularis.
prefix: vectorbase
pattern: ^\D{4}\d{6}(\-\D{2})?$
prefixed: 0
local_id: ISCW007415
resources:
 - identifier: MIR:00100291
   accessurl: https://www.vectorbase.org/search/site/${lid}?&site="Genome"
   keyword: hypothetical protein
   description: Vectorbase at EMBL-EBI
   homepage: http://www.vectorbase.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
---
