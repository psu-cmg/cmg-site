+++
title = "Scale reliant mixed effects models enhance microbiome data analysis"
date = "2026-03-25T00:00:00"
draft = false

authors = ["KC McGovern", "JD Silverman"]
publication = "_Microbiome_"
publication_short = "_Microbiome_"
publication_types = ["2"]

abstract = "Linear models, including those used for differential abundance analyses, are frequently used in microbiome research to assess how experimental conditions (e.g., disease state or age) affect microbial abundance. Linear mixed-effects models (MEMs) extend linear models to accommodate complex designs, such as longitudinal sampling or hierarchical study structures. However, when applied to microbiome data, existing MEM approaches suffer from high false positive and false negative rates because sequence counts are compositional – they reflect relative rather than absolute abundances. Current methods attempt to overcome this limitation through normalization, but these approaches rely on strong, often unrealistic assumptions about the unmeasured biological scale (e.g., total microbial load). Here we introduce scale-reliant mixed-effects models (SR-MEM), which extend our earlier scale-reliant inference framework by explicitly modeling uncertainty in the unmeasured scale via user-defined probability distributions. By treating scale as a latent variable rather than fixing it through normalization, SR-MEM enables robust inference for complex experimental designs. SR-MEM can incorporate external scale measurements (e.g., flow cytometry, qPCR) or leverage scale information from independent studies to further improve inference. Across simulations and multiple real-world case studies, SR-MEM consistently controls the false discovery rate while maintaining comparable or higher power than standard approaches relying on normalization or bias correction. In reanalyses of published datasets, SR-MEM yields results that are more reproducible across studies and more consistent with known biological and pharmacological effects. SR-MEM provides a principled and practical framework for mixed-effects modeling of microbiome sequence count data in the presence of unmeasured biological scale. By avoiding normalization-based assumptions and instead propagating scale uncertainty through inference, SR-MEM improves error control and reproducibility in longitudinal and hierarchical studies. An accessible implementation is provided in the ALDEx3 R package."

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
url_custom = [{name = "DOI", url = "https://doi.org/10.1186/s40168-026-02377-x"}]

math = false
highlight = true

[header]
image = ""
caption = ""
+++
