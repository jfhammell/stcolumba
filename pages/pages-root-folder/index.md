---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-exterior-970x321.jpg

widget1:
  title: "Services"
  url: /worship/
  image: widget-interior-img-1592.jpg
  text: "<b>Sunday Worship 9:30am</b><br/>Children's Sunday School (Fall through Spring)"

widget2:
  title: "Ash Wednesday"
  url: /2019/ash-wednesday/
  image: widget-ash-ahna-ziegler-558901-unsplash-640x384.jpg
  text: 'The Ash Wednesday service will be at 7pm on March 6.'
#  title: "Facilities"
#  url: /community/facilities/
#  image: widget-hall-303x182.jpg
#  text: 'A community hub in Manor Park, the facilities of St Columba are used by various groups throughout the week, and on weekends by individuals for special occasions such as birthday or anniversary parties.  If you have an event or meeting, one of the church halls may be a perfect fit for your needs.'

widget3:
  title: "Pancake Supper"
  url: /2019/pancake-supper/
  image: widget-pancakes-640x384.png
  text: 'St Columba is hosting a Shrove Tuesday Pancake Supper on March 5, 5-7pm.  Free will offering at the door.'

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
    url: /donate/
    text: Support our work and donate now!
    style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
