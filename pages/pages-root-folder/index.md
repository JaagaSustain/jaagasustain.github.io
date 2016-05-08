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
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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