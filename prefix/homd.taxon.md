---
identifier: MIR:00000171
name: HOMD Taxonomy
description: The Human Oral Microbiome Database (HOMD) provides a site-specific comprehensive database for the more than 600 prokaryote species that are present in the human oral cavity. It contains genomic information based on a curated 16S rRNA gene-based provisional naming scheme, and taxonomic information. This datatype contains taxonomic information.
prefix: homd.taxon
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100217
   accessurl: http://www.homd.org/modules.php?op=modload&name=HOMD&file=index&oraltaxonid=${id}&view=dynamic
   test_id: 811
   description: HOMD taxon information at The Forsyth Institute
   homepage: http://www.homd.org/index.php
   institution: The Forsyth Institute, Boston
   location: USA
   official: false
---
