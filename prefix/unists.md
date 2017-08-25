---
identifier: MIR:00000162
name: UniSTS
description: UniSTS is a comprehensive database of sequence tagged sites (STSs) derived from STS-based maps and other experiments. STSs are defined by PCR primer pairs and are associated with additional information such as genomic position, genes, and sequences.
prefix: unists
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100207
   accessurl: http://www.ncbi.nlm.nih.gov/genome/sts/sts.cgi?uid=${id}
   test_id: 456789
   description: UniSTS at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/sites/entrez?db=unists
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: false
   provider_code: ncbi
---
