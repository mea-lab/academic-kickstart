---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Toward an automatic system for computer-aided assessment in facial palsy"
authors: ["Diego", "Yana", "Babak", "Joseph R. Dusseldorp", "Suresh Mohan", "Joana Tavares", "Martinus M. van Veen", "Emily Fortier", "Tessa", and Nate Jowett]
date: 2020-02-01
doi: "https://doi.org/10.1089/fpsam.2019.29000.gua"

# Schedule page publish date (NOT publication's date).
publishDate: 2020

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "_Facial Plastic Surgery & Aesthetic Medicine_, Vol. 2, No. 1, p. 42-49"
publication_short: ""

abstract: "
**Importance** <br> Quantitative assessment of facial function is challenging, and subjective grading scales such as House–Brackmann, Sunnybrook, and eFACE have well-recognized limitations. Machine learning (ML) approaches to facial landmark localization carry great clinical potential as they enable high-throughput automated quantification of relevant facial metrics from photographs and videos. However, the translation from research settings to clinical application still requires important improvements.
<br>
**Objective** <br> To develop a novel ML algorithm for fast and accurate localization of facial landmarks in photographs of facial palsy patients and utilize this technology as part of an automated computer-aided diagnosis system.
<br>
**Design, Setting, and Participants** <br> Portrait photographs of 8 expressions obtained from 200 facial palsy patients and 10 healthy participants were manually annotated by localizing 68 facial landmarks in each photograph and by 3 trained clinicians using a custom graphical user interface. A novel ML model for automated facial landmark localization was trained using this disease-specific database. Algorithm accuracy was compared with manual markings and the output of a model trained using a larger database consisting only of healthy subjects.
<br>
**Main Outcomes and Measurements** <br> Root mean square error normalized by the interocular distance (NRMSE) of facial landmark localization between prediction of ML algorithm and manually localized landmarks.
<br>
**Results**<br> Publicly available algorithms for facial landmark localization provide poor localization accuracy when applied to photographs of patients compared with photographs of healthy controls (NRMSE, 8.56 ± 2.16 vs. 7.09 ± 2.34, p ≪ 0.01). We found significant improvement in facial landmark localization accuracy for the facial palsy patient population when using a model trained with a relatively small number photographs (1440) of patients compared with a model trained using several thousand more images of healthy faces (NRMSE, 6.03 ± 2.43 vs. 8.56 ± 2.16, p ≪ 0.01).
<br>
**Conclusions and Relevance**<br> Retraining a computer vision facial landmark detection model with fewer than 1600 annotated images of patients significantly improved landmark detection performance in frontal view photographs of this population. The new annotated database and facial landmark localization model represent the first steps toward an automatic system for computer-aided assessment in facial palsy.
"

# Summary. An optional shortened abstract.
summary: ""

tags: ["Facial Analysis", "Computer-based diagnosis", "Facial Palsy"]
categories: ["Facial Analysis"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.liebertpub.com/doi/full/10.1089/fpsam.2019.29000.gua
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
