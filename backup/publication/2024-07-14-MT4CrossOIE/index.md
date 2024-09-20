---
title: 'MT4CrossOIE: Multi-stage Tuning for Cross-lingual Open Information Extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Tongliang Li'
  - 'Zixiang Wang'
  - 'Linzheng Chai'
  - 'Jian Yang'
  - 'Jiaqi Bai'
  - yuweiyin
  - 'Jiaheng Liu'
  - 'Hongcheng Guo'
  - 'Liqun Yang'
  - 'Hebboul Zine el-abidine'
  - 'Zhoujun Li'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Expert Systems with Applications*
publication_short: In *ESWA*

abstract: 'Cross-lingual open information extraction aims to extract structured information from raw text across multiple languages. Previous work uses a shared cross-lingual pre-trained model to handle the different languages but underuses the potential of the language-specific representation. In this paper, we propose an effective multi-stage tuning framework called MT4CrossIE, designed for enhancing cross-lingual open information extraction by injecting language-specific knowledge into the shared model. Specifically, the cross-lingual pre-trained model is first tuned in a shared semantic space (e.g., embedding matrix) in the fixed encoder and then other components are optimized in the second stage. After enough training, we freeze the pre-trained model and tune the multiple extra low-rank language-specific modules using mixture-of-LoRAs for model-based cross-lingual transfer. In addition, we leverage two-stage prompting to encourage the large language model (LLM) to annotate the multi-lingual raw data for data-based cross-lingual transfer. The model is trained with multi-lingual objectives on our proposed dataset OpenIE4++ by combing the model-based and data-based transfer techniques. Experimental results on various benchmarks emphasize the importance of aggregating multiple plug-in-and-play language-specific modules and demonstrate the effectiveness of MT4CrossIE in cross-lingual OIE.'

# Summary. An optional shortened abstract.
summary: 'MT4CrossOIE: Multi-stage Tuning for Cross-lingual Open Information Extraction'

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2308.06552'
url_code: 'https://github.com/CSJianYang/Multilingual-Multimodal-NLP'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1016/j.eswa.2024.124760'
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

![picture](https://yuweiyin.com/files/img/2024-07-14-MT4CrossOIE-Training.png)

```bibtex
@inproceedings{MT4CrossOIE,
    title = "MT4CrossOIE: Multi-stage Tuning for Cross-lingual Open Information Extraction",
    author = "Li, Tongliang  and
    Wang, Zixiang  and
    Chai, Linzheng  and
    Yang, Jian  and
    Bai, Jiaqi  and
    Yin, Yuwei  and
    Liu, Jiaheng  and
    Guo, Hongcheng  and
    Yang, Liqun  and
    Hebboul, Zine el-abidine  and
    Li, Zhoujun",
    booktitle = "Expert Systems with Applications",
    month = "Jul",
    year = "2024",
    publisher = "Elsevier",
    pages = "124760",
    url = "https://doi.org/10.1016/j.eswa.2024.124760",
}
```
