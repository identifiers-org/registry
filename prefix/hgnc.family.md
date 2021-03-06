---
identifier: MIR:00000520
name: HGNC Family
description: The HGNC (HUGO Gene Nomenclature Committee) provides an approved gene name and symbol (short-form abbreviation) for each known human gene. All approved symbols are stored in the HGNC database, and each symbol is unique. In addition, HGNC also provides symbols for both structural and functional gene families. This collection refers to records using the HGNC family symbol.
prefix: hgnc.family
pattern: ^[A-Z0-9-]+(#[A-Z0-9-]+)?$
prefixed: 0
local_id: PADI
resources:
 - identifier: MIR:00100671
   accessurl: http://www.genenames.org/genefamilies/${lid}
   keyword: Peptidyl arginine deiminases
   description: HGNC Family at HUGO Genome Nomenclature Committee
   homepage: http://www.genenames.org/
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: false
---
