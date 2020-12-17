---
title: "Fundamental Tradeoffs between Invariance and Sensitivity to Adversarial Perturbations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Florian Tramer
- admin
- Nicholas Carlini
- Nicolas Papernot
- Joern-Henrik Jacobsen


# Author notes (optional)
# author_notes:


date: "2020-06-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-10"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML*

abstract: Adversarial examples are malicious inputs crafted to induce misclassification. Commonly studied sensitivity-based adversarial examples introduce semantically-small changes to an input that result in a different model prediction. This paper studies a complementary failure mode, invariance-based adversarial examples, that introduce minimal semantic changes that modify an input's true label yet preserve the model's prediction. We demonstrate fundamental tradeoffs between these two types of adversarial examples.
We show that defenses against sensitivity-based attacks actively harm a model's accuracy on invariance-based attacks, and that new approaches are needed to resist both attack types. In particular, we break state-of-the-art adversarially-trained and certifiably-robust models by generating small perturbations that the models are (provably) robust to, yet that change an input's class according to human labelers. Finally, we formally show that the existence of excessively invariant classifiers arises from the presence of overly-robust predictive features in standard datasets. 

# Summary. 
summary: This paper studies a complementary failure mode, invariance-based adversarial examples, that introduce minimal semantic changes that modify an input's true label yet preserve the model's prediction.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://proceedings.mlr.press/v119/tramer20a.html'
url_code: 'https://github.com/ftramer/Excessive-Invariance'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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


