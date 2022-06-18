---
title: "Worth the wait? Time window feature optimization for intrusion detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Casey Wilson
- admin
- Anna Little

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2019 IEEE International Workshop on Big Data Analytics for Cyber Threat Hunting
publication_short: In IEEE Cyberhunt 2019

abstract: Time as a variable for generating features has been widely overlooked in Intrusion Detection System (IDS) research. Computer and network attacks are time series, where time is an important factor that may affect feature generation, and as a result, classification. Nevertheless, there has been little exploration on how to calibrate time for IDSs and attack classification techniques. In this paper we explore time windows as a technique for generating more effective and descriptive features for attack classification. We suggest a framework for feature generation and selection that uses Recursive Feature Elimination (RFE) and time window exploration. Our initial results when applying this framework indicate that there is up to 47% improvement of F1 scores in attack classification when attack features are generated over a variety of time windows, compared to a single, global time window. We find that features calculated over longer lengths of time may be more useful for detecting attacks than over shorter lengths of time. Our methods seem to be most effective at detecting DDoS attacks, particularly those that occur over medium or long durations of time.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/1QgkEauM0DQgWVti-qaWftDiJu6tIp8ePyX-V59HFOfY/edit?usp=sharing'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
