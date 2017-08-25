---
identifier: MIR:00000125
name: PhosphoSite Residue
description: PhosphoSite is a mammalian protein database that provides information about in vivo phosphorylation sites. This datatype refers to residue-level information, providing a information about a single modification position in a specific protein sequence.
prefix: phosphosite.residue
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100159
   accessurl: http://www.phosphosite.org/siteAction.do?id=${id}
   test_id: 2842
   description: PhosphoSite Residue
   homepage: http://www.phosphosite.org/homeAction.do
   institution: Cell Signaling Technology, Inc.
   location: USA
   official: false
---
