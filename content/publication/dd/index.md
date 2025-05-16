---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Enhancing Substance Use Detection in Clinical Notes with Large Language Models"
authors: [
    'Fabrice Harel-Canada',
    'Anabel Salimian',
    'Brandon Moghanian',
    'Sarah Clingan',
    'Allan Nguyen',
    'Tucker Avra',
    'Michelle Poimboeuf',
    'Ruby Romero',
    'Arthur Funnell',
    'Panayiotis Petousis',
    'Michael Shin',
    'Nanyun Peng',
    'Chelsea L. Shover',
    'David Goodman-Meza'
]
date: 2025-05-15T20:09:19-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-30T20:09:19-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In Review"
publication_short: "In Review"

abstract: "Identifying substance use behaviors in electronic health records (EHRs) is challenging because critical details are often buried in unstructured notes that use varied terminology and negation, requiring careful contextual interpretation to distinguish relevant use from historical mentions or denials. Using MIMIC-III/IV discharge summaries, we created a large, annotated drug detection dataset to tackle this problem and support future systemic substance use surveillance. We then investigated the performance of multiple large language models (LLMs) for detecting eight substance use categories within this data. Evaluating models in zero-shot, few-shot, and fine-tuning configurations, we found that a fine-tuned model, Llama-DrugDetector-70B, outperformed others. It achieved near-perfect F1-scores (>=0.95) for most individual substances and strong scores for more complex tasks like prescription opioid misuse (F1=0.815) and polysubstance use (F1=0.917). These findings demonstrate that LLMs significantly enhance detection, showing promise for clinical decision support and research, although further work on scalability is warranted."

# Summary. An optional shortened abstract.
summary: ""

tags: ["epidemiology", "drug use", "substance use", "cocaine", "heroin", "methamphetamine", "benzodiazapines", "prescription opioids", "cannabis", "injection drug use"]
categories: ["In Review"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "paper.pdf"
url_code: "https://github.com/fabriceyhc/drugdetector"
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
