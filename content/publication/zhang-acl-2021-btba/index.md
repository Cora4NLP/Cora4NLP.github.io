---
# Documentation: https://wowchemy.com/docs/managing-content/






title: "A Bidirectional Transformer Based Alignment Model for Unsupervised Word Alignment"
authors: [Jingyi Zhang, Josef van Genabith]
date: 2021-08-02T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-02T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing"
publication_short: "ACL 2021"

abstract: "Word alignment and machine translation are two closely related tasks. Neural translation models, such as RNN-based and Transformer models, employ a target-to-source attention mechanism which can provide rough word alignments, but with a rather low accuracy. High-quality word alignment can help neural machine translation in many different ways, such as missing word detection, annotation transfer and lexicon injection. Existing methods for learning word alignment include statistical word aligners (e.g. GIZA++) and recently neural word alignment models. This paper presents a bidirectional Transformer based alignment (BTBA) model for unsupervised learning of the word alignment task. Our BTBA model predicts the current target word by attending the source context and both left-side and right-side target context to produce accurate target-to-source attention (alignment). We further fine-tune the target-to-source attention in the BTBA model to obtain better alignments using a full context based optimization method and self-supervised training. We test our method on three word alignment tasks and show that our method outperforms both previous neural word alignment approaches and the popular statistical word aligner GIZA++."



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

url_pdf: "https://aclanthology.org/2021.acl-long.24.pdf"
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
