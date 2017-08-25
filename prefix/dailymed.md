---
identifier: MIR:00000434
name: DailyMed
description: DailyMed provides information about marketed drugs. This information includes FDA labels (package inserts). The Web site provides a standard, comprehensive, up-to-date, look-up and download resource of medication content and labeling as found in medication package inserts. Drug labeling is the most recent submitted to the Food and Drug Administration (FDA) and currently in use; it may include, for example, strengthened warnings undergoing FDA review or minor editorial changes. These labels have been reformatted to make them easier to read.
prefix: dailymed
pattern: ^[A-Za-z0-9-]+
prefixed: 0
resources:
 - identifier: MIR:00100558
   accessurl: http://dailymed.nlm.nih.gov/dailymed/lookup.cfm?setid=${id}
   test_id: 8889bcd7-d0e9-434b-b09d-30132bd033b0
   description: DailyMed at NLM
   homepage: http://dailymed.nlm.nih.gov/dailymed/
   institution: U.S. National Library of Medicine, Bethesda, Maryland
   location: USA
   official: false
---
