+++
title = "A k-mer-based estimator of the substitution rate between repetitive sequences"
date = "2026-07-03T00:00:00"
draft = false

authors = ["H Wu", "A Blanca", "P Medvedev"]
publication = "_Algorithms for Molecular Biology_"
publication_short = "_Algorithms Mol Biol_"
publication_types = ["2"]

abstract = "Background: K-mer-based analysis of genomic data is ubiquitous, but the presence of repetitive k-mers continues to pose problems for the accuracy of many methods. For example, the Mash tool (Ondov et al 2016) can accurately estimate the substitution rate between two low-repetitive sequences from their k-mer sketches; however, it is inaccurate on repetitive sequences such as the centromere of a human chromosome. Follow-up work by Blanca et al. (2021) has attempted to model how mutations affect k-mer sets based on strong assumptions that the sequence is non-repetitive and that mutations do not create spurious k-mer matches. However, the theoretical foundations for extending an estimator like Mash to work in the presence of repeat sequences have been lacking. Results: In this work, we relax the non-repetitive assumption and propose a novel estimator for the mutation rate. We derive theoretical bounds on our estimator’s bias. Our experiments show that it remains accurate for repetitive genomic sequences, such as the alpha satellite higher order repeats in centromeres. We demonstrate our estimator’s robustness across diverse datasets and various ranges of the substitution rate and k-mer size. Finally, we show how sketching can be used to avoid dealing with large k-mer sets while retaining accuracy. Our software is available at https://github.com/medvedevgroup/Repeat-Aware_Substitution_Rate_Estimator."

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
url_custom = [{name = "DOI", url = "https://doi.org/10.1186/s13015-026-00304-1"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
