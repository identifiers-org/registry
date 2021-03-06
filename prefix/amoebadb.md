---
identifier: MIR:00000148
name: AmoebaDB
description: AmoebaDB is one of the databases that can be accessed through the EuPathDB (http://EuPathDB.org; formerly ApiDB) portal, covering eukaryotic pathogens of the genera Cryptosporidium, Giardia, Leishmania, Neospora, Plasmodium, Toxoplasma, Trichomonas and Trypanosoma. While each of these groups is supported by a taxon-specific database built upon the same infrastructure, the EuPathDB portal offers an entry point to all these resources, and the opportunity to leverage orthology for searches across genera.
prefix: amoebadb
pattern: ^EDI_\d+$
prefixed: 0
local_id: EDI_244000
resources:
 - identifier: MIR:00100193
   accessurl: http://amoebadb.org/amoeba/showRecord.do?name=GeneRecordClasses.GeneRecordClass&source_id=${lid}
   keyword: phosphatidylcholine-sterol acyltransferase precursor, putative
   description: AmoebaDB at EuPathDB
   homepage: http://amoebadb.org/amoeba/
   institution: Center for Tropical & Emerging Global Diseases, University of Georgia
   location: USA
   official: false
---
