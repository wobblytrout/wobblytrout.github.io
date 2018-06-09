---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_trees_1.png
widget1:
  title: "Armoured Alliance"
  url: '/armoured-alliance/'
  image: aa-1-302x182.png
  alttext: "Armoured Alliance Small Screenshot"
  text: 'Real time tank strategy game, become one with the tank and murder the everybody!!! you can do it, I believe in you..'
widget2:
  title: "Development Blog"
  url: '/blog/'
  image: seagoogly-1-302x182.png
  alttext: "Development Blog"
  text: '<em>Sometimes</em> about development, other times about: <br/>1. CNC Machines <br/>2. Keyboards <br/>3. Covfefe '
widget3:
  title: "MEMES"
  url: '/memes/'
  image: memes-1-302x182.png
  alttext: "Screaming Carrot"
  text: 'This is the place MEMES GROW'  
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
  url: /armoured-alliance/
  text: Check out my latest game!! ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
