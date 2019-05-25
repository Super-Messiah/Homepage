+++
math = true
title = " Seismic attenuation compensation via inversion and imaging"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2018-11-30T10:00:00
date_end = 2018-11-30T11:00:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = ""

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yufeng Wang"]

# Location of event.
location = "Department of Geophysics, Stanford Unversity, USA"

# Name of event and optional event URL.
event = "Group meeting at Stanford Wave Physics Laboratory (SWPLab)"
event_url = "https://pangea.stanford.edu/researchgroups/swp/"

# Abstract. What's your talk about?
abstract = "In this talk, I introduce two effective approaches for seimic attenuation compensation, i.e., inversion framework with $L_{1-2}$ minimization and $Q$-RTM with adaptive stabilization scheme. Compared to conventional **$L_1$** metric, our proposed $L_{1−2}$ penalty has potential to recover exact sparse reflectivity series from noisy attenuated seismograms (kernel matrix is severely ill-conditioned). Compared to conventional low-pass filtering, our proposed stabiliza- tion scheme exhibits superior properties of time-variance and $Q$-dependence. I also present a CUDA-based code package named cu$Q$-RTM, which aims to achieve an efficient, storage-saving and stable $Q$-RTM."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = "swpreport.pdf"

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["Seismic-Q-compensation"]

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
