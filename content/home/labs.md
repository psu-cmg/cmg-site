+++
# Labs widget.
widget = "projects"
active = true
date = 2016-04-20T00:00:00

title = "Labs"
subtitle = ""

# Order that this section will appear in.
weight = 20

# Content.
# Display content from the following folder.
# For example, `folder = "lab"` displays content from `content/lab/`.
folder = "lab"

# View.
# Customize how labs are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all labs or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "University Park"
  tag = ".university_park"

[[filter]]
  name = "Hershey"
  tag = ".hershey"

[[filter]]
  name = "Université Laval"
  tag = ".laval"

+++

