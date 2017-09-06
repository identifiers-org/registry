---
identifier: MIR:00000105
name: PhosphoSite Protein
description: PhosphoSite is a mammalian protein database that provides information about in vivo phosphorylation sites. This datatype refers to protein-level information, providing a list of phosphorylation sites for each protein in the database.
prefix: phosphosite.protein
pattern: ^\d{5}$
prefixed: 0
local_id: 12300
synonyms:
 - PhosphoSitePlus
resources:
 - identifier: MIR:00100138
   accessurl: http://www.phosphosite.org/proteinAction.do?id=${lid}
   keyword: TFIIH to the initiation
   description: PhosphoSite
   homepage: http://www.phosphosite.org/homeAction.do
   institution: Cell Signaling Technology, Inc.
   location: USA
   official: false
---
