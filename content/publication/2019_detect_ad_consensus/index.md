---
title: "Detecting Cognitive Impairments by Agreeing on Interpretations of Linguistic Features"
authors:
- Zining Zhu
- Jekaterina Novikova
- Frank Rudzicz
date: "2019-07-27T00:00:00Z"
doi: 10.18653/v1/n19-1146

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proc. of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics, NAACL*
publication_short: NAACL 2019

abstract: "Linguistic features have shown promising applications for detecting various cognitive impairments. To improve detection accuracies, increasing the amount of data or the number of linguistic features have been two applicable approaches. However, acquiring additional clinical data can be expensive, and hand-crafting features is burdensome. In this paper, we take a third approach, proposing Consensus Networks (CNs), a framework to classify after reaching agreements between modalities. We divide linguistic features into non-overlapping subsets according to their modalities, and let neural networks learn low-dimensional representations that agree with each other. These representations are passed into a classifier network. All neural networks are optimized iteratively. In this paper, we also present two methods that improve the performance of CNs. We then present ablation studies to illustrate the effectiveness of modality division. To understand further what happens in CNs, we visualize the representations during training. Overall, using all of the 413 linguistic features, our models significantly outperform traditional classifiers, which are used by the state-of-the-art papers."

# Summary. An optional shortened abstract.
summary: "In this paper, we propose Consensus Networks, a framework to classify after reaching agreement across modalities. Our models significantly outperform traditional classifiers, which are used by the state-of-the-art papers."

tags:
- NAACL
featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/1808.06570
url_pdf: https://www.aclweb.org/anthology/N19-1146.pdf
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---