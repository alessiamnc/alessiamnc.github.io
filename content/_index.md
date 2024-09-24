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
  - block: cv
    id: CV
    content:
      title: Vita
      text: {{% staticref "uploads/cv.pdf" %}}Please find my updated CV here.{{% /staticref %}}
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
