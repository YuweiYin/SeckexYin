---
title: 'UM4: Unified Multilingual Multiple Teacher-Student Model for Zero-Resource Neural Machine Translation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Jian Yang'
  - yuweiyin
  - 'Shuming Ma'
  - 'Dongdong Zhang'
  - 'Shuangzhi Wu'
  - 'Hongcheng Guo'
  - 'Zhoujun Li'
  - 'Furu Wei'

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-07-23T00:00:00Z'
doi: '10.24963/ijcai.2022/618'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence*
publication_short: In *IJCAI 2022*

abstract: Most translation tasks among languages belong to the zero-resource translation problem where parallel corpora are unavailable. Multilingual neural machine translation (MNMT) enables one-pass translation using shared semantic space for all languages compared to the two-pass pivot translation but often underperforms the pivot-based method. In this paper, we propose a novel method, named as Unified Multilingual Multiple teacher-student Model for NMT (UM4). Our method unifies source-teacher, target-teacher, and pivot-teacher models to guide the student model for the zero-resource translation. The source teacher and target teacher force the student to learn the direct source-target translation by the distilled knowledge on both source and target sides. The monolingual corpus is further leveraged by the pivot-teacher model to enhance the student model. Experimental results demonstrate that our model of 72 directions significantly outperforms previous methods on the WMT benchmark.

# Summary. An optional shortened abstract.
summary: 'UM4: Unified Multilingual Multiple Teacher-Student Model for Zero-Resource Neural Machine Translation'

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.ijcai.org/proceedings/2022/0618.pdf'
url_code: 'https://github.com/YuweiYin/UM4'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://yuweiyin.com/files/pdf/2022-07-23-IJCAI-UM4-Slides.pdf'
url_source: 'https://www.ijcai.org/proceedings/2022/618'
url_video: 'https://www.ijcai.org/proceedings/2022/video/618'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: '2022-07-23-IJCAI-UM4'
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

![picture](https://yuweiyin.com/files/img/2022-07-23-IJCAI-UM4.png)

- [Spotlight Video](https://ijcai-22.org/video/?vid=38986462) \| [Full Oral Video](https://ijcai-22.org/video/?vid=38984605)

```bibtex
@inproceedings{um4,
  title     = {UM4: Unified Multilingual Multiple Teacher-Student Model for Zero-Resource Neural Machine Translation},
  author    = {Yang, Jian and Yin, Yuwei and Ma, Shuming and Zhang, Dongdong and Wu, Shuangzhi and Guo, Hongcheng and Li, Zhoujun and Wei, Furu},
  booktitle = {Proceedings of the Thirty-First International Joint Conference on
               Artificial Intelligence, {IJCAI-22}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Lud De Raedt},
  pages     = {4454--4460},
  year      = {2022},
  month     = {7},
  note      = {Main Track},
  doi       = {10.24963/ijcai.2022/618},
  url       = {https://doi.org/10.24963/ijcai.2022/618},
}
```
