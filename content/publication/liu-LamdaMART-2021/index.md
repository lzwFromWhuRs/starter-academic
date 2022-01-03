---
title: "Detecting home countries of social media users with machine-learned ranking approach: a case study in Hong Kong"

authors:
- admin
- Wenzhong Shi
- Anshu Zhang

# author_notes:
# - "Equal contribution"
# - "Equal contribution"



date: "2021-08-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Geography*, 134 (2021): 102532"
publication_short: "*Applied Geography*, 134 (2021): 102532"


abstract: Inferring individual's home country from geotagged footprints is widely applied in human mobility research. Previous studies mainly used simple empirical methods that are based on intuitive hypothetical assumptions. Because the exact relationships between users' home countries and geotagged footprints haven't be quantitatively revealed, empirical methods based on human intuitions and past experiences are used for rough approximation. In this study, we propose a machine-learning approach for the task of home country detection, by formulating the task as a query-ranking problem and using a machine-learned ranking model for problem solving. The used model is a Multiple Additive Regression Trees framework that aims to rank regions in specific orders and the region ranked first is designated as the home country. Our approach is data-driven and can adaptively learn the unknown function from input (geotagged footprints) to output (user's home country), thus alleviating the bias introduced by previous empirical methods. We conduct experiments with real-world datasets, and results demonstrate that our approach achieves better performance than previous empirical methods. The model's parameter sensitivity is also investigated, and results show that user's origin may be a factor affecting the approach's performance and that our approach achieves robust good performance with various parameter settings.




# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
#- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S014362282100148X
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# slides: example



# {{% alert note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /alert %}}

# {{% alert note %}}
# Click the *Slides* button above to demo Academic's Markdown slides feature.
# {{% /alert %}}

# Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).


---


