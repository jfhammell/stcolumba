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
  title: "Online Services"
  url: /worship/
  image: widget-zoom-chris-montgomery-smgTvepind4-unsplash.jpg
  text: "<b>Sunday Worship 9:30am</b><br/>Join us virtually via Zoom. <a href='/2020/sunday-school'>Children's Sunday School</a> is available at 1:30pm. Contact the <a href='mailto:webmaster@stcolumbaottawa.ca'>webmaster</a> to receive the invitation."
#  image: widget-interior-img-1592.jpg
#  text: "<b>Sunday Worship 9:30am</b><br/>Children's Sunday School (Fall through Spring)"

widget2:
  title: "COVID-19"
  url: /2020/covid-19/
  image: widget-covid-19-640x384.png
  text: "In-person worship services are currently suspended.  Online virtual services are held via Zoom.  Contact the <a href='mailto:webmaster@stcolumbaottawa.ca'>webmaster</a> if you would like to join."

widget3:
  title: "Facilities"
  url: /community/facilities/
  image: widget-hall-303x182.jpg
  text: 'Unfortunately, we are not able to rent the facilities at this time.  Please keep us in mind when provincial restrictions are lifted.'
#  text: 'A community hub in Manor Park, the facilities of St&nbsp;Columba are used by various groups throughout the week, and on weekends by individuals for special occasions such as birthday or anniversary parties.  If you have an event or meeting, one of the church halls may be a perfect fit for your needs.'

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
