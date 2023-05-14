---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Pena's Lab is set to open in August 2023. We are currently seeking assistance at various levels.

As an affirmative action and equal opportunity employer, Pena's Lab, affiliated with the Biological Sciences Department at Florida Atlantic University, is committed to fostering a diverse team. We strongly encourage women and minority applicants to apply and join Pena's Lab. Your contribution is highly valuable!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

I am dedicated to providing exceptional supervision and mentorship to students. I am committed to fostering an environment where students can thrive academically and professionally. I prioritize open communication, constructive feedback, and personalized guidance to support each student's individual goals and aspirations. I believe in cultivating a collaborative and inclusive atmosphere that encourages students to explore their scientific interests, develop critical thinking skills, and contribute meaningfully to their research projects. It is my utmost priority to ensure that students receive the necessary resources and support to excel in their academic pursuits. I am genuinely invested in their success and take pride in nurturing the next generation of computational neuroscientists.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
