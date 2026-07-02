---
title: 'Iterative Reranking as a Compute-Scaling Method for LLM-Based Rankers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dong Liu
  - Filippo Betello

date: '2026-03-29T00:00:00Z'
doi: '10.1007/978-3-032-21321-1_16'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'In *Advances in Information Retrieval*, pp. 111-117'
publication_short: In *ECIR 2026*

abstract: 'E-commerce search faces challenges such as sparse data and poor generalization from issues like multi-attribute resolution, multi-hop reasoning, and implicit intent. We propose iterative reranking as a compute-scaling strategy for LLM-based rankers, repeatedly applying listwise rankers to refine results by exploiting LLM non-determinism. Evaluated on three open datasets with three open-source LLMs, the method trades increased computation for consistently improved performance, yielding strong nDCG@40 gains on DL19, FutureQueryEval, and difficult Amazon query types. These findings show that iterative reranking is an effective inference-time scaling approach for LLM rankers. We make our code available (https://github.com/amazon-science/IterativeListwiseReranking).'

# Summary. An optional shortened abstract.
summary: 'We propose iterative reranking, a compute-scaling strategy that repeatedly applies listwise LLM rankers to exploit their non-determinism, yielding consistent nDCG gains across open datasets and LLMs.'

tags:
  - Information Retrieval
  - Large Language Models
  - Reranking
  - Search

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/amazon-science/IterativeListwiseReranking'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1007/978-3-032-21321-1_16'
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
