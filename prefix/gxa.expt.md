---
identifier: MIR:00000379
name: GXA Expt
description: The Gene Expression Atlas (GXA) is a semantically enriched database of meta-analysis based summary statistics over a curated subset of ArrayExpress Archive, servicing queries for condition-specific gene expression patterns as well as broader exploratory searches for biologically interesting genes/samples. This collection references experiments.
prefix: gxa.expt
pattern: ^[AEP]-\w{4}-\d+$
prefixed: 0
local_id: E-MTAB-2037
synonyms:
 - Gene Expression Atlas Experiment
resources:
 - identifier: MIR:00100483
   accessurl: http://www.ebi.ac.uk/gxa/experiments/${lid}
   keyword: Oryza sativa
   description: GXA Expt at EBI
   homepage: http://www.ebi.ac.uk/gxa/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
---
