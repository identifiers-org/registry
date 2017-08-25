---
identifier: MIR:00000126
name: NeuroLex
description: The NeuroLex project is a dynamic lexicon of terms used in neuroscience.  It is supported by the Neuroscience Information Framework project and incorporates information from the NIF standardised ontology (NIFSTD), and its predecessor, the Biomedical Informatics Research Network Lexicon (BIRNLex).
prefix: neurolex
pattern: ^([Bb]irnlex_|Sao|nlx_|GO_|CogPO|HDO|nifext_)\d+$
prefixed: 0
resources:
 - identifier: MIR:00100160
   accessurl: http://www.neurolex.org/wiki/${id}
   test_id: Birnlex_721
   description: NeuroLex Neuroscience Lexicon
   homepage: http://www.neurolex.org/wiki/Main_Page
   institution: Department of Neuroscience, University of California, San Diego
   location: USA
   official: true
 - identifier: MIR:00100183
   accessurl: http://purl.bioontology.org/ontology/BIRNLEX/${id}
   test_id: birnlex_1672
   description: NeuroLex through NCBO's BioPortal
   homepage: http://bioportal.bioontology.org/ontologies/BIRNLEX
   institution: National Center for Biomedical Ontology, Stanford
   location: USA
   official: false
   provider_code: bptl
---
