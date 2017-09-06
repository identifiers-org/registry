---
identifier: MIR:00000077
name: MACiE
description: MACiE (Mechanism, Annotation and Classification in Enzymes) is a database of enzyme reaction mechanisms. Each entry in MACiE consists of an overall reaction describing the chemical compounds involved, as well as the species name in which the reaction occurs. The individual reaction stages for each overall reaction are listed with mechanisms, alternative mechanisms, and amino acids involved.
prefix: macie
pattern: ^M\d{4}$
prefixed: 0
local_id: M0001
resources:
 - identifier: MIR:00100108
   accessurl: http://www.ebi.ac.uk/thornton-srv/databases/cgi-bin/MACiE/entry/getPage.pl?id=${lid}
   keyword: A member of the Isomerases, Racemases and epimerases, 
   description: MACiE database of mechanisms, annotation and classification in enzymes
   homepage: http://www.ebi.ac.uk/thornton-srv/databases/MACiE/index.html
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
---
