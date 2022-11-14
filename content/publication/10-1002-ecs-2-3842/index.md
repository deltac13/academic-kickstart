---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'From DNA sequences to microbial ecology: Wrangling NEON soil microbe data
  with the neonMicrobe R package'
subtitle: ''
summary: ''
authors:
- Clara Qin
- Ryan Bartelme
- Y. Anny Chung
- Dawson Fairbanks
- Yang Lin
- Daniel Liptzin
- Chance Muscarella
- Kusum Naithani
- Kabir Peay
- Peter Pellitier
- Ayanna St. Rose
- Lee Stanish
- Zoey Werbin
- Kai Zhu
tags:
- ''
categories: []
date: '2021-01-01'
lastmod: 2022-11-13T21:43:27-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-11-14T02:43:27.252803Z'
publication_types:
- '2'
abstract: Soil microbial communities play critical roles in various ecosystem processes,
  but studies at a large spatial and temporal scale have been challenging due to the
  difficulty in finding the relevant samples in available data sets as well as the
  lack of standardization in sample collection and processing. The National Ecological
  Observatory Network (NEON) has been collecting soil microbial community data multiple
  times per year for 47 terrestrial sites in 20 eco‐climatic domains, producing one
  of the most extensive standardized sampling efforts for soil microbial biodiversity
  to date. Here, we introduce the neonMicrobe R package—a suite of downloading, preprocessing,
  data set assembly, and sensitivity analysis tools for NEON’s newly published 16S
  and ITS amplicon sequencing data products which characterize soil bacterial and
  fungal communities, respectively. neonMicrobe is designed to make these data more
  accessible to ecologists without assuming prior experience with bioinformatic pipelines.
  We describe quality control steps used to remove quality‐flagged samples, report
  on sensitivity analyses used to determine appropriate quality filtering parameters
  for the DADA2 workflow, and demonstrate the immediate usability of the output data
  by conducting standard analyses of soil microbial diversity. The sequence abundance
  tables produced by neonMicrobe can be linked to NEON’s other data products (e.g.,
  soil physical and chemical properties, plant community composition) and soil subsamples
  archived in the NEON Biorepository. We provide recommendations for incorporating
  neonMicrobe into reproducible scientific workflows, discuss technical considerations
  for large‐scale amplicon sequence analysis, and outline future directions for NEON‐enabled
  microbial ecology. In particular, we believe that NEON marker gene sequence data
  will allow researchers to answer outstanding questions about the spatial and temporal
  dynamics of soil microbial communities while explicitly accounting for scale dependence.
  We expect that the data produced by NEON and the neonMicrobe R package will act
  as a valuable ecological baseline to inform and contextualize future experimental
  and modeling endeavors.
publication: '*Ecosphere*'
doi: 10.1002/ecs2.3842
---
