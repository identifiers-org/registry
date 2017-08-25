---
identifier: MIR:00000245
name: PharmGKB Gene
description: The PharmGKB database is a central repository for genetic, genomic, molecular and cellular phenotype data and clinical information about people who have participated in pharmacogenomics research studies. The data includes, but is not limited to, clinical and basic pharmacokinetic and pharmacogenomic research in the cardiovascular, pulmonary, cancer, pathways, metabolic and transporter domains.
prefix: pharmgkb.gene
pattern: ^PA\w+$
prefixed: 0
resources:
 - identifier: MIR:00100316
   accessurl: http://www.pharmgkb.org/gene/${id}
   test_id: PA131
   description: PharmGKB Gene at Stanford
   homepage: http://www.pharmgkb.org/
   institution: Department of Genetics, School of Medicine, Stanford University, Stanford, California
   location: USA
   official: false
---
