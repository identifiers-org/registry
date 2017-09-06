---
identifier: MIR:00000422
name: PANTHER Pathway Component
description: The PANTHER (Protein ANalysis THrough Evolutionary Relationships) Classification System is a resource that classifies genes by their functions, using published scientific experimental evidence and evolutionary relationships to predict function even in the absence of direct experimental evidence. The PANTHER Pathway Component collection references specific classes of molecules that play the same mechanistic role within a pathway, across species. Pathway
components may be proteins, genes/DNA, RNA, or simple molecules. Where the identified component is a protein, DNA, or transcribed RNA, it is associated with protein sequences in the PANTHER protein family trees through manual curation.
prefix: panther.pthcmp
pattern: ^G|P|U|C|S\d{5}$
prefixed: 0
local_id: P00266
resources:
 - identifier: MIR:00100545
   accessurl: http://www.pantherdb.org/pathway/pathCatDetail.do?clsAccession=${lid}
   keyword: MAP kinase superfamily
   description: PANTHER Pathway Component at USC (Los Angeles)
   homepage: http://www.pantherdb.org/
   institution: Keck School of Medicine, University of Southern California
   location: USA
   official: false
---
