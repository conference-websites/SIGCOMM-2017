---
layout: default
title: Social Events
group: Conference

events:
- id: welcome
  name: Welcome Reception
  date: Monday, August 21
  time: 7:00pm - 10pm
  address: Centennial Hall, Luskin Center
  image: images/hotels/ucla-luskin-conference.jpg

- id: n2women-dinner
  name: N2Women Dinner
  date: Monday, August 21
  time: 8:30pm - 10:30pm
  address: Legacy Room, Luskin Center
  image: images/hotels/ucla-luskin-conference.jpg
  note: N2Women dinner will be held on Monday, the night before the conference, in The Legacy Room in Luskin Center, located on the second floor, south side of the building. N2Women Dinner aims to foster the minority community within SIGCOMM, and make it easier for the under-represented attendees to fully participate in the conference. Attendees will have the opportunity to meet multiple senior members of the community from universities, research labs and industry. The dinner is open to everyone who identifies with any minority, not just women. Please RSVP on the registration site if you plan to attend.

- id: conference-banquet
  name: Conference Banquet
  date: Tuesday, August 22
  time: 7:30pm - 11:30pm
  address: Dickson Plaza North, UCLA Campus
  <!-- image: images/map_UCLA/banquet.jpg -->
  <!-- image_url: images/map_UCLA/banquet.jpg -->
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d3304.9521178746377!2d-118.44515114892431!3d34.07074168050565!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e2!4m5!1s0x80c2bc88a7fe279b%3A0x1b84a71ecd8dc065!2sLuskin+Conference+Center+Hotel%2C+Westwood+Plaza%2C+Los+Angeles%2C+CA!3m2!1d34.0692557!2d-118.44569829999999!4m5!1s0x80c2bc882c2b241d%3A0xb18303a724ec74d2!2sDickson+Court+North%2C+Los+Angeles%2C+CA+90095!3m2!1d34.072666399999996!2d-118.4402231!5e0!3m2!1sen!2sus!4v1496344087951"

- id: student-dinner
  name: Student Dinner
  date: Wednesday, August 23
  time: 7:30pm - 10:00pm
  address: Sunset Recreation Center, UCLA Campus
  <!-- image: images/map_UCLA/student_dinner.jpg -->
  <!-- image_url: images/map_UCLA/student_dinner.jpg -->
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d3304.903396367546!2d-118.45034284892431!3d34.07199058050537!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e2!4m5!1s0x80c2bc88a7fe279b%3A0x1b84a71ecd8dc065!2sLuskin+Conference+Center+Hotel%2C+Westwood+Plaza%2C+Los+Angeles%2C+CA!3m2!1d34.0692557!2d-118.44569829999999!4m5!1s0x80c2bc8d9bea29ef%3A0x26fb0a1951297b14!2sSunset+Canyon+Recreation+Center%2C+Easton+Drive%2C+Los+Angeles%2C+CA!3m2!1d34.0750513!2d-118.45172199999999!5e0!3m2!1sen!2sus!4v1496344030928"

---

# {{ page.title }}

In addition to the technical activities, SIGCOMM 2017 will organize the following social events:

{% for event in page.events %}
{% include event.html %}
{% endfor %}
