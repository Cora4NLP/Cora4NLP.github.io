---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MedDistant19: Towards an Accurate Benchmark for Broad-Coverage Biomedical Relation Extraction"
authors: [Saadullah Amin, Pasquale Minervini, David Chang, Pontus Stenetorp, Günter Neumann]
date: 2022-10-12T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-21T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "COLING 2022"
publication_short: "COLING 2022"

abstract: "Relation extraction in the biomedical domain is challenging due to the lack of labeled data and high annotation costs, needing domain experts. Distant supervision is commonly used to tackle the scarcity of annotated data by automatically pairing knowledge graph relationships with raw texts. Such a pipeline is prone to noise and has added challenges to scale for covering a large number of biomedical concepts. We investigated existing broad-coverage distantly supervised biomedical relation extraction benchmarks and found a significant overlap between training and test relationships ranging from 26% to 86%. Furthermore, we noticed several inconsistencies in the data construction process of these benchmarks, and where there is no train-test leakage, the focus is on interactions between narrower entity types. This work presents a more accurate benchmark MedDistant19 for broad-coverage distantly supervised biomedical relation extraction that addresses these shortcomings and is obtained by aligning the MEDLINE abstracts with the widely used SNOMED Clinical Terms knowledge base. Lacking thorough evaluation with domain-specific language models, we also conduct experiments validating general domain relation extraction findings to biomedical relation extraction."

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

url_pdf: "https://arxiv.org/pdf/2204.04779.pdf"
url_code: "https://github.com/pminervini/meddistant-baselines"
url_dataset: "https://github.com/suamin/MedDistant19"
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
projects: [CORA4NLP, XAINES, Precise4Q, CLARIFY]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
