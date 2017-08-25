---
identifier: MIR:00000395
name: TreeFam
description: TreeFam is a database of phylogenetic trees of gene families found in animals. Automatically generated trees are curated, to create a curated resource that presents the accurate evolutionary history of all animal gene families, as well as reliable ortholog and paralog assignments.
prefix: treefam
pattern: ^\w{1,2}\d+$
prefixed: 0
resources:
 - identifier: MIR:00100515
   accessurl: http://www.treefam.org/family/${id}
   test_id: TF101014
   description: TreeFam database
   homepage: http://www.treefam.org/
   institution: Beijing Genomics Institute, Beijing
   location: China
   official: false
---
