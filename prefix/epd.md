---
identifier: MIR:00000408
name: EPD
description: The Eukaryotic Promoter Database (EPD) is an annotated non-redundant collection of eukaryotic POL II promoters, for which the transcription start site has been determined experimentally. Access to promoter sequences is provided by pointers to positions in nucleotide sequence entries. The annotation part of an entry includes description of the initiation site mapping data, cross-references to other databases, and bibliographic references. EPD is structured in a way that facilitates dynamic extraction of biologically meaningful promoter subsets for comparative sequence analysis.
prefix: epd
pattern: ^[A-Z-_0-9]+$
prefixed: 0
local_id: TA_H3
synonyms:
 - Eukaryotic Promoter Database
resources:
 - identifier: MIR:00100528
   accessurl: http://epd.vital-it.ch/cgi-bin/query_result.pl?out_format=NICE&Entry_0=${lid}
   keyword: Chromosomal protein
   description: EPD at Swiss Institute of Bioinformatics
   homepage: http://epd.vital-it.ch/
   institution: Swiss Institute of Bioinformatics (SIB), Geneva
   location: Switzerland
   official: false
---
