---
identifier: MIR:00000172
name: IRD Segment Sequence
description: Influenza Research Database (IRD) contains information related to influenza virus, including genomic sequence, strain, protein, epitope  and bibliographic information. The Segment Details page contains descriptive information and annotation data about a particular genomic segment and its encoded product(s).
prefix: ird.segment
pattern: ^\w+(\_)?\d+(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100218
   accessurl: http://www.fludb.org/brc/fluSegmentDetails.do?ncbiGenomicAccession=${id}
   test_id: CY077097
   description: IRD at BioHealthBase
   homepage: http://www.fludb.org/
   institution: Southwestern Medical Center, University of Texas, Dallas
   location: USA
   official: false
---
