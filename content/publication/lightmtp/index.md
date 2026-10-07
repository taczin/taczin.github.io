---
title: 'LightMTP: Lightweight Latent Multi-Token Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Julie Kallini
  - Gerard de Melo
  - Chen Shani

date: '2026-10-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-10-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['manuscript']

# Publication name and optional abbreviated publication name.
publication: 'arXiv:2610.06031'
publication_short: ''

abstract: 'Next-token prediction (NTP) is the standard pretraining objective for large language models, yet it provides an explicit training signal only for the immediate next token, which can lead models to exploit local patterns instead of capturing longer-range structure and ideas. Multi-token prediction (MTP) addresses this by training models to predict several future tokens. However, existing MTP methods often introduce a large number of new parameters with limited improvements in downstream performance. Latent MTP approaches address this efficiency issue by encoding future tokens into a vector representation. However, these approaches usually rely on external helper models for future token encoding. We propose LightMTP, a lightweight, i.e., parameter-efficient, latent MTP approach that bootstraps the future token representations from the model''s own hidden states. Our two LightMTP variants extend supervision to more future tokens without requiring the additional computational overhead of conventional MTP nor the external supervision latent MTP normally relies on. LightMTP adds at most 1% extra parameters, retains better performance on general language modeling benchmarks, and achieves similar gains in planning, coding, and reasoning.'

# Summary. An optional shortened abstract.
summary: 'A parameter-efficient latent multi-token prediction objective that bootstraps future-token representations from the model''s own hidden states, adding at most 1% extra parameters while matching the gains of conventional MTP in planning, coding, and reasoning.'

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2610.06031'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2610.06031'
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
