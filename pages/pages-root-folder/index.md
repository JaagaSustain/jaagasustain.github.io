---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

image:
  title: logo.jpg

widget1:
  title: "Incubate"
  url: '/incubate/'
  image: incubate-small.png
  text: "We support entrepreneurs using technology to address environmental challenges with free coworking space and access to technology platforms, mentors and partners. Apply to solve real world problems around us."
widget2:
  title: "Consult"
  url: '/consult/'
  image: consult-small.png
  text: 'We develop innovative products and processes to help realise a more sustainable world. Get in touch to find out how we can help you reduce your environmental impact while gaining economic value.'
widget3:
  title: "Partner"
  url: '/partner/'
  image: partner-small.jpg
  text: 'We partner with incubators, accelerators and other innovation centres and help them implement robust innovation management practices. We bring experience of helping mature over 50 early stage innovations.'

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
  text: Incubate at Sustain
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div class="small-6 large-centered columns">
	<h3 align="center">Solve problems that really matter.</h3>
</div>

