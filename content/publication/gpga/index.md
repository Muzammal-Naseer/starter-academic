---
title: "Guidance Through Surrogate: Towards a Generic Diagnostic Attack" 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
 - admin
 - Salman Khan
 - Fatih Porikli
 - Fahad Shahbaz Khan
 

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-03-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-06-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * Transactions on Neural Networks and Learning Systems, TNNLS 2022*
publication_short: In *TNNLS*

abstract: Adversarial training is an effective approach to make deep neural networks robust against adversarial attacks. Recently, different adversarial training defenses are proposed that not only maintain a high clean accuracy but also show significant robustness against popular and well studied adversarial attacks such as PGD. High adversarial robustness can also arise if an attack fails to find adversarial gradient directions, a phenomenon known as gradient masking. In this work, we analyse the effect of label smoothing on adversarial training as one of the potential causes of gradient masking. We then develop a guided mechanism to avoid local minima during attack optimization, leading to a novel attack dubbed Guided Projected Gradient Attack (G-PGA). Our attack approach is based on a match and deceive loss that finds optimal adversarial directions through guidance from a surrogate model. Our modified attack does not require random restarts, large number of attack iterations or search for an optimal step-size. Furthermore, our proposed G-PGA is generic, thus it can be combined with an ensemble attack strategy as we demonstrate for the case of Auto-Attack, leading to efficiency and convergence speed improvements. More than an effective attack, G-PGA can be used as a diagnostic tool to reveal elusive robustness due to gradient masking in adversarial defenses.

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**TNNLS 2022**</span>, <span style="font-size:120%;color:#3380FF">**Impact Factor [14.25]**</span> <br> Match and Deceive loss for guidance to break adversarial defenses.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: arXiv
   url: https://ieeexplore.ieee.org/abstract/document/9825707

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
# example

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

