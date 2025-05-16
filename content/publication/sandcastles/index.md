---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sandcastles in the Storm: Revisiting the (Im)possibility of Strong Watermarking"
authors: [
	"Fabrice Y Harel-Canada", 
	"Boran Erol", 
	"Connor Choi", 
	"Jason Liu", 
	"Gary Jiarui Song", 
	"Nanyun Peng", 
	"Amit Sahai"
]
date: 2025-07-17T20:09:19-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-30T20:09:19-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025), Vienna, Austria. Association for Computational Linguistics."
publication_short: "In ACL"

abstract: "Watermarking AI-generated text is critical for combating misuse. Yet recent theoretical work argues that any watermark can be erased via random walk attacks that perturb text while preserving quality. However, such attacks rely on two key assumptions: (1) rapid mixing (watermarks dissolve quickly under perturbations) and (2) reliable quality preservation (automated quality oracles perfectly guide edits). Through large-scale experiments and human-validated assessments, we find mixing is slow: 100% of perturbed texts retain traces of their origin after hundreds of edits, defying rapid mixing. Oracles falter, as state-of-the-art quality detectors misjudge edits (77% accuracy), compounding errors during attacks. Ultimately, attacks underperform: automated walks remove watermarks just 26% of the time -- dropping to 10% under human quality review. These findings challenge the inevitability of watermark removal. Instead, practical barriers -- slow mixing and imperfect quality control -- reveal watermarking to be far more robust than theoretical models suggest. The gap between idealized attacks and real-world feasibility underscores the need for stronger watermarking methods and more realistic attack models."

# Summary. An optional shortened abstract.
summary: ""

tags: ["watermarking", "adversarial attacks", "quality oracle", "empirical study", "theoretical"]
categories: ["ACL"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "paper.pdf"
url_code: "https://github.com/fabriceyhc/sandcastles"
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

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
