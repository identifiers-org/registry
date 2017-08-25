---
identifier: MIR:00000383
name: InChI
description: The IUPAC International Chemical Identifier (InChI) is a non-proprietary identifier for chemical substances that can be used in printed and electronic data sources. It is derived solely from a structural representation of that substance, such that a single compound always yields the same identifier.
prefix: inchi
pattern: ^InChI\=1S?\/[A-Za-z0-9]+(\+[0-9]+)?(\/[cnpqbtmsih][A-Za-z0-9\-\+\(\)\,\/]+)*$
prefixed: 0
resources:
 - identifier: MIR:00100491
   accessurl: http://rdf.openmolecules.net/?${id}
   test_id: InChI=1S/C2H6O/c1-2-3/h3H,2H2,1H3
   description: InChI through RDF Open Molecules
   homepage: http://rdf.openmolecules.net/
   institution: BiGCaT, Department of Bioinformatics, Maastricht
   location: Netherlands
   official: false
 - identifier: MIR:00100492
   accessurl: http://www.chemspider.com/${id}
   test_id: InChI=1S/C2H6O/c1-2-3/h3H,2H2,1H3
   description: InChI through Chemspider
   homepage: http://www.chemspider.com/
   institution: Royal Society of Chemistry, Cambridge
   location: UK
   official: false
 - identifier: MIR:00100493
   accessurl: http://webbook.nist.gov/cgi/cbook.cgi?${id}
   test_id: InChI=1S/C2H6O/c1-2-3/h3H,2H2,1H3
   description: InChI through NIST
   homepage: http://webbook.nist.gov/chemistry
   institution: National Institute of Standards and Technology, Gaithersburg, Maryland
   location: USA
   official: false
 - identifier: MIR:00100494
   accessurl: http://www.ebi.ac.uk/chebi/advancedSearchFT.do?searchString=${id}
   test_id: InChI=1S/C2H6O/c1-2-3/h3H,2H2,1H3
   description: InChI through ChEBI
   homepage: http://www.ebi.ac.uk/chebi/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
