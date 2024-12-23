---
title: 'Infinitely Deep Graph Transformation Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Qisheng Zhang
  - ZHiqian Chen
  - Yanshen Sun
  - Chang-Tien Lu
  - Liang Zhao

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-12-12T00:00:00Z'
doi: '10.1109/ICDM58522.2023.00087'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Conference on Data Mining*
publication_short: In *ICDM2023*

abstract: 

# Summary. An optional shortened abstract.
summary: Deep Equilibrium Model for Node-Edge Co-Evolution Graph Neural Network

tags:
  - Graph Neural Network

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://par.nsf.gov/servlets/purl/10505932'
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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

{{< math >}}
$$
\min_{\Theta_v, \Theta_e, W_{ev}, W_{ve}, \Omega}  \mathcal{L}_1(F', g_{\Theta_e}(H_v)) + \mathcal{L}_2(E', f_{\Theta_e}(H_e)) , \\
 \text{subject to: }  H_e = \phi(W_{ve}     H_v B  ) , \\
 H_v = \phi( W_{ev} \phi( W_{ve} H_v B ) B^{\intercal} +b_{\Omega}(E_0, F_0)) ,\\
 \lambda_{pf}(B B^{\intercal}) \lambda_{pf} ( W_{ev}^{|\cdot|} W_{ve}^{|\cdot|}) <1 .
$$
{{< /math >}}