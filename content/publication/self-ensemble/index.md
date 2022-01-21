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

date: "2022-01-01T00:00:00Z"
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

abstract: While the untargeted black-box transferability of adversarial perturbations has been extensively studied before, changing an unseen model's decisions to a specific targeted class remains a challenging feat. In this paper, we propose a new generative approach for highly transferable targeted perturbations (ours). We note that the existing methods are less suitable for this task due to their reliance on class-boundary information that changes from one model to another, thus reducing transferability. In contrast, our approach matches the perturbed image distribution' with that of the target class, leading to high targeted transferability rates. To this end, we propose a new objective function that not only aligns the global distributions of source and target images, but also matches the local neighbourhood structure between the two domains. Based on the proposed objective, we train a generator function that can adaptively synthesize perturbations specific to a given input. Our generative approach is independent of the source or target domain labels, while consistently performs well against state-of-the-art methods on a wide range of attack settings. As an example, we achieve 32.63% target transferability from (an adversarially weak) VGG19BN to (a strong) WideResNet on ImageNet val. set, which is 4x higher than the previous best generative attack and 16x better than instance-specific iterative attack. Code is available at [here](https://github.com/Muzammal-Naseer/TTP)

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**ICCV 2021**</span> <br> Adversarial generator trained to model global targeted adversarial patterns by matching source and target domains in the discriminator's latent space. Training does not require source/target labels or classfication scores. 
# Patterns found via our method show high (black-box, zero knowledge about victim model) transferability to differnet network architectures, tranining mechanisms and defenses including against state-of-the-art input procressing.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Code
   url: https://github.com/Muzammal-Naseer/TTP
 - name: arXiv
   url: https://arxiv.org/abs/2103.14641
 - name: Video Presentation
   url: https://drive.google.com/file/d/1KSe9Zp6_uADkMgXQkHpoKtN85Q1sX_Wv/view?usp=sharing
 - name: Poster
   url: https://drive.google.com/file/d/1kIMIwUHcaHYpWiphHmT38_S0ruS2TrrG/view?usp=sharing

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

