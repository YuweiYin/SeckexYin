---
title: 'HanoiT: Enhancing Context-aware Translation via Selective Context'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Jian Yang'
  - yuweiyin
  - 'Shuming Ma'
  - 'Liqun Yang'
  - 'Hongcheng Guo'
  - 'Haoyang Huang'
  - 'Dongdong Zhang'
  - 'Yutao Zeng'
  - 'Zhoujun Li'
  - 'Furu Wei'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-04-15T00:00:00Z'
doi: '10.1007/978-3-031-30675-4_34'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Database Systems for Advanced Applications DASFAA 2023*
publication_short: In *DASFAA 2023*

abstract: Context-aware neural machine translation aims to use the document-level context to improve translation quality. However, not all words in the context are helpful. The irrelevant or trivial words may bring some noise and distract the model from learning the relationship between the current sentence and auxiliary context. To mitigate this problem, we propose a novel end-to-end encoder-decoder model with a layer-wise selection mechanism to sift and refine the long document context. To verify the effectiveness of our method, extensive experiments and extra quantitative analysis are conducted on four document-level machine translation benchmarks. The experimental results demonstrate that our model significantly outperforms previous models on all datasets via the soft selection mechanism.

# Summary. An optional shortened abstract.
summary: 'HanoiT: Enhancing Context-aware Translation via Selective Context'

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2301.06825.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1007/978-3-031-30675-4_34'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: '2022-12-09-EMNLP-CROP'
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

![picture](https://yuweiyin.com/files/img/2023-04-15-DASFAA-HanoiT.png)

```bibtex
@inproceedings{hanoit,
  title = "HanoiT: Enhancing Context-aware Translation via Selective Context",
  author = "Yang, Jian and Yin, Yuwei and Ma, Shuming and Yang, Liqun and Guo, Hongcheng and Huang, Haoyang and Zhang, Dongdong and Zeng, Yutao and Li, Zhoujun and Wei, Furu",
  booktitle = "Database Systems for Advanced Applications",
  publisher = "Springer Nature Switzerland",
  pages = "471--486",
  year = "2023",
  month = "4",
  url = "https://doi.org/10.1007/978-3-031-30675-4_34",
  address = "Cham",
}
```
