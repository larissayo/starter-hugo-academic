---
# Leave the homepage title empty to use the site title
title: Larissa Yocom
type: landing

sections:
  - block: markdown
    content:
      title: Welcome
      subtitle: In my research group, we are interested in advancing research about the ecological role of fire, how climate, fire and vegetation are related over time and space, and how management can promote the beneficial aspects of fire and minimize the negative consequences.
      #text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      #background:
      #  image = "aspen_regen_glowing.jpg"  # Name of image in `static/img/`.
  - block: collection
    id: people
    content:
        title: People
        filters:
          folders:
            - authors
  - block: portfolio
    id: research
    content:
      title: Research
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: recent  
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: opportunities
    content:
      title: Opportunities
      #subtitle: x
      text: If you are interested in joining the lab, please contact me.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      #background:
      #  image = "aspen_regen_glowing.jpg"  # Name of image in `static/img/`.
---
