---
identifier: MIR:00000547
name: ExAC Transcript
description: The Exome Aggregation Consortium (ExAC) is a coalition of investigators seeking to aggregate and harmonize exome sequencing data from a variety of large-scale sequencing projects, and to make summary data available for the wider scientific community. The data pertains to unrelated individuals sequenced as part of various disease-specific and population genetic studies and serves as a reference set of allele frequencies for severe disease studies. This collection references transcript information.
prefix: exac.transcript
pattern: ^ENST\d{11}$
prefixed: 0
resources:
 - identifier: MIR:00100724
   accessurl: http://exac.broadinstitute.org/transcript/${id}
   test_id: ENST00000407236
   description: ExAC Transcript at Exome Aggregation Consortium
   homepage: http://exac.broadinstitute.org/
   institution: Exome Aggregation Consortium (ExAC), Cambridge, Massachusetts
   location: USA
   official: false
---
