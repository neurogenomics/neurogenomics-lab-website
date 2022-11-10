---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Contact
subtitle:


design:
  background:
    # Name of image in `assets/media/`.
    image: contact_background.png
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.7
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true



content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Contact details (edit or remove options as required)
  email: nskene@ic.ac.uk
  address:
    street: Sir Michael Uren Hub
    city: London
    postcode: 'W12 0BZ'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '51.515829'
    longitude: '-0.224929'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM the lab
      link: 'https://twitter.com/n_skene'
    - icon: github
      icon_pack: fab
      name: Use our code
      link: 'https://github.com/neurogenomics'


  design:
    columns: '2'

---
