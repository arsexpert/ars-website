---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: ars-homepage-header.jpg
widget1:
  title: "Business Valuation and Consulting"
  url: 'services#valuation'
  text: 'Intro text for this section. Leads to the backpage explaining how we can help you with this service.'
widget2:
  title: "Litigation Consulting and Support"
  url: 'services#litigation'
  text: 'Intro text for this section. Leads to the backpage explaining how we can help you with this service.'
widget3:
  title: "Expert Witness Testimony"
  url: 'services#witness'
  text: 'Intro text for this section. Leads to the backpage explaining how we can help you with this service.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
