---
title: SDM 25' Tutorial

event: SDM25
event_url: https://meetings.siam.org/program.cfm?CONFCODE=SDM25

location: The Westin Alexandria Old Town
address:
  street: 400 Courthouse Square
  city: Alexandria
  region: VA
  postcode: '22314'
  country: United States

summary: Unifying Spectral and Spatial Graph Neural Networks
abstract: 'Many real-world networks evolve over time, which results in dynamic graphs such as human mobility networks and brain networks. Usually, the “dynamics on graphs” (e.g., node attribute values evolving) are observable, and may be related to and indicative of the underlying “dynamics of graphs” (e.g., evolving of the graph topology). Tradition- ally, both types of dynamics have been highly complex to model, but in recent years, research on each has attracted increasing attention with the help of expressive models, such as graph neural networks. However, modeling and mapping between them have not yet been well-explored on account of two significant challenges: 1) the difficulty with mapping continuous multi-attributed data to discrete graph topologi- cal data, and 2) the ineffectiveness and inefficiency of learn- ing the long, high-dimensional time series of the dynamics. To address these challenges, we propose to learn the map- ping between the dynamics on graphs and the dynamics of graphs with a new graph neural network, which is based on an adaptive echo-state architecture. Specifically, we pro- pose a new deep echo-state graph dynamics encoder that is scalable for graphs with large time duration and sizes. Then to ensure a good learnability, a new neural architec- ture search (NAS) strategy is proposed and tailored for the proposed deep echo-state encoder and dynamic graph pre- dictor. Extensive experiments on synthetic and real-world application data demonstrate the outstanding effectiveness and efficiency of the proposed method.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-05-03T13:30:00Z'
date_end: '2025-05-03T15:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3627673.3679088'
# url_slides: 'https://github.com/XGraph-Team/Spectral-Graph-Survey/blob/3ea4b2a0f818f6287b4ddefa19a6c1372a619134/CIKM%2024%20tutorial.pdf'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}} -->

<!-- Slides can be added in a few ways: -->

<!-- - **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
