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
  url: /worship/
  text: "<b>Sunday Worship 10:00am</b><br/>All are welcome. Sunday School available for the children."

#widget1:
#  title: "Holy Week Services"
#  image: widget-holy-week-2023-640x384.png
#  url: /2023/holy-week/
#  text: "Join us for worship services during Holy Week for Palm Sunday, Maundy Thursday, Good Friday, and Easter Sunday."

#widget2:
#  title: "COVID-19"
#  url: /2022/green-stage/
#  image: widget-covid-19-640x384.png
#  text: "In-person worship services have been suspended due to the pandemic.  Please join us online over Zoom."
#  text: "Precautions have been put in place following the diocese pandemic plan to ensure a safe worship space."

widget2:
  title: "Christmas Services"
  url: /2023/christmas/
  image: widget-christmas-2023-640x384.png
  text: "Join us for worship services during the Advent and Christmas season."

widget3:
  title: "Holly & Bake Sale"
  url: /2023/holly-sale/
  image: widget-holly-sale-2023.png
  text: "St Columba hosts our annual sale of fresh holly and homemade baked goods on Saturday, December 23 at 10am."

#widget3:
#  title: "Facilities"
#  url: /community/facilities/
#  image: widget-hall-303x182.jpg
#  text: 'We have re-opened the facilities of St&nbsp;Columba with restrictions as per the COVID-19 pandemic plan.  If you have an event or meeting, contact us to see if one of the church halls may fit your needs.'
#  text: 'A community hub in Manor Park, the facilities of St&nbsp;Columba are used by various groups throughout the week, and on weekends by individuals for special occasions such as birthday or anniversary parties.  If you have an event or meeting, one of the church halls may be a perfect fit for your needs.'
#  text: 'Unfortunately, we are not able to rent the facilities at this time.  Please keep us in mind when COVID-19 restrictions are lifted.'

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
