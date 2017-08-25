---
identifier: MIR:00000602
name: dbGaP
description: The database of Genotypes and Phenotypes (dbGaP) archives and distributes the results of studies that have investigated the interaction of genotype and phenotype.
prefix: dbgap
pattern: ^phs[0-9]{6}.v\d+.p\d+$
prefixed: 0
resources:
 - identifier: MIR:00100803
   accessurl: https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=${id}
   test_id: phs000768.v2.p1
   description: dbGaP through NCBI
   homepage: https://www.ncbi.nlm.nih.gov/projects/gap
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
