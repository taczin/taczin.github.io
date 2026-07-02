---
title: 'Your LLM Has a Passport: Investigating Brand Origin Geographic Bias in E-Commerce Rankings'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Filippo Betello
  - Paul Missault
  - admin
  - Maryna Beliuha

date: '2026-06-25T00:00:00Z'
doi: '10.1145/3805689.3806438'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In *Proceedings of the 2026 ACM Conference on Fairness, Accountability, and Transparency*, pp. 8089-8106'
publication_short: In *FAccT '26*

abstract: 'Large Language Models (LLMs) have recently demonstrated strong zero-shot ranking capabilities in Information Retrieval (IR). However, their deployment in e-commerce raises concerns about fairness, particularly when geographic biases influence product visibility. This paper examines how brand origin and user location affect LLM-based rankings across three models developed by companies headquartered in different regions: Llama in the US, Mistral in Europe, and Qwen in China. Using the Amazon Shopping Queries Dataset, we evaluate the impact of brand information on rankings under three conditions: (i) no brand location context, (ii) explicit brand origin, and (iii) explicit user location. Our evaluation combines standard IR metrics (NDCG) with list similarity measures (Jaccard, FRBO) and geographic coverage of top-K results. Our analysis reveals systematic differences: Mistral favors European brands, Qwen exhibits strong North American bias, and Llama remains comparatively balanced. Providing brand origin information alters rankings, with sensitivity varying across models, while user location exerts the strongest effect, shifting continental representation in Qwen by up to 59%. Despite these biases, all models maintain competitive ranking performance. These findings highlight the risks of geographic skew in LLM-driven IR systems and underscore the need for fairness-aware ranking pipelines in e-commerce. By uncovering how LLMs encode and amplify geographic preferences, this study provides actionable insights for both researchers and practitioners working toward more transparent and equitable retrieval systems.'

# Summary. An optional shortened abstract.
summary: 'We show that LLM-based e-commerce rankers (Llama, Mistral, Qwen) exhibit systematic geographic bias favoring brands and continents tied to their developers'' home region, with user-location context having the strongest effect on rankings.'

tags:
  - LLM Ranking
  - Geographical Bias
  - E-Commerce Ranking

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1145/3805689.3806438'
url_video: ''

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
slides: ''
---
