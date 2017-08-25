---
identifier: MIR:00000226
name: ProtClustDB
description: ProtClustDB is a collection of related protein sequences (clusters) consisting of Reference Sequence proteins encoded by complete genomes. This database contains both curated and non-curated clusters.
prefix: protclustdb
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100285
   accessurl: http://www.ncbi.nlm.nih.gov/sites/entrez?Db=proteinclusters&Cmd=DetailsSearch&Term=${id}
   test_id: O80725
   description: ProtClustDB at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/proteinclusters?db=proteinclusters
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
