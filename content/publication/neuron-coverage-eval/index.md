---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Is Neuron Coverage a Meaningful Measure for Testing Deep Neural Networks?"
authors: [
	"[Fabrice Harel-Canada](/)", 
	"[Lingxiao Wang](https://scholar.google.com/citations?user=VPyxd6kAAAAJ&hl)",
	"[Muhammad Ali Gulzar](http://web.cs.ucla.edu/~gulzar/)",
	"[Quanquan Gu](http://web.cs.ucla.edu/~qgu/)",
	"[Miryung Kim](http://web.cs.ucla.edu/~miryung/)"
]
date: 2020-07-30T20:09:19-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-30T20:09:19-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1", "3"]

# Publication name and optional abbreviated publication name.
publication: "Is Neuron Coverage a Meaningful Measure for Testing Deep Neural Networks?"
publication_short: ""

abstract: "Recent effort to test deep learning systems has produced an intuitive and compelling test criterion called neuron coverage (NC), which resembles the notion of traditional code coverage. NC measures the proportion of neurons activated in a neural network and it is implicitly assumed that increasing NC improves the quality of a test suite. In an attempt to automatically generate a test suite that increases NC, we design a novel diversity promoting regularizer that can be plugged into existing adversarial attack algorithms. We then assess whether such attempts to increase NC could generate a test suite that (1) detects adversarial attacks successfully, (2) produces natural inputs, and (3) is unbiased to particular class predictions. Contrary to expectation, our extensive empirical evaluation finds that increasing NC actually makes it harder to generate an effective test suite: higher neuron coverage leads to fewer defects detected, less natural inputs, and more biased prediction preferences. Our results invoke skepticism that neuron coverage may not be a meaningful measure for testing deep neural networks and call for a new test generation technique that considers defect detection, naturalness, and output impartiality in tandem."

# Summary. An optional shortened abstract.
summary: ""

tags: ["se4ml", "se", "ml", "testing", "neuron coverage", "empirical study"]
categories: ["ESEC/FSE"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "Is_Neuron_Coverage_a_Meaningful_Measure_for_Testing_Deep_Neural_Networks (preprint).pdf"
url_code: "https://github.com/fabriceyhc/nc_diversity_attacks"
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
