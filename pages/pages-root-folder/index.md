---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: ibelongstoyou.jpg
widget1:
  title: "Drama Korea"
  url: 'https://www.drakor.ga/drama/'
  image: 'https://dummyimage.com/302x183/334d5c/efc94c.png&text=Drama'
  text: ''
widget2:
  title: "Film Korea"
  url: 'https://www.drakor.ga/film/'
  image: 'https://dummyimage.com/302x183/334d5c/efc94c.png&text=Film'
  text: ''
widget3:
  title: "Teaser"
  url: 'https://www.drakor.ga/teaser/'
  image: 'https://dummyimage.com/302x183/334d5c/efc94c.png&text=Teaser'
  text: ''
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
  url: https://www.knoacc.org/
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
