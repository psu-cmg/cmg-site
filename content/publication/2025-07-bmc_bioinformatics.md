+++
title = "Replacing normalizations with interval assumptions enhances differential expression and differential abundance analyses"
date = "2025-07-01T00:00:00"
draft = false

authors = ["KC McGovern", "JD Silverman"]
publication = "_BMC Bioinformatics_"
publication_short = "_BMC Bioinformatics_"
publication_types = ["2"]

abstract = "Background: Methods for differential expression and differential abundance analysis often rely on normalization to address sample-to-sample variation in sequencing depth. However, normalizations imply strict, unrealistic assumptions about the unmeasured scale of biological systems (e.g., microbial load or total cellular transcription). Even slight errors in these assumptions introduce bias, leading to elevated false positive and negative rates. Results: We introduce interval assumptions as a generalization of normalizations. Unlike normalizations, our interval methods allow researchers to account for potential errors in assumptions about the system scale. Interval assumptions are also customizable and allow researchers to express more biologically plausible assumptions about scale. Interval assumptions even generalize Quantitative Microbiome Profiling (QMP), allowing researchers to account for errors in flow cytometry-based measurements of total cellular concentration. We develop a novel hypothesis testing framework that allows us to integrate interval assumptions into existing tools. We develop a modified version of the popular ALDEx2 method using interval assumptions rather than normalizations. Through real and simulated data analyses, we find that interval assumptions can dramatically decrease false positive rates (i.e., from 45% to 5%) while retaining or increasing statistical power. We also study interval assumptions under misspecification and show they still improve on normalizations. Conclusions: Interval assumptions enhance the rigor and reproducibility of differential expression and differential abundance analyses. Our results add to a growing body of literature arguing that normalizations should be replaced with alternative methods that allow researchers to account for scale uncertainty. However, compared to recent alternatives like scale models and sensitivity analyses, interval assumptions are easier to use, are more robust to misspecification, and have stronger and more interpretable inferential guarantees."

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
url_custom = [{name = "DOI", url = "https://doi.org/10.1186/s12859-025-06177-2"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
