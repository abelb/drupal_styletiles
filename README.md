Style Tiles + Foundation + Drupal
=================

Style Tiles built on Foundation for Drupal Front End Developers


This project is based on Foundation 3.
http://foundation.zurb.com/

I have created Style tiles using Foundation. Each section uses HTML code taken from Drupal so that you can write scss for style tile that you can reuse in your theme.

This is a work in progress. Please let me know if you have any feedback.

##TODO:
* Create stylesheet switcher so user can swap colors, @font-face fonts, background images.
* Add more Drupal elements
* Add different ways to layout colro swatches - lightest to darkest? Main first, then accents? Showing different values of all five colors?
* Create multiple pages to show elements in place - More of a prototype


##Installation instructions:

I created a project by installing zurb-foundation gem with Compass
For instructions, go here: http://foundation.zurb.com/docs/gem-install.php

You will need to install the zurb-foundation gem:

``[sudo] gem install zurb-foundation``

Then navigate to the directory where you have pulled the project and watch the project

``compass watch .``


## Different Style Tiles

I have created two different directories: Base & Example

Both use HTML code output from Drupal core (i think :) let me know if i missed something)
* Base - This is a style tile shows Foundation styles with Foundation classes built into the HTML.
* Example - This is a style tile that removes the Foundation classes to make it easier for style overrides.
