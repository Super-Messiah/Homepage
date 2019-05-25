+++
# Project title.
math = true
title = "Seismic $Q$ compensation"
weight = 2

# Date this page was created.
date = 2019-05-02T00:00:00

# Project summary to display on homepage.
summary = """Seismic attenuation compensation is an important method to enhance signal resolution and fidelity, which can be performed on either prestack or poststack data. I aim at developing the state-of-the-art algorithms and general framework that includes seismic inversion and imaging schemes to compensate the subsurface $Q$ filtering effects."""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Seismic Q compensation"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

  # Show image only in page previews?
  preview_only = true
+++

When seismic waves travel through the earth subsurface, the absorption and dispersion caused by the anelasticity of the subsurface will inevitably degrade the quality of seismograms, decrease the resolution of migrated images, and eventually affect the reliability of seismic interpretation.  It is essential to compensate amplitude loss and phase distortion. In general, attenuation compensation in geophysics can be roughly classified into two categories: seismic record-based compensation and propagation-based compensation.


## $L_{1-2}$ minimization

{{< figure src="3Dfielddata.png" numbered="true" alt="" title="Seismic attenuation compensation via $L_{1-2}$ minimization inversion scheme on 3-D field data." 
caption="**a)** Original attenuated data. **b)** The compensated data using our proposed $L_{1−2}$ minimization." >}}

## Adaptive stabilization

{{< figure src="propagators.png" numbered="true" alt="" title="The compensated time propagator and stabilized time propagators, we clip the same amplitude value for these three figures."
caption="**a)** The compensated time propagator without stabilization. **b)** The stabilized time propagator using low-pass Tukey filtering method. **c)** The stabilized time propagator using our proposed adaptive stabilization scheme." >}}
