---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Design and Validation of an Open-Source Closed-Loop Testbed for Artificial Pancreas Systems"
authors: 
- Xugui Zhou
- Maxfield Kouzel
- Haotian Ren
- Homa Alemzadeh

date: 2022-06-10T00:00:00+02:00

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-10T17:07:06+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "to appear in IEEE/ACM international conference on Connected Health: Applications, Systems and Engineering Technologies (CHASE)"
publication_short: "to appear in IEEE/ACM International Conference on CHASE"

abstract: "The development of a fully autonomous artificial pancreas system (APS) to independently regulate the glucose levels of a patient with Type 1 diabetes has been a long-standing goal of diabetes research. A significant barrier to progress is the difficulty of testing new control algorithms and safety features, since clinical trials are time- and resource-intensive. To facilitate ease of validation, we propose an open-source APS testbed by integrating APS controllers with two state-of-the-art glucose simulators and a novel fault injection engine. The testbed is able to reproduce the blood glucose trajectories of real patients from a clinical trial conducted over six months. We evaluate the performance of two closed-loop control algorithms (OpenAPS and Basal Bolus) using the testbed and find that more advanced control algorithms are able to keep blood glucose in a safe region 93.49% and 79.46% of the time on average, compared with 66.18% of the time for the clinical trial. The fault injection engine simulates the real recalls and adverse events reported to the U.S. Food and Drug Administration (FDA) and demonstrates the resilience of the controller in hazardous conditions. We used the testbed to generate 2.5 years of synthetic data representing 20 different patient profiles with realistic adverse event scenarios, which would have been expensive and risky to collect in a clinical trial. The proposed testbed is a valid tool that can be used by the research community to demonstrate the effectiveness of different control algorithms and safety features for APS."


# Summary. An optional shortened abstract.
# summary: "We formalize and study the problem of optimal allocation strategies for a (perfect) vaccine in the infinite-dimensional SIS model."


tags: []
categories: []
#featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2208.06479
url_dataset: https://github.com/UVA-DSA/ContextSafetyMonitorAPS/tree/master/simulationData
url_code: https://github.com/UVA-DSA/APS_TestBed
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
