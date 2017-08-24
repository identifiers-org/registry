---
identifier: MIR:00000006
name: Taxonomy
description: The taxonomy contains the relationships between all living forms for which nucleic acid or protein sequence have been determined.
prefix: taxonomy
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100007
   accessurl: http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&id=
   description: NCBI Taxonomy
   location: USA
   official: true
   provider_code: ncbi
 - identifier: MIR:00100019
   accessurl: http://purl.uniprot.org/taxonomy/
   description: Taxonomy through UniProt PURL
   location: USA, UK and Switzerland
   official: false
 - identifier: MIR:00100299
   accessurl: http://www.ebi.ac.uk/ena/data/view/Taxon:
   description: European Nucleotide Archive (ENA)
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100507
   accessurl: http://purl.bioontology.org/ontology/NCBITAXON/
   description: BioPortal
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100695
   accessurl: http://taxonomy.bio2rdf.org/describe/?url=http://bio2rdf.org/taxonomy:
   description: Bio2RDF
   location: 
   official: false
 - identifier: MIR:00100770
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ncbitaxon/terms?short_form=NCBITaxon_
   description: NCBI Taxonomy through OLS
   location: UK
   official: false
   provider_code: ols
---
