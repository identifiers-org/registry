---
identifier: MIR:00000488
name: PaxDb Organism
description: PaxDb is a resource dedicated to integrating information on absolute protein abundance levels across different organisms. Publicly available experimental data are mapped onto a common namespace and, in the case of tandem mass spectrometry data, re-processed using a standardized spectral counting pipeline. Data sets are scored and ranked to assess consistency against externally provided protein-network information. PaxDb provides whole-organism data as well as tissue-resolved data, for numerous proteins. This collection references protein abundance information by species.
prefix: paxdb.organism
pattern: ^\d+$
prefixed: 0
local_id: 9606
resources:
 - identifier: MIR:00100624
   accessurl: http://pax-db.org/#!species/${lid}
   keyword: Human, GPM, Oct,2012
   description: PaxDb v3 at University of Zurich
   homepage: http://pax-db.org/
   institution: Institute of Molecular Life Sciences, University of Zurich, Zurich
   location: Switzerland
   official: false
---
