+++
title = "Cu$Q$-RTM: A CUDA-based code package for stable and efficient $Q$-compensated RTM"
date = 2018-12-21T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Yufeng Wang**", "Hui Zhou", "Xuebin Zhao", "Qingchen Zhang", "Poru Zhao", "Xiance Yu", "Yangkang Chen"]

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
abstract = """
Reverse time migration (RTM) in attenuating media should take the absorption and dispersion effects into consideration. The latest proposed viscoacoustic wave equation with decoupled fractional Laplacians (DFLs) facilitates separate amplitude compensation and phase correction in $Q$-compensated RTM ($Q$-RTM). However, intensive computation and enormous storage requirements of $Q$-RTM prevent it from being extended into practical application, especially for large-scale 2D or 3D case. The emerging graphics processing unit (GPU) computing technology, built around a scalable array of multithreaded Streaming Multiprocessors (SMs), presents an opportunity for greatly accelerating $Q$-RTM by appropriately exploiting GPU's architectural characteristics. We present the cu$Q$-RTM, a CUDA-based code package that implements $Q$-RTM based on a set of stable and efficient strategies, such as streamed CUFFT, checkpointing-assisted time-reversal reconstruction (CATRC) and adaptive stabilization. The cu$Q$-RTM can run in a multi-level parallelism (MLP) fashion, either synchronously or asynchronously, to take advantages of all the CPUs and GPUs available, while maintaining impressively good stability and flexibility. We mainly outline the architecture of the cu$Q$-RTM code package and some program optimization schemes. The speedup ratio on a single GeForce GTX760 GPU card relative to a single core of Intel Core i5-4460 CPU can reach above 80 in large-scale simulation. The strong scaling property of multi-GPU parallelism is demonstrated by performing $Q$-RTM on a Marmousi model with one to six GPU(s) involved. Finally, we further verify the feasibility and efficiency of the cu$Q$-RTM on a field data set."""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1190/GEO2017-0624.1"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["Seismic-Q-compensation", "High-performance-computing"]

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
links = [{name = "Citations: 0", url = ""}]

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
