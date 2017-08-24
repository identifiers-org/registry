---
identifier: MIR:00000080
name: HGNC
description: The HGNC (HUGO Gene Nomenclature Committee) provides an approved gene name and symbol (short-form abbreviation) for each known human gene.  All approved symbols are stored in the HGNC database, and each symbol is unique. HGNC identifiers refer to records in the HGNC symbol database.
prefix: hgnc
pattern: ^((HGNC|hgnc):)?\d{1,5}$
prefixed: 0
resources:
 - identifier: MIR:00100111
   accessurl: http://www.genenames.org/cgi-bin/gene_symbol_report?hgnc_id=
   description: HUGO Genome Nomenclature Committee
   location: UK
   official: true
   provider_code: ebi
 - identifier: MIR:00100698
   accessurl: http://hgnc.bio2rdf.org/describe/?url=http://bio2rdf.org/
   description: Bio2RDF
   location: 
   official: false
---
