---
identifier: MIR:00000054
name: GEO
description: The Gene Expression Omnibus (GEO) is a gene expression repository providing a curated, online resource for gene expression data browsing, query and retrieval.
prefix: geo
pattern: ^G(PL|SM|SE|DS)\d+$
prefixed: 0
resources:
 - identifier: MIR:00100082
   accessurl: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=${id}
   test_id: GDS1234
   description: Gene Expression Omnibus at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/geo/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
