---
title: 'Multilingual Agreement for Multilingual Neural Machine Translation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Jian Yang'
  - yuweiyin
  - 'Shuming Ma'
  - 'Haoyang Huang'
  - 'Dongdong Zhang'
  - 'Zhoujun Li'
  - 'Furu Wei'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-08-02T00:00:00Z'
doi: '10.18653/v1/2021.acl-short.31'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics*
publication_short: In *ACL 2021*

abstract: Although multilingual neural machine translation (MNMT) enables multiple language translations, the training process is based on independent multilingual objectives. Most multilingual models can not explicitly exploit different language pairs to assist each other, ignoring the relationships among them. In this work, we propose a novel agreement-based method to encourage multilingual agreement among different translation directions, which minimizes the differences among them. We combine the multilingual training objectives with the agreement term by randomly substituting some fragments of the source language with their counterpart translations of auxiliary languages. To examine the effectiveness of our method, we conduct experiments on the multilingual translation task of 10 language pairs. Experimental results show that our method achieves significant improvements over the previous multilingual baselines.

# Summary. An optional shortened abstract.
summary: 'Multilingual Agreement for Multilingual Neural Machine Translation'

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2021.acl-short.31.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://aclanthology.org/2021.acl-short.31/'
url_video: 'https://aclanthology.org/2021.acl-short.31.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: '2021-08-02-ACL-Multilingual-Agreement'
#   focal_point: ''
#   preview_only: false

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

![picture](https://yuweiyin.com/files/img/2021-08-02-ACL-Multilingual-Agreement.png)

```bibtex
@inproceedings{agreement,
  title     = "Multilingual Agreement for Multilingual Neural Machine Translation",
  author    = "Yang, Jian and Yin, Yuwei and Ma, Shuming and Huang, Haoyang and Zhang, Dongdong and Li, Zhoujun and Wei, Furu",
  booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 2: Short Papers)",
  publisher = "Association for Computational Linguistics",
  url       = "https://aclanthology.org/2021.acl-short.31",
  doi       = "10.18653/v1/2021.acl-short.31",
  pages     = "233--239"
}
```
