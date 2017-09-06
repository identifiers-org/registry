---
identifier: MIR:00000137
name: ClinicalTrials.gov
description: ClinicalTrials.gov provides free access to information on clinical studies for a wide range of diseases and conditions. Studies listed in the database are conducted in 175 countries
prefix: clinicaltrials
pattern: ^NCT\d{8}$
prefixed: 0
local_id: NCT00222573
synonyms:
 - NCT
resources:
 - identifier: MIR:00100179
   accessurl: http://clinicaltrials.gov/ct2/show/${lid}
   keyword: Aspirin versus Aspirin
   description: ClinicalTrials.gov at NIH
   homepage: http://clinicaltrials.gov/
   institution: National Library of Medicine and ClinicalTrials.gov, Maryland
   location: USA
   official: true
 - identifier: MIR:00100692
   accessurl: http://clinicaltrials.bio2rdf.org/describe/?url=http://bio2rdf.org/clinicaltrials:${lid}
   keyword: Efficacy and Safety of Adding Clopidogrel to Aspirin
   description: Bio2RDF
   homepage: http://clinicaltrials.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---
