---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "An Online Low-Cost System for Air Quality Monitoring, Prediction, and Warning"
authors: ["Rishi Sharma", "Tushar Saini", "Praveen Kumar", "Ankush Pathania",
 "Khyathi Chitineni", "Pratik Chaturvedi", "Varun Dutt"]
date: 2019-12-09T22:07:18+05:30
doi: "https://doi.org/10.1007/978-3-030-36987-3_20"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-21T22:33:42+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In: Hung, D., D´Souza, M. (eds) Distributed Computing and Internet
  Technology. ICDCIT 2020. Lecture Notes in Computer Science, vol 11969.
  Springer, Cham."
publication_short: "In: <i>ICDCIT 2020"

abstract: "Air-quality is degrading in developing countries and there is an
  urgent need to monitor and predict air-quality online in real-time. Although
  offline air-quality monitoring using hand-held devices is common, online
  air-quality monitoring is still expensive and uncommon, especially in
  developing countries. The primary objective of this paper is to propose an
  online low-cost air-quality monitoring, prediction, and warning system
  (AQMPWS) which monitors, predicts, and warns about air-quality in real-time.
  The AQMPWS monitors and predict seven pollutants, namely, PM1.0, PM2.5, PM10,
  Carbon Monoxide, Nitrogen Dioxide, Ozone and Sulphur Dioxide. In addition, the
  AQMPWS monitors and predicts five weather variables, namely, Temperature,
  Pressure, Relative Humidity, Wind Speed, and Wind Direction. The AQMPWS has
  its sensors connected to two microcontrollers in a Master-Slave configuration.
  The slave sends the data to the API in the cloud through an HTTP GET request
  via a GSM Module. A python-based web-application interacts with the API for
  visualization, prediction, and warning. Results show that the AQMPWS monitor
  different pollutants and weather variables within range specified by pollution
  control board. In addition, the AQMPWS predict the value of the pollutants and
  weather variables for the next 30-min given the current values of these
  pollutants and weather variables using an ensemble model containing a
  multilayer-perceptron and long short-term memory model. The AQMPWS is also
  able to warn stakeholders when any of the seven pollutants breach pre-defined
  thresholds. We discuss the implications of using AQMPWS for air-quality
  monitoring in the real-world. "

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
