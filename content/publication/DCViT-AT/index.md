---
title: "Boosting Adversarial Transferability using Dynamic Cues" 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
 - admin
 - Ahmad Mahmood
 - Salman Khan
 - Fahad Shahbaz Khan

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-02-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-06-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * International Conference on Learning Representations, ICLR 2023*
publication_short: In *ICLR*

abstract: Deep neural networks are vulnerable to adversarial attacks. We can develop more reliable AI models by analyzing blind spots across different architectures, datasets, and tasks using transferable adversarial attacks. This year @ICLR'23, we will present a method to study adversarial blind spots of video models by transferring adversarial perturbations from Image to Video and Multi-view models. 

Paper: https://openreview.net/forum?id=SZynfVLGd5
Code: https://github.com/Muzammal-Naseer/DCViT-AT
Authors: Muzammal Naseer*, Ahmad Mahmood*, Salman Khan, Fahad Khan

We show that we can re-configure a pre-trained Vision Transformer (ViT) by inducing dynamic cues to give the model the ability to recognize an action in a video (e.g., Kinetics) or a 3D object (e.g., ModelNet40 ) without losing the original pre-trained image solution (e.g., ImageNet). 

Therefore, we do not need specialized architectures, e.g., divided space-time attention, 3D convolutions, or multi-view convolution networks for different data modalities. Image models are effective surrogates to optimize an adversarial attack to fool black-box models in a changing environment over time.

We analyze 16 architectures across seven large-scale image and video datasets using three types of pre-trained models (supervised, self-supervised, and text-supervised). 

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**ICLR 2023**</span> <br> Learning temporal prompts within image models (ViTs) to fool video models.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Code
   url: https://github.com/Muzammal-Naseer/DCViT-AT
 - name: arXiv
   url: https://arxiv.org/abs/2302.12252

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

