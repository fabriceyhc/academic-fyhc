---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Human-in-the-Loop Synthetic Text Data Inspection with Provenance Tracking"
authors: [
	"Hong Jin Kang*", 
	"Fabrice Harel-Canada*", 
	"Muhammad Ali Gulzar",
	"Violet Peng",
	"Miryung Kim"
]
date: 2024-06-16T20:09:19-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-30T20:09:19-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Findings of the Association for Computational Linguistics: NAACL 2024, pages 3118–3129, Mexico City, Mexico. Association for Computational Linguistics."
publication_short: "In Findings of NAACL"

abstract: "Data augmentation techniques apply transformations to existing texts to generate additional data. The transformations may produce low-quality texts, where the meaning of the text is changed and the text may even be mangled beyond human comprehension. Analyzing the synthetically generated texts and their corresponding labels is slow and demanding. To winnow out texts with incorrect labels, we develop INSPECTOR, a human-in-the-loop data inspection technique. INSPECTOR combines the strengths of provenance tracking techniques with assistive labeling. INSPECTOR allows users to group related texts by their transformation provenance, i.e., the transformations applied to the original text, or feature provenance, the linguistic features of the original text. For assistive labeling, INSPECTOR computes metrics that approximate data quality, and allows users to compare the corresponding label of each text against the predictions of a large language model. In a user study, INSPECTOR increases the number of texts with correct labels identified by 3X on a sentiment analysis task and by 4X on a hate speech detection task. The participants found grouping the synthetically generated texts by their common transformation to be the most useful technique. Surprisingly, grouping texts by common linguistic features was perceived to be unhelpful. Contrary to prior work, our study finds that no single technique obviates the need for human inspection effort. This validates the design of INSPECTOR which combines both analysis of data provenance and assistive labeling to reduce human inspection effort."

# Summary. An optional shortened abstract.
summary: ""

tags: ["testing", "human study", "empirical study", "provenance", "active learning", "hci", "human-in-the-loop"]
categories: ["NAACL"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "paper.pdf"
url_code: "https://github.com/UCLA-SEAL/ProvenanceInspector"
# url_dataset:
# url_poster:
# url_project:
url_slides: "slides.pdf"
# url_source:
url_video: "https://aclanthology.org/2024.findings-naacl.197.mp4"

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
