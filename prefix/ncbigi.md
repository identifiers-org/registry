---
identifier: MIR:00000509
name: NCBI GI
description: The NCBI GI (or "gi") identifier is the original form of identifier for sequence records processed by the NCBI. This 'GenInfo' identifier system was used to access GenBank and related databases, and was assigned to both protein and nucleotide sequences.
prefix: ncbigi
pattern: ^(GI|gi)\:\d+$
prefixed: 0
resources:
 - identifier: MIR:00100652
   accessurl: http://www.ncbi.nlm.nih.gov/protein/
   description: NCBI GI at NCBI
   location: USA
   official: false
   provider_code: ncbi
---