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
  title: "Lenten Bible Study"
  url: /2019/lenten-bible-study/
  image: widget-bible-303x182.jpg
  text: 'Each Wednesday throughout the season of Lent (March 13 - April 17), Rob will host a bible study in our parish hall from noon to 1:30 p.m.  All are welcome. <b>The bible study for March 20 has been rescheduled to Friday, March 22.</b>'

widget3:
  title: "Holy Week"
  url: /2019/holy-week/
  image: widget-cross-aaron-burden-233840-unsplash-640-384.jpg
  text: 'Join us for Holy Week services: Palm Sunday, Maundy Thursday, Good Friday, and the Easter Sunday celebration.'

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
