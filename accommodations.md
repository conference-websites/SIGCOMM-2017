---
layout: default
title: Accommodations
group: Local Information

hotels:
- id: luskin
  name: UCLA Meyer and Renee Luskin Conference Center
  deadline: July 20, 2017
  rates: ["$240 single <b>(inclusive, no tax!)</b>", "$240 double <b>(inclusive, no tax!)</b>", 35$/day charge for each additional person beyond double occupancy]
  amenities: [Free WiFi]
  address: 425 Westwood Plaza, Los Angeles, CA 90095, USA
  url: http://luskinconferencecenter.ucla.edu/
  phone: +1 (855) LCC-UCLA / +1 (855) 522-8252
  distance: Conference hotel
  reservation-info: "<b>Group Code: ACM082017</b>
<br/>"
  reservation-link: http://luskinconferencecenter.webhotel.microsdc.us/bp/search_rooms.jsp?corporateId=%20&groupCode=ACM082017&promoCode=
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1904.822615352086!2d-118.44710017759802!3d34.06914894754994!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2bc8602a90341%3A0xd73874d4f138751a!2sUCLA+Meyer+and+Renee+Luskin+Conference+Center!5e0!3m2!1sen!2sus!4v1473056429590
  note: "<p>All reservations must be guaranteed with a major credit card and accompanied by a first night room deposit.</p>
<p>Guests may cancel reservations without any penalty and with a full refund if canceled by 4pm up to 72 hours prior to arrival date.  If canceled any time after 4pm, 72 hours prior to arrival and up to arrival date, a fee of one night’s room rate will be assessed.  No-shows will also be charged one night’s room rate.</p>"
  image: images/hotels/ucla-luskin-conference.jpg

- id: angeleno
  name: Hotel Angeleno
  deadline: July 31, 2017
  rates: ["Currently, fully booked", $199 plus tax single, $199 plus tax double]
  amenities: [Free WiFi, Free parking, Free shuttle within 3-mile radius]
  address: 170 N Church Ln, Los Angeles, CA 90049
  url: http://www.hotelangeleno.com/
  phone: +1 (310) 476-6411
  distance: 2 miles
  <!-- rating: 3.5 stars (4.0/5 hotels.com review) -->
  rating: 3.5
  reservation-info: "<b>Group code: \"SIGCOMM Conference 2017\"</b>"
  reservation-link: http://tinyurl.com/SIGCOMM2017Conference
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d6609.858487974233!2d-118.46133160174892!3d34.07132802202193!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x80c2bcc0b6c77eb7%3A0xfa7b1be3d9922e2e!2sHotel+Angeleno%2C+170+N+Church+Ln%2C+Los+Angeles%2C+CA+90049!3m2!1d34.073893!2d-118.46823499999999!4m5!1s0x80c2bc88a7fe279b%3A0x1b84a71ecd8dc065!2sLuskin+Conference+Center+Hotel%2C+Westwood+Plaza%2C+Los+Angeles%2C+CA!3m2!1d34.0692557!2d-118.44569829999999!5e0!3m2!1sen!2sus!4v1499873286504"
  note: "<p>All reservations must be guaranteed by a valid credit card at the time of reservation.</p>
<p>Cancellation 24 hours prior to arrival.</p>
<p>Guests can book online or call the Reservations Line at (866) 264-3536 to book their reservations, please make sure to reference the “SIGCOMM Conference 2017” room block in order to receive the special discounted rate.</p>
<p>Contact <a href=\"mailto:kcardenas@hotelangeleno.com\">Kristie Cardenas</a> if you require additional assistance</p>"
  image: images/hotels/hotel-angeleno.jpg
---

# {{ page.title }}

The main conference venue is [UCLA Meyer and Renee Luskin Conference Center](http://luskinconferencecenter.ucla.edu/).
However, there are many other options for accommodation, including the Hotel Angeleno and AirBnB, available within walking distance, via hotel shuttle, or using public transportation.

<h2><b>Several rooms in Hotel Angeleno are still available. The conference cut off date is July 13, 2017!</b></h2>

Below is a list of conference hotels:

{% for hotel in page.hotels %}
{% include hotel.html expanded=forloop.last %}
{% endfor %}

Note that the conference will provide breakfast and lunch.
