---
title: "Generalizable Tip-of-the-Tongue Retrieval with LLM Re-ranking"
authors:
- Luís Borges
- Rohan Jha
- Jamie Callan
- Bruno Martins
date: "2024-07-11"
doi: "10.1145/3626772.3657917"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-29"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SIGIR '24: Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval"
# publication_short: ""

abstract: Tip-of-the-Tongue (ToT) retrieval is challenging for search engines because the queries are usually natural-language, verbose, and contain uncertain and inaccurate information. This paper studies the generalization capabilities of existing retrieval methods with ToT queries in multiple domains. We curate a multi-domain dataset and evaluate the effectiveness of recall-oriented first-stage retrieval methods across the different domains, considering in-domain, out-of-domain, and multi-domain training settings. We further explore the use of a Large Language Model (LLM), i.e. GPT-4, for zero-shot re-ranking in various ToT domains, relying solely on the item titles. Results show that multi-domain training enhances recall, and that LLMs are strong zero-shot re-rankers, especially for popular items, outperforming direct GPT-4 prompting without first-stage retrieval.

# # Summary. An optional shortened abstract.
# summary: COILcr (COntextualized Inverted Lists with Canonical Representation) extends the orginal COIL [[Gao et al. 2021]](https://arxiv.org/abs/2104.07186) neural-lexical retrieval system by explicitly factorizing COIL into intra-context term importance weights and cross-context semantic representations. At indexing time COILcr further maps term semantic representations to a smaller set of clustered canonical representations which efficiently preserve term semantics and retrieval performance while reducing its storage and computational cost.

tags:
- Information Retrieval
- Tip-of-the-Tongue
- LLM Reranking

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3626772.3657917
url_code: 'https://github.com/LuisPB7/TipTongue'
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
