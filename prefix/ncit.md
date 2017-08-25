---
identifier: MIR:00000139
name: NCIt
description: NCI Thesaurus (NCIt) provides reference terminology covering vocabulary for clinical care, translational and basic research, and public information and administrative activities, providing a stable and unique identification code.
prefix: ncit
pattern: ^C\d+$
prefixed: 0
resources:
 - identifier: MIR:00100181
   accessurl: http://ncit.nci.nih.gov/ncitbrowser/ConceptReport.jsp?dictionary=NCI%20Thesaurus&code=${id}
   test_id: C80519
   description: NCIt at National Cancer Institute
   homepage: http://ncit.nci.nih.gov/
   institution: National Cancer Institute, Center for Bioinformatics, Maryland
   location: USA
   official: false
---
