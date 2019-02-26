+++
title = "Semantic Texture for Robust Dense Tracking"
date = 2017-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jan Czarnowski", "Stefan Leutenegger", "Andrew J. Davison"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "ICCV 2017 Workshop"
publication_short = "ICCV 2017 Workshop"

# Abstract and optional shortened version.
abstract = "We  argue  that  robust  dense  SLAM  systems  can  makevaluable use of the layers of features coming from a stan-dard CNN as a pyramid of ‘semantic texture’ which is suit-able for dense alignment while being much more robust tonuisance factors such as lighting than raw RGB values. Weuse a straightforward Lucas-Kanade formulation of imagealignment, with a schedule of iterations over the coarse-to-fine levels of a pyramid, and simply replace the usual im-age pyramid by the hierarchy of convolutional feature mapsfrom a pre-trained CNN. The resulting dense alignment per-formance is much more robust to lighting and other varia-tions, as we show by camera rotation tracking experimentson time-lapse sequences captured over many hours.  Look-ing towards the future of scene representation for real-timevisual SLAM, we further demonstrate that a selection usingsimple criteria of a small number of the total set of featuresoutput by a CNN gives just as accurate but much more effi-cient tracking performance."
abstract_short = "This work demonstrates that it is possible to perform dense whole-image alignment on feature activations coming from an off-the-shelf CNN classifier. These features form a pyramid of varying semantic levels which, optimized in a coarse-to-fine manner, allows for much more robust camera tracking."

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/abs/1708.08844"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/SkpHccE1eTQ"
url_poster = ""
url_source = ""
url_embed = "SkpHccE1eTQ"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

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
