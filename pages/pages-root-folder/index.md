---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: plain_blue_rectangle_withtofu.png

widget1:
  title: "Projects"
  url: '/projects/'
  image: project1000_project_widget.png
  text: "I made stuff! I really did! Come check some of them out!"
widget2:
  title: "Blog"
  url: '/blog/'
  image: widget1.png
  text: "I've got a lot of things on my mind. If you wanna hear my thoughts, you can read them here."
widget3:
  title: "Tutorials"
  url: '/tutorials/'
  image: origami_sonobe_tutorial_widget.png
  text: "Wanna know how to make things my way? Here's where you can try any or all of them out."
widget4:
  title: "Store"
  url: '/store/'
  image: widget3.png
  text: "See anything you like from my tutorials? You can purchase some of my items here, specially handmade by me.
        See some things in my store that I haven't made a tutorial for? Feel free to request tutorials and I might just hop on it!"

permalink: /index.html
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
#########################
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
#########################

# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
# ONLY NEEDED FOR INDEX HOME PAGE
# Don't set to true for other pages who use the front page layout
homepage: true
---

<!--
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
-->
