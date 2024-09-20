---
title: 'm3P: Towards Multimodal Multilingual Translation with Multimodal Prompt'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Jian Yang'
  - 'Hongcheng Guo'
  - yuweiyin
  - 'Jiaqi Bai'
  - 'Bing Wang'
  - 'Jiaheng Liu'
  - 'Xinnian Liang'
  - 'Linzheng Chai'
  - 'Liqun Yang'
  - 'Zhoujun Li'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation*
publication_short: In *LREC-COLING 2024*

abstract: 'Multilingual translation supports multiple translation directions by projecting all languages in a shared space, but the translation quality is undermined by the difference between languages in the text-only modality, especially when the number of languages is large. To bridge this gap, we introduce visual context as the universal language-independent representation to facilitate multilingual translation. In this paper, we propose a framework to leverage the multimodal prompt to guide the Multimodal Multilingual neural Machine Translation (m3P), which aligns the representations of different languages with the same meaning and generates the conditional vision-language memory for translation. We construct a multilingual multimodal instruction dataset (InstrMulti102) to support 102 languages. Our method aims to minimize the representation distance of different languages by regarding the image as a central language. Experimental results show that m3P outperforms previous text-only baselines and multilingual multimodal methods by a large margin. Furthermore, the probing experiments validate the effectiveness of our method in enhancing translation under the low-resource and massively multilingual scenario.'

# Summary. An optional shortened abstract.
summary: 'm3P: Towards Multimodal Multilingual Translation with Multimodal Prompt'

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.lrec-main.948.pdf'
url_code: ''
url_dataset: 'https://huggingface.co/datasets/CSJianYang/InstrMulti102'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://aclanthology.org/2024.lrec-main.948/'
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

![picture](https://yuweiyin.com/files/img/2024-05-20-COLING-m3P.png)

```bibtex
@inproceedings{m3P,
    title = "m3{P}: Towards Multimodal Multilingual Translation with Multimodal Prompt",
    author = "Yang, Jian  and
      Guo, Hongcheng  and
      Yin, Yuwei  and
      Bai, Jiaqi  and
      Wang, Bing  and
      Liu, Jiaheng  and
      Liang, Xinnian  and
      Chai, LinZheng  and
      Yang, Liqun  and
      Li, Zhoujun",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = "may",
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.948",
    pages = "10858--10871",
}
```
