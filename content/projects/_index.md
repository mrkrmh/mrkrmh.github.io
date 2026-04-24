---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text: "Selected peer-reviewed publications and research highlights."
      filters:
        folders:
          - projects
      # Forces Hugo to sort by the 'date' field in your project folders, newest first
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: showcase
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
