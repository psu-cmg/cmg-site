+++
title = "Not every gene is special: Modelling scale controls the false discovery rate when analysing high-throughput sequencing data"
date = "2026-09-08T00:00:00"
draft = false

authors = ["SJD Santos", "AC Murariu", "JD Silverman", "GB Gloor"]

publication = "_PLOS Computational Biology_"
publication_short = "_PLOS Comput Biol_"
publication_types = ["2"]

abstract = "Differential expression/abundance analyses are commonplace in studies employing high-throughput sequencing (HTS); however different tools often fail to return comparable results when applied to the same dataset. Most tools employ normalisations to attempt to correct for technical variation in the count data. Previously, we demonstrated that these normalisations are often inappropriate due to incorrect assumptions regarding the overall scale (i.e., size) of the biological system in question. In this study, we used a combination of binomial thinning and permutation of sample groupings to produce 100 analysis iterations of 11 RNA-seq and other HTS datasets in which 5% of all features are expected to be significantly different between groups. This enabled calculation of the false discovery rate (FDR) and sensitivity across the iterations. Our simulations showed that scale misspecification results in poor control of the FDR by several commonly used tools and that, counterintuitively, FDRs increased as the modelled difference between groups increased. Implementing a scale model in ALDEx2 or ALDEx3 ameliorated unacceptably high FDRs; however, there was an inherent trade-off between satisfactory FDR control and high sensitivity- no tool offered both. We established that increasing scale uncertainty also increased the minimum difference between groups required for a feature to be reported as differentially expressed. This phenomenon was consistently observed in disparate types of HTS data and was remarkably consistent. Critically, we leveraged a ‘real-world’, non-permuted analysis of an RNA-seq dataset to demonstrate that the latter effect is not a result of our thinning/permutation approach. Overall, our work highlights the potentially unwitting choice between sensitivity and FDR control that all researchers are making when analysing sequencing data and provides guidance on choosing an appropriate amount of scale uncertainty for the analysis of HTS data."

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
url_custom = [{name = "DOI", url = "https://doi.org/10.1371/journal.pcbi.1014728"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
