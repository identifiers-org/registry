---
identifier: MIR:00000592
name: ARK
description: An Archival Resource Key (ARK) is a Uniform Resource Locator (URL) that is a multi-purpose persistent identifier for information objects of any type.
prefix: ark
pattern: ^(ark\:)/*[0-9A-Za-z]+(?:/[\w/.=*+@\$-]*)?(?:\?.*)?$
prefixed: 1
resources:
 - identifier: MIR:00100792
   accessurl: http://n2t.net/${id}
   test_id: ark:/12345/fk1234
   description: ARK via the Name-to-Thing resolver.
   homepage: http://n2t.net/
   institution: California Digital Library, University of California Office of the President
   location: USA
   official: false
---
