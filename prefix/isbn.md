---
identifier: MIR:00000064
name: ISBN
description: The International Standard Book Number (ISBN) is for identifying printed books.
prefix: isbn
pattern: ^(ISBN)?(-13|-10)?[:]?[ ]?(\d{2,3}[ -]?)?\d{1,5}[ -]?\d{1,7}[ -]?\d{1,6}[ -]?(\d|X)$
prefixed: 0
resources:
 - identifier: MIR:00100092
   accessurl: http://isbndb.com/search-all.html?kw=
   description: ISBNDB - ISBN Database
   location: USA
   official: false
 - identifier: MIR:00100093
   accessurl: http://www.worldcat.org/isbn/
   description: ISBN database at WorldCat
   location: USA
   official: false
---
