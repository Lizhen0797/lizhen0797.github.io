---
title: "Blockchain-Based Practical and Privacy-Preserving Federated Learning with Verifiable Fairness"
authors:
- Zhang Yitian
- Tang Yuming
- Zhang Zijian
- Li Meng
- admin
- Khan Salabat
- Chen Huaping
- Cheng Guoqiang
author_notes:
- "Equal contribution"
- "Equal contribution"
- ""
- ""
- "Corresponding author"
date: "2023-02-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Mathematics, 11*(5)"
publication_short: ""

abstract: Federated learning (FL) has been widely used in both academia and industry all around the world. FL has advantages from the perspective of data security, data diversity, real-time continual learning, hardware efficiency, etc. However, it brings new privacy challenges, such as membership inference attacks and data poisoning attacks, when parts of participants are not assumed to be fully honest. Moreover, selfish participants can obtain others’ collaborative data but do not contribute their real local data or even provide fake data. This violates the fairness of FL schemes. Therefore, advanced privacy and fairness techniques have been integrated into FL schemes including blockchain, differential privacy, zero-knowledge proof, etc. However, most of the existing works still have room to enhance the practicality due to our exploration. In this paper, we propose a Blockchain-based Pseudorandom Number Generation (BPNG) protocol based on Verifiable Random Functions (VRFs) to guarantee the fairness for FL schemes. Next, we further propose a Gradient Random Noise Addition (GRNA) protocol based on differential privacy and zero-knowledge proofs to protect data privacy for FL schemes. Finally, we implement both two protocols on Hyperledger Fabric and analyze their performance. Simulation experiments show that the average time that proof generation takes is 18.993 s and the average time of on-chain verification is 2.27 s under our experimental environment settings, which means the scheme is practical in reality.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false
selected: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/2227-7390/11/5/1091/htm
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).