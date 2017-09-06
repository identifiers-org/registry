---
identifier: MIR:00000394
name: Affymetrix Probeset
description: An Affymetrix ProbeSet is a collection of up to 11 short (~22 nucleotide) microarray probes designed to measure a single gene or a family of genes as a unit. Multiple probe sets may be available for each gene under consideration.
prefix: affy.probeset
pattern: \d{4,}((_[asx])?_at)?
prefixed: 0
local_id: 243002_at
resources:
 - identifier: MIR:00100514
   accessurl: https://www.affymetrix.com/LinkServlet?probeset=${lid}
   keyword: Probe Sets returned:<b>4</b>
   description: Affymetrix ProbeSet in Santa Clara
   homepage: http://www.affymetrix.com/
   institution: Affymetrix, Santa Clara, California
   location: USA
   official: true
 - identifier: MIR:00100672
   accessurl: http://cu.affymetrix.bio2rdf.org/describe/?url=http://bio2rdf.org/affymetrix:${lid}
   keyword: Human Genome U133B
   description: Bio2RDF
   homepage: http://cu.affymetrix.bio2rdf.org/fct/
   institution: Bio2RDF.org
   location: 
   official: false
---
