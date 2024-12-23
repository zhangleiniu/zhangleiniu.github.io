---
title: "Network Interdiction Goes Neural"
authors:
- admin
- Zhiqian Chen
- Chang-Tien Lu
- Liang Zhao
date: "2024-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Network interdiction problems are combinatorial optimization problems involving two players: one aims to solve an optimization problem on a network, while the other seeks to modify the network to thwart the first player's objectives. Such problems typically emerge in an attacker-defender context, encompassing areas such as military operations, disease spread analysis, and communication network management. The primary bottleneck in network interdiction arises from the high time complexity of using conventional exact solvers and the challenges associated with devising efficient heuristic solvers. GNNs, recognized as a cutting-edge methodology, have shown significant effectiveness in addressing single-level CO problems on graphs, such as the traveling salesman problem, graph matching, and graph edit distance. Nevertheless, network interdiction presents a bi-level optimization challenge, which current GNNs find difficult to manage. To address this gap, we represent network interdiction problems as Mixed-Integer Linear Programming (MILP) instances, then apply a multipartite GNN with sufficient representational capacity to learn these formulations. This approach ensures that our neural network is more compatible with the mathematical algorithms designed to solve network interdiction problems, resulting in improved generalization. Through two distinct tasks, we demonstrate that our proposed method outperforms theoretical baseline models and provides advantages over traditional exact solvers."

# Summary. An optional shortened abstract.
summary: Solving Network Interdiction Problems with Graph Neural Networks

tags:
- Graph Neural Network

featured: true

links:
- name: Custom Link
  url: ''
url_pdf: https://arxiv.org/abs/2405.16409
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Multipartite graph representation of network interdiction instances'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs. -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
