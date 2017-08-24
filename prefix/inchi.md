---
identifier: MIR:00000383
name: InChI
description: The IUPAC International Chemical Identifier (InChI) is a non-proprietary identifier for chemical substances that can be used in printed and electronic data sources. It is derived solely from a structural representation of that substance, such that a single compound always yields the same identifier.
prefix: inchi
pattern: ^InChI\=1S?\/[A-Za-z0-9]+(\+[0-9]+)?(\/[cnpqbtmsih][A-Za-z0-9\-\+\(\)\,\/]+)*$
prefixed: 0
resources:
 - identifier: MIR:00100491
   accessurl: http://rdf.openmolecules.net/?
   description: InChI through RDF Open Molecules
   location: Netherlands
   official: false
 - identifier: MIR:00100492
   accessurl: http://www.chemspider.com/
   description: InChI through Chemspider
   location: UK
   official: false
 - identifier: MIR:00100493
   accessurl: http://webbook.nist.gov/cgi/cbook.cgi?
   description: InChI through NIST
   location: USA
   official: false
 - identifier: MIR:00100494
   accessurl: http://www.ebi.ac.uk/chebi/advancedSearchFT.do?searchString=
   description: InChI through ChEBI
   location: UK
   official: false
   provider_code: ebi
---
