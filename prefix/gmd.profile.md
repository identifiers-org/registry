---
identifier: MIR:00000423
name: Golm Metabolome Database Profile
description: Golm Metabolome Database (GMD) provides public access to custom mass spectral libraries, metabolite profiling experiments as well as additional information and tools. GMD's metabolite profiles provide relative metabolite concentrations normalised according to fresh weight (or comparable quantitative data, such as volume, cell count, etc.) and internal standards (e.g. ribotol) of biological reference conditions and tissues.
prefix: gmd.profile
pattern: ^([0-9a-fA-F]){8}(-([0-9a-fA-F]){4}){3}-([0-9a-fA-F]){12}$
prefixed: 0
resources:
 - identifier: MIR:00100546
   accessurl: http://gmd.mpimp-golm.mpg.de/profile/default.aspx?XemlId=${id}
   test_id: 10b38aaf-b977-4950-85b8-f4775f66658d
   description: Golm Metabolome Database (Profile) at Max Planck Institute of Molecular Plant Physiology
   homepage: http://gmd.mpimp-golm.mpg.de/
   institution: Max Planck Institute of Molecular Plant Physiology, Potsdam
   location: Germany
   official: false
---
