+++
title = "Fast and Memory-Efficient Dynamic Programming Approach for Large-Scale EHH-Based Selection Scans"
date = "2025-11-17T00:00:00"
draft = false

authors = ["A Rahman", "TQ Smith", "ZA Szpiech"]
publication = "_Molecular Biology and Evolution_"
publication_short = "_Mol Biol Evol_"
publication_types = ["2"]

abstract = "Haplotype-based statistics are widely used for finding genomic regions under positive selection. At the heart of many such statistics is the computation of extended haplotype homozygosity (EHH), which captures the decay of homozygosity away from a focal site. This computation, repeated for potentially millions of sites, is computationally demanding, as it involves tracking counts of unique haplotypes iteratively over long genomic distances and across many individuals. Because of these computational challenges, existing tools do not scale well when applied to large-scale population datasets, such as the 1000 Genomes Project, or the UK Biobank with 500,000 individuals. Optimizing computation becomes crucial when data sets grow large, especially when handling large sample sizes or generating training data for machine learning algorithms. Here, we propose a dynamic programming algorithm that substantially improves runtime and memory usage over existing tools on both real and simulated data. On real phased data, we achieve 5-50x speedup with minimal memory footprint. Our simulations show an even more pronounced performance gap with large populations (up to 15x speedup and 46x memory reduction). EHH-based statistics designed for unphased genotypes run an order of magnitude faster, and multi-parameter support results in 20x runtime improvement. Source code and binaries are available at https://github.com/szpiech/selscan as selscan v2.1."

abstract_short = ""

image_preview = ""
selected = false
projects = []
tags = []

url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "DOI", url = "https://doi.org/10.1093/molbev/msaf275"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
