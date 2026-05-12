---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Publications
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: publication

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  filter_button:
  - name: All
    tag: '*'

  - name: Featured Publications
    tag: featured

design:
  columns: '1'
  view: 5
  flip_alt_rows: false

---
