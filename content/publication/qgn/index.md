---
title: 'Query-driven Generative Network for Document Information Extraction in the Wild'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haoyu Cao
  - Jiefeng Ma
  - et al

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-10-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Thirtieth ACM International Conference on Multimedia*
publication_short: In *ACMMM-2022 (Oral)*

abstract: This paper focuses on solving Document Information Extraction (DIE) in the wild problem, which is rarely explored before. In contrast to existing studies mainly tailored for document cases in known templates with predefined layouts and keys under the ideal input without OCR errors involved, we aim to build up a more practical DIE paradigm for real-world scenarios where input document images may contain unknown layouts and keys in the scenes of the problematic OCR results. To achieve this goal, we propose a novel architecture, termed Query-driven Generative Network (QGN), which is equipped with two consecutive modules, i.e., Layout Context-aware Module (LCM) and Structured Generation Module (SGM). Given a document image with unseen layouts and fields, the former LCM yields the value prefix candidates serving as the query prompts for the SGM to generate the final key-value pairs even with OCR noise. To further investigate the potential of our method, we create a new large-scale dataset, named LArge-scale STructured Documents (LastDoc4000), containing 4,000 documents with 1,511 layouts and 3,500 different keys. In experiments, we demonstrate that our QGN consistently achieves the best F1-score on the new LastDoc4000 dataset by at most 30.32% absolute improvement. A more comprehensive experimental analysis and experiments on other public benchmarks also verify the effectiveness and robustness of our proposed method for the wild DIE task.

# Summary. An optional shortened abstract.
summary: In contrast to existing studies mainly tailored for document cases in known templates with predefined layouts and keys, we aim to build up a more practical DIE paradigm for real-world scenarios in zero-shot setting and in the scenes of the problematic OCR results.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'gqn.pdf'
url_video: 'https://dl.acm.org/doi/abs/10.1145/3503161.3547877'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'An illustration of our proposed LCM stacked with L layers of LCB'
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
