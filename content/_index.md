---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
     # default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
        - name: All
          tag: '*'
        - name: Job Market Paper
          tag: JMP
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: Feel free to reach out via one of the following options.
      email: alessia.menichetti@phdstudent.hhs.se
      phone: +46 724032450
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Find me on X (former Twitter)
          link: 'https://twitter.com/alessiamnc_'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
