---
title: 'Natural Question Generation using Transformers and Reinforcement Learning'
authors:
- Sneha Balasubramoni

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: '2022-12-01T00:00:00Z'
doi: '10.1109/OCIT56763.2022.00061'

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '2022 OITS International Conference on Information Technology (OCIT)'
# publication_short: ""

abstract: Natural Question Generation (NQG) is among the most popular open research problems in Natural Language Processing (NLP) alongside Neural Machine Translation, Open Domain Chatbots, etc. Among the many approaches taken up to solve this problem, neural networks have been deemed the benchmark in this particular research area. This paper aims at adopting a generator - evaluator framework in a neural network architecture to allow additional focus on the context of the content used for framing a question. The generator uses NLP architectures like transformers (T5) to generate a question given a context while the evaluator uses Reinforcement Learning (RL) to check the correctness of the generated question. The involvement of RL has improved the results (as shown in Table 2), and there is increased computational efficiency as the training is coupled with the policy of RL. This turns the problem into a reinforcement learning task and allows for the generation of a wide range of questions for the same context-answer pair. The given algorithm is tested on the benchmark dataset - SQuAD with BLEU score as the evaluation metric.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Natural Question Generation
- Transformers
- Reinforcement Learning
- SQuAD Dataset
- BLEU Score

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/Sneha421/Question-Generation-NLP-RL'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

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
