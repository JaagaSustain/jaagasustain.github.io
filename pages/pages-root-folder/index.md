---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use âº layout: frontpage
#
layout: frontpage

image:
  title: logo.jpg

widget1:
  title: "Incubate"
  url: '/incubate/'
  image: incubate-small.png
  text: 'We help entrepreneurs address environmental challenges using technology-enabled products and processes. We provide free coworking space, hands-on product development support and access to technology platforms, mentors and partners.'
widget2:
  title: "Consult"
  url: '/consult/'
  image: consult-small.png
  text: 'We work closely with SMEs and LEs and help them transition to sustainable practices. Our services include new product and process development, setting up of innovation management practices and evaluation of new innovations.'
widget3:
  title: "Partner"
  url: '/partner/'
  image: partner-small.png
  text: "We partner with incubators, accelerators and other innovation centres by providing a tailored innovation management service."
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
callforaction:
  url: /incubate/
  text: Explore Incubation
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

