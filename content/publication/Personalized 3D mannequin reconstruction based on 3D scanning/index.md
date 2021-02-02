---
title: "Personalized 3D mannequin reconstruction based on 3D scanning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Duan Li
- Ge Wu
- Taku Komura
- Dongliang Zhang
- Yueqi Zhong

# Author notes (optional)
author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2018-04-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Clothing Science and Technology*
publication_short: In *ICW*

abstract: Personalized customization is a new manufacturing trend in high-end products (e.g. senior
custom clothing).Traditional apparel customization (made-to-measure & bespoken) highly
depends on experienced tailors. A personalized mannequin is essential for apparel customization
using CAD technologies. Currently, a common method of reconstructing mannequin is based on
body measurements or body features. It only preserves the body size instead of preserving the
accurate user’s stature. However, the same human body measurement does not equal to the
same body shape. This may result in an unfit garment for the user. This paper proposes a novel
scanning-based pipeline to reconstruct a personalized mannequin, which preserves both body
size and body stature information. We first capture the body of a user via 3D scanning, and a
statistical body model is fit to the scanned data. This results in a skinned articulated model of
the user. The scanned body is then adjusted to be pose-symmetric via linear blending skinning.
The updated pose-symmetric body is then segmented to initialize the stature symmetry
processing. Finally, a slice-based method is proposed to generate a symmetric 3D mannequin.
The process of apparel customization can be easily digitalized with the help of the proposed
mannequin reconstruction system and the corresponding existing clothing CAD software.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Personalized 3D Mannequin Reconstruction Based on 3D Scanning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
