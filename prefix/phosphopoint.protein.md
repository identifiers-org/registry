---
identifier: MIR:00000386
name: PhosphoPoint Phosphoprotein
description: PhosphoPOINT is a database of the human kinase and phospho-protein interactome. It describes the interactions among kinases, their potential substrates and their interacting (phospho)-proteins. It also incorporates gene expression and uses gene ontology (GO) terms to annotate interactions. This collection references phosphoprotein information.
prefix: phosphopoint.protein
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100500
   accessurl: http://kinase.bioinformatics.tw/showall.jsp?type=PhosphoProtein&info=Gene&name=${id}&drawing=0&sorting=0&kinome=0
   test_id: AURKA
   description: PhosphoPoint Phosphoprotein at National Taiwan University
   homepage: http://kinase.bioinformatics.tw/
   institution: Department of Computer Science and Information Engineering, National Taiwan University
   location: Republic of China
   official: false
---
