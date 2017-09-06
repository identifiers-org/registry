---
identifier: MIR:00000362
name: HGNC Symbol
description: The HGNC (HUGO Gene Nomenclature Committee) provides an approved gene name and symbol (short-form abbreviation) for each known human gene. All approved symbols are stored in the HGNC database, and each symbol is unique. This collection refers to records using the HGNC symbol.
prefix: hgnc.symbol
pattern: ^[A-Za-z-0-9_]+(\@)?$
prefixed: 0
local_id: DAPK1
synonyms:
 - HUGO Gene Nomenclature Committee Symbol
resources:
 - identifier: MIR:00100460
   accessurl: http://www.genenames.org/cgi-bin/gene_symbol_report?match=${lid}
   keyword: CCDS43842
   description: HGNC Symbol at HUGO Genome Nomenclature Committee
   homepage: http://www.genenames.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
   provider_code: ebi
---
