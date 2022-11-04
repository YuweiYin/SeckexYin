---
title: 'Improving Multilingual Neural Machine Translation with Auxiliary Source Languages'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Weijia Xu'
  - yuweiyin
  - 'Shuming Ma'
  - 'Dongdong Zhang'
  - 'Haoyang Huang'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-11-07T00:00:00Z'
doi: '10.18653/v1/2021.findings-emnlp.260'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Findings of the Association for Computational Linguistics EMNLP 2021*
publication_short: In *EMNLP 2021 Findings*

abstract: Multilingual neural machine translation models typically handle one source language at a time. However, prior work has shown that translating from multiple source languages improves translation quality. Different from existing approaches on multi-source translation that are limited to the test scenario where parallel source sentences from multiple languages are available at inference time, we propose to improve multilingual translation in a more common scenario by exploiting synthetic source sentences from auxiliary languages. We train our model on synthetic multi-source corpora and apply random masking to enable flexible inference with single-source or bi-source inputs. Extensive experiments on Chinese/English-Japanese and a large-scale multilingual translation benchmark show that our model outperforms the multilingual baseline significantly by up to +4.0 BLEU with the largest improvements on low-resource or distant language pairs.

# Summary. An optional shortened abstract.
summary: Improving Multilingual Neural Machine Translation with Auxiliary Source Languages

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2021.findings-emnlp.260.pdf'
url_code: 'https://github.com/YuweiYin/MNMT_Aux_Src_Lang'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://aclanthology.org/2021.findings-emnlp.260/'
url_video: 'https://aclanthology.org/2021.findings-emnlp.260.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '2021-11-07-EMNLP-AuxSource'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
# slides: example
---

<!-- {{% callout note %}} -->
<!-- Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software. -->
<!-- {{% /callout %}} -->

<!-- {{% callout note %}} -->
<!-- Create your slides in Markdown - click the _Slides_ button to check out the example. -->
<!-- {{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<script> 
MathJax = {
  tex: {
    inlineMath: [['$', '$']],
    processEscapes: true
  }
};
</script>

![picture](https://yuweiyin.com/files/img/2021-11-07-EMNLP-AuxSource.png)

```bibtex
@inproceedings{auxiliary,
  title     = "Improving Multilingual Neural Machine Translation with Auxiliary Source Languages",
  author    = "Xu, Weijia and Yin, Yuwei and Ma, Shuming and Zhang, Dongdong and Huang, Haoyang",
  booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2021",
  publisher = "Association for Computational Linguistics",
  url       = "https://aclanthology.org/2021.findings-emnlp.260",
  doi       = "10.18653/v1/2021.findings-emnlp.260",
  pages     = "3029--3041",
}
```
