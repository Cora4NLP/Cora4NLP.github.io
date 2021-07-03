---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Probing Word Translations in the Transformer and Trading Decoder for Encoder Layers"
authors: [Hongfei Xu, Josef van Genabith, Qiuhui Liu, Deyi Xiong]
date: 2021-04-01T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-01T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of NAACL-2021: long paper"
publication_short: "NAACL 2021"

abstract: "Due to its effectiveness and performance, the Transformer translation model has attracted wide attention, most recently in terms of probing-based approaches. Previous work focuses on using or probing source linguistic features in the encoder. To date, the way word translation evolves in Transformer layers has not yet been investigated. Naively, one might assume that encoder layers capture source information while decoder layers translate. In this work, we show that this is not quite the case: translation already happens progressively in encoder layers and even in the input embeddings. More surprisingly, we find that some of the lower decoder layers do not actually do that much decoding. We show all of this in terms of a probing approach where we project representations of the layer analyzed to the final trained and frozen classifier level of the Transformer decoder to measure word translation accuracy. Our findings motivate and explain a Transformer configuration change: if translation already happens in the encoder layers, perhaps we can increase the number of encoder layers, while decreasing the number of decoder layers, boosting decoding speed, without loss in translation quality? Our experiments show that this is indeed the case: we can increase speed by up to a factor 2.3 with small gains in translation quality, while an 18-4 deep encoder configuration boosts translation quality by +1.42 BLEU (En-De) at a speed-up of 1.4."
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

url_pdf: ""
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
