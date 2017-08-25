---
identifier: MIR:00000064
name: ISBN
description: The International Standard Book Number (ISBN) is for identifying printed books.
prefix: isbn
pattern: ^(ISBN)?(-13|-10)?[:]?[ ]?(\d{2,3}[ -]?)?\d{1,5}[ -]?\d{1,7}[ -]?\d{1,6}[ -]?(\d|X)$
prefixed: 0
resources:
 - identifier: MIR:00100092
   accessurl: http://isbndb.com/search-all.html?kw=${id}
   test_id: 9781584885658
   description: ISBNDB - ISBN Database
   homepage: http://isbndb.com/
   institution: ISNBdb project, San Gabriel, California
   location: USA
   official: false
 - identifier: MIR:00100093
   accessurl: http://www.worldcat.org/isbn/${id}
   test_id: 9781584885658
   description: ISBN database at WorldCat
   homepage: http://www.worldcat.org/
   institution: OCLC Online Computer Library Center, Inc. Ohio
   location: USA
   official: false
---
