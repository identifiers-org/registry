---
identifier: MIR:00000042
name: MINT
description: The Molecular INTeraction database (MINT) stores, in a structured format, information about molecular interactions by extracting experimental details from work published in peer-reviewed journals.
prefix: mint
pattern: ^MINT\-\d{1,7}$
prefixed: 0
local_id: MINT-7905142
resources:
 - identifier: MIR:00100070
   accessurl: http://mint.bio.uniroma2.it/mint/search/inFrameInteraction.do?interactionAc=${lid}
   keyword: Protein transport protein SEC13
   description: The Molecular INTeraction database (MINT)
   homepage: http://mint.bio.uniroma2.it/mint/
   institution: University of Rome Tor Vergata, Rome
   location: Italy
   official: false
 - identifier: MIR:00100654
   accessurl: http://www.ebi.ac.uk/intact/query/interaction_id:${lid}
   keyword: http://mint.bio.uniroma2.it/mint/search/interaction.do?ac=MINT-7905142
   description: MINT subset through IntAct
   homepage: http://www.ebi.ac.uk/intact/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
