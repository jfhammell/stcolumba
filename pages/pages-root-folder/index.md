---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-exterior-970x321.jpg

#widget1:
#  title: "Virtual Services"
#  url: /2021/red-stage
#  image: widget-zoom-chris-montgomery-smgTvepind4-unsplash.jpg
#  text: "<b>Sunday Worship 9:30am</b><br/>Join us virtually via Zoom. <a href='mailto:webmaster@stcolumbaottawa.ca'>Contact us</a> to receive the invitation."

widget1:
  title: "Worship Services"
  image: widget-interior-img-1592.jpg
  url: /2021/yellow-stage/
  text: "<b>Sunday Worship 9:30am</b><br/>All are welcome. COVID-19 precautions are in place."
#  url: /worship/
#  image: widget-zoom-chris-montgomery-smgTvepind4-unsplash.jpg
#  text: "<b>Sunday Worship 9:30am</b><br/>Join us virtually via Zoom. <a href='/2020/sunday-school'>Children's Sunday School</a> is available at 1:30pm. Contact the <a href='mailto:webmaster@stcolumbaottawa.ca'>webmaster</a> to receive the invitation."

#widget2:
#  title: "COVID-19"
#  url: /2021/yellow-stage/
#  image: widget-covid-19-640x384.png
#  text: "We resumed in-person worship services at St&nbsp;Columba on September 5, 2021.  Precautions have been put in place following the diocese pandemic plan to ensure a safe worship space."

widget2:
  title: "Blessing of the Animals"
  url: /2021/blessing-animals/
  image: widget-cat-isabela-ferreira-780664-unsplash.jpg
  text: "Join us with your pets on <b>Sunday, October 3</b> for the Blessing of the Animals service on the Feast of St Francis."

widget3:
  title: "Facilities"
  url: /community/facilities/
  image: widget-hall-303x182.jpg
  text: 'We have re-opened the facilities of St&nbsp;Columba with restrictions as per the COVID-19 pandemic plan.  If you have an event or meeting, contact us to see if one of the church halls may fit your needs.'
#  text: 'A community hub in Manor Park, the facilities of St&nbsp;Columba are used by various groups throughout the week, and on weekends by individuals for special occasions such as birthday or anniversary parties.  If you have an event or meeting, one of the church halls may be a perfect fit for your needs.'
#  text: 'Unfortunately, we are not able to rent the facilities at this time.  Please keep us in mind when provincial restrictions are lifted.'

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
