---
identifier: MIR:00000070
name: KEGG Genes
description: KEGG GENES is a collection of gene catalogs for all complete genomes and some partial genomes, generated from publicly available resources.
prefix: kegg.genes
pattern: ^\w+:[\w\d\.-]*$
prefixed: 0
resources:
 - identifier: MIR:00100100
   accessurl: http://www.kegg.jp/entry/${id}
   test_id: syn:ssr3451
   description: KEGG GENES Database
   homepage: http://www.genome.jp/kegg/genes.html
   institution: Kyoto University Bioinformatics Center
   location: Japan
   official: true
---
