---
identifier: MIR:00000540
name: GWAS Central Study
description: GWAS Central (previously the Human Genome Variation database of Genotype-to-Phenotype information) is a database of summary level findings from genetic association studies, both large and small. It gathers datasets from public domain projects, and accepts direct data submission. It is based upon Marker information encompassing SNP and variant information from public databases, to which allele and genotype frequency data, and genetic association findings are additionally added. A Study (most generic level) contains one or more Experiments, one or more Sample Panels of test subjects, and one or more Phenotypes. This collection references a GWAS Central Study.
prefix: gwascentral.study
pattern: ^HGVST\d+$
prefixed: 0
local_id: HGVST1828
resources:
 - identifier: MIR:00100717
   accessurl: http://www.gwascentral.org/study/${lid}
   keyword: GWAS of Colorectal cancer
   description: GWAS Central Study at University of Leicester
   homepage: http://www.gwascentral.org/studies
   institution: Department of Genetics, University of Leicester, Leicester
   location: UK
   official: false
---
