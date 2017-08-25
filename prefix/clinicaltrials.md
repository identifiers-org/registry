---
identifier: MIR:00000137
name: ClinicalTrials.gov
description: ClinicalTrials.gov provides free access to information on clinical studies for a wide range of diseases and conditions. Studies listed in the database are conducted in 175 countries
prefix: clinicaltrials
pattern: ^NCT\d{8}$
prefixed: 0
resources:
 - identifier: MIR:00100179
   accessurl: http://clinicaltrials.gov/ct2/show/${id}
   test_id: NCT00222573
   description: ClinicalTrials.gov at NIH
   homepage: http://clinicaltrials.gov/
   institution: National Library of Medicine and ClinicalTrials.gov, Maryland
   location: USA
   official: true
 - identifier: MIR:00100692
   accessurl: http://clinicaltrials.bio2rdf.org/describe/?url=http://bio2rdf.org/clinicaltrials:${id}
   test_id: NCT00222573
   description: Bio2RDF
   homepage: http://clinicaltrials.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---
