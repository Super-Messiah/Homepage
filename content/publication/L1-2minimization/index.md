+++


title = "$L_{1−2}$ minimization for exact and stable seismic attenuation compensation"
date = 2018-02-19T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Yufeng Wang**", "Xiong Ma", "Hui Zhou", "Yangkang Chen"]

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
publication = "*Geophysical Journal International*"
publication_short = ""

# Abstract.
abstract = """
Frequency-dependent amplitude absorption and phase velocity dispersion are typically linked by the causality-imposed Kramers-Kronig (K-K) relations, which inevitably degrade the quality of seismic data. Seismic attenuation compensation is an important processing approach for enhancing signal resolution and fidelity, which can be performed on either prestack or poststack data so as to mitigate amplitude absorption and phase dispersion effects resulting from intrinsic anelasticity of subsurface media. Inversion-based compensation with $L_1$ norm constraint, enlightened by the sparsity of the reflectivity series, enjoys better stability over traditional inverse $Q$ filtering. However, constrained $L_1$ minimization serving as the convex relaxation of the literal **$L_0$** sparsity count may not give the sparsest solution when the kernel matrix is severely ill-conditioned. Recently, nonconvex metric for compressed sensing has attracted considerable research interest. In this paper, we propose a nearly unbiased approximation of the vector sparsity, denoted as **$L_{1- 2}$** minimization, for exact and stable seismic attenuation compensation. Nonconvex penalty function of **$L_{1- 2}$** norm can be decomposed into two convex subproblems via difference of convex algorithm (DCA), each subproblem can be solved efficiently by alternating direction method of multipliers (ADMM). The superior performance of the proposed compensation scheme based on $L_{1- 2}$ metric over conventional $L_1$ penalty is further demonstrated by both synthetic and field examples."""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1093/gji/ggy064"

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
projects = ["Seismic-Q-compensation", "Seismic-signal-processing"]

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
links = [{name = "Citations: 13", url = "https://scholar.google.com/scholar?oi=bibs&hl=en&cites=15437515801899234189"}]

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
