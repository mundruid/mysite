---
title: "IoT Spy: Observability and Alerting for Internet of Things (IoT) Security"

event: BSides Atlanta 2022
event_url: https://pretalx.com/bsides-atlanta-2022/talk/UMQE97/

location: Atlanta, GA
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Observability vs monitoring and how observability is used for security with IoT spy.
abstract: Observability is the method of revealing the state and measuring attributes that characterize a system. Observability in information security has been prevalently synonymous to Splunk logs, metrics, and dashboards. Interestingly, a multitude of open source monitoring tools that are used for network telemetry can offer a holistic view of the security of an organization by deploying metrics, logs, flows, and structured data processing. The contributions of my talk are twofold. First I will introduce a modern, open source, observability stack, Telegraf-Influx-Grafana (TIG) and discuss what makes it a robust stack for security observability. Telegraf is an open source collector agent that is expandable, offers 200+ plugins, and can be scaled easily with multiple instances for streaming data. Influx Database (DB) is a powerful time series database that offers speed with time series processing, storing, and correlating. Grafana is a visualization tool that specializes in presenting time series with the user experience in mind. In the second part of my talk, I will present a use case of TIG stack for IoT security observability and alerting. I will demonstrate how one can measure, forecast, and alert for anomalies in IoT devices using TIG stack and a set of prevalent home devices such as security cameras, smart plugs, lights, and home assistants. This talk will demonstrate new techniques for security observability and will show the potential for a modern telemetry stack to improve the state of observing and measuring security.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-08-27T13:00:00Z"
date_end: "2022-08-27T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-07-20T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---