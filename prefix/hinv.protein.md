---
identifier: MIR:00000169
name: H-InvDb Protein
description: H-Invitational Database (H-InvDB) is an integrated database of human genes and transcripts. It provides curated annotations of human genes and transcripts including gene structures, alternative splicing isoforms, non-coding functional RNAs, protein functions, functional domains, sub-cellular localizations, metabolic pathways, protein 3D structure, genetic polymorphisms (SNPs, indels and microsatellite repeats), relation with diseases, gene expression profiling, molecular evolutionary features, protein-protein interactions (PPIs) and gene families/groups. This datatype provides access to the 'Protein' view.
prefix: hinv.protein
pattern: ^HIP\d{9}(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100215
   accessurl: http://h-invitational.jp/hinv/protein/protein_view.cgi?hip_id=${id}
   test_id: HIP000030660
   description: H-Invitational Protein View at BIRC
   homepage: http://h-invitational.jp/hinv/ahg-db/index.jsp
   institution: BIRC, Tokyo
   location: Japan
   official: false
---
