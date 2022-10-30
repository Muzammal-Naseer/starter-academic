---
title: "On Improving Adversarial Transferability of Vision Transformers" 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
 - admin
 - Kanchana Ranasinghe
 - Salman Khan
 - Fahad Shahbaz Khan
 - Fatih Porikli

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-02-03T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-06-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * International Conference on Learning Representations, ICLR 2022*
publication_short: In *ICLR*

abstract: Vision transformers (ViTs) process input images as sequences of patches via self-attention; a radically different architecture than convolutional neural networks (CNNs). This makes it interesting to study the adversarial feature space of ViT models and their transferability. In particular, we observe that adversarial patterns found via conventional adversarial attacks show very low black-box transferability even for large ViT models. However, we show that this phenomenon is only due to the sub-optimal attack procedures that do not leverage the true representation potential of ViTs. A deep ViT is composed of multiple blocks, with a consistent architecture comprising of self-attention and feed-forward layers, where each block is capable of independently producing a class token. Formulating an attack using only the last class token (conventional approach) does not directly leverage the discriminative information stored in the earlier tokens, leading to poor adversarial transferability of ViTs. Using the compositional nature of ViT models, we enhance the transferability of existing attacks by introducing two novel strategies specific to the architecture of ViT models. (i) Self-Ensemble, we propose a method to find multiple discriminative pathways by dissecting a single ViT model into an ensemble of networks. This allows explicitly utilizing class-specific information at each ViT block. (ii) Token Refinement, we then propose to refine the tokens to further enhance the discriminative capacity at each block of ViT. Our token refinement systematically combines the class tokens with structural information preserved within the patch tokens. An adversarial attack, when applied to such refined tokens within the ensemble of classifiers found in a single vision transformer, has significantly higher transferability. Code is available at [here](https://github.com/Muzammal-Naseer/On-Improving-Adversarial-Transferability-of-Vision-Transformers)

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**ICLR 2022**</span>, <span style="font-size:120%;color:#D35400">**Spotlight**</span> <br> Self-ensemble with token/feature refinement for adversarial transferability.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Code
   url: https://github.com/Muzammal-Naseer/On-Improving-Adversarial-Transferability-of-Vision-Transformers
 - name: arXiv
   url: https://arxiv.org/abs/2106.04169
 - name: Reviews & Response
   url: https://openreview.net/forum?id=D6nH3719vZy
 - name: Video Presentation
   url: https://recorder-v3.slideslive.com/?share=62589&s=569ede9b-273e-45e8-a12a-be057e75aea1
 - name: Poster
   url: https://drive.google.com/file/d/1EC2aJEeQP2Wu0jemD2fJhOamaC1EoaFF/view?usp=sharing

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

