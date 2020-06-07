---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Automatic Facial Landmark Localization in Clinical Populations--Improving Model Performance with a Small Dataset"
authors: ["Diego", "Babak", "Tessa", "Yana"]
date: 2020-03-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "_Submitted to_ Journal of Neuroengineering"
publication_short: ""

abstract: "
**Background** <br>

Automatic facial landmark localization in videos is an important first step in many computer vision applications, including the objective assessment of orofacial function. Convolutional neural networks (CNN) for facial landmarks localization are typically trained on faces of healthy and young adults, so model performance is inferior when applied to faces of older adults or people with diseases that affect facial movements, a phenomenon known as algorithmic bias. Fine-tuning pre-trained CNN models with representative data is a well-known technique used to reduce algorithmic bias and improve performance on clinical populations. However, the question of how much data is needed to properly fine-tune the model remains.  

<br>**Methods** <br>

In this paper, we fine-tuned a popular CNN model for automatic facial landmarks localization using different number of manually annotated photographs from patients with facial palsy and evaluated the effects of the number of photographs used for model fine-tuning in the model performance by computing the normalized root mean squared error between the facial landmarks positions predicted by the model and those provided by manual annotators. Furthermore, we studied the effect of annotator bias by fine-tuning and evaluating the model with data provided by multiple annotators. 

<br>**Results** <br>

Our results showed that fine-tuning the model with as little as 8 photographs from a single patient significantly improved the model performance on other individuals from the same clinical population, and that the best performance was achieved by fine-tuning the model with 320 photographs from 40 patients. Using more photographs for fine-tuning did not improve the model performance further. Regarding the annotator bias, we found that fine-tuning a CNN model with data from one annotator resulted in models biased against other annotators; our results also showed that this effect can be diminished by averaging data from multiple annotators.

<br>**Conclusions** <br>

It is possible to remove the algorithmic bias of a\textbf{depth} CNN model for automatic facial landmark localization using data from only 40 participants (total of 320 photographs). These results pave the way to future clinical applications of CNN models for the automatic assessment of orofacial function in different clinical populations, including patients with Parkinson’s disease and stroke."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Facial Analysis", "Fairnes in AI", "Facial Palsy", "Deep-learning"]
categories: ["Facial Analysis"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.researchsquare.com/article/rs-19405/v1
#url_code:
#url_dataset:
#url_poster:
#url_project:
#url_slides:
#url_source:
#url_video:

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
