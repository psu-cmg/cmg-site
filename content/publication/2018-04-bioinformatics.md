+++
title = "RecoverY: k-mer-based read classification for Y-chromosome-specific sequencing and assembly"
date = "2018-04-01T00:00:00"
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["S Rangavittal", "RS Harris", "M Cechova", "M Tomaszkiewicz", "R Chikhi", "[__KD Makova__](http://www.bx.psu.edu/makova_lab)", "[__P Medvedev__](http://medvedevgroup.com)"]

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
publication = "_Bioinformatics_"
publication_short = "_BIOINFORMATICS_"

# Abstract and optional shortened version.
abstract = "### Motivation\nThe haploid mammalian Y chromosome is usually under-represented in genome assemblies due to high repeat content and low depth due to its haploid nature. One strategy to ameliorate the low coverage of Y sequences is to experimentally enrich Y-specific material before assembly. As the enrichment process is imperfect, algorithms are needed to identify putative Y-specific reads prior to downstream assembly. A strategy that uses _k_-mer abundances to identify such reads was used to assemble the gorilla Y. However, the strategy required the manual setting of key parameters, a time-consuming process leading to sub-optimal assemblies.\n### Results\n We develop a method, RecoverY, that selects Y-specific reads by automatically choosing the abundance level at which a _k_-mer is deemed to originate from the Y. This algorithm uses prior knowledge about the Y chromosome of a related species or known Y transcript sequences. We evaluate RecoverY on both simulated and real data, for human and gorilla, and investigate its robustness to important parameters. We show that RecoverY leads to a vastly superior assembly compared to alternate strategies of filtering the reads or contigs. Compared to the preliminary strategy used by Tomaszkiewicz _et al._, we achieve a 33% improvement in assembly size and a 20% improvement in the NG50, demonstrating the power of automatic parameter selection.\n### Availability and implementation\nOur tool RecoverY is freely available at https://github.com/makovalab-psu/RecoverY.\n### Supplementary information\nSupplementary data are available at _Bioinformatics_ online."
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
url_custom = [{name = "DOI", url = "https://doi.org/10.1093/bioinformatics/btx771"}]

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
