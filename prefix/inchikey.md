---
identifier: MIR:00000387
name: InChIKey
description: The IUPAC International Chemical Identifier (InChI, see MIR:00000383) is an identifier for chemical substances, and is derived solely from a structural representation of that substance. Since these can be quite unwieldly, particularly for web use, the InChIKey was developed. These are of a fixed length (25 character) and were created as a condensed, more web friendly, digital representation of the InChI.
prefix: inchikey
pattern: ^[A-Z]{14}\-[A-Z]{10}(\-[A-Z])?
prefixed: 0
resources:
 - identifier: MIR:00100501
   accessurl: http://www.chemspider.com/inchikey=
   description: InChIKey through ChemSpider
   location: UK
   official: false
 - identifier: MIR:00100505
   accessurl: http://cactus.nci.nih.gov/chemical/structure/
   description: InChiKey resolver at NCI
   location: USA
   official: false
---
