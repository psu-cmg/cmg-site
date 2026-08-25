+++
title = "Estimation of substitution and indel rates via k-mer statistics"
date = "2026-07-09T00:00:00"
draft = false

authors = ["MR Hera", "P Medvedev", "D Koslicki", "A Blanca"]
publication = "_Algorithms for Molecular Biology_"
publication_short = "_Algorithms Mol Biol_"
publication_types = ["2"]

abstract = "Methods utilizing k-mers are widely used in bioinformatics, yet our understanding of their statistical properties under realistic mutation models remains incomplete. Previously, substitution-only mutation models have been considered to derive precise expectations and variances for mutated k-mers and intervals of mutated and non-mutated sequences. In this work, we consider a mutation model that incorporates insertions and deletions in addition to single-nucleotide substitutions. Within this framework, we derive closed-form k-mer-based estimators for the three fundamental mutation parameters: substitution, deletion rate, and insertion rates. We provide theoretical guarantees in the form of concentration inequalities, ensuring accuracy of our estimators under reasonable model assumptions. Empirical evaluations on simulated evolution of genomic sequences confirm our theoretical findings, demonstrating that accounting for insertions and deletions signals allows for accurate estimation of mutation rates and improves upon the results obtained by considering a substitution-only model. An implementation of estimating the mutation parameters from a pair of fasta files is available here: https://github.com/KoslickiLab/estimate_rates_using_mutation_model.git. The results presented in this manuscript can be reproduced using the code available here: https://github.com/KoslickiLab/est_rates_experiments.git."

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
url_custom = [{name = "DOI", url = "https://doi.org/10.1186/s13015-026-00299-9"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
