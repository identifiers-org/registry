---
identifier: MIR:00000416
name: BacMap Map
description: BacMap is an electronic, interactive atlas of fully sequenced bacterial genomes. It contains labeled, zoomable and searchable chromosome maps for sequenced prokaryotic (archaebacterial and eubacterial) species. Each map can be zoomed to the level of individual genes and each gene is hyperlinked to a richly annotated gene card. All bacterial genome maps are supplemented with separate prophage genome maps as well as separate tRNA and rRNA maps. Each bacterial chromosome entry in BacMap contains graphs and tables on a variety of gene and protein statistics. Likewise, every bacterial species entry contains a bacterial 'biography' card, with taxonomic details, phenotypic details, textual descriptions and images. This collection references genome map information.
prefix: bacmap.map
pattern: ^\w+(\_)?\d+(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100539
   accessurl: http://bacmap.wishartlab.com/maps/${id}/index.html
   test_id: AP011135
   description: BacMap Genome Map at University of Alberta
   homepage: http://bacmap.wishartlab.com/
   institution: Department of Computing Science, Food and Nutritional Science, University of Alberta, Edmonton
   location: Canada
   official: false
---
