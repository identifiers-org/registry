---
identifier: MIR:00000122
name: IMEx
description: The International Molecular Exchange (IMEx) is a consortium of molecular interaction databases which collaborate to share manual curation efforts and provide accessibility to multiple information sources.
prefix: imex
pattern: ^IM-\d+(-?)(\d+?)$
prefixed: 0
local_id: IM-19210-3
resources:
 - identifier: MIR:00100155
   accessurl: http://www.ebi.ac.uk/intact/imex/main.xhtml?query=${lid}
   keyword: <span id="totalResultsTable"
   description: IMEx Consortium running at EBI
   homepage: http://www.imexconsortium.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100663
   accessurl: https://imexcentral.org/icentral/imex/rec/${lid}
   keyword: MAP1LC3B
   description: IMEx Consortium though Intact
   homepage: http://www.ebi.ac.uk/intact/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
---
