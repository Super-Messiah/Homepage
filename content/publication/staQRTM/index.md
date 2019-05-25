+++
# Is this a featured publication? (true/false)
featured = true

title = "Adaptive stabilization for $Q$-compensated reverse time migration"
date = 2017-11-14T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Yufeng Wang**", "Hui Zhou", "Hanming Chen", "Yangkang Chen"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Geophysics*"
publication_short = ""

# Abstract.
abstract = """Reverse time migration (RTM) for attenuating media should take amplitude compensation and phase correction into consideration. However, the attenuation compensation during seismic propagation suffers from numerical instability because of the boosted high-frequency ambient noise. We develop a novel adaptive stabilization method for $Q$-compensated RTM ($Q$-RTM), which exhibits superior properties of time-variance and $Q$-dependence over conventional low-pass filtering based method. We derive the stabilization operator by first analytically derive k-space Green's functions for constant-$Q$ wave equation with decoupled fractional Laplacians (DFLs) and its compensated equation. The time propagator of the Green's function for the viscoacoustic wave equation decreases exponentially, whereas that of the compensated equation is exponential divergent at high-wavenumber and is not stable after the wave is extrapolated for a long time. The Green's functions therefore theoretically explain how the numerical instability existing in $Q$-RTM arises and shed light on how to overcome this problem pertinently. The stabilization factor required in the proposed method can be explicitly identified by the specified gain limit according to an empirical formula. The $Q$-RTM results for noise-free data using low-pass filtering and adaptive stabilization are compared over a simple five-layer model and the BP gas chimney model to verify the superiority of the proposed approach in terms of fidelity and stability. The $Q$-RTM result for noisy data from the BP gas chimney model further demonstrates that the proposed method enjoys a better anti-noise performance and helps significantly enhance the resolution of seismic images.  """

# Summary. An optional shortened abstract.
summary = "We develop a novel adaptive stabilization method for $Q$-compensated RTM ($Q$-RTM), which exhibits superior properties of time-variance and $Q$-dependence over conventional low-pass filtering based method. We derive the stabilization operator by first analytically derive k-space Green's functions for constant-$Q$ wave equation with decoupled fractional Laplacians (DFLs) and its compensated equation."

# Digital Object Identifier (DOI)
doi = "10.1190/geo2017-0244.1"



# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["Seismic-Q-compensation"]

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Citations: 22", url = "https://scholar.google.com/scholar?oi=bibs&hl=en&cites=5517535537660926910"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

## Highlights

This research is highlighted in [The Leading Edge](https://library.seg.org/doi/10.1190/tle37020152.1) as Geophysics Bright Spots Paper by Geophysics Editors. Click [<i class="far fa-file-pdf"></i>](Geophysics Bright Spots.pdf) to download the PDF version.
