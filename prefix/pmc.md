---
identifier: MIR:00000147
name: PMC International
description: PMC International (PMCI) is a free full-text archive of biomedical and life sciences journal literature. PMCI is a collaborative effort between the U.S. National Institutes of Health and the National Library of Medicine, the publishers whose journal content makes up the PMC archive, and organizations in other countries that share NIH's and NLM's interest in archiving life sciences literature.
prefix: pmc
pattern: PMC\d+
prefixed: 0
local_id: PMC3084216
synonyms:
 - PubMed Central
 - PMCI
resources:
 - identifier: MIR:00100191
   accessurl: http://www.ncbi.nlm.nih.gov/pmc/articles/${lid}/?tool=pubmed
   keyword: (MIASE)
   description: PubMed Central
   homepage: http://www.ncbi.nlm.nih.gov/pmc/
   institution: NCBI
   location: USA
   official: false
   provider_code: ncbi
 - identifier: MIR:00100498
   accessurl: http://europepmc.org/articles/${lid}
   keyword: (MIASE)
   description: Europe PMC
   homepage: http://europepmc.org/
   institution: Europe PubMed Central partners
   location: UK
   official: true
   provider_code: epmc
 - identifier: MIR:00100747
   accessurl: http://pubmedcentralcanada.ca/pmcc/articles/${lid}
   keyword: (MIASE)
   description: PubMedCentral Canada
   homepage: http://pubmedcentralcanada.ca/pmcc
   institution: Canadian Institute of Health, Ottawa
   location: Canada
   official: false
   provider_code: cpmc
---
