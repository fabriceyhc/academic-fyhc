---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sibylvariant Transformations for Robust Text Classification"
# authors: [
# 	"[Fabrice Harel-Canada](/)", 
# 	"[Lingxiao Wang](https://scholar.google.com/citations?user=VPyxd6kAAAAJ&hl)",
# 	"[Muhammad Ali Gulzar](http://web.cs.ucla.edu/~gulzar/)",
# 	"[Quanquan Gu](http://web.cs.ucla.edu/~qgu/)",
# 	"[Miryung Kim](http://web.cs.ucla.edu/~miryung/)"
# ]
authors: [
	"Fabrice Harel-Canada", 
	"Muhammad Ali Gulzar",
	"Nanyun Peng",
	"Miryung Kim"
]
date: 2022-05-22T20:09:19-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-01T20:09:19-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Findings of the Association for Computational Linguistics: ACL-IJCNLP 2022, Dublin, Ireland, 2022."
publication_short: "In Findings of ACL"

abstract: "The vast majority of text transformation techniques in NLP are inherently limited in their ability to expand input space coverage due to an implicit constraint to preserve the original class label. In this work, we propose the notion of sibylvariance (SIB) to describe the broader set of transforms that relax the label-preserving constraint, knowably vary the expected class, and lead to significantly more diverse input distributions. We offer a unified framework to organize all data transformations, including two types of SIB: (1) Transmutations convert one discrete kind into another, (2) Mixture Mutations blend two or more classes together. To explore the role of sibylvariance within NLP, we implemented 41 text transformations, including several novel techniques like Concept2Sentence and SentMix. Sibylvariance also enables a unique form of adaptive training that generates new input mixtures for the most confused class pairs, challenging the learner to differentiate with greater nuance. Our experiments on six benchmark datasets strongly support the efficacy of sibylvariance for generalization performance, defect detection, and adversarial robustness."

# Summary. An optional shortened abstract.
summary: ""

tags: ["data augmentation", "robustness", "empirical study", "pytorch"]
categories: ["Findings of ACL"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "sibyl.pdf"
url_code: "https://github.com/fabriceyhc/Sibyl"
# url_dataset:
url_poster: "sib_poster.pdf"
# url_project:
url_slides: "sib_slides.pdf"
# url_source:
url_video: "sib_video.mp4"

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
