---
title: 'Dialogue Discourse Parsing as Generation: A Sequence-to-Sequence LLM-based Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Chuyuan Li'
  - yuweiyin
  - 'Giuseppe Carenini'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 25th Annual Meeting of the Special Interest Group on Discourse and Dialogue*
publication_short: In *SIGDIAL 2024*

abstract: 'Existing works on dialogue discourse parsing mostly utilize encoder-only models and sophisticated decoding strategies to extract structures. Despite recent advances in Large Language Models (LLMs), there has been little work applying directly these models on discourse parsing. To fully utilize the rich semantic and discourse knowledge in LLMs, we explore the feasibility of transforming discourse parsing into a generation task using a text-to-text paradigm. Our approach is intuitive and requires no modification of the LLM architecture. Experimental results on STAC and Molweni datasets show that a sequence-to-sequence model such as T0 can perform reasonably well. Notably, our improved transition-based sequence-to-sequence system achieves new state-of-the-art performance on Molweni, demonstrating the effectiveness of the proposed method. Furthermore, our systems can generate richer discourse structures such as directed acyclic graphs, whereas previous methods are limited to trees.'

# Summary. An optional shortened abstract.
summary: 'Dialogue Discourse Parsing as Generation: A Sequence-to-Sequence LLM-based Approach'

tags: []

# Display this page in the Featured widget?
featured: false
# featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2024.sigdial-1.1.pdf'
url_code: 'https://github.com/chuyuanli/Seq2Seq-DDP'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://aclanthology.org/2024.sigdial-1.1/'
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

![picture](https://yuweiyin.com/files/img/2024-09-18-SIGDIAL-Seq2Seq-DDP.png)

```bibtex
@inproceedings{seq2seq_ddp,
    title = "Dialogue Discourse Parsing as Generation: A Sequence-to-Sequence {LLM}-based Approach",
    author = "Li, Chuyuan  and
      Yin, Yuwei  and
      Carenini, Giuseppe",
    editor = "Kawahara, Tatsuya  and
      Demberg, Vera  and
      Ultes, Stefan  and
      Inoue, Koji  and
      Mehri, Shikib  and
      Howcroft, David  and
      Komatani, Kazunori",
    booktitle = "Proceedings of the 25th Annual Meeting of the Special Interest Group on Discourse and Dialogue",
    month = sep,
    year = "2024",
    address = "Kyoto, Japan",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.sigdial-1.1",
    pages = "1--14",
}
```
