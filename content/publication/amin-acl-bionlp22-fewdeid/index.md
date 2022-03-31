---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Few-Shot Cross-lingual Transfer for Coarse-grained De-identification of Code-Mixed Clinical Texts"
authors: [Saadullah Amin, Noon Pokaratsiri Goldstein, Morgan K. Wixted, Alejandro P. Garcia-Rudolph, Catalina Martínez-Costa, Günter Neumann]
date: 2022-05-26T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-28T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 21st Workshop on Biomedical Language Processing"
publication_short: "ACL-BioNLP 2022"

abstract: "Despite the advances in digital healthcare systems offering curated structured knowledge, much of the important information still lies in large-volumes of unlabeled and unstructured clinical texts. These texts, which often contain protected health information (PHI), are subject to information extraction tools for downstream applications, risking the identification of patients. Existing works in de-identification rely on using large-scale annotated corpora in English, which often are not reproducible in real-world multilingual settings. Pre-trained language models (LM) have shown great potential of transfer learning in low-resource settings. In this work, we showcase the adaptation of LMs in few-shot cross-lingual transfer in solving a real-world challenge—Spanish-Catalan code-mixed clinical notes de-identification in the stroke domain. We annotate a gold evaluation dataset to assess few-shot setting performance where only a few hundred labeled examples are used for training. Our model boosts the zero-shot F1-score from 73.7% to 91.2% in a multi-task setup using the MEDDOCAN corpus (Marimon et al., 2019) and our code-mixed domain-constrained few-shot corpus with Multilingual BERT (mBERT) (Devlin et al., 2019). Our best model achieves a human-evaluation F1-score of 97.2% when generalized to an out-of-sample test set."

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

url_pdf: "https://drive.google.com/file/d/1ObHumDgKSfFs_Ufj271rFIoJMSYwnpGz/view?usp=sharing"
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
projects: [CORA4NLP, Precise4Q]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
