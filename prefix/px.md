---
identifier: MIR:00000513
name: ProteomeXchange
description: The ProteomeXchange provides a single point of submission of Mass Spectrometry (MS) proteomics data for the main existing proteomics repositories, and encourages the data exchange between them for optimal data dissemination.
prefix: px
pattern: ^(R)?PXD\d+{6}$
prefixed: 0
resources:
 - identifier: MIR:00100660
   accessurl: http://proteomecentral.proteomexchange.org/cgi/GetDataset?ID=${id}
   test_id: PXD000500
   description: ProteomeXchange at Seattle
   homepage: http://www.proteomexchange.org/
   institution: Institute for Systems Biology, Seattle, WA, USA
   location: USA
   official: false
---
