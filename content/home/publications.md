---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: collection
# widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: 'Research'
subtitle: ''

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    featured_only: false
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Choose a view for the listings:
  view: citation
  columns: '1'

# {{< icon name="graduation-cap" pack="fas" >}} [Google Scholar](https://scholar.google.com/citations?user=DPAmfKEAAAAJ&hl=en&sortby=pubdate)
# {{% callout note %}}
# Search publications by [filtering](./publication/).
# {{% /callout %}}

---

{{% callout note %}}
{{< icon name="graduation-cap" pack="fas" >}}{{< staticref "https://scholar.google.com/citations?user=DPAmfKEAAAAJ&hl=en&sortby=pubdate" "newtab" >}}Google Scholar{{< /staticref >}}
{{% /callout %}}
