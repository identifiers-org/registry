---
identifier: MIR:00000409
name: RFAM
description: The Rfam database is a collection of RNA families, each represented by multiple sequence alignments, consensus secondary structures and covariance models (CMs). The families in Rfam break down into three broad functional classes: non-coding RNA genes, structured cis-regulatory elements and self-splicing RNAs. Typically these functional RNAs often have a conserved secondary structure which may be better preserved than the RNA sequence. The CMs used to describe each family are a slightly more complicated relative of the profile hidden Markov models (HMMs) used by Pfam. CMs can simultaneously model RNA sequence and the structure in an elegant and accurate fashion.
prefix: rfam
pattern: ^RF\d{5}$
prefixed: 0
resources:
 - identifier: MIR:00100686
   accessurl: http://rfam.xfam.org/family/${id}
   test_id: RF00230
   description: Rfam at EMBL-EBI
   homepage: http://rfam.xfam.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
---
