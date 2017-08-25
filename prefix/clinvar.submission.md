---
identifier: MIR:00000595
name: ClinVar Submission
description: ClinVar archives reports of relationships among medically important variants and phenotypes. It records human variation, interpretations of the relationship specific variations to human health, and supporting evidence for each interpretation. Each ClinVar record (RCV identifier) represents an aggregated view of interpretations of the same variation and condition from one or more submitters. Submissions for individual variation/phenotype combinations (SCV identifier) are also collected and made available separately. This collection references submissions, and is based on SCV accession.
prefix: clinvar.submission
pattern: ^SCV\d+(\.\d+)?$
prefixed: 0
resources:
 - identifier: MIR:00100795
   accessurl: http://www.ncbi.nlm.nih.gov/clinvar?term=${id}
   test_id: SCV000151292
   description: ClinVar Submission at NCBI
   homepage: http://www.ncbi.nlm.nih.gov/clinvar/
   institution: National Center for Biotechnology Information (NCBI), NIH, Maryland
   location: USA
   official: false
   provider_code: ncbi
---
