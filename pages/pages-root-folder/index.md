---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: home.jpg
widget1:
  title: "About Us"
  url: '/about-us/'
  image: about.jpg
  text: 'Mauris accumsan, ex eu dapibus congue, nulla diam malesuada tortor, eget sodales nisi ex non eros. Etiam eu ornare nisl, non euismod urna. Suspendisse aliquet sagittis nisl sed ullamcorper. <em>Tanzania</em> oMauris accumsan, ex eu dapibus congue, nulla diam malesuada tortor, eget sodales nisi ex non eros. Etiam eu ornare nisl, non euismod urna. Suspendisse aliquet sagittis nisl sed ullamcorper.'
widget2:
  title: "Membership"
  url: '/about-us/'
  image: membership.jpg
  text: '<em>Tanzania</em> Mauris accumsan, ex eu dapibus congue.<br/>1. Nulla diam malesuada tortor, eget sodales nisi ex non eros :)<br/>2. Etiam eu ornare nisl, non euismod urna. <br/>3. Built on </a>.<br/>4. Suspendisse aliquet sagittis nisl sed.<br/>5. Suspendisse aliquet'
  
widget3:
  title: "Events"
  url: '/blog/'
  image: events_1.jpg
  text: '<em>TzBLux</em> Quisque feugiat et massa eu sollicitudin. Donec id est nec nisl luctus finibus eget vitae lacus. Nullam pulvinar suscipit dui. Nullam aliquam suscipit iaculis. Donec sit amet lorem ligula. Mauris scelerisque lectus non urna bibendum, at ultricies risus rhoncus. Nam vitae risus semper mi pulvinar posuere. <a href="http://twitter.com/phlow">@tzblux</a>.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# 
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

