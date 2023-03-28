---
title: 'An Open-Source Library of 2D-GMM-HMM Based on Kaldi Toolkit and Its Application to Handwritten Chinese Character Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiefeng Ma
  - Zirui Wang
  - Jun Du

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2021-03-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Image and Graphics 2021*
publication_short: In *ICIG-2021*

abstract: As an open source toolkit based on 1D-HMM framework, Kaldi toolkit is widely used in many signal processing tasks. However, when dealing with complex spatial structures, e.g. in image related tasks, 2D-HMM is more suitable since it allows free transition between hidden states in both horizontal and vertical directions. Although 2D-HMM framework has been proposed for years, there is still a lack of efficient open source toolkit for further research due to its complexity. In this paper we present a highly efficient code library of 2D-GMM-HMM based on Kaldi toolkit with implementation details. As a demonstration of its effectiveness, we apply 2D-GMM-HMM to handwritten Chinese character recognition (HCCR) task. The experiments on a 50-class HCCR task have proved that the 2D-GMM-HMM system has obvious advantages over the 1D-GMM-HMM system in terms of recognition accuracy and modeling precision. Moreover, the visual analysis shows that 2D-GMMHMM can well segment the Chinese characters into basic components such as radicals via the hidden states in both horizontal and vertical directions while 1D-GMM-HMM can only conduct the segmentation in the horizontal direction. The project code of 2D-GMM-HMM library and its recipe on HCCR is publicly available at https://github.com/jfmaUSTC/2DHMM.

# Summary. An optional shortened abstract.
summary: We present a highly efficient code library of 2D-GMM-HMM based on Kaldi toolkit and apply it to Handwritten Chinese Character Recognition (HCCR) task.. The visual analysis shows that 2D-GMMHMM can well segment the Chinese characters into basic components such as radicals via the hidden states in both horizontal and vertical directions

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '2dhmm.pdf'
url_code: 'https://github.com/jfmaUSTC/2DHMM'
url_poster: 'https://drive.google.com/file/d/11rFDpZl8czkuEdGhx7nCiBvfNoXmKsAL/view?usp=share_link'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '2D-GMM-HMM System'
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
