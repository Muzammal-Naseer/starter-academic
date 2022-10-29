---
title: "Self-supervised Video Transformer" 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
 - Hanan Gani
 - admin
 - Mohammad Yaqub

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-06-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * British Machine Vision Conference, BMVC 2022*
publication_short: In *BMVC*

abstract: Vision Transformer (ViT), a radically different architecture than convolutional neural networks offers multiple advantages including design simplicity, robustness and state-of-the-art performance on many vision tasks. However, in contrast to convolutional neural networks, Vision Transformer lacks inherent inductive biases. Therefore, successful training of such models is mainly attributed to pre-training on large-scale datasets such as ImageNet with 1.2M or JFT with 300M images. This hinders the direct adaption of Vision Transformer for small-scale datasets. In this work, we show that self-supervised inductive biases can be learned directly from small-scale datasets and serve as an effective weight initialization scheme for fine-tuning. This allows to train these models without large-scale pre-training, changes to model architecture or loss functions. We present thorough experiments to successfully train monolithic and non-monolithic Vision Transformers on five small datasets including CIFAR10/100, CINIC10, SVHN, Tiny-ImageNet and two fine-grained datasets: Aircraft and Cars. Our approach consistently improves the performance of Vision Transformers while retaining their properties such as attention to salient regions and higher robustness. Our codes and pre-trained models are available at: https://github.com/hananshafi/vits-for-small-scale-datasets.

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**BMVC 2022**</span><br> Vision Transformers, whether monolithic or non-monolithic, both suffer when trained from scratch on small datasets. This is primarily due to the lack of locality, inductive biases and hierarchical structure of the representations which is commonly observed in the Convolutional Neural Networks. As a result, ViTs require large-scale pre-training to learn such properties from the data for better transfer learning to downstream tasks. We show that inductive biases can be learned directly from the small dataset through self-supervision, thus serving as an effective weight initialization for finetuning on the same dataset. Our proposed self-supervised inductive biases improve the performance of ViTs on small datasets without modifying the network architecture or loss functions.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Code
   url: https://github.com/hananshafi/vits-for-small-scale-datasets
 - name: arXiv
   url: https://arxiv.org/abs/2210.07240v1

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

