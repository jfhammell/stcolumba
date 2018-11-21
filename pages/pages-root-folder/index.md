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

#widget2:
#  title: "Facilities"
#  url: /community/facilities/
#  image: widget-hall-303x182.jpg
#  text: 'A community hub in Manor Park, the facilities of St Columba are used by various groups throughout the week, and on weekends by individuals for special occasions such as birthday or anniversary parties.  If you have an event or meeting, one of the church halls may be a perfect fit for your needs.'

widget2:
  title: "Christmas Services"
  url: /2018/christmas/
  image: widget-gareth-harper-175342-unsplash-640x384.jpg
  text: "Join us for Christmas in Manor Park. Find our special service times during the season celebrating the birth of Christ."

widget3:
  title: "Holly, Baked Goods & Gifts"
  url: /2018/holly-sale/
  image: widget-holly-sale.png
  text: "St Columba's annual Holly Sale is on <b>Saturday, December&nbsp;22 at 10am</b> with bags of fresh holly, homemade jams & jellies, baked goods, and embroidered gifts."

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
