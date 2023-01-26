---
id: 96821511-53fc-404c-aa3b-fb26b81a8bea
blueprint: graphql_testing
featured_media: containers/assets/images/cullen-jones-1qc1tognjqe-unsplash.jpg/1761cc6f04022e534d45ca9cf50f1165.webp
title: 'Testing Page'
description: |-
  A description.
  _In markdown!_
page_builder:
  -
    id: lddh68js
    component_type: basic_page_header
    custom_logo: false
    title: 'This is just the basic header'
    show_subtitle: true
    subtitle: |-
      This content is markdown as well.
      __Some more example text__
    show_in_app: true
    type: header_builder
    enabled: true
  -
    id: lddh8mhk
    component_type: text_with_description
    text_alignment: text-left
    title: 'Example of Text w/ Description'
    description: '__Here is some more content that should be returned as markdown and not HTML__'
    type: content_builder
    enabled: true
updated_by: 5f4a8722-fdee-4572-8c55-858f88a568dc
updated_at: 1674760737
---
__This content is markdown__
But it is at the top level and does not seem affected by whatever is happening with the nested fields...