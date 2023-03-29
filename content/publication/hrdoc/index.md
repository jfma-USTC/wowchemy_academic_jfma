---
title: 'HRDoc: Dataset and Baseline Method Toward Hierarchical Reconstruction of Document Structures'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiefeng Ma
  - Jun Du
  - Pengfei Hu
  - Zhenrong Zhang
  - et al

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-03-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Thirty-Seventh AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI-2023 (Oral)*

abstract: The problem of document structure reconstruction refers to converting digital or scanned documents into corresponding semantic structures. Most existing works mainly focus on splitting the boundary of each element in a single document page, neglecting the reconstruction of semantic structure in multi-page documents. This paper introduces hierarchical reconstruction of document structures as a novel task suitable for NLP and CV fields. To better evaluate the system performance on the new task, we built a large-scale dataset named HRDoc, which consists of 2,500 multi-page documents with nearly 2 million semantic units. Every document in HRDoc has line-level annotations including categories and relations obtained from rule-based extractors and human annotators. Moreover, we proposed an encoder-decoder-based hierarchical document structure parsing system (DSPS) to tackle this problem. By adopting a multi-modal bidirectional encoder and a structure-aware GRU decoder with soft-mask operation, the DSPS model surpass the baseline method by a large margin. All scripts and datasets will be made publicly available at https://github.com/jfma-USTC/HRDoc.

# Summary. An optional shortened abstract.
summary: We built a large-scale dataset named HRDoc, which consists of 2,500 multi-page documents with nearly 2 million semantic units. Moreover, we proposed an encoder-decoder-based hierarchical document structure parsing system (DSPS) to tackle document structure reconstruction task. Code and dataset are available at https://github.com/jfma-USTC/HRDoc.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'hrdoc.pdf'
url_code: 'https://github.com/jfma-USTC/HRDoc'
url_dataset: 'https://github.com/jfma-USTC/HRDoc#release-issues'
url_poster: 'https://drive.google.com/file/d/17diRMpzR37HpzXG4h6azZQqTJXx9NYCD/view?usp=share_link'
url_project: 'https://github.com/jfma-USTC/HRDoc'
url_slides: 'https://drive.google.com/file/d/1A3vUsA6deeL1keU7llPOoS7s_y5qQwG9/view?usp=share_link'
url_video: 'https://drive.google.com/file/d/1XzWVpnpm-UsHYgi0jq2gGSGr-GZ6E497/view?usp=share_link'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'The processing procedure of hierarchical document structure reconstruction task. '
  focal_point: ''
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
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
