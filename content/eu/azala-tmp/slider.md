---
widget: slider
headless: true  # This file represents a page section.

weight: 10  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 450px


item:
  - title: COVID-19aren Liburu Zuria
    content: 'Pandemiak hamabost hilabete bete dituen honetan, arlo desberdinetako akademiko eta profesionalek egindako gogoeta kolektiboa.'
    # Choose `center`, `left`, or `right` alignment.
    align: left
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    # overlay_color: '#666'  # An HTML color value.
    overlay_img: fusion-medical-animation-npjP0dCtoxo-unsplash.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.6  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta:
      label: Deskargatu Liburu Zuria
      url: 'https://example.org'
      icon_pack: fas
      icon: download
    cta_alt:
      url: '/lib/'
      label: Irakurri webgunean
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5

---