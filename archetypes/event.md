+++
title = "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}  # Schedule page publish date.
draft = false

# Event type.
# Legend:
# 0 = Uncategorized
# 1 = Seminar
# 2 = Journal Club
# 3 = Retreat
event_types = ["0"]

# Presenters. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
presenters = [""]

# Abstract and optional shortened version.
abstract = ""
abstract_short = ""

# Event start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = {{ .Date }}
time_end = {{ .Date }}

# Optional event URL.
event_url = ""

# Location of event.
location = ""

# Is this a selected event? (true/false)
selected = false

# Projects (optional).
#   Associate this event with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning.md"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""
url_zoom = ""

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

