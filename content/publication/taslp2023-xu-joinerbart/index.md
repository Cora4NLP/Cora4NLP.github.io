---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "JoinER-BART: Joint Entity and Relation Extraction with Constrained Decoding, Representation Reuse and Fusion"
authors: ["Hongyang Chang", "Hongfei Xu", "Josef van Genabith", "Deyi Xiong", "Hongying Zan"]
date: 2023-09-27T10:33:03+02:00
doi: "10.1109/TASLP.2023.3310879"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-09-27T10:33:03+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing"
publication_short: "TASLP"

abstract: "Joint Entity and Relation Extraction (JERE) is an important research direction in Information Extraction (IE). Given the surprising performance with fine-tuning of pre-trained BERT in a wide range of NLP tasks, nowadays most studies for JERE are based on the BERT model. Rather than predicting a simple tag for each word, these approaches are usually forced to design complex tagging schemes, as they may have to extract entity-relation pairs which may overlap with others from the same sequence of word representations in a sentence. Recently, sequence-to-sequence (seq2seq) pre-trained BART models show better performance than BERT models in many NLP tasks. Importantly, a seq2seq BART model can simply generate sequences of (many) entity-relation triplets with its decoder, rather than just tag input words. In this paper, we present a new generative JERE framework based on pre-trained BART. Different from the basic seq2seq BART architecture: 1) our framework employs a constrained classifier which only predicts either a token of the input sentence or a relation in each decoding step, and 2) we reuse representations from the pre-trained BART encoder in the classifier instead of a newly trained weight matrix, as this better utilizes the knowledge of the pre-trained model and context-aware representations for classification, and empirically leads to better performance. In our experiments on the widely studied NYT and WebNLG datasets, we show that our approach outperforms previous studies and establishes a new state-of-the-art (92.91 and 91.37 F1 respectively in exact match evaluation)."


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

url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10236558"
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
projects: [Cora4NLP]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
