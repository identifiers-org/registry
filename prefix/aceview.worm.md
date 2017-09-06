---
identifier: MIR:00000282
name: Aceview Worm
description: AceView provides a curated sequence representation of all public mRNA sequences (mRNAs from GenBank or RefSeq, and single pass cDNA sequences from dbEST and Trace). These are aligned on the genome and clustered into a minimal number of alternative transcript variants and grouped into genes. In addition, alternative features such as promoters, and expression in tissues is recorded. This collection references C. elegans genes and expression.
prefix: aceview.worm
pattern: ^[a-z0-9-]+$
prefixed: 0
local_id: aap-1
synonyms:
 - AceView WormGenes
resources:
 - identifier: MIR:00100363
   accessurl: http://www.ncbi.nlm.nih.gov/IEB/Research/Acembly/av.cgi?db=worm&c=Gene&l=${lid}
   keyword: phosphoinositide 3-kinase
   description: AceView Worm at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/IEB/Research/Acembly/index.html?worm
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
