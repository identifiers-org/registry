---
identifier: MIR:00000080
name: HGNC
description: The HGNC (HUGO Gene Nomenclature Committee) provides an approved gene name and symbol (short-form abbreviation) for each known human gene.  All approved symbols are stored in the HGNC database, and each symbol is unique. HGNC identifiers refer to records in the HGNC symbol database.
prefix: hgnc
pattern: ^((HGNC|hgnc):)?\d{1,5}$
prefixed: 0
local_id: hgnc:2674
synonyms:
 - HUGO Gene Nomenclature Committee
resources:
 - identifier: MIR:00100111
   accessurl: http://www.genenames.org/cgi-bin/gene_symbol_report?hgnc_id=${lid}
   keyword: CCDS43842
   description: HUGO Genome Nomenclature Committee
   homepage: http://www.genenames.org
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100698
   accessurl: http://hgnc.bio2rdf.org/describe/?url=http://bio2rdf.org/${lid}
   keyword: Gene Symbol for DAPK1
   description: Bio2RDF
   homepage: http://hgnc.bio2rdf.org/fct
   institution: Bio2RDF.org
   location: 
   official: false
---
