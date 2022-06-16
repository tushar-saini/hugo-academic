---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Modelling Particulate Matter Using Multivariate and Multistep Recurrent Neural Networks"
authors: ["Tushar Saini", "Pratik Chaturvedi", "Varun Dutt"]
date: 2021-12-09T22:33:42+05:30
doi: "https://doi.org/10.3389/fenvs.2021.752318"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-21T22:33:42+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers In Environmental Science"
publication_short: "Front. Environ. Sci"

abstract: "Air quality is a major problem in the world, having severe health implications. Long-term exposure to poor air quality causes pulmonary and cardiovascular diseases. Several studies have also found that deteriorating air quality also causes substantial economic losses. Thus, techniques that can forecast air quality with higher accuracy may help reduce health and economic consequences. Prior research has utilized state-of-the-art artificial neural network and recurrent neural network models for forecasting air quality. However, a comprehensive investigation of different architectures of recurrent neural network, especially LSTMs and ensemble techniques, has been less explored. Also, there have been less explorations of long-term air quality forecasts via these methods exists. This research proposes the development and calibration of recurrent neural network models and their ensemble, which can forecast air quality in terms of PM<sub>2.5</sub> concentration 6 hours ahead in time. For forecasting air quality, a vanilla-LSTM, a stack-LSTM, a bidirectional-LSTM, a CNN-LSTM, and an ensemble of individual LSTM models were trained on the UCI Machine Learning Beijing dataset. Data were split into two parts, where 80% of data were used for training the models, while the remaining 20% were used for validating the models. For comparative analysis, four regression losses were calculated, namely root mean squared error, mean absolute percentage error, mean absolute error and Pearson’s correlation coefficient. Results revealed that among all models, the ensemble model performed the best in predicting the PM<sub>2.5</sub> concentrations. Furthermore, the ensemble model outperformed other models reported in literature by a long margin. Among the individual models, the bidirectional-LSTM performed the best. We highlight the implications of this research on long-term forecasting of air quality via recurrent and ensemble techniques."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
