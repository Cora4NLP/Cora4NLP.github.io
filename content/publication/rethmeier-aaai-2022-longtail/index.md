---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Long-Tail Zero and Few-Shot Learning via Contrastive Pretraining on and for Small Data"
authors: [N. Rethmeier, I. Augenstein]
date: 2020-10-21T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-21T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AAAI Workshop on Artificial Intelligence with Biased or Scarce Data"
publication_short: "AIBSD"

abstract: "For natural language processing 'text-to-text' tasks, the prevailing approaches heavily rely on pretraining large self-supervised models on increasingly larger 'task-external' data. Transfer learning from high-resource pretraining works well, but research has focused on settings with very large data and compute requirements, while the potential of efficient low-resource learning, without large 'task-external' pretraining, remains under-explored. In this work, we evaluate against three core challenges for resource efficient learning. Namely, we analyze: (1) pretraining data (X) efficiency; (2) zero to few-shot label (Y) efficiency; and (3) long-tail generalization, since long-tail preservation has been linked to algorithmic fairness and because data in the tail is limited by definition. To address these challenges, we propose a data and compute efficient self-supervised, contrastive text encoder, pretrained on 60MB of 'task-internal' text data, and compare it to RoBERTa, which was pretrained on 160GB of 'task-external' text. We find our method outperforms RoBERTa, while pretraining and fine-tuning in a 1/5th of RoBERTa's fine-tuning time."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/2010.01061"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [CORA4NLP]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
