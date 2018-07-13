+++
title = "Error correction and statistical analyses for intra-host comparisons of feline immunodeficiency virus diversity from high-throughput sequencing data"
date = "2015-12-12T00:00:00"
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Y Liu", "[__F Chiaromonte__](http://sites.psu.edu/chiaromonte)", "H Ross", "R Malhotra", "D Elleder", "[__M Poss__](https://www.huck.psu.edu/users/mary-poss)"]

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
publication = "_BMC Bioinformatics_"
publication_short = "_BMC BIOINFORMATICS_"

# Abstract and optional shortened version.
abstract = "### Background\nInfection with feline immunodeficiency virus (FIV) causes an immunosuppressive disease whose consequences are less severe if cats are co-infected with an attenuated FIV strain (PLV). We use virus diversity measurements, which reflect replication ability and the virus response to various conditions, to test whether diversity of virulent FIV in lymphoid tissues is altered in the presence of PLV. Our data consisted of the 3\" half of the FIV genome from three tissues of animals infected with FIV alone, or with FIV and PLV, sequenced by 454 technology.\n### Results\nSince rare variants dominate virus populations, we had to carefully distinguish sequence variation from errors due to experimental protocols and sequencing. We considered an exponential-normal convolution model used for background correction of microarray data, and modified it to formulate an error correction approach for minor allele frequencies derived from high-throughput sequencing. Similar to accounting for over-dispersion in counts, this accounts for error-inflated variability in frequencies - and quite effectively reproduces empirically observed distributions. After obtaining error-corrected minor allele frequencies, we applied ANalysis Of VAriance (ANOVA) based on a linear mixed model and found that conserved sites and transition frequencies in FIV genes differ among tissues of dual and single infected cats. Furthermore, analysis of minor allele frequencies at individual FIV genome sites revealed 242 sites significantly affected by infection status (dual vs. single) or infection status by tissue interaction. All together, our results demonstrated a decrease in FIV diversity in bone marrow in the presence of PLV. Importantly, these effects were weakened or undetectable when error correction was performed with other approaches (thresholding of minor allele frequencies; probabilistic clustering of reads). We also queried the data for cytidine deaminase activity on the viral genome, which causes an asymmetric increase in G to A substitutions, but found no evidence for this host defense strategy.\n### Conclusions\nOur error correction approach for minor allele frequencies (more sensitive and computationally efficient than other algorithms) and our statistical treatment of variation (ANOVA) were critical for effective use of high-throughput sequencing data in understanding viral diversity. We found that co-infection with PLV shifts FIV diversity from bone marrow to lymph node and spleen."
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
url_custom = [{name = "DOI", url = "https://doi.org/10.1186/s12859-015-0607-z"}]

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
