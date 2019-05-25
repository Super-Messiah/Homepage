+++
# Project title.
math = true
title = "Deep learning"
weight = 5

# Date this page was created.
date = 2019-05-02T00:00:00

# Project summary to display on homepage.
summary = """The task of training a deep learning algorithm to accurately identify a nonlinear map from a few and potentially very high-dimensional input and output data pairs seems at best naive. Coming to our rescue, for many cases pertaining to the modeling of physical systems, there exists a vast amount of prior knowledge such as the principled physical laws that govern the time-dependent dynamics of a system. Encoding such structured information into a learning algorithm results in amplifying the information content of the data that the algorithm sees, enabling it to quickly steer itself towards the right solution and generalize well even when only a few training examples are available."""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deep learning"]

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

In the course of analyzing complex geophysical systems, the apeture and density of data acquisition is limited, and we are inevitably faced with the challenge of inverting subsurface properties and imaging subsurface structures under partial information. In this small data regime, the vast majority of state-of-the-art machine learning techniques (e.g., deep/convolutional/recurrent neural networks) are lacking robustness and fail to provide any guarantees of convergence. In this project, I apply [physics informed neural networks (PINNs)](https://maziarraissi.github.io/research/1_physics_informed_neural_networks/) that are trained to solve supervised learning tasks while respecting any given law of physics described by general nonlinear partial differential equations (PDEs) to seismic modeling, inversion and imaging. 

## Physics informed neural networks

The recently proposed [physics informed neural networks (PINNs)](https://maziarraissi.github.io/research/1_physics_informed_neural_networks/), which are trained to solve supervised machine learning tasks while respecting the given law of physics, sheds a light on full wave simulation that is free of numerical instability and artifical boundary.
