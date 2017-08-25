---
identifier: MIR:00000315
name: TIGRFAMS
description: TIGRFAMs is a resource consisting of curated multiple sequence alignments, Hidden Markov Models (HMMs) for protein sequence classification, and associated information designed to support automated annotation of (mostly prokaryotic) proteins.
prefix: tigrfam
pattern: ^TIGR\d+$
prefixed: 0
resources:
 - identifier: MIR:00100398
   accessurl: http://www.jcvi.org/cgi-bin/tigrfams/HmmReportPage.cgi?acc=${id}
   test_id: TIGR00010
   description: TIGRFAM at JCVI
   homepage: http://www.jcvi.org/cgi-bin/tigrfams/Listing.cgi
   institution: The Institute for Genomic Research, Rockville, Maryland
   location: USA
   official: false
---
