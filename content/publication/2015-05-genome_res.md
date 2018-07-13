+++
title = "Accurate typing of short tandem repeats from genome-wide sequencing data and its applications"
date = "2015-05-01T00:00:00"
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["A Fungtammasan", "G Ananda", "SE Hile", "MSW Su", "C Sun", "R Harris", "[__P Medvedev__](http://medvedevgroup.com)", "[__K Eckert__](https://profiles.psu.edu/profiles/display/113435)", "[__KD Makova__](http://www.bx.psu.edu/makova_lab)"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "_Genome Research_"
publication_short = "_GENOME RES_"

# Abstract and optional shortened version.
abstract = "Short tandem repeats (STRs) are implicated in dozens of human genetic diseases and contribute significantly to genome variation and instability. Yet profiling STRs from short-read sequencing data is challenging because of their high sequencing error rates. Here, we developed STR-FM, __s__hort __t__andem __r__epeat profiling using __f__lank-based __m__apping, a computational pipeline that can detect the full spectrum of STR alleles from short-read data, can adapt to emerging read-mapping algorithms, and can be applied to heterogeneous genetic samples (e.g., tumors, viruses, and genomes of organelles). We used STR-FM to study STR error rates and patterns in publicly available human and in-house generated ultradeep plasmid sequencing data sets. We discovered that STRs sequenced with a PCR-free protocol have up to ninefold fewer errors than those sequenced with a PCR-containing protocol. We constructed an error correction model for genotyping STRs that can distinguish heterozygous alleles containing STRs with consecutive repeat numbers. Applying our model and pipeline to Illumina sequencing data with 100-bp reads, we could confidently genotype several disease-related long trinucleotide STRs. Utilizing this pipeline, for the first time we determined the genome-wide STR germline mutation rate from a deeply sequenced human pedigree. Additionally, we built a tool that recommends minimal sequencing depth for accurate STR genotyping, depending on repeat length and sequencing read length. The required read depth increases with STR length and is lower for a PCRfree protocol. This suite of tools addresses the pressing challenges surrounding STR genotyping, and thus is of wide interest to researchers investigating disease-related STRs and STR evolution."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning.md"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
url_custom = [{name = "DOI", url = "https://doi.org/10.1101/gr.185892.114"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
