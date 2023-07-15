---
title: "COILcr: Efficient Semantic Matching in Contextualized Exact Match Retrieval"
authors:
- Zhen Fan
- Luyu Gao
- Rohan Jha
- Jamie Callan
date: "2023-03-17"
doi: "10.1007/978-3-031-28244-7_19"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Advances in Information Retrieval (ECIR 2023)"
# publication_short: ""

abstract: Lexical exact match systems that use inverted lists are a fundamental text retrieval architecture. A recent advance in neural IR, COIL, extends this approach with contextualized inverted lists from a deep language model backbone and performs retrieval by comparing contextualized query-document term representation, which is effective but computationally expensive. This paper explores the effectiveness-efficiency tradeoff in COIL-style systems, aiming to reduce the computational complexity of retrieval while preserving term semantics. It proposes COILcr, which explicitly factorizes COIL into intra-context term importance weights and cross-context semantic representations. At indexing time, COILcr further maps term semantic representations to a smaller set of canonical representations. Experiments demonstrate that canonical representations can efficiently preserve term semantics, reducing the storage and computational cost of COIL-based retrieval while maintaining model performance. The paper also discusses and compares multiple heuristics for canonical representation selection and looks into its performance in different retrieval settings.

# Summary. An optional shortened abstract.
summary: COILcr (COntextualized Inverted Lists with Canonical Representation) extends the orginal COIL [[Gao et al. 2021]](https://arxiv.org/abs/2104.07186) neural-lexical retrieval system by explicitly factorizing COIL into intra-context term importance weights and cross-context semantic representations. At indexing time COILcr further maps term semantic representations to a smaller set of clustered canonical representations which efficiently preserve term semantics and retrieval performance while reducing its storage and computational cost.

tags:
- Information Retrieval
- Lexical Exact Match
- Deep Language Models

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.cs.cmu.edu/~callan/Papers/ecir23-zhen-fan.pdf
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
