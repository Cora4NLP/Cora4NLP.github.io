---
# Documentation: https://wowchemy.com/docs/managing-content/






title: "Multi-Head Highly Parallelized {LSTM} Decoder for Neural Machine Translation"
authors: [Hongfei Xu, Qiuhui Liu, Josef van Genabith, Deyi Xiong, Meng Zhang]
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

abstract: "One of the reasons Transformer translation models are popular is that self-attention networks for context modelling can be easily parallelized at sequence level. However, the computational complexity of a self-attention network is $O(n^2)$, increasing quadratically with sequence length. By contrast, the complexity of LSTM-based approaches is only O(n). In practice, however, LSTMs are much slower to train than self-attention networks as they cannot be parallelized at sequence level: to model context, the current LSTM state relies on the full LSTM computation of the preceding state. This has to be computed n times for a sequence of length n. The linear transformations involved in the LSTM gate and state computations are the major cost factors in this. To enable sequence-level parallelization of LSTMs, we approximate full LSTM context modelling by computing hidden states and gates with the current input and a simple bag-of-words representation of the preceding tokens context. This allows us to compute each input step efficiently in parallel, avoiding the formerly costly sequential linear transformations. We then connect the outputs of each parallel step with computationally cheap element-wise computations. We call this the Highly Parallelized LSTM. To further constrain the number of LSTM parameters, we compute several small HPLSTMs in parallel like multi-head attention in the Transformer. The experiments show that our MHPLSTM decoder achieves significant BLEU improvements, while being even slightly faster than the self-attention network in training, and much faster than the standard LSTM."





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

url_pdf: "https://aclanthology.org/2021.acl-long.23.pdf"
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
