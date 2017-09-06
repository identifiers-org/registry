---
identifier: MIR:00000064
name: ISBN
description: The International Standard Book Number (ISBN) is for identifying printed books.
prefix: isbn
pattern: ^(ISBN)?(-13|-10)?[:]?[ ]?(\d{2,3}[ -]?)?\d{1,5}[ -]?\d{1,7}[ -]?\d{1,6}[ -]?(\d|X)$
prefixed: 0
local_id: 9781584885658
resources:
 - identifier: MIR:00100092
   accessurl: http://isbndb.com/search-all.html?kw=${lid}
   keyword: Handbook of Dynamic System Modeling
   description: ISBNDB - ISBN Database
   homepage: http://isbndb.com/
   institution: ISNBdb project, San Gabriel, California
   location: USA
   official: false
 - identifier: MIR:00100093
   accessurl: http://www.worldcat.org/isbn/${lid}
   keyword: Handbook of dynamic system modeling
   description: ISBN database at WorldCat
   homepage: http://www.worldcat.org/
   institution: OCLC Online Computer Library Center, Inc. Ohio
   location: USA
   official: false
---
