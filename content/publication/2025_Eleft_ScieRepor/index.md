---
abstract: "Lithic use-wear analysis examines micro- and macroscopic traces on tool surfaces resulting from human use and post-depositional processes. Polish, formed through surface abrasion with different materials, is a key diagnostic feature that is increasingly analyzed using machine learning to enhance automation and standardization. However, further research is needed to explore whether deep learning approaches, in particular, can be effectively applied to use-wear analysis and to determine the optimal surface area size (e.g., patch size and microscope objectives) and model architecture (custom vs. pre-trained) for achieving the best results. This study employs convolutional neural networks (CNNs) to classify experimental polish based on contact material (wood, hide, bone) and use intensity, while also assessing optimal imaging and analytical parameters. The results of this exploratory study suggest that CNNs may effectively identify polish from bone and hide but perform less effectively with wood. The models also successfully distinguish between polish formed by short- and long-term use. Custom models outperformed pre-trained ones, particularly when using images that captured smaller areas of the tool’s surface, suggesting that bigger surface areas may lack the necessary information for optimal results. These findings underscore the need to expand use-wear datasets in terms of size and variability and optimize CNN architectures and workflows."

authors:
- Eanastasia Eleftheriadou
- et al.

date: "2025"
doi: "https://doi.org/10.1038/s41598-025-18179-4"

featured: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
publication: "*Nature Scientific Reports* (2025)"
publication_short: ""
publication_types:
- 2
publishDate: "2025-10-31T00:00:00Z"
summary: In this study, we used convolutional neural networks (CNNs) to try and automate the classification of polish traces on stone tools — basically, the shiny or smooth spots that develop on tools from use-wear (e.g., from cutting wood, hide, or bone). We set up experiments with known contact materials (wood, hide, bone) and different use-intensity durations. We also experimented with different imaging parameters (like microscope objective magnification, patch size of image segments) and compared different model architectures (custom CNN vs pre-trained models like ResNet50). We looked into the following questions:
* Whether a CNN can reliably tell the difference between polish made by contact with bone, hide or wood.
* Whether the duration of use (short term vs long term) affects how easily the model classifies polish
* How the imaging setup and model design affect performance (does using a smaller patch of the tool surface versus a larger one matter? Which objective magnification works best? Does a model trained from scratch outperform one that is pre-trained?).

We found that CNN approach can classify polish from bone and hide quite well, but struggles more with wood.  And also, the models were also able to distinguish polish from short-duration use versus longer use. We also emphasise that to really make this kind of approach robust, the datasets need to be much larger and more varied (different raw materials, contact materials, use contexts) and that imaging/analysis workflows should be optimised. It shows that deep learning has real promise in helping archaeologists analyse use-wear on tools in a more automated, standardised way — which could reduce human bias and increase repeatability. But it also cautions that there are still big challenges: small datasets, limited raw-material/usage variation, and model/generalisation issues mean we’re not yet at the point of “plug-and-play” ML for use-wear. For other researchers (working on archaeological objects, use-wear, materials) this paper suggests that combining controlled experiments + imaging + ML could open new lines of investigation, but we all need to pay attention to dataset design, imaging setup, and model choice.



tags:
- Use-wear analysis
- Raw material
- Experimental archaeology
- Machine Learning
featured: false

title: "Classifying polish in use-wear analysis with convolutional neural networks"

url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
