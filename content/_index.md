---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please reach out via email.
      # Contact (add or remove contact options as necessary)
      email: tamaraczinczoll@gmail.com
      address:
        street: Prof.-Dr.-Helmert-Str. 2-3
        city: Potsdam
        postcode: '14482'
        country: Germany
        country_code: DE
      directions: H-2.15
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Connect
          link: 'https://www.linkedin.com/in/t-czinczoll/'
      # Automatically link email and phone or display as text?
      autolink: true
      
    design:
      columns: '2'
---
