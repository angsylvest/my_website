---
title: "An empirical characterization of ODE models of swarm behaviors in common foraging scenarios"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- John Harwell

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-07-30T00:00:00Z" 
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: |
  There is a large class of real-world problems, such as warehouse transport, at different scales, swarm densities, etc., that can be characterized as Central Place Foraging Problems (CPFPs). We contribute to swarm engineering by designing an Ordinary Differential Equation (ODE) model that strives to capture the underlying behavioral dynamics of the CPFP in these application areas. Our simulation results show that a hybrid ODE modeling approach combining analytic parameter calculations and post-hoc (i.e., after running experiments) parameter fitting can be just as effective as a purely post-hoc approach to computing parameters via simulations, while requiring less tuning and iterative refinement. This makes it easier to design systems with provable bounds on behavior. Additionally, the resulting model parameters are more understandable because their values can be traced back to problem features, such as system size, robot control algorithm, etc. Finally, we perform real-robot experiments to further understand the limits of our model from an engineering standpoint.


# Summary. An optional shortened abstract.
summary: "We study the forward collective behavior problem: how to predict swarm behavior given a problem de- scription and high level characteristics of the robot control algorithm. We present a differential equation model of swarm behavior which does not require post- hoc parameter tuning or knowledge of the nature of the problem the swarm is working on to produce accurate predictions."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://link.springer.com/article/10.1007/s10514-023-10121-9'
url_slides: ''
url_source: 'https://link.springer.com/article/10.1007/s10514-023-10121-9'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
