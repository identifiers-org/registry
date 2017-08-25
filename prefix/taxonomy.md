---
identifier: MIR:00000006
name: Taxonomy
description: The taxonomy contains the relationships between all living forms for which nucleic acid or protein sequence have been determined.
prefix: taxonomy
pattern: ^\d+$
prefixed: 0
resources:
 - identifier: MIR:00100007
   accessurl: http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&id=${id}
   test_id: 9606
   description: NCBI Taxonomy
   homepage: http://www.ncbi.nlm.nih.gov/Taxonomy/
   institution: National Center for Biotechnology Information (NCBI)
   location: USA
   official: true
   provider_code: ncbi
 - identifier: MIR:00100019
   accessurl: http://purl.uniprot.org/taxonomy/${id}
   test_id: 9606
   description: Taxonomy through UniProt PURL
   homepage: http://www.uniprot.org/taxonomy/
   institution: UniProt Consortium
   location: USA, UK and Switzerland
   official: false
 - identifier: MIR:00100299
   accessurl: http://www.ebi.ac.uk/ena/data/view/Taxon:${id}
   test_id: 9606
   description: European Nucleotide Archive (ENA)
   homepage: http://www.ebi.ac.uk/ena/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
 - identifier: MIR:00100507
   accessurl: http://purl.bioontology.org/ontology/NCBITAXON/${id}
   test_id: 9606
   description: BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/NCBITAXON
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
 - identifier: MIR:00100695
   accessurl: http://taxonomy.bio2rdf.org/describe/?url=http://bio2rdf.org/taxonomy:${id}
   test_id: 9606
   description: Bio2RDF
   homepage: http://taxonomy.bio2rdf.org/fct/
   institution: Bio2RDF.org
   location: 
   official: false
 - identifier: MIR:00100770
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ncbitaxon/terms?short_form=NCBITaxon_${id}
   test_id: 9606
   description: NCBI Taxonomy through OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/ncbitaxon/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ols
---
