---
identifier: MIR:00000548
name: ExAC Gene
description: The Exome Aggregation Consortium (ExAC) is a coalition of investigators seeking to aggregate and harmonize exome sequencing data from a variety of large-scale sequencing projects, and to make summary data available for the wider scientific community. The data pertains to unrelated individuals sequenced as part of various disease-specific and population genetic studies and serves as a reference set of allele frequencies for severe disease studies. This collection references gene information.
prefix: exac.gene
pattern: ^ENSG\d{11}$
prefixed: 0
resources:
 - identifier: MIR:00100725
   accessurl: http://exac.broadinstitute.org/gene/${id}
   test_id: ENSG00000169174
   description: ExAC Gene at Exome Aggregation Consortium
   homepage: http://exac.broadinstitute.org/
   institution: Exome Aggregation Consortium (ExAC), Cambridge, Massachusetts
   location: USA
   official: false
---
