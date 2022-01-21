---
title: "Supporting Evidence Retrieval with Cross-Sentence Coupling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Meng-Tse Wu
- Keh-Yih Su

# Author notes (optional)
author_notes:
- "First Author"
- "Second Author"
- "Third Author"

date: "2020-10-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Technologies and Applications of Artificial Intelligence*
publication_short: In *TAAI*

abstract: This paper proposes a novel approach to identify the supporting evidence (SE) sentence (within a related document) that has low lexicon recall rate with the given question passage. Previous approaches such as BERT mainly identify SE sentences via implic- itly measuring the text similarity between the question and each sentence in the related document. However, some SE sentences possess low recall rates because they have low word-overlapping with the question text. This situation frequently occurs when the complete information crosses more than one sentence. We thus propose a novel model that incorporates cross-sentence coupling between adjacent sentences. The experiments conducted on a Chinese QA data-set show the proposed model has made 2.1% EM improvement comparing with BERT baseline.

# Summary. An optional shortened abstract.
summary: 

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
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: 
  caption: 'At the TAAI Award Ceremony'
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
slides: example
---


Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
