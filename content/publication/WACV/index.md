---
title: 'Aligned Dense Supervision for Full-Range Monocular Detection of Human Body Meshes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tiange Xiang
  - admin
  - Jun Liu
  - Dong Huang

date: '2022-07-016T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE Winter Conference on Applications of Computer Vision (WACV). (Manuscript)*
# publication_short: In *ROBIO*

abstract: "The flourishing success of Deep Neural Networks (DNNs) in RGB-input perception tasks has opened unbounded possibilities for non-RGB-input perception tasks, such as object detection from wireless signals, point-clouds, and infrared images. Comparing to the matured development pipeline of RGB-input (source modality) models, developing non-RGB-input (target-modality) models from scratch poses excessive challenges in the modality-specific network design/training tricks and labor in target-modality annotation. In this paper, we propose AdveRsarial Calibration (ARC), an efficient pipeline for calibrating target-modality inputs to the DNN models developed on the source modality. Instead of designing target-modality-specific models from scratch, we compose a target-modality-input model by adding a small calibrator module ahead of a pre-trained source-modality model. In training the target-modality model, ARC leverages (1) prior knowledge adversarially sampled from the source-modality model and (2) paired (target, source) modality data with zero or a few (10%) manual annotations. We demonstrate the effectiveness of ARC by composing the WiFi-input, Lidar-input, and Thermal-Infrared-input models from the pre-trained RGB-input models respectively."

# Summary. An optional shortened abstract.
summary: In this paper, an improved network architecture is proposed for learning and generation of personal hand-writing style fonts based on small character set.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/WACV/ADS.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
