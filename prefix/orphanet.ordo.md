---
identifier: MIR:00000532
name: Orphanet Rare Disease Ontology
description: The Orphanet Rare Disease ontology (ORDO) is a structured vocabulary for rare diseases, capturing relationships between diseases, genes and other relevant features which will form a useful resource for the computational analysis of rare diseases.
It integrates a nosology (classification of rare diseases), relationships (gene-disease relations, epiemological data) and connections with other terminologies (MeSH, UMLS, MedDRA), databases (OMIM, UniProtKB, HGNC, ensembl, Reactome, IUPHAR, Geantlas) and classifications (ICD10).
prefix: orphanet.ordo
pattern: ^Orphanet(_|:)C?\d+$
prefixed: 0
resources:
 - identifier: MIR:00100705
   accessurl: http://www.ebi.ac.uk/ols/ontologies/ordo/terms?short_form=${id}
   test_id: Orphanet_C023
   description: ORDO via OLS
   homepage: http://www.ebi.ac.uk/ols/ontologies/ordo
   institution: European Bioinformatics Institute, Hinxton, Cambridge
   location: UK
   official: true
   provider_code: ols
---
