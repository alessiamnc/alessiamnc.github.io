---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome to my website!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: alessia.menichetti@phdstudent.hhs.se
      phone: +46 7024032450
      # appointment_url: 'https://calendly.com'
      address: 
        street: Bertil Ohlins gata 4
        city: Stockholm
       # region: 
        postcode: '11350'
        country: Sweden
        country_code: SE
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Reach out on Twitter 
          link: 'https://twitter.com/Twitter'

      # Automatically link email and phone or display as text?
      autolink: true
    
---
