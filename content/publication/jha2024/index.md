---
title: "Jina-ColBERT-v2: A General-Purpose Multilingual Late Interaction Retriever"
authors:
- Rohan Jha
- Bo Wang
- Michael Günther
- Georgios Mastrapas
- Saba Sturua
- Isabelle Mohr
- Andreas Koukounas
- Mohammad Kalim Akram
- Nan Wang
- Han Xiao
date: "2024-09-14"
doi: "[10.48550/arXiv.2408.16672"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-29"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "ArXiv"
# publication_short: ""

abstract: Multi-vector dense models, such as ColBERT, have proven highly effective in information retrieval. ColBERT's late interaction scoring approximates the joint query-document attention seen in cross-encoders while maintaining inference efficiency closer to traditional dense retrieval models, thanks to its bi-encoder architecture and recent optimizations in indexing and search. In this work we propose a number of incremental improvements to the ColBERT model architecture and training pipeline, using methods shown to work in the more mature single-vector embedding model training paradigm, particularly those that apply to heterogeneous multilingual data or boost efficiency with little tradeoff. Our new model, Jina-ColBERT-v2, demonstrates strong performance across a range of English and multilingual retrieval tasks.

# # Summary. An optional shortened abstract.
# summary: COILcr (COntextualized Inverted Lists with Canonical Representation) extends the orginal COIL [[Gao et al. 2021]](https://arxiv.org/abs/2104.07186) neural-lexical retrieval system by explicitly factorizing COIL into intra-context term importance weights and cross-context semantic representations. At indexing time COILcr further maps term semantic representations to a smaller set of clustered canonical representations which efficiently preserve term semantics and retrieval performance while reducing its storage and computational cost.

tags:
- Multilingual Information Retrieval
- ColBERT

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2408.16672'
url_code: 'https://huggingface.co/jinaai/jina-colbert-v2'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ncbimeta
---
