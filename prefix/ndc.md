---
identifier: MIR:00000431
name: National Drug Code
description: The National Drug Code (NDC) is a unique, three-segment number used by the Food and Drug Administration (FDA) to identify drug products for commercial use. This is required by the Drug Listing Act of 1972. The FDA publishes and updates the listed NDC numbers daily.
prefix: ndc
pattern: ^\d+\-\d+\-\d+
prefixed: 0
resources:
 - identifier: MIR:00100554
   accessurl: http://www.hipaaspace.com/Medical_Billing/Coding/National.Drug.Codes/
   description: National Drug Code at Food and Drug Administration
   location: USA
   official: true
 - identifier: MIR:00100700
   accessurl: http://ndc.bio2rdf.org/describe/?url=http://bio2rdf.org/ndc:
   description: Bio2RDF
   location: 
   official: false
---
