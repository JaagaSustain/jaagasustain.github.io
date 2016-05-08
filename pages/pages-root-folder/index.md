---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Cowork at Jaaga Startup"
  url: 'http://jaagastartup.in/cowork/'
  image: widget-1-302x182.jpg
  text: 'We are a curated community of entrepreneurs, intrapreneurs and wantrepreneurs who share skills, networks and knowledge. Within a well laid out coworking space with high speed internet, we collaborate and help each other build stronger ventures.'
widget2:
  title: "Host an Event at Jaaga Startup"
  url: 'http://jaagastartup.in/event-space/'
  text: 'We love hosting interesting, creative organisations and events. So if you need a central location to host your audience, do get in touch by clicking the button below! We offer free space to meetups and other free events targeting the entrepreneurial ecosystem.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://vine.co/v/itAO72AdMpb/embed/postcard" width="300" height="300" alt=""/></a>'
widget3:
  title: "Incubate at Jaaga Startup"
  url: 'http://jaagastartup.in/sustain/'
  image: widget-github-303x182.jpg
  text: 'Jaaga Startup's Sustain initiative strengthens entrepreneurs using technology to address environmental challenges. We offer free coworking space for 3 months and access to experienced mentors and partners.'
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
  url: /cowork/
  text: Join our Jaagarnauts ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
