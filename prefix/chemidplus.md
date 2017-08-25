---
identifier: MIR:00000096
name: ChemIDplus
description: ChemIDplus is a web-based search system that provides access to structure and nomenclature authority files used for the identification of chemical substances cited in National Library of Medicine (NLM) databases. It also provides structure searching and direct links to many biomedical resources at NLM and on the Internet for chemicals of interest.
prefix: chemidplus
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100127
   accessurl: http://chem.sis.nlm.nih.gov/chemidplus/direct.jsp?regno=${id}
   test_id: 000057272
   description: ChemIDplus at National Library of Medicine
   homepage: http://chem.sis.nlm.nih.gov/chemidplus/chemidheavy.jsp
   institution: National Library of Medicine, Maryland
   location: USA
   official: false
---
