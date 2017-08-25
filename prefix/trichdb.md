---
identifier: MIR:00000154
name: TrichDB
description: TrichDB is one of the databases that can be accessed through the EuPathDB (http://EuPathDB.org; formerly ApiDB) portal, covering eukaryotic pathogens of the genera Cryptosporidium, Giardia, Leishmania, Neospora, Plasmodium, Toxoplasma, Trichomonas and Trypanosoma. While each of these groups is supported by a taxon-specific database built upon the same infrastructure, the EuPathDB portal offers an entry point to all these resources, and the opportunity to leverage orthology for searches across genera.
prefix: trichdb
pattern: ^\w+$
prefixed: 0
resources:
 - identifier: MIR:00100199
   accessurl: http://trichdb.org/trichdb/showRecord.do?name=GeneRecordClasses.GeneRecordClass&source_id=${id}
   test_id: TVAG_386080
   description: TrichDB at EuPathDB
   homepage: http://trichdb.org/trichdb/
   institution: Center for Tropical & Emerging Global Diseases, University of Georgia
   location: USA
   official: false
---
